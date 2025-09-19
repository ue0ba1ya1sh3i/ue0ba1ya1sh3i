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

## Code Rules

### Definitions
| Purpose | Naming Rules | Examples |
|------|----------|----|
| Variables / Functions / Files / Folders / Basic | camelCase | `userData`, `loginCheck` |
| Components | PascalCase | `UserCard`, `LoginForm` |
| Constants / Environment Variables (.env) | UPPER_SNAKE_CASE (all uppercase) | `FIREBASE_API`, `DB_URL` |
| When the same name must be distinguished by an underscore | snake_case | `stripe_price`, `firebase_data` |

### Basic Rules
- #### These are just the basics, so follow any exceptions.
- #### Files in `node_modules` that you did not create are excluded.
- #### Unorganized data should be entered first.
- #### Use a new line between ungrouped data and other data.
- #### Generally, group similar items together.
- #### If similar items are better treated as separate types, group them as separate types.
- #### Use a new line at the end.
- #### Develop with a SaaS mindset (avoid unnecessary comments and code).
- #### Use a tab space indentation of 2.

### Code
- ### Define definition relationships first.
- #### If items are grouped and unnamed, use comments to clarify.
- #### Do not use semicolons.
- #### Write JSON-type objects in the same way as JSON.

### JSON
- ### If unnecessary groups must be specified, group them all on one line.

### Comments / Markdown
- #### Leave spaces between comments.
- ### Comments do not have to follow definition rules.
- ### Do not write unnecessary content.

### Example

#### JSON
```json
{
  "title": "XXXX",
  "message": "XXXX",
  
  "rewrites": [{ "source": "**", "destination": "/index.html" }],
  
  "headers": [
    {
    "source": "/assets/**",
    "headers": [{ "key": "Cache-Control", "value": "public,max-age=31536000,immutable" }]
    },
  },
  
  "user": {
    "mail": "XXXX@XXXX.XXXX",
    "name": "XXXX"
  }
}
```

#### JavaScript (Code)
```javascript

// Library
import { StrictMode, Suspense } from "react"
import { BrowserRouter, Routes, Route } from "react-router-dom"

````

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
