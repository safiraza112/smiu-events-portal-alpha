# SMIU Events Portal - Alpha

The SMIU Events Portal is a front-end website built for the SMIU Student Affairs Office. Students can browse upcoming events, explore societies and register for events. It has 6 responsive pages and is built with HTML, CSS and Bootstrap 5.3.3.

## Group Members
| Name | Roll No. | GitHub Username | Pages Built |
|---|---|---|---|
| Safi Raza (Member 1, Team Lead) | BSE-24S-069 | safiraza112 | Repo setup, navbar/footer, index.html, contact.html |
| Wakeel Hussain (Member 2) | BSE-24S-054 | wakeelh1 | events.html, event-details.html |
| Ibrahim Abbasi (Member 3) | BSE-24S-102 | abbasiibrahim851-web | societies.html, register.html |
| Umar Khan (Member 4) | BSE-24S-095 | umarkhan987 | Images and README |


## Screenshots
- Home page (phone):

  ![Home page on phone](images/home-phone.png)

- Home page (desktop):

  ![Home page on desktop](images/home-desktop.png)
  
## How to Run
1. Clone the repo.
2. Open `index.html` in a browser (internet is needed for Bootstrap CDN).

## Teamwork Problem and Solution
While working on the project, we faced a merge conflict in css/style.css. Member 1 had already merged Pull Request #1 into main with carousel photo styles and the icon hover effect. After that, Member 2 (Wakeel Hussain) opened Pull Request #2 from his alpha branch with new table and status badge styles. Both of us had added CSS to the same part of style.css, so GitHub showed "This branch has conflicts that must be resolved" and blocked the merge. We solved it with GitHub's "Resolve conflicts" editor. We removed only the conflict marker lines (<<<<<<<, ======= and >>>>>>>) and kept both sets of CSS, so nobody's work was deleted. Then we marked the file as resolved, committed the merge, approved the Pull Request and merged it into main. After that, we pulled the latest main and checked that the Home page and the new styles still worked. From this, we learned to pull the latest main before starting new work and to merge Pull Requests one at a time to avoid conflicts.
Built with HTML5, CSS3, Bootstrap 5.3.3, Bootstrap Icons, Git and GitHub.
