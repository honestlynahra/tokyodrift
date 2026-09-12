# tokyodrift
# Tokyo Drifter 🐌

[![GitHub](https://img.shields.io/badge/GitHub-Project-black?logo=github)](https://github.com/)

## Basic Details

### Team Name: Coders

### Team Members

* Member 1: Nahra Noushad - Institute of Engineering & Technology Calicut University
* Member 3: Saranya S - Institute of Engineering & Technology Calicut University

### Project Description

Tokyo Drifter is a completely unnecessary interactive web experience featuring a snail that follows your mouse cursor around the screen. 🐌

The project tracks mouse speed, distance travelled by the snail, and escape attempts while displaying random funny messages. It serves absolutely no practical purpose — and that's the point!

### The Problem (that doesn't exist)

Have you ever felt that your mouse cursor was lonely?

Have you ever wondered what would happen if a snail followed your every move?

Have you ever needed to measure how far a snail travels while doing absolutely nothing useful?

**We identified a serious problem:**

People are moving their mouse without being chased by a determined snail.

### The Solution (that nobody asked for)

Introducing **Tokyo Drifter** — the world's most unnecessary snail companion.

Our solution is simple:

* A snail follows your mouse wherever it goes.
* The snail tracks how much distance it travels.
* It displays random messages questioning your life choices.
* Click the snail and it tries to escape.
* Move your mouse quickly and watch the snail grow slightly larger.

Because apparently, someone needed to build this.

## Technical Details

### Technologies/Components Used

#### For Software:

* **Languages used:** HTML5, CSS3, JavaScript
* **Frameworks used:** None
* **Libraries used:** None
* **Tools used:** Visual Studio Code, Web Browser, Git/GitHub

#### For Hardware:

Not applicable. This is a software-only project.

### Implementation

#### For Software:

The project is implemented as a single HTML file containing the webpage structure, CSS styling, and JavaScript logic.

**1. Mouse Tracking**

The mouse position is continuously updated using the `mousemove` event.

**2. Snail Movement**

The snail follows the mouse cursor using a simple movement algorithm. The snail moves gradually toward the cursor instead of instantly teleporting.

**3. Statistics Tracking**

The project calculates:

* Mouse movement speed.
* Total distance travelled by the snail.
* Number of escape attempts.

**4. Random Messages**

A random message is displayed every few seconds, such as:

> "Why are you running?"

> "This is my cardio."

> "This website is completely useless."

**5. Escape Mechanism**

When the user clicks the snail, it jumps away from the cursor and increases the escape counter.

# Installation

### Clone the Repository

```bash
git clone https://github.com/your-username/tokyo-drifter.git
```

### Navigate to the Project

```bash
cd tokyo-drifter
```

# Run

### Option 1: Open Directly

Open the HTML file in your browser.

### Option 2: Run Using a Local Server

```bash
python -m http.server 8000
```

Open the following URL in your browser:

```text
http://localhost:8000
```

### Project Documentation

#### For Software:

# Screenshots (Add at least 3)

![Tokyo Drifter Initial](screenshots/tokyo-drifter-initial.png)

*Initial view of Tokyo Drifter showing the title, subtitle, and the snail on the screen.*

![Tokyo Drifter Message](screenshots/tokyo-drifter-message.png)

*The snail follows the cursor while displaying a random message: "Why are you running?"*

![Tokyo Drifter Statistics](screenshots/tokyo-drifter-statistics.png)

*The statistics panel displays snail speed, distance travelled, and escape attempts.*

# Diagrams

![Workflow](diagrams/workflow.png)

*Workflow showing how mouse movement controls the snail, how the statistics are updated, and how clicking the snail triggers an escape.*

### Project Demo

# Video

(https://drive.google.com/file/d/1KaS2lxyIj_GbFned9bLXNZfFLzzT4qTt/view?usp=sharing)
*The demo video demonstrates the snail following the mouse, displaying random messages, updating statistics, and escaping when clicked.*

# Additional Demos

* [Live Demo](https://tokyodrift.vercel.app/)
* [GitHub Repository](https://github.com/your-username/tokyo-drifter)

## Team Contributions

* Saranya S: Project concept, HTML structure, CSS styling, and JavaScript implementation, and demo presentation.
* Nahra Noushad: UI design, testing, and screenshot documentation, Project documentation, README preparation.
---

**Made with 🐌 and absolutely no practical purpose.**
