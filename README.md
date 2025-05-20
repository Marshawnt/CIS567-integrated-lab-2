# CIS567-integrated-lab-2
# Get user input
user_input = input()

# Separate the first character and the phrase
char_to_count = user_input[0]
phrase = user_input[2:]

# Count occurrences of the character in the phrase
count = phrase.count(char_to_count)

# Determine the correct plural form
if count == 1:
    print(f"{count} {char_to_count}")
else:
    print(f"{count} {char_to_count}'s")
