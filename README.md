# Dynamic Exam Answer Key Matrix

A simple, browser-based tool that converts pasted examination answers into a visual answer matrix. It organizes multiple-choice, true/false, matching, and short-answer responses into a clean, easy-to-read layout.

## Features

- **Section A – Multiple Choice:** Displays answers in a numbered grid.
- **Section B – True or False:** Organizes T/F responses into a visual matrix.
- **Section C – Matching:** Displays matching answers in a numbered grid.
- **Section D – Short Answers:** Organizes questions and their corresponding answers into a numbered list.
- **Automatic Parsing:** Accepts answers separated by spaces, commas, semicolons, or new lines.
- **Flexible Input:** Supports numbered formats such as `1. A`, `2. B`, and `1-A`.
- **Live Updates:** Automatically generates the matrix as you type or paste answers.
- **Clear Function:** Clears all input fields and generated results.
- **Responsive Design:** Uses a clean, dark-themed interface.

## Technologies Used

- HTML5 – Page structure.
- CSS3 – Styling, layout, and responsive design.
- JavaScript – Input processing, answer parsing, and dynamic matrix generation.

## How to Use

1. Download or clone the project.
2. Open the `index.html` file in a web browser.
3. Paste your examination answers into the appropriate sections.
4. The answer matrix updates automatically.
5. Alternatively, click **Generate Matrix** to generate the results manually.
6. Click **Clear** to reset all sections.

## Input Examples


<img width="370" height="416" alt="image" src="https://github.com/user-attachments/assets/bf7ea470-749e-4f62-9f75-521064a935f6" />


**Section A – Multiple Choice**
```text
A B C D A C B
```

**Section B – True or False**
```text
T F T T F T
```

**Section C – Matching**
```text
H G J A B C
```

**Section D – Short Answers**
```text
What is software engineering?
The systematic application of engineering principles to software development.

What is debugging?
The process of identifying and fixing errors in a program.
```

## Project Structure

```text
Dynamic-Exam-Answer-Key-Matrix/
│
└── index.html
```

## Requirements

- A modern web browser (Chrome, Firefox, Edge, etc.).
- No installation required.
- No internet connection required.
- No external libraries or frameworks.

## Key Functionality

The application uses JavaScript functions to:

- Parse pasted answers into numbered tokens.
- Generate dynamic HTML tables.
- Organize short-answer questions and responses.
- Update results automatically when inputs change.
- Clear all fields and generated content.

## License

This project is available for educational and personal use.
