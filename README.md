# Civic Issues Reporter

A vanilla JavaScript and HTML web application for citizens to report civic issues and for authorities to manage them.

## Overview
Civic Issues Reporter empowers citizens to report problems like potholes, streetlights, garbage, and water leaks directly to their local authorities. It includes a frontend dashboard for citizens to track their reports and a comprehensive admin panel for authorities to triage, route, and resolve issues.

## Technology Stack
- **Frontend Core:** HTML5, Vanilla JavaScript, CSS
- **Styling:** Tailwind CSS (via CDN)
- **Icons:** Lucide Icons (via CDN)
- **Mapping:** Leaflet.js (for geolocation and map visualization)
- **Authentication & Database:** Supabase
- **Email/OTP:** EmailJS

## Features
### Citizen Portal
- **Dashboard:** Platform-wide statistics and recent reports feed.
- **Reporting Form:** Categorized issue reporting with priority levels, geolocation (map pinpointing), and photo evidence uploads.
- **My Reports:** View historical reports, track status, and provide rating/feedback on resolved issues.
- **Authentication:** Email-based registration with OTP verification.

### Admin Portal
- **Analytics Dashboard:** Visual insights into resolution times, total reports, and active alerts using Chart.js.
- **Live Map:** Geographic clustering of active issues.
- **Triage Center:** Filter pending tasks by department, criticality, or status.
- **Action Commands:** Broadcast messages, transfer tasks between departments, and update issue statuses.

## File Structure
The project does not require a build step. All files are pure HTML, CSS, and JS.
- `index.html` - Landing page.
- `login.html` & `signup.html` - Authentication pages.
- `dashboard.html`, `report.html`, `my-reports.html`, `profile.html`, `settings.html` - Citizen views.
- `admin.html` - Administrative authority view.
- `report-details.html` - Standalone detailed view of a single report.

## Setup Instructions
Since this is a vanilla static site, you can simply open any of the HTML files directly in your browser.
For the best experience, host the files using a simple local server (e.g., Live Server extension in VS Code) to ensure full compatibility with modern browser features like geolocation and local storage.

1. Clone the repository.
2. Open the project in your IDE.
3. Use a static server (like VS Code Live Server) on the root directory and navigate to `index.html` or `login.html`.
