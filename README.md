# Central Finance AI Agent Dashboard

Live dashboard: [https://andreay321.github.io/Dashboard/](https://andreay321.github.io/Dashboard/)

## Overview

This dashboard displays the Central Finance AI Agent portfolio for the Beijing team. It provides a centralized view of all AI agents under development, their status, timelines, and allows team members to add comments and updates.

## Features

- **Agent Portfolio View**: Browse all 9 AI agents with details
- **Search & Filter**: Filter by team (Lian, Jenny, Lucy) or delivery timeline (OP2025 FPS2/FPS3)
- **Interactive Details**: Click any agent to view complete information including:
  - Scope and description
  - AI ID, Jarvis Status, AHA information
  - JIRA ticket links
  - Comments history
- **Comments System**: Add status updates and comments (stored locally in browser)
- **Statistics Dashboard**: View counts by timeline and JIRA entries

## AI Agents Included

### Accrual Assistant
1. Accounting Accrual Agent
2. Completeness Monitor Agent
3. Readiness Agent
4. Reconciliation Agent

### ICMR Assistant
5. Resolution Agent

### Settlement Assistant
6. Settlement Rule for Investment Measure Agent

### Other Assistants
7. Allocation amount explanation
8. AI Agent for universal allocation management
9. Data consistency agent (CFIN Operation Assistant)

## Data Source

Source data: AI Agent List.xlsx from Central Finance Development team

## Technology

- Pure HTML, CSS, JavaScript (no dependencies)
- Client-side storage using localStorage
- Responsive design for mobile and desktop

## Usage

Simply visit the live URL above. Click any row in the table to:
1. View complete agent details
2. See comment history
3. Add new status updates

Comments are saved in your browser's local storage and persist across sessions.

## Updates

To update the dashboard with new agents or information, update the `agentsData` array in `index.html`.

Last updated: 2026-07-03
