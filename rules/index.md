## Basic Rules
- These are just basic rules; follow exceptions if they exist
- Exclude files not created by you, such as those in node_modules
- End files with a newline
- Develop with a SaaS mindset (avoid unnecessary comments, code, or systems)
- Leave a space between comments

## Code Definition Rules
| Purpose | Naming Convention | Example |
|---------|-----------------|--------|
| Variable / Function / File / Folder / General | camelCase | userData, loginCheck |
| Boolean | camelCase (verb first) | isOpen, isAnonymous |
| Component | PascalCase | UserCard, LoginForm |
| Constant / Environment Variable (.env) | UPPER_SNAKE_CASE | FIREBASE_KEY, VITE_TITLE |
| Others / When a space in the name helps | snake_case (uppercase allowed) | stripe_price, firebase_data |

## Code / Files
- Define code definitions first
- Use comments to clarify unnamed groups
- Do not use semicolons
- Use JSON notation for JSON-like objects

- Naming
  - Group similar items (functions, folders) together
  - If necessary, separate different types into their own groups

## Folders
- index is the main file of a folder
  - Use index as the main file name for grouped content
  - If index is not allowed, use the specified name
  - If necessary, use snake_case (uppercase allowed) for the folder name
    ```text
    / - README.md
        README_english.md
        rules/ - index.md
                  english.md
    ```

- Remove folders that have no meaning
  - But if they represent different functionalities, keep them
    ```text
    /- rules.md
    ```

## JSON (Data)
- Write ungrouped data first
- Leave a blank line between ungrouped and grouped data
- If necessary to group unnecessary data, write it in a single line
  ```json
  {
    "id": "XXXX",
    settings: [["XXXX", "XXXX"]],

    "user": {
      name: "XXXX",
      email: "XXXX@XXXX.XXXX"
    }
  }

## Comments
- Comments do not have to follow naming rules
  - `// Set data`