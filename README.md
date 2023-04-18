# reverse_string_using_function
def reverse(string):                        #function named reverse
    """reversing of the given string"""
    reversed= ""                            #empty string reversed
    for i in range(len(string)-1, -1, -1):
        reversed+= string[i]                # storing the values in reversed
    return reversed
my_string = "1234abcd"                      #this is my string 
print(reverse(my_string))                    # reversed
