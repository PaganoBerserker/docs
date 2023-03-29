---
title: DOCUMENTS REPOSITORY README
author: Decentralized Climate Foundation
date: 2022-02-04
category: README
layout: post
permalink: /readme
---

## Introduction

The purpose of the following workshop is to decentralize a static website using various free tools and services.

The process should be documented in a markdown report (cheatsheet).

If the foundation has a manual and/or cheatsheet related to the topic, contribute to the foundation's manual, otherwise add the documentation to the docs repository.

Add issues to the official repository if you have found or proposed improvements.

# Previous knowledge.

* Having completed the Git and GitFlow workshop.
* Basic concepts about IPFS.
* Access to fleek.co account or creating one.

## Cheatsheet

The [**docs**](https://githubcom/DECENTRALIZEDCLIMATE/docs) project from the Decentralized Foundation repository is cloned to the local machine.

```linux=
git clone https://github.com/DECENTRALIZEDCLIMATE/docs.git
```

The respective dependencies such as ruby and jekyll were installed.

After we have the repository, the template for the webpage is downloaded and implemented within the downloaded repository.

[**Template Dowload**](https://github.com/sighingnow/jekyll-gitbook)

We can use the terminal to download the template faster, and thus have the
complete directory without errors.


```linux
git clone https://github.com/sighingnow/jekyll-gitbook.git
```

The image shows the replacement of the template files (jekyll-gitboo) in our "docs" file.

![](/assets/Readme/13.32.37.png)

Next, we need to add the .md files from our "docs" folder to the posts on the page. To do this, we must edit each file with its respective header, as shown below, and give it a name that will make it easier for us to keep track of [date-name-language].

Do not forget to respect the format of the template, as well as using the guide posts that come with the same template as examples, in case you have doubts about how to edit the document.

![](/assets/Readme/14.11.21.png)
![](/assets/Readme/14.18.39.png)

We must properly edit the title (this will be the main title, the others will be subtitles, if using .md, ## should be used for editing the remaining text), the creation date, author, category, and layout.

When we have the files edited with their respective header, we must move the files to "posts" so that when we launch the page, we can visualize the desired change.

![](/assets/Readme/14.34.15.png)

We can go to the URL of our server and we will be able to see that the changes have been made.

![](/assets/Readme/13.32.37.png)



### Licence.
```
Copyright (C) DECENTRALIZED CLIMATE FOUNDATION A.C.
Permission is granted to copy, distribute and/or modify this document
under the terms of the GNU Free Documentation License, Version 1.3
or any later version published by the Free Software Foundation;
with no Invariant Sections, no Front-Cover Texts, and no Back-Cover Texts.
A copy of the license is included in the section entitled "GNU
Free Documentation License". 
```
