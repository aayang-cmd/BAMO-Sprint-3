# Brewers Community Foundation Website

A full-stack, API-driven web application built for the Brewers Community Foundation to showcase community impact stories, donation initiatives, and interactive fan experiences through dynamic frontend components powered by the Monday.com API and GraphQL.

---

## Features

- Dynamic impact carousel powered by Monday.com API
- Live carousel autoplay with interactive navigation controls
- Brewers-themed live score widget UI
- GraphQL API integration with Monday.com
- Real-time content fetching and rendering
- Responsive and modern UI/UX
- Toast notification system for API feedback
- Custom animations and transitions
- Base64 image/media handling
- Form submission directly into Monday.com boards
- Modular frontend architecture using HTML, CSS, and JavaScript

---

# Tech Stack

## Frontend
- HTML5
- CSS3
- JavaScript (Vanilla JS)

## APIs & Backend Services
- Monday.com API
- GraphQL

## Tools & Platforms
- Monday.com
- GitHub
- VS Code

---

# Project Structure

```bash
├── index.html
├── style.css
├── main.js
├── mondayAPI.js
├── monday-config.json
├── brewers-widget.html
├── .env
└── .gitignore
```

---

# Application Overview

## Dynamic Carousel System

The application features a dynamic impact-story carousel that fetches content directly from Monday.com boards and automatically rotates slides every 5 seconds.

### Carousel Features
- Dynamic slide generation
- Image preloading for performance optimization
- Smooth autoplay functionality
- Hover pause interactions
- Previous/next controls
- Fallback placeholder content if API data fails

---

## Monday.com API Integration

The application uses GraphQL queries and mutations to interact with Monday.com boards for:
- Fetching carousel content
- Creating grant request submissions
- Managing organization data
- Dynamically rendering board items

The API configuration is centralized through a config file for maintainability and scalability.

---

## Brewers Score Widget

A custom floating Brewers score widget was built with:
- Live-style animated indicators
- Popup game panel
- Dynamic score cards
- Responsive floating UI
- Brewers-themed branding and animations

---

# Installation

## 1. Clone the Repository

```bash
git clone https://github.com/your-username/brewers-community-foundation.git
cd brewers-community-foundation
```

---

## 2. Install Dependencies

No package manager is required for this project since it uses vanilla HTML, CSS, and JavaScript.

You can run the application locally using:
- VS Code Live Server
- Any local development server

Example:

```bash
npx serve
```

---

## 3. Configure Environment Variables

Create a `.env` file:

```env
MONDAY_API_TOKEN=your_token_here
MONDAY_BOARD_ID=your_board_id
MONDAY_GROUP_ID=your_group_id
```

---

## 4. Configure Monday.com Settings

Update `monday-config.json` with your:
- Board IDs
- Group IDs
- Column mappings
- Carousel board configuration

---

# Running the Project

Open `index.html` with a local development server.

Example with VS Code Live Server:
1. Right-click `index.html`
2. Select **Open with Live Server**

---

# UI Highlights

## Modern Brewers Branding
- Navy and gold Brewers-inspired color palette
- Custom typography
- Responsive layouts
- Interactive hover states
- Animated transitions

---

# Key Learning Outcomes

This project demonstrates:
- Full-stack development concepts
- API integration and data handling
- GraphQL query/mutation workflows
- Dynamic DOM rendering
- Frontend performance optimization
- Responsive UI/UX design
- Debugging and troubleshooting
- Real-time content rendering

---

# Future Improvements

- Authentication system
- Backend middleware layer
- Database integration
- Admin dashboard
- Improved accessibility
- Enhanced analytics tracking
- Deployment pipeline
- Expanded mobile responsiveness

---

# Author

## Aaron Yang, Omar Santibanez, Brandon Taylor-Hughlett

Full-Stack Developer Intern at i.c.stars Milwaukee

Focused on building API-driven applications, improving workflows through data integration, and creating impactful user experiences through modern web technologies.

---

# License

This project is for educational and portfolio purposes.
