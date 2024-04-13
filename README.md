Round 2 - GDSC VIT VLR CYBERSECURITY: Task - Pizza

Gave different attempts to find the coupon, still trying👍
All the attempts have been done in Python
First Attempt:
1) Converted the given byte stream to a string using <str_name>.decode().
2) Realised that all the elements of the string are in hexadecimal notation.
3) Tried taking the individual elements and converting them to characters, but received the same hexadecimal value. Hence, this method doesn't seem to be viable.

Second Attempt:
1) Assign the byte stream directly to a variable
2) The string is iterated using a for loop, converting all the values to characters - for i in st: print(chr(i+65))
3) Output received:  [DXQKIs`UjKJwsNqxRH
