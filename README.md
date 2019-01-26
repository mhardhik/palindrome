#palindrome
#AUTHOR MUMMADI HARDHIK
THE PROGRAMME  TELL IS THE STRING IS A PALINDROME OR NOT
my_str=input("enter to check if palindrome")
my_str= my_str.casefold()
y = reversed(my_str)
if (list(my_str) == list(y)):
    print ("it is a palindrome")
else:
    print("it is not a palindrome")
