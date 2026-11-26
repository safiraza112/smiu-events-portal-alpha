# SMIU Events Portal - Alpha

The SMIU Events Portal is a front-end website built for the SMIU Student Affairs Office. Students can browse upcoming events, explore societies and register for events. It has 6 responsive pages and is built with HTML, CSS and Bootstrap 5.3.3. It was developed as a group project using one shared GitHub repository, separate branches, Pull Requests and code review.

## Group Members

| Name | Roll No. | GitHub Username | Pages Built |
|---|---|---|---|
| Safi Raza (Member 1, Team Lead) | BSE-24S-069 | safiraza112 | Repo setup, navbar/footer, index.html, contact.html |
| Wakeel Hussain (Member 2) | BSE-24S-054 | wakeelh1 | events.html, event-details.html |
| Ibrahim Abbasi (Member 3) | BSE-24S-102 | abbasiibrahim851-web | societies.html, register.html |
| Umar Khan (Member 4) | BSE-24S-095 | umarkhan987 | Images and README |

## Pages

- **Home (index.html):** responsive navbar with the SMIU logo, hero section with a campus photo and call-to-action buttons, carousel of 3 featured events, 3 upcoming event cards, a "Why Join" section with Bootstrap Icons, and a footer.
- **Events (events.html):** grid of 8 event cards (1 column on phone, 2 on tablet, 4 on desktop) with date and category badges, plus a striped, hoverable schedule table.
- **Event Details (event-details.html):** banner image, info list (date, time, venue, fee), an accordion for Schedule / Speakers / Rules, and a "Register Now" button that opens a Bootstrap modal with a short form.
- **Societies (societies.html):** 6 society cards with member-count badges and Join buttons, and an admissions alert.
- **Register (register.html):** full registration form built with the Bootstrap grid (two columns on desktop, one on phone) with text, email, phone, select, radio, checkbox and textarea fields.
- **Contact (contact.html):** contact form, office details, a map, and a "Meet the Team" section with one card per group member.

## Technologies Used

- HTML5 and CSS3 (custom styles in css/style.css with CSS variables)
- Bootstrap 5.3.3 (CDN) and Bootstrap Icons
- Git and GitHub (branches, Pull Requests and code review)

Bootstrap components used: navbar, carousel, cards, grid, badges, accordion, modal, table, alert, form controls and buttons.

## Screenshots

Home page (phone):

![Home page on phone](images/home-phone.png)

Home page (desktop):

![Home page on desktop](images/home-desktop.png)

## How to Run

1. Clone the repository: git clone https://github.com/safiraza112/smiu-events-portal-alpha.git
2. Open the project folder.
3. Open `index.html` in a browser. You can also use the Live Server extension in VS Code.
4. An internet connection is needed for Bootstrap, Bootstrap Icons and the fonts, which load from a CDN.

## Teamwork

We worked with one shared repository. Nobody pushed directly to main. Each member worked on their own branch, opened a Pull Request, and a different member reviewed and merged it. Pull Requests #1 to #13 in this repository show the history.

## Teamwork Problem and Solution

While working on the project, we faced a merge conflict in css/style.css. Member 1 had already merged Pull Request #1 into main with carousel photo styles and the icon hover effect. After that, Member 2 (Wakeel Hussain) opened Pull Request #2 from his alpha branch with new table and status badge styles. Both of us had added CSS to the same part of style.css, so GitHub showed "This branch has conflicts that must be resolved" and blocked the merge. We solved it with GitHub's "Resolve conflicts" editor. We removed only the conflict marker lines and kept both sets of CSS, so nobody's work was deleted. Then we marked the file as resolved, committed the merge, approved the Pull Request and merged it into main. A similar conflict appeared later when the navbar logo change touched style.css and all six pages, and we solved it the same way. From this, we learned to pull the latest main before starting new work and to merge Pull Requests one at a time to avoid conflicts.

## Credits

The SMIU logo and campus photo are from the official SMIU website and are used for this student project. Event and society photos are free stock photos.
