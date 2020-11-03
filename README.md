## Learn the fundamentals of Tech Comm as you learn how to host your own Online Resume on GitHub Pages

This README will show you on hosting a resume on GitHub pages in a very simple way. The practical steps in this tutorial also relate to Andrew Etter's book _Modern Technical Writing_ where you can learn about about the fundamtals of Techincal Communication especially creating good documentation.  

## Table of Contents
- [Overview](#audience)
- [Prerequisites](#prerequisites)
- [Steps](#instructions)
- [FAQs](#faqs)
- [More Resources](#more-resources)
- [Authors and Acknowledgments](#authors-and-acknowledgments)


## Overview

 > Hosting your resume in a static website is a very simple and portable process. It is always a good idea to host a website because documentations always will always get outdated. It gives you the power to fix any inaccuracies and keep all your content up to date instantly while also making sure that your content has also good quality. GitHub has now made it very easy for users to host static websites through GitHub pages. Using MarkDown, a popular markup language, for formatting your web content along with a site generator such as Jekyll results in a really easy and straighforward process in hosting a static website on GitHub Pages. 

## Prerequisites
For this tutorial, you will need two things: 
1) **a Github account.** If you do not have a GitHub account, you would need to make one by going to this link [https://github.com](https://github.com). This tutorial will use the web version of GitHub. 
    > GitHub is very popular Distributed Version Control Systems(DVCS). It has a user-friendly interface  that allows for isolated work and has overall good performance in software development. Having your porject live online also means other people can easily contribute to your project and give you tips on how to make your project even better, just like what was mentioned in Andrew Etter's book in the section called 'Help Others Write'.
    
2) **a resume formatted in Markdown**. Your resume will need to be formatted in Markdown. If you are not yet familiar with MarkDown, I highly suggest you try and learn it. It is a very simple lightweight markup language that you can learn in just a few minutes. A good tutorial on Markdown can be found below this page. 
    > You would also need a MarkDown Editor for this step. There are a lot of available editors that you can use depending on the opearting system you are using. One good editor is [dillinger.io](https://dillinger.io). 

## Steps

1. First, create a new repository from your GitHub profile. 
    > A repository is a directory where your files related to your project will be stored. Repositories can either be stored locally or in this case, it would be stored online in GitHub.
    
    ![repo](Images/add-repo-shortcut.png)

2. Inside your repository, add the files **README.md** and **index.md**. 
    > The README file will just contain descriptions on what your page is about. For this tutuorial, this file will just conatin a description telling that your site is a sttic website displaying your resume. You can include the process on how you did the process of hosting your site, just like this tutorial. 
    
    ![add](Images/add-two-files.png)    

    > Next, The index file will contain the content you want to be displayed on your static website. In this case, your page will contain your resume that was formatted in Markdown. 

    ![add_index](Images/add-index.gif)

3. Before you view your static page, you have to go to Settings to specify the Source so you can enable GitHub pages for your repository. In this case, you only currently have the **main** branch so choose this branch. After that, you can now view your page by going to the link: _https://your-usesrname.gitub.io_. You can also do this by going to **Settings** You can continue editing your **index.md** file if you want to make any more changes in the formatting of your content.

    ![Source](Images/enable-gh-page.png)
    
    > If this is not the first static page you are hosting from your GitHub account, the link of your static website would become: _https://your-usesrname.gitub.io/repository-name_. 

4. You can also add themes on your page using Jekyll templates. Jekyll is a very popular static site generator that easy displays and processes your content, which is formatted in a lightweight markup language, in a working static website without any databases or any installations. There are a handful of [Jekyll themes](https://pages.github.com/themes/) that are supported by GitHub pages that you can use for your own statci website.

    > Adding themes through Jekyll will automatically adds another file in your repository named _config.yml. This file will just contain the name of the theme that you would have chosen.

    4.1 Go to your repository's page. On the main tabs, click on **Settings**
    
    4.2 You will be directed to the **Options** tab inside Settings. Scroll down to **GitHub Pages**
    
    4.3 Click on **Change Theme** under **Theme Chooser**
    
    4.4 Select any theme that you like and click **Select Theme**
    
    ![theme](Images/select-theme.png)
    
    > Making static website through static generators such as Jekyll is a simple and portable process. There are many site generators available today such as Sphinx,Hugo, AsciiDoc, etc. These tools will help you create your own functional documentation website. If you have time and if you want to learn more about Jekyll themes, you should consider customizing your theme. You can find different themes on GitHub that you can fork and play around with. 

5. Finally, you can edit your yaml file(_config.yml_) as well, to add or edit the page title and description. Hosting your own static page can be very easy through GitHub Pages and supported Jekyll themes. Since you now have the basic knwoledge of creating your web content using MarkDown, and hosting it on GitHub Pages along with Jekyll themes, you can start to learn more about **Jekyll** and potentially make your own theme for your next static website.

## FAQs
- **Why should I use MarkDown for my static website?**
    > MarkDown is a very popular markup language. It is a modern way of formatting web content that translates to HTML. More importantly, as I have mentioned above, it is very easy to learn compared to other markup languages such as AsciiDoc and reStructuredText. You can learn it in as fast as 10 minutes. Additionally, it can be used for writing email, notes, and general word processing.

- **Why is my resume not showing up?**
    > There could be a couple things that are preventing your resume from showing up on your site. 
    
   >    1. You might have typed your sttaic page url wrong. Make sure the url is the same from the url displayed under the section **GitHub Pages** in **Settings**.
   
   >    2. You might have missed a step in the instructions. Make sure you choose your Source to enable GitHub Pages for your repository as this is a very important step for you to be able to show your resume on your static website.

## More Resources
-  [Andrew Etter - Modern Technical Writing: An Introduction to Software Documentation](https://www.amazon.ca/Modern-Technical-Writing-Introduction-Documentation-ebook/dp/B01A2QL9SS)
- Links to good MarkDown Resources:
    - [Overview of Markown](https://www.markdownguide.org/getting-started)
    - [MarkDown Tutorial](https://www.markdowntutorial.com)
    - [MarkDown CheatSheet](https://www.markdownguide.org/cheat-sheet)
- MarkDown Editors:
    - [dillinger.io](https://dillinger.io) - Online
    - [Visual Studio Code](https://code.visualstudio.com/download)
    - [Atom](https://flight-manual.atom.io/getting-started/sections/installing-atom/)
- Jekyll Resources:
    - [Jekyll - Site Generator Tutorial](https://www.youtube.com/playlist?list=PLLAZ4kZ9dFpOPV5C5Ay0pHaa0RJFhcmcB)

## Authors and Acknowledgements
Author - Nicole Ciceron


