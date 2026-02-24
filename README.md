# cvi-student-portfolio-template
Student portfolio template for the CVI PKI Career Pathway Cohort (labs, notes, reflections, projects).

# CVI PKI Career Pathway — Student Portfolio

This repository documents my hands-on learning and professional development through the **CyberVisionaries Institute (CVI) PKI Career Pathway Cohort**.

This is my working portfolio — not the curriculum repository.

All instructional materials live in the CVI curriculum repo.
All work artifacts live here.

## 1. Repository Purpose

This repository serves as:
1. A structured lab documentation workspace
2. A technical reflection journal
3. A growing PKI portfolio
4. Evidence of hands-on capability

Everything committed here should reflect professional standards.

## 2. Repository Structure
- `labs/` — weekly lab documentation and outputs
- `notes/` — weekly key concepts in my own words
- `reflections/` — weekly reflection responses
- `projects/` — mini-projects and capstones (as assigned)
- `assets/` — screenshots, diagrams, supporting images

Each folder has a specific purpose.
Do not mix content types across directories.

## 3. Embedding Screenshots (Use Relative Paths Only)
When documenting labs, you will often include screenshots of terminal output, certificate details, or command results.

Follow this standard:

### Step 1 — Store Screenshots Properly
All screenshots must be stored in:

#### assets/screenshots/week-01/

(Adjust the week number accordingly.)
Do not store screenshots in the root directory.

### Step 2 — Embed Using a Relative Path
When embedding an image inside a Markdown file (for example inside labs/week-01/key-pair-generation.md), use a relative path.

Example:

![Key Pair Output](../../assets/screenshots/week-01/keypair-output.png)

Explanation:
- .. moves up one folder level
- From labs/week-01/ you move up twice to reach the repository root
- Then navigate into assets/screenshots/week-01/

#### This is called a relative file path.

### ❌ Do NOT Use:
Absolute file paths from your computer
- (C:\Users\YourName\Desktop\image.png)
- Drag-and-drop links that reference your local machine
- Public URL links unless explicitly instructed

### Why Relative Paths Matter
Using relative paths ensures:
- Your repository renders correctly for others
- Reviewers can view images without errors
- Your documentation follows professional Git standards

If your image does not render, your path is incorrect.
Debug the path before submitting.

## 4. Weekly Workflow
Each week follows this structure:
1. Review lesson notes and lab instructions from the CVI curriculum repository
2. Complete the lab exercises
3. Document results in `labs/`
4. Summarize key concepts in `notes/`
5. Submit reflections in `reflections/`
6. Commit changes with a clear, professional message

## 5. Document Standards

All entries should demonstrate:
1. Clear technical reasoning
2. Structured thinking
3. Concise explanations
4. Professional tone

Avoid:
- Vague summaries
- Copying definitions without understanding
- Single-word commit messages

This repository represents your technical growth.

## About CVI
CyberVisionaries Institute builds sustainable, demonstrable technical capability in cybersecurity through structured training and mentorship.

This portfolio reflects that progression.

