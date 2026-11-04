# William Tuckwell | WTStudio

**Junior Software Engineer / Web Developer · South Wales, UK**

I build websites for small businesses through WTStudio and develop Python/Django applications. My work spans client websites, serverless enquiry handling, interactive galleries and application development. I completed Level 3 Software Engineering training through HyperionDev with Imperial College London.

**[Portfolio website](https://wtstudio.net) · [GitHub](https://github.com/willtuckwell1) · [Online CV](https://willtuckwell1.github.io/MyCV/) · [Download CV (PDF)](https://github.com/willtuckwell1/MyCV/blob/main/William_Tuckwell_CV-Updated.pdf)**

## About this portfolio

This repository documents client website implementations, distinguishing live deployments from development work. It is a **case-study portfolio, not a source-code repository**: client code, configuration and business data are not included. The descriptions below distinguish implemented features from integrations that depend on client configuration.

**Client confidentiality:** Client repositories remain private. This public portfolio contains written summaries and links only, not client source files, images, credentials or deployment configuration.

For publicly inspectable application code, see [Tuckwells Newsroom](https://github.com/willtuckwell1/tuckwells-newsroom).

## Client work

### Live website links

- [Tom Pugh Contracting](https://tompughcontracting.com/)
- [RM Plastering & Finishing](https://rmplasteringandfinishing.com/)
- [The Kitchen Suite](https://thekitchensuite.co.uk/)
- [SJH & Sons](https://sjhandsons.co.uk/)

These links open the public websites, not their private source repositories.

### Tom Pugh Contracting — services, project galleries and enquiries

**[Live website](https://tompughcontracting.com/)**

**Brief:** Present a contracting business's services clearly, organise a substantial collection of project photography and make it easy to enquire about specific services.

**My contribution**

- Built seven responsive pages covering Home, Services, Plant Hire, Haulage, Projects, Our Approach and Contact.
- Developed a coordinated green-and-neutral visual identity using the client's logo, supplied photography and locally hosted typography.
- Created a crossfading homepage slideshow that preloads the next image, pauses in hidden tabs and respects reduced-motion preferences.
- Organised project photography into selectable categories with full-size photo viewers and shareable gallery links.
- Connected service-specific enquiry links to a preselected contact form and implemented server-side email handling through Netlify Functions and Resend.
- Added an automated enquiry test suite and refined navigation, galleries and forms for phone, tablet and desktop layouts.
- Published the website on its custom domain with HTTPS and documented hosting and handover requirements.

**Technical decisions:** Load additional project photography on demand, keep service journeys connected to the enquiry form, and preserve normal mobile navigation with touch-friendly controls.

**Stack:** HTML · CSS · JavaScript · Node.js · Netlify Functions · Resend · DNS/HTTPS

### SJH & Sons — construction website, 3D animation and enquiry delivery

**[Live website](https://sjhandsons.co.uk/) · [Slideshow gallery](https://sjhandsons.co.uk/gallery)**

**Brief:** Create a distinctive website for a Cardiff construction business, showcase its services and completed work, and deliver quote enquiries to the business inbox.

**My contribution**

- Built a seven-page responsive website covering the homepage, services, projects, gallery, about, reviews and contact.
- Created a Three.js house-building animation with staged construction, an orbiting camera and synchronised captions.
- Adapted the experience for phones: normal page scrolling, independently timed repeating animation and portrait camera framing, while preserving desktop scroll-controlled playback.
- Built a photo slideshow with thumbnails, previous/next controls, keyboard navigation, touch-swipe support and optional automatic playback.
- Implemented server-side enquiry delivery through Netlify Functions and Resend, including input validation, HTML escaping, a honeypot, request-size limits and explicit error responses.
- Added five automated function tests covering request validation, missing configuration, email payload generation and provider rejection.
- Deployed through Netlify, configured the custom domain and sending-domain DNS, and verified HTTPS and delivery of a clearly labelled test enquiry.

**Technical decisions:** Keep email credentials server-side, publish only allowlisted website assets, and separate mobile animation playback from page scrolling so the visual experience does not block navigation.

**Stack:** HTML · CSS · JavaScript · Three.js · Node.js · Netlify Functions · Resend · DNS/HTTPS

### Coast Cafe — responsive food and seasonal website

**Status:** Implemented locally; this case study does not claim a verified public production deployment.

**Brief:** Give a traditional cafe a welcoming online presence, make its food and menus easy to explore, and reflect client feedback in the design.

**My contribution**

- Built a responsive cafe website with food photography, favourites, menu content, facilities and visitor information.
- Refined the colour palette, typography and visual styling around the cafe's branding and menu artwork.
- Added a separate Christmas page with a coordinated seasonal design and festive menu artwork that visitors can open full size.
- Used descriptive image alternatives, a skip link, semantic sections and lazy-loaded supporting photography.
- Iterated on the layout, imagery and menu presentation in response to client feedback.

**Technical decision:** Keep the everyday and seasonal menus connected through clear navigation, while giving the Christmas page its own coordinated visual treatment.

**Stack:** HTML · CSS · Responsive design · Accessible content

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

**[Live website](https://thekitchensuite.co.uk/)**

**Brief:** Present a temporary-kitchen business online and provide routes for prospective customers to make contact and arrange appointments.

**My contribution**

- Developed the website interface with HTML, CSS and JavaScript.
- Implemented serverless handlers for booking and chat functionality.
- Added Google OAuth integration code to support the booking setup.
- Documented deployment, booking and chat-assistant configuration for handover.
- Separated the public website interface from server-side integration settings, keeping credentials out of the frontend and public portfolio.

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
| Frontend development | Responsive HTML/CSS interfaces, keyboard/touch slideshow controls and Three.js animation |
| Backend development | Django application work and Node.js serverless handlers |
| APIs and integrations | Token-authenticated Django REST API; Resend email delivery; booking and OAuth integration code |
| Testing | Newsroom automated tests; client enquiry tests including payload escaping and provider failures |
| Deployment | Git/GitHub workflows, Netlify builds and deployment verification |
| Client delivery | Business website case studies, feedback-led iteration, domain setup and project handover documentation |
| Search discovery | XML sitemap, robots.txt and production URL verification for RM Plastering |

## Contact

Visit **[wtstudio.net](https://wtstudio.net)** or **[my GitHub profile](https://github.com/willtuckwell1)**.

Client websites and associated branding remain the property of their respective owners. This repository contains original portfolio documentation only; no licence to client source code or assets is granted.
