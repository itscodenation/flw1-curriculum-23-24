# Lesson 1.8: DOM Manipulation, Part 3, Review, & Project Work Time

<br>

## Lesson Materials

📖 Link Materials to Class Agenda:
- [Slides](https://docs.google.com/presentation/d/1sZj3ENnnILyUpDmOK9Wiq_maRGFWj0Qh47ATeRDUi50/edit?usp=sharing) (make a copy for your program - link the copy)
- [Coding Exercise(s)]()
- [Exit Ticket]()

<br>

## Key Points

- 👋 Welcome & Do Now (10)


- 🔄 Create & Append (20):
1. Introduce `createElement()`:
   - A method that creates an HTML element.
   - E.g., `let para = document.createElement("p");`

2. Introduce `appendChild()`:
   - This method appends an element as the last child.
   - After creating an element, it's often modified before appending it to the DOM.
   - E.g., `document.body.appendChild(para);`

3. Discuss saving created elements:
   - Elements are often saved in variables, similar to HTML selectors.
   - Modifications, such as changing the innerHTML, are often made before appending.
   - E.g., `para.innerHTML = "This is a paragraph";`

4. Show examples of creating multiple elements:
   - The importance of getting the syntax correct.
   - Provide examples with correct and incorrect syntax and prompt students to identify which is correct.

5. Elaborate on the order of appending:
   - The order in which elements are appended matters, especially when nesting elements.
   - It's best to start with the innermost element.
   - E.g., 
     ```javascript
     div2.appendChild(para); //para is nested within div2
     body.appendChild(div1); //div1 is appended to the body
     ```

6. Highlight the use case:
   - Useful for nesting elements.
   - Variables allow for easy updates.

- 💻 JavaScript Lab (35):
   - Allow students to complete tasks independently.
   - Offer resources as support and breakdown/walk through content when necessary.

- ⏳ Break (10)

- 💻 Project Work Time (35)
1. Have students open their planning doc and project.
2. Ask them to:
   - Complete any pending tasks from the last work session.
   - Add their contact information, including GitHub, email, LinkedIn, and resume.
   - Use CSS to format the sizes of all pictures in their project.
   - Encourage additional CSS styling to make their projects stand out.

- 👋 Closing (10)
    - Recap the day’s lesson.
    - Encourage questions and provide clarification if needed.

