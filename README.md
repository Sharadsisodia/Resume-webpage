# Resume-webpage
My resume 
# HTML Structure
The document starts with the standard `<!DOCTYPE html>` declaration, followed by the `<html>` element that contains all the content of the webpage.
## Head Section
Inside the `<head>` tag, there are two `<link>` elements. The first one links to a local CSS file named `style.css`, which likely contains the styling rules for the page. The second `<link>` imports the Font Awesome library from a CDN, which provides access to icons used in the contact section.

## Title
The `<title>` tag sets the title of the webpage, which appears on the browser tab.

## Body Section
The `<body>` contains all the content that will be displayed to the user.

### Header
The `<header>` element includes the name "Sharad Sisodia" and the title "Full Stack Developer," separated by horizontal rules (`<hr>`).

### Main Content
The `<main>` tag is used to encapsulate the primary content of the webpage.

#### Left Column (mainLeft)
This `<article>` contains three `<section>` elements for Contact, Skills, and Education. Each section has a heading (`<h2>`) and relevant content. The contact section uses Font Awesome icons for email, GitHub, and LinkedIn, followed by corresponding links.

#### Right Column (mainRight)
Another `<article>` that includes sections for About, Work Experience, and Projects. The About section describes the individual’s background and skills. The Work Experience section currently lists "Fresher," indicating no prior work experience. The Projects section details a Face Recognition System project with a link to the GitHub repository and a description of the project.

### Font Awesome Icons
Icons like `fa-envelope`, `fab fa-github`, and `fab fa-linkedin` are used to represent email, GitHub, and LinkedIn, respectively.
