# Dynamic Exam Answer Key Matrix

A browser-based application designed to organize examination answers into a clean, numbered visual matrix. It allows users to paste answers from different examination sections and view them in a separate, customizable results screen.

## Features

- **Multiple Choice (Section A):** Displays answers in a numbered grid.
- **True or False (Section B):** Organizes T/F answers into a visual matrix.
- **Matching (Section C):** Displays matching answers in a numbered grid.
- **Short Answers (Section D):** Displays questions alongside their corresponding answers.
- **Live Rendering:** Automatically processes pasted or typed answers.
- **Separate Views:** Provides a Home screen for entering answers and an Answers screen for viewing results.
- **Theme Customization:** Supports Dark, Light, and seven ROYGBIV colour themes.
- **Navigation:** Allows users to move between the Home and Answers screens.
- **Clear Function:** Clears all input fields.
- **Responsive Interface:** Features a modern, clean design.

## Technologies Used

- HTML5 – Application structure.
- CSS3 – Styling, layouts, animations, and colour themes.
- JavaScript – Answer processing, dynamic rendering, and navigation.

## How to Run

1. Download or clone the project.
2. Locate the `index.html` file.
3. Open it using a modern web browser.
4. Paste your examination answers into the appropriate sections.
5. Click **View Answers** to display the generated matrix.
6. Use the theme buttons to customize the appearance.
7. Click **Back to Home** to edit your answers.

## Input Examples
<img width="453" height="395" alt="image" src="https://github.com/user-attachments/assets/d637c153-ed6d-4213-82f5-5247086ad78e" />


<img width="485" height="329" alt="image" src="https://github.com/user-attachments/assets/008ab52a-af9c-435d-8a42-c282ca148bb0" />


### Section A – Multiple Choice
```text
A B C D A B C
```

### Section B – True or False
```text
T F T T F T
```

### Section C – Matching
```text
H G J A B C
```

### Section D – Short Answers
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

- Modern web browser.
- No installation required.
- No external libraries or frameworks.
- No internet connection required.

## Core JavaScript Functions

- `parseTokens()` – Processes and numbers pasted answers.
- `buildGrid()` – Generates the answer matrices.
- `buildShortAnswers()` – Organizes short-answer questions and responses.
- `renderAll()` – Updates all generated results.
- `openAnswersView()` – Opens the results screen.
- `goHome()` – Returns to the input screen.
- `setTheme()` – Changes the application's colour theme.
- `clearAll()` – Clears all entered answers.

## License

Free for educational and personal use.
