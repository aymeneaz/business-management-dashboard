# NEXORA Business Management Dashboard

NEXORA is a modern responsive business management dashboard demonstrating frontend application development, CRUD operations, data persistence, search, filtering, and dashboard visualization.

## Features

- Dashboard with fictional KPI cards and responsive revenue visualization
- Customer management with create, read, update, delete, search, and status filtering
- Product and inventory management with category filtering and automatic stock statuses
- Order management with search, status filtering, and detail modal
- Settings for profile, business details, and notification preferences
- LocalStorage persistence
- Form validation, confirmation dialogs, empty states, and toast notifications
- Responsive off-canvas mobile navigation
- Accessible labels, focus states, semantic tables, and modal dialogs

## Technologies

- HTML5
- CSS3
- Vanilla JavaScript
- LocalStorage
- Inline SVG for the revenue chart

No frontend framework or external JavaScript dependency is required.

## Project Structure

```text
business-management-dashboard/
├── index.html     # Application shell and semantic page structure
├── style.css      # Responsive design system and component styles
├── script.js      # Navigation, rendering, CRUD, chart, validation, and persistence
├── README.md      # Project documentation
└── assets/        # Reserved for future static assets
```

## How to Run

Open `index.html` directly in a modern browser, or open the folder in VS Code and use the Live Server extension for a local development server. No build step or backend is required.

## Demo Data

All customer, product, order, revenue, and statistic records included in this portfolio project are fictional demo data. The LocalStorage values are browser-local demo state, not secure storage or a real source of business truth.

The application uses these LocalStorage keys:

- `nexora_customers`
- `nexora_products`
- `nexora_settings`

## Future Improvements

A production version could add:

- ASP.NET Core Web API
- SQL Server and Entity Framework Core
- Authentication and JWT
- Role-Based Access Control
- Server-side validation
- A real database and REST API
- Deployment and monitoring

## Portfolio Purpose

This project demonstrates business application development and frontend engineering skills through a polished, reusable admin dashboard experience with realistic workflows and responsive UI behavior.
