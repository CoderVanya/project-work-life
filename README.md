# Project Work-Life — Personal Edition v0.5

A local-first personal workspace for Career, Marginalia, Executive MBA, Writing & Research, and Personal Life.

## Run locally
1. Install Node.js LTS.
2. In this folder run `npm install`.
3. Run `npm run dev`.
4. Open the local URL printed by Vite.

## Data and privacy
Tasks, notes, wellbeing observations and journal entries are stored in browser localStorage on this device and browser. They are not synced or encrypted. Use the in-app JSON backup regularly. Do not commit personal data or API keys to a public repository.

## Coach connection
The Coach page currently explains the secure backend requirement and links to ChatGPT separately. A live in-app OpenAI connection is not configured. It requires a server-side API integration; never place an API key in frontend code.

## v0.5 changes
- Fixed capacity note to use React state and persist as you type.
- Added an interactive month calendar with previous/next month navigation, today shortcut, selectable dates, due-task indicators and add-action shortcut.
- Added a Coach section that transparently explains the backend requirement for live AI conversations.