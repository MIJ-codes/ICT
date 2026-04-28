# AGENTS.md — ICT Notes Integration Rules

## Goal
Update `Chapters/Chapter4.tex` by merging missing content from:
- `Information & Communication Technology (Class-11-12) (1).pdf`
- current `Chapter4.tex`

Do NOT append everything at the end. Integrate content into the correct existing sections.

## Style Rules
- Notes must be in English.
- Use existing LaTeX template only.
- Do not change `main.tex`.
- Do not change `preamble.tex` unless asked.
- Do not spam boxes.
- Use `definitionbox` only for formal definitions.
- Use `formulabox` only for formulas/structures.
- Use `summarybox` only at the end of a major section.
- Use normal paragraphs and itemize/enumerate for ordinary explanation.
- Avoid raw arrow bullets. Use `itemize` and `enumerate`.
- Keep explanations exam-ready but not bloated.

## Integration Rules
For each missing topic:
1. Find the correct existing section.
2. Insert content inside that section or create a nearby subsection.
3. Keep logical order.
4. Preserve all existing working code examples.
5. Do not duplicate definitions already present.
6. If a topic already exists, expand it instead of making a new duplicate section.

## Required Additions from the new book

### Core Concepts section
Add:
- WWW as a dynamic interactive graphical hypertext information system.
- Explain that web is built from:
  1. HTML
  2. HTTP
  3. Web Browser
- Clarify Internet vs WWW.

### Website / Webpage area
Add:
- Webpage may contain text, audio, video, still images, animation.
- Webpage is also called a web document.
- Homepage = first page shown after entering a website.

### Types of Website section
Expand static and dynamic websites with:
Static:
- fixed content
- no user input/update
- fast loading
- no database connection
- one-way server-to-client communication
- made with HTML/CSS
- advantages and disadvantages

Dynamic:
- runtime content/design changes
- database support
- user input/update possible
- server-side languages: PHP, ASP.NET, JSP
- advantages and disadvantages

Keep the comparison table, but expand it using the book.

### New subsection after Types of Website
Add:
- Local webpage
- Remote webpage

### New section near URL/Browser
Add:
- HTTP
- client request
- server response
- browser displays webpage
- HTTP connects browser and server, sends request, brings webpage, disconnects

### New section near HTTP
Add:
- How the Web Works
Use ordered flow:
1. User enters URL
2. Browser sends HTTP request
3. Request goes through internet
4. Server finds requested HTML/page
5. Server sends response
6. Browser interprets HTML
7. Browser displays page

### New section near HTTP
Add:
- FTP
- upload
- download
- login/password may be required
- private access
- public access

### Browser/Search Engine section
Expand:
- browser interprets webpage code and displays result
- browser can download information
- browser can upload information
- browser navigates through hyperlinks
- examples: Internet Explorer, Mozilla Firefox, Google Chrome, Safari, Opera

Add:
- Web browsing
- Direct browsing by URL
- Keyword browsing through search engine

### Website classification by purpose
Add section after Types of Website:
- Archive site
- Business site
- E-commerce site
- Community site
- Database site
- Development site
- Directory site
- Download site
- Game site
- Information site
- News site

Use a longtable if appropriate.

## Validation
After editing:
- Ensure LaTeX compiles with XeLaTeX.
- Do not leave duplicate headings.
- Do not leave Bengali text in the note.
- Do not create a giant ending dump section.