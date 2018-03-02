---
title: ""
author: "Tham, Wei Yang"
date: "January 15, 2018"
output: 
  html_document:
    toc: true
    toc_float: true
    keep_md: true
---



## Resources
- [Happy Git with R (still very useful for non-R users!)](http://happygitwithr.com/)
- [Excuse me, do you have a moment to talk about version control?](https://peerj.com/preprints/3159.pdf)
- [git vs. Dropbox from a researcher's perspective](https://michaelstepner.com/blog/git-vs-dropbox)

## Set up a Github account

- [https://github.com/](https://github.com/)
- [Some tips here](http://happygitwithr.com/github-acct.html)
    + Try to get your username right the first time!
- Academia gets free private repos: request from [https://education.github.com/](https://education.github.com/)

## Install Git
- This is where I will be least helpful, especially for Windows users
- [Follow this section of Happy Git with R closely](http://happygitwithr.com/install-git.html)

## Introduce yourself to Git

Run the code below in your [shell](http://happygitwithr.com/shell.html). 

- `user.name`: use some version of your real name so we know who is making changes
- `user.email`: you **MUST** use the email associated with your Github account


```bash
git config --global user.name 'weiyangtham'
git config --global user.email 'weiyang.tham@gmail.com'
```


```bash
git config --global --list
```

```
## user.email=weiyang.tham@gmail.com
## user.name=weiyangtham
```

## Git client (aka make your life easier)
- adf

## .gitignore

