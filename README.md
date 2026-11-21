# Church Website -  Rich Pastures Church International Website

## Project Name & Description

This project is a multi-page, HTML-only church website for Rich Pastures Church International. It introduces the church, shares service and news information, provides contact details, and offers a membership and volunteer application.

## Pages Included

All paths below are relative to the project folder:

- [`index.html`](./index.html) — Home page and weekly schedule overview.
- [`about.html`](./about.html) — Church history, leadership, and core beliefs.
- [`services.html`](./services.html) — Weekly service schedule and audio sermons.
- [`blog.html`](./blog.html) — Recent announcements and a weekly reflection.
- [`contact.html`](./contact.html) — Location information and inquiry form.
- [`pages/application.html`](./pages/application.html) — Membership and volunteer application.

## HTML Features Used

- **Semantic structure:** Elements including `<header>`, `<nav>`, `<main>`, `<section>`, `<article>`, `<footer>`, `<figure>`, `<figcaption>`, `<address>`, and `<time>` organize page content.
- **Forms:** Labeled text, email, telephone, and date inputs; select options; radio buttons; checkboxes; textareas; fieldsets and legends; required fields; and submit buttons.
- **Data tables:** The services page uses a caption, column headers with `scope="col"`, and time row headers with `scope="row"`.
- **Media:** Images include alternative text and captions; an audio player provides controls and an MP3 source.
- **Links:** Relative links navigate between local pages, including `../` paths from the `pages` subfolder. Email links use `mailto:`, and social links point to external sites.
- **Text content:** Headings, paragraphs, ordered and unordered lists, emphasized text, and a Bible verse quotation use appropriate HTML elements.

## What I Learned

This project taught me how semantic HTML communicates to browsers and assistive technologies what the purpose and structure of content is. It also taught me how to associate labels with form controls, grouping related controls using fieldsets and legends, using table scopes to make header relationships clear, and providing alternate text for images.I also learned that relative paths are based on a page’s folder. If links are from `pages/application.html` they will use `../` to get to files in the parent folder.

## Challenges I Encountered

- **Subfolder navigation:** Links from `pages/application.html` initially need to travel up one directory to reach the site's other pages. Using paths such as `../index.html` and `../contact.html` fixes this; the application page itself remains `application.html`.
- **Media attribution:** The project contains local media files, but no creator, source URL, or license details were present in the project documentation or page markup. Their provenance must be confirmed before publication; those credits are not guessed here.

## Resources & Media Attributions

The following local assets are referenced by the site:

| Asset | Used on | Source and license |
|---|---|---|
| [`images/church-worshippers.jpg`](./images/church-worshippers.jpg) | `index.html` | Source and license were not provided in the project files. Confirm the creator, source URL, and license/permission before publishing. |
| [`images/church-leaders.jpg`](./images/church-leaders.jpg) | `about.html` | Source and license were not provided in the project files. Confirm the creator, source URL, and license/permission before publishing. |
| [`media/Sermon.mp3`](./media/Sermon.mp3) | `services.html` | Source and license were not provided in the project files. Confirm the recording's creator, source URL, and license/permission before publishing. |

No external image or audio source links or license credits are currently documented.