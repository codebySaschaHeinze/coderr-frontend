# Coderr Frontend

Coderr is a course project frontend for a service marketplace where customers can browse IT service offers and business users can present their profiles and services.

## Project Context

This frontend was provided as part of a course project at Developer Akademie.

My main contribution in the related project was the backend implementation, including the REST API, authentication, business logic, database models, tests, and deployment preparation.

This repository is kept public to show the full project setup and how the provided frontend connects to and demonstrates the backend functionality.

## Tech Stack

- HTML
- CSS
- Vanilla JavaScript
- Fetch API for backend communication
- JSDoc documentation generated in `scripts/docs/`

## Features

- Landing page with search entry point and platform statistics
- User registration for customer and business accounts
- Login and guest login flows
- Offer listing with search, filtering, sorting, and pagination
- Offer detail page with package selection
- Business and customer profile pages
- Own profile page with editable profile data and order-related views
- Review display, filtering, and review submission dialogs
- Imprint and privacy policy pages

## Local Setup

This project does not include a package manager setup or build script. It is a static frontend that expects a running backend API.

1. Start the related Coderr backend.
2. Serve this frontend with a local static server, for example with the Visual Studio Code Live Server extension.
3. Open `index.html` in the browser through the local server.

The backend API base URL is configured in `shared/scripts/config.js`.

## Related Backend Repository

[Backend Repository](https://github.com/codebySaschaHeinze/coderr-backend)
