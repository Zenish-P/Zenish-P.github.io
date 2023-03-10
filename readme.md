# **Hosting a markdown formated Resume on Github using Github-Pages and Jekyll**
The goal of this README is to assist the user with hosting a resume using  technologies such as Github Pages, Jekyll, Markdown, and Github.
## **_Prerequisites_**
---
The sole need is a résumé in markdown style. To build a resume in markdown format, you must be familiar with the Markdown language. For your convenience, I have included a link to a superb markdown lesson in the "Additional Resources" section. Moreover , an active Github account is required. 

## **_Introduction_**
---
## Use of Lightweight Markup Language - _Markdown_
Markdown is one of the best known format for creating any kind of documentions. Contribution is one of the core concepts of technical writing, according to Etter's book. If we continue to write our information in XML-based languages, people will find it harder to contribute. Although they are highly pricey, there are many specialised editors. In all pertinent aspects, lightweight markup is superior and free for documentation. There are numerous light markups. Our résumé is formatted in Markdown.
## _Use of Distributed Version Control System_ - _Git_
There are many open sourse version control softwares available on internet and Git is one of them that is open-source, free, and tracks changes to any set of files. It is frequently employed to coordinate the efforts of programmers who are collaborating to create software's source code. The main reasons to use git are:
>* Helps us to move back and forth in thwe version timeline.
>* Helps us to maintain various approaches/implementations of same code using branching.
>* It works offline without any need of internet connectivity.


## **_Complete Process_**
---
## _Creating a new Repository on Github_
Assuming you already have a github account. 
>1. Login to you account.
>2. Open Repositories tab.
>3. Click on `New` green coloured button on the right side.
>4. Give a Repository name '[username]'.github.io.
> > Here the `[username]` is the Github username.
>5. Add some description about your repo. 
>6. Click on `Create Repository` at the bottom of the page.
>7. After that click on `upload an existing file`.
>8. Upload your resume.md and click `commit changes`.

![Creating Repository - gif](/RepoCreationGIF.gif)
## _Host a static website_

1. Ruby installation
 * Click this link to [install Ruby](https://www.ruby-lang.org/en/downloads/).
 * Click on `Rubyinstaller` link given in the "Ways of installing Ruby section"
 * Click on the red coloured `Download Ruby` button.
 * Download the latest version of `Ruby Installer` which has a Devkit.

![DownloadingRuby-gif](/rubyDown.gif)

2. Jekyll installation
 * Open Command Prompt
 * Enter command: `gem install bundlr jekyll`.
 * Enter command: `jekyll -v` to check if the jekyll got installed.

3. Cloning Github Repo
 * Open Command Prompt
 * Type "git clone https://github.com/[username]/[username].github.io"
 * Now enter command: cd [username].github.io 

4. Initializing the website
 * In the command prompt type `jekyll new [website name]` - here enter the name of the website you want it to be.
 * Install Webrick Bundle using `bundle add webrick`
 * Then type `install bundle`
 * Enter command `cd [website name]`
 * Enter command `bundle exec jekyll serve` 
 * To see the website type `localhost:4000` in the web browser 

5. Pushing the files to Github
 * Type `git add --all` 
 * Type `git commit -m "any message"`
 * Type `git push -u origin main`

Now when you type "http://[username].github.io" in the web browser and you can see that the website has been hosted.

This is how you resume will look like. 


![resume.gif](/resume.gif)


## **_Additional Resources_**
-----------------------
1. Great place to learn markdown for beginners - [Markdown Tutorial](https://www.markdowntutorial.com/)
2. A great resource for understanding of techincal writing is Andrew Etter's Modern Technical Writing.Available on Amazon - [Etter's book](https://www.amazon.ca/Modern-Technical-Writing-Introduction-Documentation-ebook/dp/B01A2QL9SS)
3. A great resource for beginner to indepth knowledge of git - [Git Tutorial](https://www.w3schools.com/git/)


## **_Authors and Acknowledgement_**

---

>The author of this README.md is Zenish Yopinbhai Patel.The book "Modern Technical Writing" by Andrew Etter served as a significant source of inspiration. I must express my gratitude to my COMP3040 classmate group. They aided in my comprehension of the requirements for completing this article. 
 
### **_FAQs_**

---

Q: Why Markdown is superior to word processing
> The best word processors are expensive. They are out of most people's price range as a result. As a result, people fail to participate. The majority of individuals can easily utilise Markdown because it is free source and straightforward to use. People are encouraged to participate as a result.
