# William Tuckwell | WTStudio

**Junior Software Engineer / Web Developer · South Wales, UK**

I build websites for small businesses through WTStudio and develop Python/Django applications. I have delivered websites for RM Plastering & Finishing, Evan Thomas Agricultural & Fencing and The Kitchen Suite, and completed Software Engineering Level 3 at London Imperial College.

**[Portfolio website](https://wtstudio.net) · [GitHub](https://github.com/willtuckwell1)**

## About this portfolio

This repository documents three delivered client websites. It is a **case-study portfolio, not a source-code repository**: client code, configuration and business data are not included. The descriptions below distinguish implemented features from integrations that depend on client configuration.

For publicly inspectable application code, see [Tuckwells Newsroom](https://github.com/willtuckwell1/tuckwells-newsroom).

## Client work

### RM Plastering & Finishing

**[Live website](https://rmplasteringandfinishing.com/)**

**Brief:** Present a South Wales plastering business clearly online, showcase completed work and help prospective customers get in touch.

**My contribution**

- Built a responsive single-page website using HTML, CSS and JavaScript.
- Organised services, a project gallery, business information and contact options into a clear enquiry journey.
- Used GitHub and Netlify for version-controlled website delivery.
- Added a standards-based XML sitemap and robots.txt with the correct production domain.
- Updated the Netlify build to publish both crawl files, checked the build in isolation and verified the deployed sitemap.

**Technical decision:** The sitemap contains the homepage only. In-page sections are not separate pages, so adding fragment URLs would misrepresent the site's structure.

**Stack:** HTML · CSS · JavaScript · Git/GitHub · Netlify

### Evan Thomas Agricultural & Fencing

**Brief:** Showcase agricultural and fencing services, make project photography easy to browse and support customer enquiries.

**My contribution**

- Developed responsive service and gallery interfaces using HTML, CSS and JavaScript.
- Implemented an enquiry journey with frontend handling and Netlify serverless functions.
- Added automated enquiry tests and a build script for the published website.
- Worked with version-controlled deployment and ongoing website updates.

**Technical focus:** The project separates browser-side enquiry handling from server-side functions and includes a dedicated enquiry test file.

**Stack:** HTML · CSS · JavaScript · Node.js · Netlify Functions · Git/GitHub

### The Kitchen Suite

**Brief:** Present a kitchen business online and provide routes for prospective customers to make contact and arrange appointments.

**My contribution**

- Developed the website interface with HTML, CSS and JavaScript.
- Implemented serverless handlers for booking and chat functionality.
- Added Google OAuth integration code to support the booking setup.
- Documented deployment, booking and chat-assistant configuration for handover.

**Technical focus:** Booking and OAuth integration code is part of the implementation; live integration availability depends on the client's credentials and service configuration. This portfolio does not claim independently verified live booking or chat operation.

**Stack:** HTML · CSS · JavaScript · Node.js · Netlify Functions · Google OAuth

## Software engineering project

### [Tuckwells Newsroom — public source code](https://github.com/willtuckwell1/tuckwells-newsroom)

A Django news application created as a software engineering capstone project.

- Reader, journalist and editor roles with permissions.
- Article review and approval workflows.
- Account registration, authentication and password reset.
- Publisher/journalist subscriptions and newsletters.
- A token-authenticated REST API.
- Automated tests and MariaDB support.

This is the best starting point for reviewing my application structure, data modelling, permissions, API implementation and testing.

## Skills demonstrated

| Area | Evidence |
| --- | --- |
| Frontend development | Responsive HTML/CSS interfaces, JavaScript galleries and enquiry journeys |
| Backend development | Django application work and Node.js serverless handlers |
| APIs and integrations | Token-authenticated Django REST API; booking and OAuth integration code |
| Testing | Newsroom automated tests; dedicated client enquiry tests |
| Deployment | Git/GitHub workflows, Netlify builds and deployment verification |
| Client delivery | Three delivered business websites and project handover documentation |
| Search discovery | XML sitemap, robots.txt and production URL verification for RM Plastering |

## Contact

Visit **[wtstudio.net](https://wtstudio.net)** or **[my GitHub profile](https://github.com/willtuckwell1)**.

Client websites and associated branding remain the property of their respective owners. This repository contains original portfolio documentation only; no licence to client source code or assets is granted.
