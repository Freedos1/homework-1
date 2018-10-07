# Homework 1

This homework assignment covers the content that we discussed in class up until and including February 5.

Hello!


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

Next, edit this line to add your name:Alfred KABORE

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

* What is the scheme/protocol? HTTPS
* What is the host? nsnsp
* What is the port number? 443
* What is the path? commitments
* What are the query parameters? date
* What is the fragment?

#### 6. In the following URL: `http://localhost:4000/admin?`

* What is the scheme/protocol? http
* What is the host? 
* What is the port number? 4000
* What is the path? admin
* What are the query parameters? ~
* What is the fragment?

#### 7. In the following URL: `http://www.lehman.edu/academics/mathematics-computer-science/index.php`

* What is the scheme/protocol? http
* What is the host? lehman
* What is the port number? 80
* What is the path? academics
* What are the query parameters?
* What is the fragment?

#### 8. In the following URL: `https://en.wikipedia.org/wiki/Greek_alphabet#Glyph_variants`

* What is the scheme/protocol?
* What is the host?
* What is the port number?
* What is the path?
* What are the query parameters?
* What is the fragment?


### 9. HTTPS

What does the S stand for in HTTPS? Secure

Why is HTTPS better than HTTP?
Hyper Text Transfer Protocol Secure (HTTPS) is the secure version of HTTP, the protocol over which data is sent between your browser and the website that you are connected to. 

Should all web pages use HTTPS?    yes   



## Webpages

Pleaes ensure you have read chapters 1–9 (except 7) in the [HTML & CSS book](https://isbndb.com/book/9781118008188) or similar information available from MDN here:

* https://developer.mozilla.org/en-US/docs/Web/HTML
* https://developer.mozilla.org/en-US/docs/Web/Tutorials


### 10. What is a webpage?
A webpage is a document commonly written in HyperText Markup Language (HTML) that is accessible through the Internet or other network using an Internet browser


### 11. Webpage I like

What's one webpage you like? Why?


### 12. Website I don’t like

What's one webpage you like? Why?


### 13. Resources

Where is a good place to look for information about HTML tags?


### 14. HTML Versions

Which version of HTML are we covering in this class? What is it's DOCTYPE tag?
HTML5 
<!DOCTYPE html>

What is XML?  
Extensible Markup Language is a markup language that defines a set of rules for encoding documents in a format that is both human-readable and machine-readable

What is XHTML?
Extensible Hypertext Markup Language is part of the family of XML markup languages. It mirrors or extends versions of the widely used Hypertext Markup Language, the language in which Web pages are formulated


### 15. HTML

Are web pages ASCII (plain text) files, or compiled (binary) files like an executable program?

Are HTML files interpreted or executed?


### 16. Browser versioning

Which versions of Microsoft Internet Explorer support the `<nav>` tag?


### 17. HTML Validity

What is one tool that can tell you if you have written valid HTML?


### 18. Accessibility

What does "Accessibility" mean in the context of web development?

What types of people does accessibility concern?

What is one tool you can use to verify the accessibility of your websites?


### 19. head / body

What is the `<head>` tag for?
The <head> element is a container for all the head elements. The <head> element can include a title for the document, scripts, styles, meta information, and more. 

What is the `<body>` tag for?
The <body> element contains all the contents of an HTML document, such as text, hyperlinks, images, tables, lists, etc.


### 20. Head…

What's the difference between `<head>`, `<header>`, and heading tags?
The head tag is used for holding Meta information, title, links, etc. and is not displayed on the page. 
The header tag is used within the body of the website and can be used multiple times if required, e.g. to determine the top of an article.


### 21. Tables

What are all the tags associated with [HTML tables](https://developer.mozilla.org/en-US/docs/Learn/HTML/Tables) (e.g. `<table>`, `<tr>`, etc.)?


### 22. Non-closing tags

Which tags don't have a closing pair (e.g. `<br>`)?
HTML void elements are ones that do not have a required closing . The void elements or singleton tags in HTML are those tags that don't require a closing 

### 23. Links

How do you make a link open in a new window?


### 24. IFRAME

What is an IFRAME?
An IFrame (Inline Frame) is an HTML document embedded inside another HTML document on a website. 
What are IFRAMEs commonly used for?
The IFrames HTML element are often used to insert content from another source, such as an advertisement, into a Web page



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
