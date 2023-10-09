# Guvi_Assessment_01
Guvi Data Science Assessment 1
Problems

1. You are a cyber security manager, and your task is to identify if the password entered by the user is strong or not. The basic rule to check the password strength is it should have at least 8 characters, andcontain at least one each of uppercase letters, lowercase letters, digits, and special characters (any character that is not a letter or digit). Write a function checkpass(password) that takes a string argument password and return True if it fits the criteria for a strong password and False if not.
(a) Example 1:
• Argument: '12345678'
• Returns: False
(b) Example 2:
• Argument: 'Hello@123'
• Returns: True


2. Ankit, a teaching assistant in data science, has been frequently taking leave in the past few weeks. His supervisor, who is is concerned that he might have exceeded his quota of paid leaves. To investigate this, the supervisor analyzed Ankit’s attendance for the last two weeks, consisting of five working days every week. The attendance register indicated ‘P’ for present and ‘A’ for absent. Ankit faces suspension if his attendance falls below 70%. Your task is to write a function attendance(record) that takes Ankit’s attendance record as a string argument and determines whether he could be suspended or not. The function argument is a string containing the attendance in the form of ’P’ or ’A’ separated by a single space. Return value should be a 2-tuple whose first element is the string 'suspended' if he has less than 70% attendance, and 'not suspended' if his attendance is 70% or above. The second element should be the percentage of his attendance as a
fraction (0.7 for 70%).
(a) Example 1
• Argument: 'P P A A A P A P A A'
• Returns: ('suspended', 0.4)
(b) Example 2
• Argument: 'P P P A P P A P A P'
• Returns: ('not suspended', 0.7)


3. Ankit is always fascinated by the number 2. He always wants to know who came second in a race, the second person to set foot on the moon and so on. If Ankit is provided with a list of numbers and asked to find the maximum, he reports the second highest number as the maximum because according to him, 2 is higher than 1. Let us consider Ankit becoming the instructor of a data science course. Write a function ankit_max(marks_dict) for that returns the name of the highest scorer in his class according to Ankit. It should take a dict of the form {Name1: marks1, Name2: marks2, ...}, where the keys Name1, Name2, ... identify students, and marks1, marks2, ... are their respective marks as numbers. If there is no second highest, the function should return None.
(a) Example 1
• Argument: {'Alok': 10, 'Bikash': 24, 'Chandan': 26,
'Dali': 28, 'Eli': 30}
• Returns: 'Dali'
(b) Example 2
• Argument: {'Xavier': 25, 'Ibrahim': 25, 'Yatin': 25,
'Sami': 25, 'Takahashi': 25}
• Returns: None


4. Write a function multiple_of_3(number) which takes an integer number to check if it is divisible by 3, without using the modulo or division operator. Instead, use the fact that any number is divisible by 3 if the sum of its digits is divisible by 3. Consider 0 as divisible by 3.
(a) Example 1
• Argument: 123
• Returns: True
(b) Example 2
• Argument: 124
• Returns: False


5. Write a function deduplicate(arg) that takes a string arg as parameter
and returns another string after removing all the adjacent
repeated characters in arg.
(a) Example 1
• Argument: 'poonam'
• Returns: 'ponam'
(b) Example 2
• Argument: 'suruuuuuuuuuuuuuuuuuuuuuuuur'
• Returns: 'surur'
(c) Example 3
• Argument: 'blahblahblah'
• Returns: 'blahblahblah

