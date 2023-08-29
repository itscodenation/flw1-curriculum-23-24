# Lesson 1.4: Conditionals & Project Intro

<br>

## Lesson Materials

📖 Link Materials to Class Agenda:
- [Slides](https://docs.google.com/presentation/d/1VLk9JKX1lsLEnl6QXl1gAL2izUg0Loe-rjikesURDe0/edit?usp=sharing) (make a copy for your program - link the copy)
- [Coding Exercise(s)]
- [Exit Ticket]

<br>

## Key Points

- 👋 Welcome & Do Now (10):
  - Activity: Start with an activity to engage students and get them talking. Using Padlet, an online interactive board, students will mark a location of a place they would like to visit but haven’t been to before. Ask them to be ready to share their reason.
  - Discussion: Go around the room (or virtual room) and have each student share their chosen place and reason. This is a great way for students to learn a bit about each other and get comfortable speaking in the group.<br><br>
  
- 💬 Conditionals (10):
  -  Start with a brief review of conditional statements. 
  - Provide examples and explain the syntax.
  - Work through a few examples as a class. 
  - Ask students to suggest changes to the code and predict the outcomes.<br><br>

- 💻 Code Along (5):
  -  Share your screen and code in real-time, explaining your thought process as you go. Students will follow along, practicing using conditionals in their own code.<br><br>

- ＆ Compound Conditionals (15):
  - Explain compound conditionals and logical operators. Provide examples and explain the syntax.
  - Work through a few examples as a class. Ask students to suggest changes to the code and predict the outcomes.<br><br>

- 💻 Code Along (10):
  - Provide students with a set of coding exercises to work on independently. 
  - Encourage them to experiment with using different logical operators and to consider all possible outcomes.<br><br>

- ⏳ Break (10):<br><br>

- 🗣️ Technical Questions (5):
  - Talk about strategies for asking technical questions clearly and effectively. Discuss the importance of providing all necessary information, being concise, and asking specific questions.<br><br>

- 💻 Project Intro & Planning (40)
  - Provide an overview of the end-of-unit project. 
  - Discuss the requirements and show examples of completed projects.
  - Discuss the importance of project planning and brainstorming. 
  - Provide tips for effective planning and time management.
  - Provide time for students to start planning their projects. 
    - They should create a project plan that includes a list of tasks to be completed, a timeline, and any resources they will need.

- 👋 Closing (10):
  - Recap the key takeaways from the lesson.
  - Address any questions or concerns.<br><br>
  

## Common Misconceptions
1. **Conditionals**: 
    - Misconception: Many people think that the condition in an `if` statement has to be a boolean (`true` or `false`). However, JavaScript (and many other programming languages) will convert non-boolean values to a boolean value, which is a concept known as 'truthy' or 'falsy'.
    - Example: In JavaScript, all values are truthy unless they are defined as falsy. Only values defined as falsy are false, 0, '', null, undefined, and NaN.

2. **Comparison Operators**: 
    - Misconception: `==` and `===` are the same. However, `==` compares values while `===` compares both value and type.
    - Example: `0 == ''` will return true, but `0 === ''` will return false.

3. **Compound Conditionals**:
    - Misconception: `&&` (AND) and `||` (OR) have the same precedence. However, `&&` has higher precedence than `||`.
    - Example: In the expression `a && b || c`, `a && b` is evaluated first.

4. **Truthy and Falsy**: 
    - Misconception: All non-zero numbers are truthy. However, in JavaScript, `-0` is considered falsy.
    - Example: `if (-0) { console.log("Truthy"); } else { console.log("Falsy"); }` will print "Falsy".

5. **Logical Operators**: 
    - Misconception: `!` (NOT) operator only inverts `true` to `false` and `false` to `true`. However, it also converts truthy values to `false` and falsy values to `true`.
    - Example: `!1` returns `false` and `!0` returns `true`.

## Additional Materials
- n/a
