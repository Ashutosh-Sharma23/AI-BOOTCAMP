# AI-BOOTCAMP
Create a list of random numbers and print all the even numbers in the list

# create random list
list = [2,3,4,10,14,15,16,17,18,19,20]
print("Even numbers in the list are: ", end=' ')

# iterating list
for i in list:
    if i % 2 == 0:
        print(i, end=' ')
        
        
Create a string and print it in reverse order. Now reverse the words also.

# Create a string
text = "Todays AI Bootcamp is very interesting and informative"

# Reverse the complete string character by character
reverse_string = text[::-1]


print("Original String:", text)
print("Reversed String:", reverse_string)

# Reverse the order of words
reverse_words = text.split()
print("Reversed order of words:", end=' ')
for i in range(len(reverse_words)-1, -1, -1):
    print(reverse_words[i], end=' ')
