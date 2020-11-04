# Learn how to host a Resume on GitHub Pages

## Table of Contents
* [Introduction](#introduction)
* [GitHub](#what-is-github) 
* [MarkDown](#what-is-markdown)
* [Prerequisites](#prerequisites)
* [Hosting Resume](#lets-get-started)
* [More Resources](#more-resources) 
* [Authors and Acknowledgement](#authors-and-acknowledgment)
* [FAQ's](#faqs)
## Introduction
This README provides a detailed step-by-step description on how to host resumes on GitHub using the concepts from **Etter's Book  Modern Technical Writing.**

<img  src="resume.gif" alt="gif of a resume">

<br> <br>
## What is GitHub?

<img  src="gitLogopng.png" alt="GitHub logo">

[Github](https://www.youtube.com/watch?v=w3jLJU7DT5E&ab_channel=GitHub) is a code sharing and publishing platform which can connect people and facilitate them to work on a problem together from anywhere in the world. Github uses a feature called **Version Control** which keeps a track of all the changes done on the project by you or other developers.

The three features of GitHub `fork, pull request and merge` makes it so powerful. *Fork* is coping a repository from one user account to another. Then you can modify that repository under your own account. If you would like to share your changes, you can create a *pull request* for the original owner of the repo, who can then *merge* the changes found in your repo with the original one. 

> GitHub is one of the most popular *Distributed Version Control Systems(DVCS)* which gives you the power of fixing small issues instantly and keep all file in sync with latest software. 
>Being an open source community, it gives opportunity to a number of developers  to contribute to the project.

</br>

## What is MarkDown?

<img src="markdown.gif" alt="GitHub logo">

</br>[Markdown](https://www.youtube.com/watch?v=f49LJV1i-_w&ab_channel=Codecademy) is a lightweight markup language used to add formating elements to unformated text, that makes writing for the internet easier. It has been widely adopted by the developer community because it is less time consuming to adopt and can be used for any writing purpose. 

> In modern technical writing, everyone is considered to be a contributor and using a lightweight markup language, which is human readable and easy to learn, can increase your contributors significantly. 
Such languages are much more faster, easier and safer, which you can edit using your favourite text editor or a web browser.


<br>

### Prerequisites

For this tutorial, you will need two things:

**1. A GitHub Account**

Signing up for a [GitHub account](https://github.com/) can never be that simpler. You just need to create a username, followed by an email address and a password and you are all set to explore the GitHub world.

**2. A Resume**

Your resume can be of any format, i.e. .txt, .md etc. In this tutorial, we will be hosting Markdown created resumes.

<br>

### Lets Get Started

Once you are all set with the above mentioned prerequisites, following steps should be pursued. 

#### 1. Creating a Repository
A repository, also known as *Repo*, is a folder where all your project files are stored.

* Click the `+` button at the upper-right corner of any page. 
* Select `New repository` from the dropdown menu.
* Using the `Owner` button you can select which account should own the repository
* Enter a suitable name and an optional description. (If you are planning to publish the site, then repository name **must** end with `.github.io`).
* You can choose to make it private or public.
* Select `Add a README file` under *Initialize this repository with:* This option will create a README file for you and makes it easier to implement.
* Click `Create repository`.

> While storing a document, make sure you place a README file in the root of the repository. The file should contain a quick summary of the product being documented, what dependencies it has and how to contribute to it.
> This helps the reader.

<br>
<img  src="createRepo.gif" alt="gif of creating a Repository">


#### 2. Add a file to the Repository
You can add more pages to your site by creating new files.
* Click on the `Add file` drop-down button.
* Select the suitable option from the drop down menu. 
* Give the file a name and an extension like .txt or .md, if going for `Create a file`, 
* Click `Commit new file`.

<img src="createFile.gif" alt="gif of adding a File"> 


#### 3. Adding theme to the file
You can add a theme to your *GitHub Pages* to customize the outlook of your site. This can be done by adding a [Jekyll](https://docs.github.com/en/free-pro-team@latest/github/working-with-github-pages/about-github-pages-and-jekyll) theme.
*Jekyll is a powerfull software which transforms plain text to static websites*. Static websites are defined well in Etter's Book as:
> "Static websites are fast, simple, portable and can be hosted anywhere. They have no dependencies, no database and nothing to install and therefore relocating the website is just like relocating a directory."

Jekyll theme can be added with the following steps:  

* Click `Settings` under repository name.
* Scroll down to **GitHub Pages**.
* Click `Choose a theme`.
* Select the theme you like.
* Click `Select theme`.

A new file, `_config.yml` should be created in your repo that stores all the Jekyll commands. 

<br> <img src="theme.gif" alt="gif of adding a theme"> 

<br>


### More Resources
* GitHub Resources
    * [What is GitHub?](https://www.youtube.com/watch?v=w3jLJU7DT5E&ab_channel=GitHub)
    * [GitHub for beginners](https://readwrite.com/2013/09/30/understanding-github-a-journey-for-beginners-part-1/)
* Markdown Resources
    * [What is MarkDown?](https://www.youtube.com/watch?v=f49LJV1i-_w&ab_channel=Codecademy)
    * [Markdown Tutorial](https://www.markdowntutorial.com/)
    * More about [GitHub Flavored Markdown](https://github.github.com/gfm/)
* Jekyll Resources
    * [What is Jekyll?](https://www.youtube.com/watch?v=T1itpPvFWHI&list=PLLAZ4kZ9dFpOPV5C5Ay0pHaa0RJFhcmcB&ab_channel=MikeDane)
    * [Jekyll Tutorial](https://www.youtube.com/playlist?list=PLLAZ4kZ9dFpOPV5C5Ay0pHaa0RJFhcmcB)
* A link to [Andrew Etter's book](https://www.amazon.ca/Modern-Technical-Writing-Introduction-Documentation-ebook/dp/B01A2QL9SS)


<br>

### Authors and Acknowledgment

**Author**
* Shrey Malhan

**Group Members**
* Nicole Ciceron
* Mohammad Inan

<br>

### FAQ's
**Why is Markdown better than a Word Processor?**

As stated in Andrew Etter's book, 
> "Microsoft Word is a wonderful choice for creating résumés and a horrible
choice for creating documentation."

Being an advanced software, Word gets complicated with its formatting as it has a steap learning curve, whereas, markdown is easy to operate with its simple syntax.



**How can I change the description of my repository?**

> * The description of the repository is under the **ABOUT** section on the right side of the screen 

> * Click `⚙️` on the right side of the **ABOUT** section and you can change the desription.

---


