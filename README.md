# CRM

Today, then everything else. A one-page kanban CRM for a consultant juggling clients: each client is a column with its value, dates and contacts, and each task is a card with a due date.

Built by [Jordi Albanell](https://jordialbanell.com/projects). Try it on [jordialbanell.com](https://jordialbanell.com/projects/crm).

## What it does

- **Work and Personal boards**, one column per client or project, with its value, dates, notes and contacts.
- **Cards for tasks**, with due dates, urgent flags, tags and recurring tasks. Drag cards and columns to reorder them.
- **A money bar** across the top: pipeline, invoiced, at risk and done this year, from the values on your columns.
- **Four views:** Board, Calendar, Gantt (columns as a timeline) and Today, a day planner you fill from your cards.
- **An inbox** column for things that arrive before they have a home.

This copy keeps everything in your browser (localStorage): no account, no server, nothing leaves your device. Clear your browser data and the board goes with it.

## Use it

It's one HTML file with no dependencies.

- **Quickest:** download `index.html` and open it in your browser. It starts with a sample board; edit or delete anything.
- **Online:** drop the folder on [Vercel](https://vercel.com/new), Netlify or GitHub Pages. Each visitor gets their own board in their own browser.

The version on jordialbanell.com also syncs the board to a database and has an AI assistant. Those parts are switched off in this file.

## Licence and credit

MIT licence, copyright (c) 2026 Jordi Albanell. See [LICENSE](LICENSE).

In plain words: you can use this code, change it, share it and build on it, including for paid work. The one legal condition is that **every copy keeps the copyright line and the LICENSE file**, so the code always says where it came from. Removing them breaks the licence.

If you put something live that's built on it, a "Based on CRM by [Jordi Albanell](https://jordialbanell.com)" link is appreciated.
