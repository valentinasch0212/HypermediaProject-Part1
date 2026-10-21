# Personal CV Website — Hypermedia Project Part 1

**Student:** Valentina Andrea Schotborgh Barrios  
**Course:** Multimedia and User Interfaces — Universitat de Girona

## Project overview

This project is a personal curriculum vitae website. Its purpose is to present my academic background, technical skills, projects, experience and contact details in a clear, accessible, and organized format. The website is a static, single-page document written in English using HTML5 and an external CSS stylesheet. It does not require JavaScript, a backend, or any framework.

## User persona (hypothetical)

**Name:** James Clark (fictional)  
**Age:** 32  
**Occupation:** Junior technical recruiter  
**Goal:** Quickly evaluate the technical profile and academic background of a student applying for an internship or entry-level software development role.  
**Needs:** Readable descriptions of projects, clear skills, concise experience, and direct contact links.  
**Frustrations:** Complicated navigation, long unstructured text, and contact information that is difficult to find.  
**Typical use:** James opens the CV on a laptop during an initial candidate screening, checks the projects and skills, and follows the GitHub link if the profile looks relevant.

This persona is an illustrative design assumption, not the result of a real user interview.

## Information architecture

The website uses a single-page information architecture because its content is a personal CV rather than a large collection of separate resources. This choice makes it possible to access the main information without loading different pages or learning a complex navigation system. The first visible area introduces my name, academic profile, current location, and photograph. A navigation menu follows the introduction and provides links to the main sections of the document. Each menu link uses an HTML anchor pointing to a section identifier, such as `href="#projects"` and `id="projects"`.

The content is organized into six sections: About, Skills & Languages, Projects, Experience, Education, and Contact. About provides a short professional summary so that visitors can quickly understand my interests and background. Skills & Languages groups technical knowledge and language proficiency in two related columns. Projects gives concrete examples of academic and technical work, using descriptive headings and lists to help readers scan the information. Experience presents tutoring and leadership activities, while Education summarizes my academic qualifications. Contact is placed at the end and contains only my email address and GitHub profile, allowing interested visitors to take the next step.

This hierarchy is intended for a hypothetical recruiter or academic visitor who may have little time to read the entire page. Clear section titles and consistent navigation labels support quick scanning. The page also includes a Back to top link so users can return to the beginning without searching for the menu. Since the website is relatively short and its content is fixed, a search bar, additional pages, or more complicated navigation would not add much value. Semantic HTML elements, including `header`, `nav`, `main`, `section`, `article`, and `footer`, describe the organization of the document.

## Visual design

The visual design aims to be simple, professional, and readable, following the introductory HTML and CSS techniques covered in class. A light lavender background and dark text create a soft contrast, while a darker purple accent is used for headings, navigation links, and selected details. This limited palette helps establish a consistent visual identity without making the CV look like a complex commercial website. Arial is used as the main font because it is familiar, widely available, and easy to read on different screens.

The top area is the most prominent part of the page. It contains the main heading with my full name, a short academic subtitle, my current location, and a profile photograph. Flexbox places the text next to the photograph on wider screens. The navigation menu is visually separated from the introduction with a thin border and spacing. Throughout the page, headings use a clear hierarchy: one main `h1`, section headings with `h2`, and subsection or entry headings with `h3`. Paragraphs and lists keep the text organized, while margins and padding create space between sections and improve readability.

The Skills & Languages section uses a two-column Flexbox layout to present related information side by side. Other sections follow a vertical reading order, which is appropriate for a CV. CSS selectors based on elements, classes, and identifiers are used to apply consistent styles. The box model is visible in the spacing, borders, and content widths. Media queries adjust the layout on narrower screens: the introductory elements stack vertically, the two columns become one, and navigation links can wrap onto additional lines. The overall design intentionally avoids animations, elaborate effects, and frameworks because the objective is to demonstrate a clear application of the course material. The Figma design proposal is based on the same visual structure as the implemented website.

## Technologies and course concepts

- HTML5: document structure, headings, paragraphs, lists, images, hyperlinks, and semantic elements.
- External CSS: selectors, typography, colors, margins, padding, borders, and the box model.
- Flexbox: header, navigation, two-column skills section, and footer.
- Media queries: responsive layout for smaller screens.

## Project structure

```text
cv-web/
├── index.html
├── style.css
├── assets/
│   └── foto_perfil.JPG
└── README.md
```

## How to run

Open `index.html` in a web browser, or use the Live Server extension in Visual Studio Code. No installation or build step is necessary.

## Project links

- **Figma design:** https://www.figma.com/design/knP3ikM76ySNg6wk7nfnQ6/Sin-t%C3%ADtulo?node-id=0-1
- **GitHub repository:** TODO — add the repository URL after publication.
- **Live website:** TODO — add the GitHub Pages URL after publication.


