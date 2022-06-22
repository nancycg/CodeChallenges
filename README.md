# CodeChallenges
CoderByte Practice Solutions


Grouper
Have the function Grouper(str) take the people parameter, which will be a list of people. The list of people follows the format below:

{person1};{person2};{person3};...

Every person is named according to the following format:

{name}-{age}

Where:
name is the person’s name.
age is their age.

For example:

Peter-18
Anna-22

Your function must return the list of people grouped by age range. Each range age matches with a period of ten years. People must be sorted by age, or alphabetically by their names if they are the same age. If two people have the same name, both must be included in the output.

The output must follow the format below:

{representative period 1}:{person1};{person2};{person3}...;{representative period 2}:{person1};{person2};{person3}...;...
Examples
Input: Kevin-25;Simon-22;Larry-25;Anna-22
Output: 20:Anna-22;Simon-22;Kevin-25;Larry-25
Input: Kevin-25;Nora-31;John-24;Simon-22;Sam-30
Output: 20:Simon-22;John-24;Kevin-25;30:Sam-30;Nora-31

ALL Test cases passed: HURRAY

<img width="1369" alt="SUCCESS" src="https://user-images.githubusercontent.com/20887138/175120103-f6d4e816-719f-446e-9801-e413880f33da.png">
