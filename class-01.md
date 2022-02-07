# Class 01: Introductory to html and javascript

+ [Duckett HTML book: Introductions](#html0)
 
+ [Html Chapter 1: "structure"(pp.12-39)](#html1)
 
+ [HTML Chapter 8: “Extra Markup” (p.176-199)](#html2)
 
+ [HTML Chapter 17: “HTML5 Layout” (pp.428-451)](#html3)
 
+ [HTML Chapter 18: “Process & Design” (pp.452-475)](#html4)

+ [Duckett Js Book: Introduction](#js1)

+ [JS Chapter 1: “The ABC of Programming” (pp.11-52)](#js2)


## <a name="html0"></a>Duckett HTML Introductions
 People Access the web through many different mediums.<br>
 This can range from browsers, web servers, devices and screen readers.<br> 
 Web Servers are computers that remain connected to the internet. They make <br>
 sure they send webapges out to devices that request them.
 
 Screen Readers: <br>
 - *Programs that read out the contents of a computer screen to a user. <br>
  They are commonly used by peoplewith visual impairments.<br>*
 
 > 1.When you connect to the web,<br>
 you do so via an Internet Service<br>
 Provider (ISP). You type a <br>
 domain name or web address<br>
 into your browser to visit a site;<br>
 for example: google.com,<br>
 bbc.co.uk, microsoft.com.<br>
 
>2.Your computer contacts a<br>
 network of servers called<br>
 Domain Name System (DNS)<br>
 servers. These act like phone<br>
 books; they tell your computer<br>
 the IP address associated with<br>
 the requested domain name.<br>

>3.The unique number that the<br>
DNS server returns to your<br>
computer allows your browser<br>
to contact the web server<br>
that hosts the website you<br>
requested. A web server is a<br>
computer that is constantly<br>
connected to the web, and is set<br>
up especially to send web pages<br>
to users.<br>

>4.The web server then sends the<br>
page you requested back to your<br>
web browser.<br>
    
   - DNS servers host the ip Addresses that all devices request.
   - They tell your device the specific ip address that is connected with the website
   > DNS servers are like the bouncers of websites. They let you have access to the club or in this case the website you requested.         

All websites use at their core HTMl and CSS it's just that larger Websites<br>
will use CMS systems(Content Managment Systems). Some examples would be like<br>
to make use of more complex techologies on the web server. This is all to futher<br>
the user experience of the website.
 - HTMl is constantly coming out with new version with each<br> 
  versions an improvement on the last


##  <a name="html1"></a>Structure

***Structure*** In HTML is created through the use of elements<br>
These are all the basic elements used on a webpage to create Structure
- **html**
- **Body**
- **h1**
- **h2**
- **P**

This diagram will help better understand the how these elements create<br>
structure to a webpage.

```<html>
      
    <body>
     
     <h1>This is the Main Heading</h1>
     
     <p>This text might be an introduction to the rest of
     the page. And if the page is a long one it might
     be split up into several sub-headings.<p>
    
     <h2>This is a Sub-Heading</h2>
    
     <p>Many long articles have sub-headings so to help
     you follow the structure of what is being written.
     There may even be sub-sub-headings (or lower-level
     headings).</p>
    
     <h2>Another Sub-Heading</h2>
    
     <p>Here you can see another sub-heading.</p>
   
    </body>
</html>

The Code above is an example of the most basic webpage structure.
at the top it starts off with a html element. An html element is basically
telling the computer that anything in between this section is one whole html code;
however if you look closely the html tag is surrounded by to angle brackets(<>).
Every element has an opening and closing tag.
```

>Tags act like containers. They tell you<br>
something about the information that lies<br>
between their opening and closing tags.<br>

```
<body>

THE GOOD STUFF

</body>


The body tag make sure that any code in between the opening a closing tags
show up inside the main window of the browser; basically without this tag you would 
have blank pages. Its like an essay without any words.
```

```
<h1>            <h2>


This tag just Creates a main header for your webpage. Its the first thing that should 
catch your eye on a page. 

```
```
<p>             </p>

This tag creates paragraphs on the page. This is useful when you have a lot of topics 
to cover.


```

```

<h2>            <h2>

h2 tags create sub headings. this is used to further sections parts of a webpage.

```

```

<title>           </title>

the title tags make sure that anything inbetween them shows up in the url of the webpage. as the the name
suggest it just names your webpage.
```
One thing to mention is that within these tags you can also have attributes. <br>
Attributes provide a little more information about what's inside a tag.<br>


```
<  p          lang    =                "en-us"   >   Paragraph in English</p>
            |_______|                |_________|
                |                         |
                V                         V
            Attribute Name          Attribute Value
```

Every Attribute must have a Name and Value. The Name is specifies what extra information<br>
is being added to the element. The Value is the Information of the Attribute.
 
## <a name="html2"></a>Extra Markup

We know that the internet is always changing and improving and with those<br>
improvments there different version of code that people use. <br>

how do we differenciate which version of Html we are using and communicate<br>
that to the computer? 

![Thinking?](https://qoobee.com/wp-content/uploads/EMO_080.gif)

### We use DOCTYPES!!!

Doctypes tell the broswer which version of HTML your webpage is using.<br>
the use of Doctypes is what allows certain webpages to render correctly.

Syntax Run-Through:
```

<!-- -->

If you want to add a comment
to your code that will not be
visible in the user's browser, you
can add the text between these
characters.
```

```
<div>
This element allows to group up
a set of elements to one block level.

```

```
<span>
This is used for one of two things

1. Seperating text you want to differentiate from
the rest.
2.Contain inline elements

```
`<em> <em>`<br>
`<strong> <strong>`<br>
`<b> <b>`<br>

These are all examples of inline elements<br>

`<em>` tag puts emphasis on a piece of _text_<br>
`<strong>` tag make the text **bolded**<br>
 `<b>` does the samething <b>strong does<br>
  
  ```
<Iframes>
This lets you cut a certain amount of a webpage and put it direcrly
into your webpage
```

```
<meta>
 Meta tags are pieces of information you use to tell the search engines and 
 those viewing your site more about your page and the information it contains.

```
The <meta> element also uses the http-equiv and content attributes in pairs.<br>
In our example, you can see three instances of the httpequiv attribute. Each one has a<br>
different purpose 
 
<strong>Author: This defines the author of the<br>
web page.<br>

 <strong>Pragma:<br>
This prevents the browser from aching the page. (That is,<br>
storing it locally to save time downloading it on subsequent<br>
visits.)<br>

<strong>Expires:<br>
Because browsers often cache the content of a page, the<br>
expires option can be used to indicate when the page<br>
should expire (and no longer be cached). Note that the date must<br>
be specified in the format shown<br>
 
 
 

## <a name="html3"></a>HTML5 Layout

In a traditional html layout authors used the ```<div>``` element to group together <br>
related elements; html5 has changed so that new elements were added which replaced<br>
all the uneccessary bulk behind using the ```<div>``` element. This in turn made the website<br>
much easier to follow. 
 
``` 
 <div id="header">
        ^
        |
      This turned into  |
                        V
                     <header>
```
Even now newer builds of html are updadted that add more funtionality and more control<br>
to the user. Here are some examples of this
                    
- ``` <footer> ```:<br>
can used in conjunction with ```<header>``` to show links to websites that were included in
the header.
- ``` <nav> ```:<br>
This is used hold to big navigation blocks like to the privacy policy, and terms of conditions<br>
at the bottom of the page. It basically just navigates to a place on a webpage(not other webpages).
                      
- ``` <article> ```:<br>
Article is interesting becuase you can think of it as an independent block of code that can be reused.<br>
For example, Screen readers and search engines might be able to look through the code on the webpage<br>
and get straight to the content of your website while being able to ignore the header or footer.<br>
It's like a tl:dr for html.
                      
- ```<aside>```:<br>
This element has one of two functions (depending on whether or not it is inside an article element), while inside an <br>
article element ```<aside>``` contains information related to article but not that important. When the ```<aside>``` is used <br>
out of an article it contains information related to the whole page.
                      
- ```<section>```:<br>
As the name Suggests, ```<section>``` contains a group of elements within a part the webpage. These elements are all<br>
related content.

- ```<hgroups>```:<br>
These just group together a set of h1-h6 elements to make one heading.
                      
- ```<figure>``` ```<figcaption>```:<br>
```<figure>``` is used to reference any information that is in the main article. ```<figure>``` should have the <br>
```<figurecaption>``` element providing a description of the ```<figure>``` element

Older browsers need help identifying newer html elements, treating them as inline elements by default. to get around<br>
this add pieces of code to your html and css code that alter how older browsers see those elements.<br>
                      
>For Html
``` 
  <!--[if lt IE 9]>
<script src="http://html5shiv.googlecode.com/svn/
  trunk/html5.js"></script>
<![endif]--> 
     
```
> For CSS
```
   header, section, footer, aside, nav, article, figure
{
display: block;}                  

```      
<br>
                      
##  <a name="html4"></a>Proccess and Design

                      
- Process and Design is all about thinking about how you want your webpage made, and recived; and better yet by whom. <br> 
- If you think about why someone would even want to visit your website you can start design your website to maximize the vistors <br>
of your page. 
-If you are targeting a certain demographic then you cater to what kind of information they would be looking for.<br>

Site maps:<br>
Are used to map the overall layout of a webpage and as rough draft for how the site would group information; this determines which information.<br>
should come before others. 

![site map](https://d2slcw3kip6qmk.cloudfront.net/marketing/blogs/chart/how-to-make-a-site-map/site_map_example2-700x533.PNG)
                      
                      
Wifeframe:<br>
                      
If sitemaps are used to indicate how information ranks then a wireframe determines where the information should go. it's like a rough draft<br>
of the website.<br>
![wireframe](https://cdn-images.visual-paradigm.com/handbooks/agile-handbook/wireframe/01-youtube-wireframe-example.png)
                      
 Designing Navigation:
 - Concise: The user should be able to navigate your webpage quickyl and effciently.
 - Clear: The user should never feel lost when viewing the webpage.
 - Selective: Your website shouldn't all its information on one page. Things like the login and contacts shouldn't clutter your main information<br>
                      
<br>
                      
## <a name="js1"></a>JS Introduction
 
    
                      
    - What is the purpose of javascript?<br>
    - What is javascript?<br>

*Javascript is a coding language that is used to make webpages interactive.*                   

  - Why does a webpage need to be interactive?<br>
    - What does interactive mean?<br>


On a standard html page everything the user will experience is laid out to them. There might be different fonts and style <br>
but what they see is pretty much the website. Javascript works in conjunction with html to create feedback for the users<br>
actions. This feedback or response is what makes a webpage interactive. Javascript allows you to change the code on the webpage<br>
while the user is viewing it.
   
                      
  - Examples of this include<br>
               - Slideshows<br>
               - Forms<br>
*Both of these are a form of user input based scripts.*<br>
Javascripts use events to run scripts on a webpage. These events are what I refered to as user inputs.<br>
             ```                     
             • A link is clicked (or tapped) on
             • A cursor hovers over an element
             • Information is added to a form
             • An interval of time has passed
             • A web page has finished loading 
             ```
             <br>


                      
 ## <a name="js2"></a>The ABC of Programming 
 
                      Scripts:<br>
A collection of steps as a form of instructions(code) for a computer to follow.<br>
Webpages can have multiple scripts on them but will only start running when the user interacts with them.<br>
To Successfully writing a script you need to have an end goal, then list out things you need to do to get that result.<br>
1. Define the goal<br>
2. Design the script<br>
3. Code each step<br>
  
People use flowcharts when drafting ideas for scripts. Flowcharts allow you categorize all the tasks needed to get the desired<br>
end result.<br>
    ![flowchart](https://jquery-plugins.net/image/plugin/flowchartjs-svg-flow-chart-diagrams-with-javascript.png)
                     
Every section in a flowchart needs to be written in a language a computer can understand them. For us we can cut corners on how<br>
much information we write to make a suffcient task list. For example below I will indicate how to make a PB&J sandwich.<br>
                    1. get bread, jelly and peanut butter<br>
                    2. spread them on two pieces of bread<br>
                    3. now you have a sandwhich<br>
Me and you both know I left out a lot of information. <br>
                      - What kind of untensil am I using? <br>
                      - which side of the bread go together?<br>
                      - how much peanut butter?<br>
                      - how much jelly?<br>
                      - which side to put peanut butter and jelly?<br>
                      - finally closing the PB&J<br>
For us this is intuitive. We can even go as far as just listing the ingredients on a piece of paper with all the supplies. A good amount<br>
of people can make out that they need to make a PB&J.<br>

This is very different from how a computer solve tasks. Computers need detailed information about what their doing. The information written<br>
needs to be effiecent yet very concise. This is a hard balance.<br>
                      
                      
 Computers need to be told Precisely what is in their enviornment(code). If a code has section that leave the computer in the dark,<br>
 you won't get the result you desire because the computer wasn't given suffient information. This is where objects and properties come in.<br>
 
  Objects:<br>
 - an entity with properties and type<br>
  Properties:<br>
 - the values associated with a javascript object<br>
The properties of an object changes with the introduction of events. Events are just another word for user inputs. these events can happen anywhere<br>
on the page. Programers are able to choose which event will trigger which part of the script.<br>

Method:<br>
changes the value of object's properties. it adds another layer of information added to the object. Method carries instructions that don't necessarily <br>
need to complete its task. They just need to be able to ask the question and interpret answers it gives you.<br>

Webpages interactivesness comes from using code that use the browsers model of the web page.<br>
                      
HTML CSS and Javascript are explained simple by attributing them to layers.<br>
- Html is the content layer<br>
- CSS is the presentation layer<br>
- Javascript is the behavior layer<br>
This means basically the html layer is what we see, the CSS is how we see it like style font and the javascript is how it reacts to the user.<br>
                      
                      
How to use objects and methods:
        
   ```          
        Document         .           write         ('good afternoon!');
        |_______|       |_|         |______________|__________________|___|
            |            |                       |            |
            V            V                       |            V
         object    member operator               |        parameters
                                                 V
                                               Method
   
  ```
                      
  Member operators: within the document there can be a lot of methods and properties. These are known as members of that object. to access members you put<br?
  ```.``` between object and the member you want to access.
  
  Parameters: data that method can require to work.<br>
                      
  Method: the ```write()```method is what allows content to be written into the page where the```script``` element sits.<br>
  
  In Html where there is a script element the brows stops and makes sure to load the ```<script>``` element.
