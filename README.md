## [日本語はこちらをご覧ください](https://github.com/ue0ba1ya1sh3i/ue0ba1ya1sh3i/blob/main/README_japanese.md)

## Table of Contents
- ### [About the Developer](#about-the-developer-1)
- ### [Skills Acquired](#skills-acquired-1)
- ### [Skills to Review](#skills-to-review-1)
- ### [Skills to Learn](#skills-to-learn-1)
- ### [Code Rules](#code-rules-1)

## About the Developer
- ### Primarily learning by creating various projects based on JavaScript
- ### Looking for collaborators

## Skills Acquired

| Category | Skills |
|----------|--------|
| Languages (Practical Level) | JavaScript, HTML / CSS, Markdown, Command Prompt |
| Frameworks | Node.js, Express |
| Services | GitHub, Firebase, SwichBot, LINE, Google Analytics, Google Search Console |
| Tools | VSCode, Git, Vite |

## Skills to Review

| Category | Skills |
|----------|--------|
| Languages | TypeScript, Google Apps Script (GAS) |
| Frameworks | React, Tailwind CSS |

## Skills to Learn

| Category | Skills |
|----------|--------|
| Languages | Dart, C#, VBA |
| Frameworks | Next.js |
| Services | GCP, AWS, Stripe |
| Tools / Others | Linux, WSL, Networking, Databases |

## Code Rules

### Definitions
| Purpose | Naming Convention | Example |
|---------|-----------------|---------|
| Variables / Functions | camelCase | `userData`, `loginCheck` |
| Components / Files | PascalCase | `UserCard`, `LoginForm` |
| Constants / Environment Variables (.env) | UPPER_SNAKE_CASE(all capital letters) | `API_KEY`, `DB_URL` |
| When you need to distinguish between the same names with underscores | UPPER_SNAKE_CASE | `README_japanese`, `firebase_data` |
| Cases where using underscores is definitely easier to read(priority) | UPPER_SNAKE_CASE | CodeRule_japanese linux_arch |

### JSON / Data
- #### Record unorganized data first

### Code
  - #### Use line breaks where necessary
  - #### Use camelCase as the default for naming definitions such as variable definitions

### Comments
- #### Add comments for complex logic or parts that are easy to forget
- #### Don't put it where it shouldn't
- #### Explain by logical sections

### Directory Structure
- #### Basically, put similar types of files in one directory.
- #### If it's difficult to understand, move it outside (e.g., change /components/pages to /pages).

### Code Organization Flow
#### 1. Start by grouping definitions and settings
#### 2. Write the main logic in order from top to bottom
#### 3. Place temporary or experimental code at the top, then refactor
