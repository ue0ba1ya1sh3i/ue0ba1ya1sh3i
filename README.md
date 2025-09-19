## 日本語版の案内
### [日本語はこちらをご覧ください](https://github.com/ue0ba1ya1sh3i/ue0ba1ya1sh3i/blob/main/README_japanese.md)

## Table of contents
- ### [About the Developer](#about-the-developer-1)
- ### [Skills Acquired](#skills-acquired-1)
- ### [Skills to Review](#skills-to-review-1)
- ### [Skills to Learn](#skills-to-learn-1)
- ### [Code Rules](#code-rules-1)

## About the developer
- ### Primarily learning by creating various projects based on JavaScript
- ### Looking for collaborators

## Skills acquired

| Category | Skills |
|----------|--------|
| Languages (Practical Level) | JavaScript, HTML / CSS, Markdown, Command Prompt |
| Frameworks | Node.js, Express |
| Services | GitHub, Firebase, SwichBot, LINE, Google Analytics, Google Search Console |
| Tools | VSCode, Git, Vite |

## Skills to review

| Category | Skills |
|----------|--------|
| Languages | TypeScript, Google Apps Script (GAS) |
| Frameworks | React, Tailwind CSS |

## Skills to learn

| Category | Skills |
|----------|--------|
| Languages | Dart, C#, VBA |
| Frameworks | Next.js |
| Services | GCP, AWS, Stripe |
| Tools / Others | Linux, WSL, Networking, Databases |

## Code rules

### Definitions
| Purpose | Naming rules | Examples |
|------|----------|----|
| Variables / Functions / Files / Folders | CamelCase | `userData`, `loginCheck` |
| Components | PascalCase | `UserCard`, `LoginForm` |
| Constants / Environment Variables (.env) | UPPER_SNAKE_CASE (all uppercase) | `FIREBASE_API`, `DB_URL` |
| When the same name must be distinguished by an underscore | UPPER_SNAKE_CASE | `stripe_price`, `firebase_data` |

### Basic rules
- #### Enter ungrouped data first
- #### Insert a newline between ungrouped and grouped data
- #### Generally, group similar data together
- #### If it's better to treat similar items as separate types, group them into separate types.

### rule
- #### Define related definitions first.
- #### If items are organized and don't have names, use comments to clarify.
- #### Do not use semicolons.
- #### No semicolon

### Comments
- #### Use spaces between comments.
- #### Comments do not have to follow definition rules.

### Example

#### JSON
```json
{
  "title": "XXXX",
  "message": "XXXX",
  
  "user": {
    "mail": "XXXX@XXXX.XXXX",
    "name": "XXXX"
  }
}
```

#### JavaScript(code)
```javascript

// Library
import { StrictMode, Suspense } from "react"
import { BrowserRouter, Routes, Route } from "react-router-dom"

```

#### Directory
```tree
index.html
index.css
index.js
font/
└── index.rtf
favicon/
├── index.png
├── 96.png
├── 192.png
└── 512.png
````
