# Chapter 0: Introdution and Preparation

## Foreward

The course COMM7780/JOUR7280 Big Data for Media and Communication is set up for master students in the school of communication, Hong Kong Baptist University. The purpose of this course is to motivate the students to become a [T-shape talent](http://www.caseinterview.com/t-shaped-skills) in communications field. The course involves intensive training of Python and quest in solving practical problems. This open book collects all the materials related with lab exercises covering Python basics, data scraping, table manipulation and data mining. Students also apply their duly learned knowledge to write data-driven reports on a regular basis.

The final projects of past students can be found in this archive GitHub organisation: https://github.com/data-projects-archive/

## Chapter introduction

This chapter covers "GitHub literacy" and walks the readers through the basic steps towards an open source experience.

## Getting-started on GitHub

You can sign up in [Github](https://github.com/). Pick a nice name, then you can start your wonderful journey conquering the galaxy of data and codes. There are many useful learning materials and meaningful projects on the platform waiting for you to open it, many interesting stories to discover.

### Understand markdown

Markdown is a lightweight and easy-to-use syntax for styling all forms of writing on the GitHub platform. - explanation by Github. Markdown is a way to style text on the web. You control the display of the document; formatting words as bold or italic, adding images, and creating lists are just a few of the things we can do with Markdown. Mostly, Markdown is just regular text with a few non-alphabetic characters thrown in, like # or *.

* Here is the official document of [Mastering Markdown](https://guides.github.com/features/mastering-markdown/) in Github.
* Also, another good introduction of use of markdown [Markdown 基本语法](https://github.com/younghz/Markdown)

### Use GitHub issue tracker as a discussion forum

The GitHub issue has a lot of features, but overall it looks like a lightweight collaboration system. Assignee or project manager can pull requests for new contributors and set a to-do list for contributors and teammates. You can use issue to ask questions, discuss with your team, label the `issue` you encounter, and collaborate with others, which greatly advances the managing of a Project.  
e.g.1: Set a to-do list for your teammates, once they finished the quest you pull, they can just tick to show the progress.
![issue](/assets/Chapter0-issue.png)  

e.g.2：To discuss with your team members to track the working process.
![discussion](/assets/Chapter0-discussion.png)

### Learn other's code from commit history

![commit history](/assets/Chapter0-commit%20history.png)  
You can see the latest update time and a brief summary of every piece of work in one's repository.  

![commit details](/assets/Chapter0-commit%20details.png)
By clicking one of the files, you can see the details of the improvements and changes they recently made, and you can learn from their work.

The red blocks represent the old one, and the green is the newer one, which makes it easy for you to know the difference and learn the logic behind it.

### Preview a Jupyter notebook hosted on GitHub with nbviewer

#### [Jupyter Notebook](http://jupyter.org/)

The Jupyter Notebook is an open-source web application that allows you to create and share documents that contain live code, equations, visualizations and narrative text. In our course, Jupyter notebook will be our daily tool to write, test, and sharing our codes and works. It's very useful for us to learn and make **reproducible works**. The good advantage of jupyter notebook includes:

* The Notebook has support for over 40 programming languages, including Python, R, Julia, and Scala.
* Notebooks can be shared with others using email, Dropbox, GitHub and the Jupyter Notebook Viewer.
* Your code can produce rich, interactive output: HTML, images, videos, LaTeX, and custom MIME types.

You can check out our [tutorial](/module-jupyter.md) for how to install Jupyter environment and use Jupyter notebook, though, it's still in improvement satge.

#### [Nbviewer](http://nbviewer.jupyter.org/)  

Nbviewer creates a simple way to view and share Jupyter Notebooks. You just need to copy the link of one Jupyter notebook and paste in nbviewer.
![](/assets/Chapter0-jupyter%20notebook%20link.jpg) 


![](/assets/Chapter0-nbviewer.png)

## GitHub Desktop

### Install Github desktop

You can download from [here](https://desktop.github.com/), and install it like you installed other apps before.

### Use GitHub Desktop to synchronize codes between local repo and GitHub hosted repo

Talking about this function, Github is like a cloud disk, which is similar to Google Drive，OneDrive. You can synchronize your codes and files between local and Github website. It's useful not just others can see your recent updates, but also improve the efficiency during the collaboration with others. If one of your teammates commit changes, you can synchronize by Github desktop and keep the same stage with them.

#### Create your first repository

![new repo](/assets/Chapter0-create%20new%20repo.png)
After you log in Github desktop, click `create new repository`, give a name you like and choose the local path you want(but keep in mind where they are).

#### Create a file in this repository

![edit file](/assets/Chapter0-edit%20file.png)
Drag the repository/folder you created into the text editor, in this case, I use *visual studio code*.  
![write a file](/assets/Chapter0-write%20a%20file.png)
Under the example repo, create your first file `hello github.md`, write an H1 line `Let's try out github`, and save it.

#### Publish your repo to Github

![publish repo](/assets/Chapter0-publish%20repo.png)
After creating your first file, open github desktop, you can see the changes you did before. Give a description of this changes in [1], then commit to master in [2],(this step is like that you confirm the changes). After that, you can click [3] and [4] to publish your repo.

![find new file](/assets/Chapter0-find%20new%20file.png)
Open the Github website, find your new repo, click the repo and check out the files in this repo, whether it keeps the same pace with your local file.

#### Re-edit your file and synchronize codes between two ends

You can re-edited the files and codes both in Github website and in local text editor.

* If you edit in the website, after you save the file, click the `fetch origin`. Then the change you commit in the website will synchronize into your local repo.

![fetch orign](/assets/Chapter0-fetch%20origin.png)

* If you edit in a local text editor, it's pretty much the same. You give a description, commit to mater, and then `fetch origin`. Then the change you commit in a local repo will synchronize into your Github site.


## GitHub pages

Github pages are websites for you and your projects. It helps you turn your Github repository into elegant websites to showcase your portfolio, your projects, documentation or anything you want to share with the world. There are no need to set up the database and configure servers. It's the most direct path to create websites for you and your projects. You can visit [github pages](https://pages.github.com/) to learn more.

### Publish your first webpage on gh-pages

#### Step 1. Create a repository

Head over to GitHub and create a new repository named `username.github.io`, where username is your username on GitHub.  
![new repo](/assets/Chapter0-new%20repo.png)
*Note: If the first part of the repository doesn’t exactly match your username, it won’t work, so make sure to get it right.*

##### Step 2. Clone the repository

There are basically two ways to clone the repository. Use terminal with codes or Github desktop. Since we just talk about the Github desktop. So we use this way to check out whether we are already familiar with it.

Click the "Set up in Desktop" button. When the GitHub desktop app opens, save the project.

![clone repo](/assets/Chapter0-clone%20repo.png)

#### Step 3. Create an index file

![html](/assets/Chapter0-html.png)

Grab your favorite text editor and add an index.html file to your project. You can copy this example in your html.

```html
<!DOCTYPE html>
<html>
    <head>
        <meta "charset=utf-8"/>
        <title>Github is fun!</title>
    </head>
    <body>
        <p>I'm hosted with GitHub Pages.</p>
    </body>
</html>
```

#### Step 4. Commit & publish

Change to your Github desktop, commit your changes, and press the publish button.
![commit/publish](/assets/Chapter0-commit%20and%20publish.png)

Then you can go to your webpage with `https://username.github.io`. Change username to yours and see what is happening. During further study, you will use Github pages to do more, to share and show anything you want with the world.

### Bind a customised domain name

Coming soon.

## References and further reading

*[Github sharing by our lecturer](https://drive.google.com/file/d/1iwL-N4GdA3WqkVwtCJ36d3X0sJyr5_ni/view?usp=sharing). You can check out more functions and possibilities on Github.

*[Github offical guide](https://guides.github.com/). You can basically learn everything about Github in it's guide.

------

If you have any questions, or seek for help troubleshotting, please [create an issue here](https://github.com/hupili/python-for-data-and-media-communication-gitbook/issues/new)