# CommBank Goal Tracker 🏦💰

A React/TypeScript web application for tracking savings goals with emoji icons, built as part of the Deloitte Australia Technology Job Simulation.

## About The Project

Extended an existing banking web app by implementing an emoji icon picker feature for goal cards. Users can now assign, change and persist custom emoji icons to their savings goals.

## Features

- **Emoji Icon Picker** — Pick and assign emojis to goal cards using emoji-mart
- **Persistent Icons** — Emoji icons saved to backend via PUT API and persist after refresh
- **Goal Management** — Create, view and update savings goals
- **Dark/Light Theme** — Toggle between dark and light mode
- **Responsive Design** — Works on mobile and desktop

## Tech Stack

- **Frontend:** React, TypeScript, Redux, Styled Components
- **API:** REST API with Axios
- **Tools:** Git, GitHub, VS Code

## Key Changes Made

- Added `icon` field to Goal model
- Built `EmojiPicker` component using emoji-mart v3
- Built `GoalIcon` and `AddIconButton` components
- Modified `GoalManager` to handle emoji selection
- Added PUT request to persist icons to backend
- Displayed emoji icons on `GoalCard` components

## Author

**Harshit Singh** — CSE-IoT Student at PSIT Kanpur
