# HTML CSS Git_Homework1_Code Refactor

## Table of Contents

1.  [Deployed Applicatoin](#Deployed-Applicatoin)
2.  [Description](#Description)
2.  [Installation](#Installation)
3.  [Usage](#Usage)
4.  [Credits](#Credits)

## Deployed Applicatoin
[https://wryanj.github.io/gt_fsf_hw1_git-html-css/]

## Description
This assignment presented us with an html file, a css file, and some related images that were used as assets in the webpage. The task for us was to re factor the code to make sure it was clean, organized semantically, and updated so that it was more efficiently coded to generate the same result. The code we were given worked (generally) with exception to the links, however, it was very messy in both the HTML and CSS file. WIthin the CSS file, there was no clear structure of the file and there were multiple classes and such that could be cut out based on better grouping of CSS properties within a class or by elemenet selector. 

I learned a lot about various CSS properties I had not been exposed to, and I also learned that white space and semantically organized code that follows a similiar top-bottom stucture in the html file and css is much easier to work on and debug, compared to having it jammed together with bad indentation and not a logical outline established. The use of comments to put human readable labels on code blocks in the HTML and CSS file also helps to navigate through the code to make fixes, consolidations or improvements. I found I prefer to have lots of white space with indentation to make it easier to see child and parent elements. 

![image](https://user-images.githubusercontent.com/72420733/101996271-e508f180-3c9e-11eb-9173-0c1c80807e77.png)

When assigning styles to the different containers and elements, initially I did this by basically creating classes grouped under a main class for each element. For example I did .header, then created a class called .header-h1 and applied that class to the h1 in the header. But, I found I can basically do the exact same thing I was trying to do but easier after I researched this some by just listing the class and then the element in the class, ie .header h1 or . header h1 nav (CSS combinators). 

![image](https://user-images.githubusercontent.com/72420733/101996206-47152700-3c9e-11eb-8679-6471aa01c839.png)

From there I learned it says basically to "format this elemenet this way, if its a child of the element with the first class I specified". I also found to go multiple levels down, example a li inside a ul inside a nav inside a .header class, you just list the class then each element like .header na ul li. So I went back and further refactored this so that my CSS looked almost the same, but I didnt have to have all those separate named classess applied in the html file to each element (I also read that if I were to go any further than maybe 3-4 levels doing this, I would re-consider how I am doing my CSS because then it may be getting too complicated. In terms of git, I learned some more about deploying in git pages and making sure your index.html is always in your root. Intiailly mine was not, but then I moved it. After that I checked the link and no images worked but I was quick to realize from our prior class, its because the old file paths I had relative to the HTML for images are no longer valid since I moved the html up one directory. So I fixed those, pushed it and then it worked.  

I still think there are ways I have not learned to make my css even more simple, but at the very leasts its reduced from what it was and much more structured. 

 **Note** I made good use of the build in code inspection feature which helps me to see the code on the screen, and trace back styling issues based on what the inspection window is saying are the cascading styles applied to an element of interest. As I cleaned up I used it to trouble shoot to see where it was gettign properties I did not want there. 

 **Note** Before submission I re-organized the repo and directory to be more concise, and follow what I found to be best practices for repo organization (although it seemed there was no goldent ticket there.)

## Installation
I deployed this URL via git hub pages. I modified the code and readme in VS code and did testing with a live server using chrome. 

## Usage
This site is not really usable. As a student, I will however use it as reference to see how I organized my HTML and CSS upon re-factor so that I can use this as a guideline in the future when authoring new code and wanting to keep it clean, structured, and easy to work on. 

## Credits
Due to my time constraints, I worked on this generally alone. I utilized instruction materials from the class instructor as well as W3 resoruces, and some help from my GT tutoring resources. I did hower exchange suggestions and comments with the class via slack and during brekouts focused on the hw assignment. 
