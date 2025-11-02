# TODO List for Funds Opportunities Remainder System

## 1. Install Dependencies
- [x] Install react-router-dom in frontend if not present

## 2. Frontend Routing
- [x] Update App.js to include React Router with routes: / (Home), /login (Login), /dashboard (Dashboard), /opportunities (Opportunities)

## 3. Home Page
- [x] Create frontend/src/pages/Home.js with title, logo, link to login
- [x] Create frontend/src/pages/Home.css for styling

## 4. Apply for Funds Functionality
- [x] Update Opportunities.js to add "Apply" button for each opportunity
- [x] Add backend route POST /api/opportunities/apply/:id to handle applications

## 5. In-App Notifications
- [x] Update Dashboard.js to poll for new funds and show pop-up notifications

## 6. Enhance CSS
- [x] Improve CSS in all components for beauty: gradients, shadows, animations

## 7. Testing
- [ ] Test full flow: login, view opportunities, apply, notifications
