# Create a Random Password Generator in Python

Credits: This code was extracted from [blog](https://geekflare.com/password-generator-python-code/) by [Hafeezul Kareem Shaik](https://geekflare.com/author/hafeezulkareem/) in [Development](https://geekflare.com/category/development/)

### Steps

-   Store all the characters as a list. We can use the string module of Python or type all of them.
-   Ask the user to enter the length of the password.
-   Shuffle the characters using the  `random.shuffle`  method.
-   Initialize an empty list to store the password.
-   Write a loop that iterates  `length`  times.
    -   Pick a random character from all the characters using the  `random.choice`  method.
    -   Append the random character to the password.
-   Shuffle the resultant password list to make it more random.
-   Convert the password list to string using the  `join`  method.
-   Print the password.