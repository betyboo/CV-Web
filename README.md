# Elisabeth Argerich Masafrets – CV Website

Personal CV website created for the Hypermedia project (Part 1).

- **Live website:** (https://betyboo.github.io/CV-Web/)
- **Figma design:** https://www.figma.com/design/KG8qXTDh9yBHEbh2cMp5iu/CV-Web-%E2%80%93-Beth?node-id=0-1&t=3dYjv5c7MPFmd5As-1

---

## 1. Project analysis: User persona

**Maria Sánchez**, 35 – Technical Recruiter

- **Background:** She studied at the UAB and has worked in human resources for 10 years, the last 5 at her current company. She enjoys her job because it lets her meet interesting people from different departments.
- **Company:** A mid-sized tech company in Manresa (not a multinational, but not a startup either).
- **Context of use:** She reviews CVs on her work computer, but sometimes also on her phone during meetings or job fairs. She spends between 2 and 5 minutes on each CV and reviews about 30 CVs a day.
- **Goals:** She wants to find committed, hardworking people from the area, with the right skills, attitude and languages. She needs to quickly find how to contact the candidate, their education and their work experience.
- **Frustrations:** All CVs look the same, people write in 10 lines what could be said in 2, and she wastes time looking for contact details or projects she cannot find.
- **Tech level:** She knows very little about technology. She recognises some names and follows the requirements the technical team gives her.
- **Quote:** *"I want things to be simple, and to find someone who meets the company's main requirements and is a good match."*

---

## 2. Project analysis: Information architecture

The website is a single page designed for Maria, who reviews about 30 CVs a day and has little time. For this reason, the information is ordered from most to least important for her.

At the top there is a sticky navigation bar, so she can jump directly to any section without scrolling, and the "Contact me" button is always visible. The header shows my name, a photo, a one-line summary of who I am and the contact buttons, so in a few seconds she knows whose CV it is and how to reach me.

Next comes a short "About me" section, so she can see whether I would fit in the team. Then comes Experience, which I placed before Education because, for a developer position, real work experience is what is valued most. It is divided into technical experience and other experience, so the most relevant jobs are seen first.

After that, Projects & Community shows my attitude and involvement. Each project is explained in one simple sentence with a link, so Maria can easily forward it to the technical team. Then come Education and Skills, with the skills shown as tags that can be read at a glance.

Finally, the footer repeats the contact information, so if she reaches the end of the page she does not need to scroll back up.

---

## 3. Project analysis: Visual design

The main goal was to create a CV with personality, since Maria is tired of CVs that all look the same, but still easy and quick to read.

The colour palette uses a cream background (#FFF6EE), which is softer and more pleasant to read than pure white. Titles and text are dark (#2B2233) to give contrast and elegance. Each colour has a specific function: coral (#E07A5F) is only used for the main buttons, so Maria can quickly see what she can click; purple (#5B3FD1) is used for details such as lines, borders and links; and light peach (#F6D8C3) is used for tags and experience cards.

For the typography I combined Playfair Display and Lato. Playfair Display is an elegant serif font that adds personality, but it is only used for titles, where its large size keeps it readable. Lato is a sans-serif font that is very legible on screen, so it is used for the body text.

The layout uses cards and tags so the information can be scanned quickly. Each section has its own style (filled cards for experience, outlined cards for projects and plain blocks for education), so the sections are easy to tell apart. The dark footer closes the page and highlights the contact information. The website is also responsive, because Maria sometimes reviews CVs on her phone.

I was inspired by the Sonali – Developer Portfolio design on Dribbble, from which I took its clean, well-organised and visual style, and adapted it to my own colour palette and typography.

---

## 4. Technologies

- **HTML5** with semantic tags ('header', 'nav', 'main', 'section', 'article', 'footer').
- **CSS3** with custom properties (variables), Flexbox, CSS Grid and media queries for the responsive design.
- **Google Fonts** (Playfair Display and Lato).

No frameworks such as Bootstrap were used. Since this is a small static single-page website, plain CSS with Flexbox and Grid was enough to build the layout, and it keeps the code lighter and easier to understand.

### Possible improvements
- A hamburger menu for mobile devices (it would need JavaScript).
- Adding more projects to the portfolio as I finish them.
