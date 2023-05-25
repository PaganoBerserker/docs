---
title: DOCUMENTS REPOSITORY README
author: Decentralized Climate Foundation
date: 2022-02-04
category: README
layout: post
---

:space_invader:
[![GNUv1.3 License](https://img.shields.io/badge/License-GNU%20v1.3-yellow.svg)](https://opensource.org/licenses/) [![GitHub contributors](https://img.shields.io/github/contributors/decentralizedclimate/docs.svg?style=flat)]() :space_invader:

## :computer:  Introduction :computer:

The purpose of the README is to guide on how to contribute to the DCF 
>And not die in the process.

### System requirements. :card_file_box:

* Access to [Fleek](https://fleek.co/) account or creating one.
* You must have installed [Rubygems version 2.5.0 or higher.](https://rubygems.org/pages/download) (check your Gems version using gem -v  since you may already have it installed on your machine).
* [GCC 10.2.1 and Make 4.3 or higher](https://www.delftstack.com/es/howto/linux/how-to-install-gcc-compiler-on-ubuntu/) (check versions using gcc -v, g++ -v, and make -v since you may already have it installed on your machine), 
* As well as [Ruby 2.5.0](https://www.ruby-lang.org/es/documentation/installation/) (check your Ruby version using ruby -v).

## :electric_plug: Installation :electric_plug:

Before contributing to DCF, you need to prepare your Linux system with Jekyll by following these steps.

As mentioned before, you should check that your Linux machine has Ruby version 2.5.0 or higher, including all headers. (If you are not sure if your version has Ruby, you can verify it with the command ruby -v).

```shell

$ ruby -v

$ sudo apt-get install ruby-full

```

Please also verify that you have the latest version of RubyGems by using the command gem -v. If it is not installed, you can proceed with the installation.


```shell

$ gem -v

$ gem update --system


```

Make sure that you have GCC 10.2.1 and Make 4.3 or higher installed (You can check their installation by using the commands gcc -v, g++ -v, and make -v, respectively).


```shell

$ sudo apt-get update

$ sudo apt-get install gcc make

$ make -v

GNU Make 4.3                                                                      
Built for x86_64-pc-linux-gnu                                                     
Copyright (C) 1988-2020 Free Software Foundation, Inc.
License GPLv3+: GNU GPL version 3 or later <http://gnu.org/licenses/gpl.html>
This is free software: you are free to change and redistribute it.                
There is NO WARRANTY, to the extent permitted by law. 

$ gcc -v

gcc version 10.2.1 20210110 (Debian 10.2.1-6) 

```

Now we need to proceed with installing Bundle 2.4.8 or higher and its gems:

```shell


$ gem install jekyll bundler

$ bundle install

$ bindle -v

Bundler version 2.4.8

$ bundle exec jekyll serve

Browse to http://localhost:4000

```

Remember that the last command is to run the website and verify that the contribution runs correctly.


## :scroll: How to contribute to Docs Project DCF.  :scroll:

### :notebook: "Verify that there are no issues in Docs Project DCF."  :notebook:

"Verify that there are no issues in Docs Project  DCF that address the contribution or problem you wish to collaborate on (as it may have already been started by another user)."

You can check the issues at the following [**link:**](https://github.com/DECENTRALIZEDCLIMATE/docs/issues)


#### :artificial_satellite:  "How to create a proposal or an issue:" :artificial_satellite:


If you have previously verified that the proposal or issue does not exist, you can write it following the following format:

After accessing the issues link, we must check if there is no related proposal or issue on the list. If we realize that there is none, we can add one by clicking on the **+** sign and assigning a brief title to it.



![](/assets/Readme/p1.png)

**Img1:** At the bottom of the issues, you can add a new one (Remember to check that there is no related open issue and its status).


![](/assets/Readme/p3.png) 

**Img2:** Once you have confirmed that there is no open issue, you can click on "Create a new issue".


![](/assets/Readme/p2.png) 

**Img3:** When contributing, you must specify a short title and also provide a description of the error that will be corrected.


---


:eye_speech_bubble: **To create an issue in Github, follow these steps:** :eye_speech_bubble:

1. Access the repository page where you want to create the issue.
2. Click on the "Issues" tab at the top of the page.
3. Click on the green "New issue" button at the top right of the page.
4. Write a brief and descriptive title for the issue in the "Title" field.
5. Describe the problem in detail in the "Write" field.
6. If applicable, use the text formatting options to add formatting, images, or links.
7. Label the issue with appropriate tags to make it easier to find and organize. Tags can be customized by the repository or used from a list of common tags.
8. Assign the issue to a responsible team member or leave it unassigned if not necessary.
9. If applicable, set a due date for the issue.
10. Click the green "Submit new issue" button to publish the issue.

It is important to provide all relevant information so that others can understand the problem and help resolve it. Additionally, it is important to label the issue correctly to make it easier to find and organize. If possible, a proposed solution or suggestions to help solve the problem can also be provided.

---

### :speech_balloon: How to contribute after creating my issue :speech_balloon:

You must clone the [docs](https://github.com/DECENTRALIZEDCLIMATE/docs)  repository to your computer (having the necessary tools and packages to run Jekyll on your computer).


>If you don't have what is necessary to run the repository, you can install what is pertinent for [Jekyll](https://jekyllrb.com/docs/) by clicking on the link.


When you have the repository perfectly installed and configured, you create, improve or solve your issues and send screenshots in the same issue (as responses to it) where we can see the changes and that it works.
>If you need to access the [Issues](https://github.com/orgs/DECENTRALIZEDCLIMATE/projects/1) section of DCF again, you can click on the link.


Send a Pull Request to the Develop branch of DCF docs, filling in the requirements, such as a brief title and comments on what was done. If everything is approved, your issue will be marked as completed and the changes will be added to the project.

#### Suggestions:

>As DCF is a decentralized project, remember that any file, image, or document that you want to contribute needs to have a reasonable size to avoid conflicts when processing it. There are ways to compress it.


## :zap: HOW TO MAKE A POST (CONTRIBUTION)  :zap:
### How to Make a Post in a Jekyll Repository

If you want to publish a post or article on docs.decentralizedclimate.org, follow these steps:

**1.-** Create a markdown file in the following directory if it's for the DCF directory:

```
https://github.com/DECENTRALIZEDCLIMATE/docs/tree/develop/_posts/

Or in the following directory if it's for social services:

https://github.com/DECENTRALIZEDCLIMATE/docs/tree/develop/_posts/socialserv
```
>Here we are simply specifying the path within the docs project, both for social services and for the docs project.

**2.-** The post must contain the following data:

- A header with the following data in markdown format:


```
---
title: Monthly Activity Report of the Decentralized Climate Foundation A.C. January.
author: Decentralized Climate Foundation
date: 2023-05-10
layout: post
---

```

- A file name starting with the date in the format YYYY-MM-DD-myposttopic.md. Some examples already exist in the directory.



**3.-** Add link a decentralized post without using permalinks:

- To add a link for social services in WorkFlow Documents, you need to go to /docs/_pages/socialServices.md and add the link in the following format:
 

```shell
## WorkFlow Documents
| Document | Last Update | 
| -------- | -------- |
| [WorkFlow Model]({% post_url socialserv/2023-01-27-socialServicesWorkFlowModel %}) | 2023-01 |
```

- To add a link for the docs project in Mans & CheetSheets, you should go to /docs/index.md and add the link in the following format:


```shell
## Mans & CheetSheets
| Document | Last Update |
| -------- | -------- |
| [Git & GitFlow ES]({% post_url 2023-05-10-January %}) |  2023-01-10 |
| [Git & GitFlow EN]({% post_url 2023-05-10-FebruaryES %}) |  2023-02-10 |
```
>Note that only the name is added in the previously mentioned format YYYY-MM-DD-myposttopic.md 

>Note that the URL is not a permalink. It is in the format YYYY-MM-DD-myposttopic without the .md extension.


**4.-** Optional: You can fork the project on your user account on the develop branch and link it to hackmd.io to edit before making a commit to your own repository. Then, submit a pull request, or edit the post directly in the GitHub editor.

**5.-** When your request is accepted on the develop branch, it will appear on the following link:

[**develop branch website**](https://dev.docs.decentralizedclimate.org/)

**6.-** Additionally, if you want to add images to your post, place them in the assets directory. Please refer to the README for more information.

**Example:**

![](/assets/Readme/p4.png)

**Img4:** Here is an example of how to reference the images located in the assets folder and in the folder where you host the images for your contribution (It is good to maintain this organization to know which images belong to which project).


>If you want to include images, but they have a high definition and therefore are very heavy, you can use tools to reduce their size so that they load more easily on WEB3.(Keep in mind that whenever you do this, the image should not lose too much fidelity; reducing it to the appropriate size is the best option).
EXAMPLE: https://squoosh.app/


### License. :mechanical_arm:

```
Copyright (C) DECENTRALIZED CLIMATE FOUNDATION A.C.
Permission is granted to copy, distribute and/or modify this document
under the terms of the GNU Free Documentation License, Version 1.3
or any later version published by the Free Software Foundation;
with no Invariant Sections, no Front-Cover Texts, and no Back-Cover Texts.
A copy of the license is included in the section entitled "GNU
Free Documentation License". 
```


### Contact: :calling:

[Decentralized Climate Foundation](https://t.me/decentralizedclimate)


### CONTACT AND DEVELOPERS
>Work developed in collaboration with the [Decentralized Climate Foundation](https://decentralizedclimate.org).

Author:
- [Gustavo Bermudez](mailto:nizaries44@gmail.com)
										  
Reviewer:
- [David E. Perez Negron R.](mailto:david@neetsec.com)





