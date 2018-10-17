# Homework 1

This homework assignment covers the content that we discussed in class up until and including February 5.


## GitHub

We will exlusively use GitHub for all assignments in this class. Therefore (and because it is broadly used in industry), you should familiarize yourself with GitHub and its features.

### 1. Learn about GitHub

Perform this "Hello World" exercise: https://guides.github.com/activities/hello-world/


### 2. Understand Markdown

[Markdown](https://en.wikipedia.org/wiki/Markdown) is a language for simple text formatting. Usually, markdown files end in `.md` (like this file, `README.md`).

You will complete this homework assignment by modifying this Markdown file (`README.md`).

Take a look at these resources to understand Markdown basics:

* https://help.github.com/articles/basic-writing-and-formatting-syntax/
* https://guides.github.com/features/mastering-markdown/
* https://github.com/adam-p/markdown-here/wiki/Markdown-Cheatsheet


### 3. Modify README

Read about the `README.md` file: https://help.github.com/articles/about-readmes/

Now, edit the `README.md` file in this homework repository by clicking the `README.md` file in the list of files:

![README file](images/readme.png)

Then click the pencil icon to edit it:

![Edit button](./images/edit.png)

Next, edit this line to add your name: **Your Name**

Click the "Preview changes" tab to see your changes.

When you are happy with your changes, click the "Commit changes" button at the bottom (optionally entering a commit title and description):

![Commit](./images/commit.png)

You should now see your name above (instead of "Your Name"). You can also see your change in the repository's commit history.


### 4. LinkedIn profile URL

[LinkedIn](linkedin.com) is a professional networking site used by almost all companies and recruiters. By establishing your professional profile now, to can begin to connect with other classmates and build your professional network.

Please sign up for LinkedIn and share your LinkedIn profile URL here. If you do not wish to be a member of LinkedIn, please write "I decline.":

[My LinkedIn Profile](https://www.linkedin.com/in/.../)


### 5. Setup GitHub Pages

[GitHub Pages](https://pages.github.com/) is a feature of GitHub that lets you serve webpages directly from a GitHub repository.

You will need to do this once for each homework assignment and class project.

Click the "Settings" tab in your repository:

![Settings tab](./images/settings.png)

Enable GitHub Pages on the master branch:

![GitHub Pages](./images/gh-pages.png)

After saving, note the public URL of your repository -- you will use this in the "Writing Code" section below:

![GitHub Pages URL](./images/gh-pages-url.png)


## The Web

Please edit this file to add your answers to the following questions.


### URLs

#### 5. In the following URL: `https://www.nsnsp.org/commitments?date=2017-12-09`

* What is the scheme/protocol? **https**
* What is the host? **www.nsnsp.org**
* What is the port number? **443**
* What is the path? **commitments**
* What are the query parameters? **date=2017-12-09**
* What is the fragment? **none, because there is no #(HashTag)**

#### 6. In the following URL: `http://localhost:4000/admin?`

* What is the scheme/protocol? **http**
* What is the host? **localhost**
* What is the port number? **4000**
* What is the path? **admin**
* What are the query parameters? **none**
* What is the fragment? **none**

#### 7. In the following URL: `http://www.lehman.edu/academics/mathematics-computer-science/index.php`

* What is the scheme/protocol? **http**
* What is the host? **www.lehman.edu**
* What is the port number? **80**
* What is the path? **academics/mathematics-computer-science/index.php**
* What are the query parameters? **none**
* What is the fragment? **none**

#### 8. In the following URL: `https://en.wikipedia.org/wiki/Greek_alphabet#Glyph_variants`

* What is the scheme/protocol? **https**
* What is the host? **en.wikipedia.org**
* What is the port number? **443**
* What is the path? **wiki/Greek_alphabet**
* What are the query parameters? **none**
* What is the fragment? **Glyph_variants**


### 9. HTTPS

What does the S stand for in HTTPS? **secure**

Why is HTTPS better than HTTP? **https is better because it offers higher security**

Should all web pages use HTTPS? **yes,always**


## Webpages

Pleaes ensure you have read chapters 1–9 (except 7) in the [HTML & CSS book](https://isbndb.com/book/9781118008188) or similar information available from MDN here:

* https://developer.mozilla.org/en-US/docs/Web/HTML
* https://developer.mozilla.org/en-US/docs/Web/Tutorials


### 10. What is a webpage?

*Your answer here.*
**A document which can be displayed in a web browser such as Firefox, Google Chrome, Microsoft Internet Explorer, Safari etc. These are also often called just "pages."**

### 11. Webpage I like

What's one webpage you like? Why?

**MDN web docs because it has a clean and simplistic, and its user friendly.**

### 12. Website I don’t like

What's one webpage you like? Why?

**craigslist is a webpage i dislike simply becauase its just a bunch of text all over the page thrown in the users face.**

### 13. Resources

Where is a good place to look for information about HTML tags?

**MDN web docs.**

### 14. HTML Versions

Which version of HTML are we covering in this class? What is it's DOCTYPE tag?

**We are covering HTML5. A Doctype tag is a preamble you will see at the top of your documents and it ensures that the browser makes a best-effort attempt at following the relevant specifications, rather than using a different rendering mode that is incompatible with some specifications.If a doctype isn't used then the broswer has a chance to switching into a mode called "quirk mode".**

What is XML?

**XML is a meta language that allows the user to create their own markup language. It's often used as a tool for software and hardware to transport and store data.**

What is XHTML?

**XHTML(Extensible Hypertext Markup Language) is a reformulation of HTML 4.0 as an application of the Extensible Markup Language (XML) and this is used for "expressing" Web pages.**

### 15. HTML

Are web pages ASCII (plain text) files, or compiled (binary) files like an executable program?

**Web pages are ASCII (plain text files)**

Are HTML files interpreted or executed?

**HTML file are interpreted.**

### 16. Browser versioning

Which versions of Microsoft Internet Explorer support the `<nav>` tag?

**IE 9 and higher.**

### 17. HTML Validity

What is one tool that can tell you if you have written valid HTML?

**This is a markup validation service https://validator.w3.org/**

### 18. Accessibility

What does "Accessibility" mean in the context of web development?

**Web accessibility means that websites, tools, and technologies are designed and developed so that people with disabilities can use them.**

What types of people does accessibility concern?

**The concerns that try to be addressed are the following:
auditory
cognitive
neurological
physical
speech
visual**

What is one tool you can use to verify the accessibility of your websites?

**This is a web accessibility evaluation tool https://www.w3.org/WAI/ER/tools/**

### 19. head / body

What is the `<head>` tag for?

**The head tag job is to contain metadata about the document and the title tag..**

What is the `<body>` tag for?

**The HTML body tag Element represents the content of an HTML document. There can be only one body tag element in a document.**

### 20. Head…

What's the difference between `<head>`, `<header>`, and heading tags?

**The HTML head tag element provides general information (metadata) about the document, including its title and links to its scripts and style sheets.**
  
**A header is a horizontal bar the full width of the screen, which appears at the top of the screen in most apps.
Headers float above content, with the option of flowing with content in special instances, such as in the Browser app.**

**Heading tags are tags that are used for the creations of headings. The most important tag is the <h1> heading tag, and will usually be the title of a post.**

### 21. Tables

What are all the tags associated with [HTML tables](https://developer.mozilla.org/en-US/docs/Learn/HTML/Tables) (e.g. `<table>`, `<tr>`, etc.)?

<table>	Defines a table
<th>	Defines a header cell in a table
<tr>	Defines a row in a table
<td>	Defines a cell in a table
<caption>	Defines a table caption
<colgroup>	Specifies a group of one or more columns in a table for formatting
<col>	Specifies column properties for each column within a <colgroup> element
<thead>	Groups the header content in a table
<tbody>	Groups the body content in a table
<tfoot>	Groups the footer content in a table

### 22. Non-closing tags

Which tags don't have a closing pair (e.g. `<br>`)?

<area> - used for the area inside of an image map

<base> - the base URL for all relative URLs in a document. There can be no more than 1 of these per document and it must be in the <head> of the page
  
<br> - this is line break, often used in text content to create a single line break instead of a paragraph. This should not be used to create visual separation on a page by stacking up many <br> tags since that is a visual need and therefore the domain of CSS

<col> - specifies column properties for each column within a <colgroup> element
  
<command> - specifies a command that a user can invoke

<embed> - used with external applications and interactive content for integration

<hr> - a horizontal rule, which is a straight line on a page. In many cases, CSS borders are used to create separator lines instead of this HTML element

<img> - one of the workhorse elements of HTML, this is the image tag. It is used to add graphic images to a webpage.

<input> - a form element that is used to capture information from visitors. There are a number of valid input types, from the common "text" input that has been used in forms for years, to some new input types that are part of HTML5

<keygen> -  this is used to dictate a key-pair generator field that is used for forms

<link> - not to be confused with the "hyperlink" or anchor (<a>) tag, this link is to set linage between a document and an external resource. You would use it to link to an external CSS file, for example
  
<meta> - meta tags are "information about content". They are found in the <head> of a document and used to convey page information to the browser. There are many possible meta tags that you can use on a webpage
  
<param> - used to define parameters for plugins

<source> - this tag allows you to specify alternative file paths for media on your page, including videos or images or audio files

<track> - this tag sets a track to be used with a media file, a video or audio, which are often added with the <video> or <audio> tags
  
<wbr> - this stands for Word Break Opportunity. It specifies where in a text it would be acceptable to add a line-break


### 23. Links

How do you make a link open in a new window?

**Apply the target attribute and give it a value _blank**

EXAMPLE:
<a href="https://www.domain.com/" target="_blank">domain.com</a>

### 24. IFRAME

What is an IFRAME?

**An IFrame (Inline Frame) is an HTML document embedded inside another HTML document on a website.** 

What are IFRAMEs commonly used for?

**The IFrame HTML element is often used to insert content from another source, such as an advertisement, into a Web page.** 

## Writing Code

In this section, you'll modify a couple HTML files that have been started for you in this repository.

Because you enabled GitHub Pages above, you can actually view these pages in your browser. Use the GitHub Pages URL that you noted above to open these pages in a web browser.

### 25. science.html

Please modify the [science.html](./science.html) file in this repository to make the resulting webpage look like this:

![Science webpage](images/science.png)


### 26. olympics.html

Please modify the [olympics.html](olympics.html) file in this repository to make the resulting webpage look like this:

![Olympics webpage](images/olympics.png)

### 27. bugs.html

Please modify the [bugs.html](bugs.html) file in this repository to fix the errors that exist in the file.


## Misc.

### 28. Pace check

Class is going… too slow / just right / too fast.


### 29. Jobs

Add a link to one web development job based in NYC:

What do you still need to learn to meet the requirements?
