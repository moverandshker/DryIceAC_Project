# DryIceAC Project Dashboard

A comprehensive project management dashboard for the Dry Ice AC Cleaning Edmonton Market Launch.

## Overview

This dashboard provides a visual interface to track progress, manage tasks, view project documents, and monitor the timeline for the DryIceAC Edmonton market launch. It directly integrates with GitHub to display and manage project data.

## Features

- **Project Overview**: Track overall project progress, upcoming tasks, and key metrics
- **Task Management**: View and manage project tasks with completion tracking
- **Timeline Visualization**: Visualize the project timeline with milestones
- **Document Repository**: Access and read project documentation
- **File Browser**: Navigate through all project files
- **GitHub Integration**: Direct connection to the GitHub repository

## Getting Started

1. Clone this repository to your local machine
2. Open `dashboard.html` in your browser
3. Enter your GitHub Personal Access Token when prompted
4. Start using the dashboard to manage your project

**Note**: You'll need to create a GitHub Personal Access Token with repo permissions to access the dashboard. Your token is stored only in your browser's local storage and is never sent to any server other than the GitHub API.

## Project Structure

- `dashboard.html`: The main dashboard application
- `project_plan.md`: Primary project planning document
- `tasks.md`: Project task list with completion status
- `timeline.md`: Project timeline with milestones
- `marketing/`: Folder containing marketing-related documents
  - `press_release_template.md`: Template for press release
  - `customer_profiles.md`: Profiles of ideal customers
  - `faq.md`: Frequently asked questions
  - `campaign_plan.md`: Digital marketing campaign plan

## Technical Details

The dashboard is built as a single HTML file with:
- Bootstrap 5 for layout and styling
- JavaScript for GitHub API integration and interactivity
- Marked.js for Markdown rendering
- Local storage for authentication persistence

## Development Notes

This is a client-side application with no server components. All data is stored in and retrieved from GitHub.

## License

This project is for demonstration purposes only. All rights reserved.

---

Developed for the DryIceAC Edmonton Market Launch - 2025