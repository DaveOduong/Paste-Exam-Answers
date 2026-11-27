# Dynamic Exam Answer Key Matrix

A simple, responsive web application for displaying exam answers in a large, easy-to-read grid. It allows users to paste answers, organize them into sections, and view them in a dedicated answer display screen.
<img width="1822" height="891" alt="image" src="https://github.com/user-attachments/assets/30986329-096d-473a-a911-3734ef0bb421" />
<img width="1822" height="765" alt="image" src="https://github.com/user-attachments/assets/b1e76efc-5a28-4da9-ad2d-176755a91d94" />



## Features

- **Four answer sections:**
  - Section A – Multiple Choice
  - Section B – True or False
  - Section C – Matching
  - Section D – Short Answers
- **Automatic answer numbering** when generating the answer grid.
- **Large responsive answer cards** arranged in a dynamic grid.
- **Nine colour themes:** Dark, Light, Red, Orange, Yellow, Green, Blue, Indigo, and Violet.
- **Automatic scrolling loop** when opening the answers screen.
- **Customizable scrolling controls** for scroll duration, pause duration, and speed.
- **Manual scrolling detection:** Using the mouse wheel or touching the screen stops automatic scrolling.
- **Separate Home and Answers screens.**
- **Clear button** to remove all entered answers.
- **Sticky top navigation and controls** on the Answers screen.

## How to Use

1. Open the application in a web browser.
2. Paste your answers into the appropriate sections.
3. Click **View Answers** to generate the answer display.
4. Use the theme buttons to change the appearance.
5. Use the scrolling controls to adjust how the answers move.
6. Click **Home** to return to the input screen.

## Input Format

### Sections A, B and C

Answers can be separated using spaces, commas, semicolons, or new lines.

Example:

```text
1. A
2. B
3. C
4. D
5. A
```

The application automatically numbers the displayed answers.

### Section D – Short Answers

Separate each question and answer using a blank line.

The first line represents the question, while the following lines contain the answer.

Example:

```text
1. What is software engineering?
Software engineering is the systematic application of engineering principles to software development.

2. What is debugging?
Debugging is the process of identifying and correcting errors in a program.
```

## Automatic Scrolling Controls

The Answers screen provides three adjustable settings:

| Setting | Description |
|---|---|
| Scroll (s) | Determines how long the page scrolls. |
| Pause (s) | Determines how long the page pauses between scrolling phases. |
| Speed | Controls the scrolling speed. |

The scrolling cycle works as follows:

1. Pause before scrolling.
2. Scroll smoothly down the page.
3. Pause at the bottom.
4. Return smoothly to the top.
5. Repeat the cycle.

The loop can be started or stopped manually. It also stops when the user manually scrolls or touches the screen.

## Project Structure

```text
Dynamic-Exam-Answer-Key-Matrix/
│
└── index.html
```

The entire application is contained in a single HTML file, including its CSS styling and JavaScript functionality.

## Technologies Used

- **HTML5** – Application structure and input fields.
- **CSS3** – Responsive layouts, answer cards, themes, and styling.
- **JavaScript** – Answer processing, grid generation, navigation, and automatic scrolling.

## Installation and Setup

1. Download or clone the project.
2. Open the project folder.
3. Open `index.html` in any modern web browser.
4. Start entering your exam answers.

No additional installation, external libraries, or internet connection is required.

## Main JavaScript Functions

| Function | Purpose |
|---|---|
| `parseTokens()` | Processes and organizes pasted answers. |
| `buildGrid()` | Generates the answer cards. |
| `buildShortAnswers()` | Displays questions and their answers. |
| `renderAll()` | Generates all answer sections. |
| `startAutoScroll()` | Starts the automatic scrolling loop. |
| `stopAutoScroll()` | Stops automatic scrolling. |
| `toggleAutoScroll()` | Starts or stops the scrolling loop. |
| `setTheme()` | Changes the application theme. |
| `openAnswersView()` | Opens the generated answer display. |
| `goHome()` | Returns to the input screen. |
| `clearAll()` | Clears all entered answers. |

## Purpose

The project is designed to make reviewing examination answers easier by presenting them in a clear, organized, and visually accessible format. The automatic scrolling feature is particularly useful when displaying large answer keys without requiring constant manual scrolling.

## License

This project is available for educational and personal use.
