# ch1w1
challenge Horiseon

practicing semantics and changing attributes and elements changes

## Acceptance Criteria

```
GIVEN a webpage meets accessibility standards
WHEN I view the source code
THEN I find semantic HTML elements
WHEN I view the structure of the HTML elements
THEN I find that the elements follow a logical structure independent of styling and positioning
WHEN I view the icon and image elements
THEN I find accessible alt attributes
WHEN I view the heading attributes
THEN they fall in sequential order
WHEN I view the title element
THEN I find a concise, descriptive title
on line 7, created a unique name for the title


----------------------------------------------------

<-what was given in starter code->
    <title>website</title>

<-what it changed to->
 <title>Horiseon</title>

------------------------------------------------
<-i worked in the body section of the starter code->

<-given html code->
<body>
    <div class="header">
     <h1>Hori<span class="seo">seo</span>n</h1>
      <div>
            <ul>
                <li>
                    <a href="#search-
                    . . .


<-changed div class to header (line 10), div was changed to nav (line 13)->

<body>
    <header>
        <h1>Hori<span class="seo">seo</span>n</h1>
        <nav>
            <ul>
                <li>
                    <a href="#search-



<-proceeded to change all '.header' to 'header' all throught the css-> 

(removed the (.) in the given css code)

<-given css code->

.header {
.header h1 {
.header h1 .seo {
.header div {
.header div ul {
.header div ul li {

-------------------------------------------------
  -cont'd working through body-


<-given html code->
   <div class="search-engine-optimization">
            <img src="./assets/images/search-engine-optimization.jpg" class="float-left" />
            <h2>Search
            . . .


<-changed div class to an section id element (line 30), added alt  attritbute for accesability,  i didthe same with lines 30-36 and 46-52->
 <section id="search-engine-optimization">
            <img src="./assets/images/search-engine-optimization.jpg" class="float-left" alt="image to explain search Engine"/>
            <h2>Search
            . . .


<-proceeded to change all element class in this section by replacing the (.) with an (#)>


<-given css code->

.search-engine-optimization {
.online-reputation-management {
.social-media-marketing {
.search-engine-optimization img {
.online-reputation-management img {
.search-engine-optimization h2 {



 -----------------------------------------------------------

<-changed div class to footer element->

<-given html code->
<div class="footer">
. . .

<-cleaned code>
<footer>
        <h2>Made with ❤️️ by Horiseon</h2>
        <p>
            &copy; 2019 Horiseon Social Solution Services, Inc.
        </p>
    </footer>
    . . .

<-got rid of the element class in the given code due to the changes done in the html above>    

<-given css code->

.footer h2 {