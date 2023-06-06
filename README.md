# Building a Simple HTML Page with CSS and Images

### Background:
HTML (Hypertext Markup Language) is the standard markup language for creating web pages. CSS (Cascading Style Sheets) is a style sheet language used to describe the presentation of a document written in HTML. Images are an essential part of web design, as they help to create an engaging and visually appealing user experience.

### Example:
Here's an example of what a finished HTML page with CSS and images might look like:

```html
<!DOCTYPE html>
<html>
<head>
	<title>My Simple HTML Page</title>
	<link rel="stylesheet" type="text/css" href="styles.css">
</head>
<body>
	<header>
		<h1>Welcome to My Page!</h1>
		<nav>
			<ul>
				<li><a href="#about">About Me</a></li>
				<li><a href="#services">My Services</a></li>
				<li><a href="#contact">Contact Me</a></li>
			</ul>
		</nav>
	</header>

	<main>
		<section id="about">
                <h2>About Me</h2>
				<p>Hi there! My name is Jane and I'm a web developer based in San Francisco. I love creating beautiful and functional websites that help businesses grow.</p>
				<img src="profile-pic.jpg" alt="Jane's Profile Picture">
		</section>

		<section id="services">
			<h2>My Services</h2>
			<ul>
				<li>Website Design and Development</li>
				<li>Search Engine Optimization</li>
				<li>Social Media Marketing</li>
			</ul>
		</section>

		<section id="contact">
			<h2>Contact Me</h2>
			<form>
				<label for="name">Name:</label>
				<input type="text" id="name" name="name"><br>

				<label for="email">Email:</label>
				<input type="email" id="email" name="email"><br>

				<label for="message">Message:</label>
				<textarea id="message" name="message"></textarea><br>

				<input type="submit" value="Send">
			</form>
		</section>
	</main>

	<footer>
		<p>&copy; 2021 Jane Doe</p>
	</footer>
</body>
</html>
```

### Problem Statement:
Your task is to build a simple HTML page with CSS and images. The page should include the following elements:
- A header with a navigation menu
- A main section with three subsections (About Me, My Services, and Contact Me)
- A footer with a copyright statement

You should also include the following:
- A stylesheet file to define the styles for the page
- At least one image on the page

### Releases:
**Release 0:** Create the basic HTML structure for the page. Add the header, main section, and footer to the page.

**Release 1:** Add a navigation menu to the header. The menu should include links to the About Me, My Services, and Contact Me sections of the page.

**Release 2:** Add the About Me section to the main section of the page. Include a profile picture and a brief bio.

**Release 3:** Add the My Services section to the main section of the page. Include a list of services you offer.

**Release 4:** Add the Contact Me section to the main section of the page. Include a form with fields for name, email, and message.

**Release 5:** Add a stylesheet file to the page. Define the styles for the header, navigation menu, main section, and footer.

### Hints:
- Use HTML tags to structure your page, such as `<header>`, `<nav>`, `<main>`, and `<footer>`.
- Use CSS to style your page, such as changing the font, color, and background of elements.
- Use the `<img>` tag to add images to your page.
- Use the `<form>` tag to create a form for users to fill out.

### Learning Outcomes:
- Understanding of basic HTML tags and elements
- Ability to add images to a web page
- Understanding of CSS selectors and properties
- Ability to create a simple stylesheet file
- Understanding of how to structure a web page using HTML tags
			