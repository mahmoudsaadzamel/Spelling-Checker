# Task-1--Spelling-Checker
The Spell Checker class is designed to handle spell-checking operations using a given dictionary as input
 The class has three main operations, each with specific functionalities:

# Store Dictionary:
The class takes a dictionary, which is a list of words, as input and stores it in a suitable data structure. In the provided implementation, the dictionary is stored in a Python dictionary (self.d), where keys are the first characters of words, and values are lists containing words starting with that character. The dictionary is organized in lexicographic order for efficient word lookups.

# Time Complexity:
The time complexity for storing the dictionary depends on the number of words in the input dictionary and the number of characters in each word. Assuming the average length of a word is 'L' and there are 'N' words in the dictionary, the time complexity for storing the dictionary is O(N * L).
Space Complexity: The space complexity for storing the dictionary depends on the total number of words in the dictionary and the average word length. Assuming the average length of a word is 'L' and there are 'N' words in the dictionary, the space complexity is O(N * L).

# Find Nearest Words:
The class provides a method named find that takes an input word as an argument and returns the nearest four words if the input word is not present in the dictionary. The nearest four words are the two words before and after the input word in lexicographic order if they exist in the dictionary. If they do not exist, the method returns the words from the adjacent characters in the alphabet.

### Time Complexity: The time complexity for finding the nearest four words depends on the number of words starting with the same character as the input word (in the dictionary) and the length of the input word. Let 'K' be the average number of words starting with the same character as the input word. The time complexity for finding the nearest words is O(K * L), where 'L' is the length of the input word.
### Space Complexity: The space complexity for this operation is O(1) as it only requires a constant amount of memory to store the nearest four words.

# Add Word to Dictionary:
The class provides a method named to add a word that takes an input word as an argument and adds it to the dictionary.

# Time Complexity: The time complexity for adding a word to the dictionary depends on the number of words starting with the same character as the input word (in the dictionary) and the length of the input word. Let 'K' be the average number of words starting with the same character as the input word. The time complexity for adding a word is O(K * L), where 'L' is the length of the input word.
# Space Complexity: The space complexity for this operation is O(1) as it only requires a constant amount of memory to add a word to the dictionary.
