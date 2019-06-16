---
layout: post
title:  "Customize your jekyll site"
date:   2019-06-13
categories: Jekyll
summary: Learn markdown and jekyll
thumbnail: https://picsum.photos/id/403/2560/600
---

1. Visual Studio Extensions   
    Open Extenions by Ctrl+Shit+x  
    There is side menu on top left. Click ... and select installed extensions. Only installed extensions are brought up on a list. Check what extensions are installed
    This list is extenstions you will need to make jekyll site. 
    Open extension panel and search extensions below to install all of them.    
    * Markdown+Math(goessner.mdmath)
    * color Picker
    * Jekyll Snippets
    * Lorem Ipsum
    * Markdown Emoji
    * Markdown Preview Github Styling  
2. markdown  
    A cheat sheet (also cheatsheet) or crib sheet is a concise set of notes used for quick reference. They contain a collection of notes, facts, and commands you can reference at any given time. For programming, the cheat sheets contain common syntaxes and data properties for a particular coding language.  
    Here is markdown cheat sheet. Click this --> [markdown-cheatsheet pdf](/assets/markdown-cheatsheet-online.pdf)
    * setup markdown snippet
    ![ markdown snippet](/assets/img/markdownsnippet.JPG) 

```json
    {
	"jkl-img-link-asset-route": {
        "prefix": "jkl-img",
        "body": [
          "/assets/img/$0"
        ],
        "description": "jekyll image assets location"
  },
  "jkl-page-desctiption":{
    "prefix": "jkl-page-desc",
    "body": [  "---",
               "title:  $0",
               "categories:",
               "- DailyDiary",
               "excerpt: |",
               "  $1 ",
               "feature_text: |",
               "  ##  $2",
               "  $3",
               "feature_image: 'https://picsum.photos/2560/600?image=2'",
               "mathjax: true  ",
               "---"
            ],
    "description": "jekyll blog page top description"        
  }
}
```
3. _config.yml  
    * It has all global variables such as title, author etc. 
    * If you delete a variable, it is not shown on page. 
    * Change title, author, username and email.  

3. Let's change "About.md"   
    * Open "About.md" file. You will see codes like this. Change "layout" from post to about  

```yml
---
layout: post
title: About
permalink: /about/
---
```  


4. Change color of title.  
    * Open "main.scss" file  
    * Find "brand-color"  
    * Change RGB code  

5. Add new post    
    * Add new md file  
    * write markdown 
    * Add emoji
    * Add image  

6. git
    * Log in to github : 
        https://github.com/JessiYoon
        Password : WpTldbs1~
        email : geun2young@gmail
        birthday : 1/1/1970
        gender: female
        Github user : JessiYoon


        
    * How to push your code 
           git remote add JessiYoon https://github.com/JessiYoon/Jekyll_site.git
    * Create new repository
    * Clone jekyll_site
    * push your project files to jekyll_site


