# [Class 11: - Audio, Video, Images](/README.md)

- ## Chapter 16: “Images” (pp.406-427)
- ## Chapter 19: “Practical Information” (476-492)
- ## Video and Audio APIs
Honorable mentions- Flash(pg 200-206)
<hr>


# Images
- ## `repeat`: Makes an image repeat horizontally and vertically.
- ##  `repeat x: Make an image repeat only on the x-axis.
- ## `repeat y`: Makes an image repeat only on the y-axis.
- ## `no repeat`: the image is only shown once.
- ## `fixed`: the image is fixed on the screen
- ## `scroll`: the image moves with the background as you scroll

This chapter just deals with the manipualtion of images throughout the webpage. Being able to resize or design a webpage by changing how the image is displayed or functions in general. 

# Practical Information

- ## `page title`: at the top of the webpage and lives within the head element.
- ## `headings` are what allow search enginges to be able to optimize webpages and depending on the search. It just describes what your webpage is about.
- ## `image alt`: this describes the image on your webpage for screeners and image based searches. 

- ## `seo`: search engine optimization. This is what allows your webpage to be either easily reachable to a user or just very hard to find. 

## when starting SEO its best to break it up into six steps
1. brainstorm
2. organize
3. research
4. compare
5. refine
6. map

- ## To deploy your site you need have a domain name and web hosting


# Video and Audio APIs
 

 I took one sample from the page I thought was interesting or cool. I chose this code block because after the play buttun click is created it needs to change from pause icon to another icon and in this piece of code they are doing just that. Overall this article is just showing the code behind a video window but the real interesing part is the forward and backward. I would never think they would be using an if statement ro rewind and fast forward. the thought just didnt occure to me. 
```
function playPauseMedia() {
  if(media.paused) {
    play.setAttribute('data-icon','u');
    media.play();
  } else {
    play.setAttribute('data-icon','P');
    media.pause();
  }
}
```