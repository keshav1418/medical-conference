Medical-Conference
# Altius: Medical Conference Website

A multi-page React web application for **Altius**, a medical conference. Visitors can explore conference details, register for the event, learn about sponsorship and partners, and read the latest news, all within a clean blue-and-white interface.

## Live Demo
[Add your deployed link here]

## Screenshots
<!-- Add screenshots of Home, Conferences, Registration, etc. -->

## Features
- **Multi-page navigation** using React Router DOM, with no full page reloads
- **Conference listings** with a "View Details" modal for each conference
- **Registration flow** with pricing tables and **multi-currency support**
- **Modal-based interactions** managed with React `useState`
- **Sponsorship and Partners pages** for prospective sponsors and collaborators
- **Newsroom** for announcements and updates
- **Contact page** for enquiries
- **Authentication pages** (Sign in / Sign up)
- **Consistent theming** with CSS custom properties (primary color `#1A4FA0`)
- **Shared layout** with a Navbar and Footer across all pages

## Tech Stack
| Category | Technology |
|---|---|
| Framework | React (functional components and hooks) |
| Routing | React Router DOM |
| Styling | CSS3 with custom properties (variables) |
| State | `useState` |
| Dev environment | CodeSandbox / Node.js |

## Project Structure
```
src/
├── components/
│   ├── Navbar
│   └── Footer
├── pages/
│   ├── Home
│   ├── Conferences
│   ├── Registration
│   ├── Newsroom
│   ├── Partners
│   ├── Sponsorship
│   ├── Contact
│   └── Auth (Sign in / Sign up)
├── App.js
└── index.js
```

## Getting Started

### Prerequisites
- Node.js (v16 or later)
- npm or yarn

### Installation
```bash
# Clone the repository
git clone https://github.com/<your-username>/<repo-name>.git

# Go to the project folder
cd <repo-name>

# Install dependencies
npm install

# Start the development server
npm start
```

The app runs at `http://localhost:3000`.

### Build for production
```bash
npm run build
```

## Design
- **Primary color:** `#1A4FA0` (blue) on a white background
- Colors and spacing are defined as CSS variables, so the theme is easy to change in one place
- Layout adapts to different screen sizes

## What I Learned
- Structuring a React app with a component-per-page architecture
- Client-side routing with React Router DOM
- Building modal overlays and form flows with state
- Building a themeable design system with CSS custom properties
- Debugging module resolution and JSX issues

## Future Improvements
- Backend integration for real registration and authentication
- Payment gateway integration
- Admin dashboard for managing conferences and registrations
- Speaker and schedule pages

## Author
**Keshav**
- GitHub: (https://github.com/keshav1418)
- LinkedIn: https://www.linkedin.com/in/keshav-manchikanti-a738332b1/
- portfoilo : https://keshav1418.github.io/MY-PORTFOILO/

## License
This project is open source and available under the [MIT License](LICENSE).
