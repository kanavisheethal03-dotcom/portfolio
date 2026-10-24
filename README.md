# Personal Portfolio Website

A beginner-friendly student portfolio made with HTML5 and CSS3. Replace the bracketed text with your own details before submitting.

## Project files

```text
portfolio-project/
├── index.html
├── style.css
├── README.md
├── images/                 (optional, only if you add a profile image)
└── screenshots/
    ├── desktop.png         (add your screenshot)
    └── mobile.png          (add your screenshot)
```

The `images/` folder is optional. The `screenshots/` folder is for your own submission captures; add the desktop and mobile screenshots after you take them.

## Personalize the portfolio

1. Open `index.html` in Visual Studio Code.
2. Use **Edit → Find** (or `Ctrl+F` on Windows/Linux, `Cmd+F` on Mac) to find text in square brackets, such as `[Your Name]`.
3. Replace each placeholder with accurate information. Update the school, degree, email, GitHub, and LinkedIn details only if you want them shown.
4. Keep project descriptions truthful. PublicAsset360 is labeled as a concept or work in progress; do not describe it as completed unless that is accurate.
5. Save your changes with `Ctrl+S` or `Cmd+S`.

## Create or open the project in Visual Studio Code

If you are copying the project to your own computer:

1. Create a folder named `portfolio-project`.
2. Inside it, create `index.html` and `style.css`. Optionally create `images/` for a profile image and `screenshots/` for your captures.
3. Copy the complete HTML into `index.html` and the complete CSS into `style.css`.
4. In Visual Studio Code, choose **File → Open Folder…** and select `portfolio-project`.
5. Keep `index.html` and `style.css` in the same folder so the stylesheet link works.

## Run it in Google Chrome

1. Save `index.html` and `style.css`.
2. Open the `portfolio-project` folder in your file manager.
3. Open `index.html` with Google Chrome (double-click it, or right-click and choose **Open with → Google Chrome**).
4. After editing either file, save it and refresh the Chrome tab.

The portfolio itself is plain HTML and CSS. It does not need a server, account, database, or JavaScript to run.

## Test the page

### Navigation

- Click **Home**, **About**, **Skills**, **Projects**, and **Contact** in the header. Each should scroll to its matching section.
- Click the hero buttons and the footer's Home link.
- Keyboard-test the page by pressing `Tab` to move through the links and buttons. The focused item should be visibly highlighted.
- Check that the email and social links point to your own details after you replace their placeholders.

### Mobile and tablet layout

1. Open the page in Chrome.
2. Open Developer Tools: `Ctrl+Shift+I` on Windows/Linux or `Cmd+Option+I` on Mac.
3. Turn on the device toolbar: `Ctrl+Shift+M` on Windows/Linux or `Cmd+Shift+M` on Mac.
4. Choose a phone preset or enter a width around 390 px. Also check a tablet-width view and a desktop-width view.
5. Scroll through every section. Confirm the text is readable, the cards fit, the navigation remains usable, and there is no sideways scrolling.
6. Turn off the device toolbar to return to the regular desktop view.

## Capture submission screenshots

1. In Chrome, show the page at desktop width and scroll to the top.
2. Capture the page using your operating system's screenshot shortcut or Chrome DevTools' **Capture screenshot** command.
3. Repeat with the device toolbar set to a phone-width view.
4. Save the files in `screenshots/` as `desktop.png` and `mobile.png`.
5. Reopen each image to check that the page is legible and the browser controls do not cover important content.

## Short project description for the submission form

This project is a responsive personal portfolio website for Sheethal S Kanavi, a third-year Computer Science Engineering student. It uses semantic HTML5 to organize an introduction, education and interests, student-level skills, projects, and contact details. CSS3 provides the visual design, responsive layouts, keyboard-focus and hover states, and subtle motion without JavaScript or a CSS framework. The portfolio presents LinkSnap and identifies PublicAsset360 as a concept or work in progress.

## How to explain the code

- **HTML5** provides the page structure. Elements such as `header`, `nav`, `main`, `section`, `article`, and `footer` describe the role of each part of the page.
- **Section IDs and links** connect the navigation to the correct page sections without JavaScript.
- **CSS variables** keep the main colors and other repeated design values consistent and easy to change.
- **Flexbox and CSS Grid** arrange content such as navigation, skill labels, and project cards.
- **Media queries** adjust spacing and columns for smaller screens.
- **`:hover` and `:focus-visible`** provide interaction feedback for mouse and keyboard users.
- **CSS transitions and keyframe animation** add restrained visual motion. A reduced-motion rule respects visitors who prefer less animation.
- **No JavaScript is required** for this website; the navigation, layout, and visual effects use HTML and CSS.

## Final requirements checklist

- [ ] Header includes a name/logo and working Home, About, Skills, Projects, and Contact links.
- [ ] Hero introduces a third-year CSE student, includes a professional introduction and software/web-development career objective, and links to Projects and Contact.
- [ ] About section includes editable education, interests, teamwork, communication, and career-goal details.
- [ ] Skills include HTML5, CSS3, Python, C programming, and DBMS, described at an appropriate student level.
- [ ] LinkSnap is listed with React, Node.js, Express, and MongoDB.
- [ ] PublicAsset360 is clearly identified as a concept or work in progress.
- [ ] Contact section includes an editable email and optional GitHub/LinkedIn links. No nonfunctional form is presented as a working message service.
- [ ] Footer includes the student's name, a copyright line, and a link back to Home.
- [ ] HTML uses a valid document structure, character encoding, page title, viewport setting, semantic elements, useful link text, and unique section IDs.
- [ ] All website styling is in `style.css`; CSS variables, Flexbox/Grid, responsive media queries, hover/focus states, and suitable CSS-only motion are used.
- [ ] The page remains readable on mobile, tablet, and desktop without horizontal overflow.
- [ ] Personal placeholders have been replaced, and desktop and mobile screenshots have been saved in `screenshots/`.

The original internship PDF was not included with the brief provided for this build. This checklist follows the requirements in the attached text brief; compare it with the PDF if it contains additional criteria.
