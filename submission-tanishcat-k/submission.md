Tanishka Keluskar

Q1. Find whether the number is odd or even.

If a number is divisble by 2,then it is even i.e., n%2 == 0 So we take the user input using echo and read commands and then use if-else statement to check if n%2 is 0.

![][image-1]
![][image-2]

Q2. Find the factorial of any number you like number.

n! = n(n-1)(n-2)...2*1 o we take the user input using echo and read commands and then use for loop to loop from 1 till n and multiply a temp variable whose value is 1 with it to get the factorial.

![][image-3]
![][image-4]

Q3. Fibonacci series using for and while loop both.

The Fibonacci series starts with 0 and 1, and every next number is the sum of the previous two numbers. So we take the user input using echo and read commands, initialize two variables as 0 and 1, and then use a for loop (or while loop) to print the series while updating the two numbers after every iteration.

![][image-5]
![][image-6]
![][image-7]

Q4. Find whether the number is prime or not (2).

A prime number has only two factors: 1 and itself. So we take the user input using echo and read commands and then use a for loop to check if the number is divisible by any number from 2 to n-1. If it is divisible, then it is not prime; otherwise, it is a prime number.

![][image-8]
![][image-9]

Q5. Compare 2 files whether they have text in tht nd delete if it is duplicate.

If two files have the same contents, then one of them is a duplicate. So we take the file names using echo and read commands and use the cmp command to compare the files. If both files are same, we delete one of them using the rm command; otherwise, we display that the files are different.

![][image-10]
![][image-11]

Q6. Write a script to check whether a number is palindrome.

we take the user input using echo and read commands, reverse the number using a while loop by extracting each digit one by one, and then compare the reversed number with the original number. If both are equal, it is a palindrome otherwise not.

![][image-12]
![][image-13]

Q7. Write a script to print multiplication table.

use a for loop to multiply the given number with each num from 1 to 10 and print the result.

![][image-14]
![][image-15]

Q8.
First, I will take the dir path as a command-line argument. Then, I will search that directory and all its subdirectories for files having the .log extension that were modified within the last 7 days. After finding all such files, I will count how many log files were found. Next, I will count the number of lines in each file using the wc -l command and keep adding them to get the total number of lines. Finally, I will print a formatted summary showing the total number of log files, the total number of lines, and a sorted list of all the log file names along with their individual line counts.
![][image-18]
![][image-19]

Q10.
First, I will take the password length and the number of passwords as arguments. If the user does not give these values, I will use the default values, which are 16 for the password length and 1 for the no. of passwords. Then, I will check whether the entered values are valid. The password length should be between 8 and 128, and the no of passwords should be between 1 and 100. If the values are not valid, I will display an error message and stop. Otherwise, I will use a loop to generate the required no of passwords. Each password will contain random uppercase, lowercase letters, digits, and symbols. Then, I will print each generated password on the screen and also save it along with the current timestamp in the passwords.log file.

![][image-16]
![][image-17]

[image-1]: screenshots/image-1.png
[image-2]: screenshots/image-2.png
[image-3]: screenshots/image-3.png
[image-4]: screenshots/image-4.png
[image-5]: screenshots/image-5.png
[image-6]: screenshots/image-6.png
[image-7]: screenshots/image-7.png
[image-8]: screenshots/image-8.png
[image-9]: screenshots/image-9.png
[image-10]: screenshots/image-10.png
[image-11]: screenshots/image-11.png
[image-12]: screenshots/image-12.png
[image-13]: screenshots/image-13.png
[image-14]: screenshots/image-14.png
[image-15]: screenshots/image-15.png
[image-16]: screenshots/image-16.png
[image-17]: screenshots/image-17.png
[image-18]: screenshots/image-18.png
[image-19]: screenshots/image-19.png