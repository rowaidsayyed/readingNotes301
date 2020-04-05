# Welcome 301d4

## worker today
* A worker today might start the morning by collaborating with a team of engineers,
* send emails to colleagues marketing a new brand,
* jump on a conference call planning an entirely different product line, 
* juggling team meetings with accounting and the party-planning committee.

Our **data-saturated** age enables us to examine our work habits and office quirks with a scrutiny that our cubicle-bound forebears could only dream of.


Note: most valuable firms have come to realize that analyzing and improving individual workers ­— a practice known as ‘‘employee performance optimization’’ — isn’t enough. 

## Group studies
* show that groups tend to innovate faster, see mistakes more quickly and find better solutions to problems
* show that people working in teams tend to achieve better results and report higher job satisfaction.


 ## group norms
 Norms are the traditions, behavioral standards and unwritten rules that govern how we function when we gather

## Google reasearch
 After looking at over a hundred groups for more than a year, Project Aristotle researchers concluded that understanding and influencing group norms were the keys to improving Google’s teams.

 ## MIT reasearch
 The researchers concluded that what distinguished the ‘‘good’’ teams from the dysfunctional groups was how teammates treated one another. 

## not all the good teams appeared to behave in the same ways. 
 * Some teams had a bunch of smart people who figured out how to break up work evenly,
 * said Anita Woolley, the study’s lead author. 
 * Other groups had pretty average members, but they came up with ways to take advantage of everyone’s relative strengths. 
 * Some groups had one strong leader. 
 * Others were more fluid, and everyone took a leadership role.

 ## all the good teams generally shared. 
 * team members spoke in roughly the same proportion
 * had high ‘‘average social sensitivity’’

 ## Google’s conclusions 
* managers have always known. 
* members listen to one another
* show sensitivity to feelings and needs.


## REST
Who is Roy Fielding?
He helped write the first web servers, that sent documents across the Internet

 The whole world wide web is built on an architectural style called “REST”
REST provides a definition of a “resource”, which is what those things point to.

 "redirect" is that having one machine tell another machine about a resource that might be on yet another machine.

## nouns
* Machines don't have a universal noun 
* Every programming language, database, or other kind of system has a different way of talking about nouns.
* URL is so important because It let's all of the systems tell each other about each other's nouns.

the browser does an HTTP GET on the URL you type in and back comes a web page.
The web page just specifies the URLs to the images and the browser goes and does more GETs using the HTTP protocol on them until all the resources are obtained and the web page is displayed

* systems would retrieve information from each other use 'HTTP GET'.
* If one system needs to add something to another system use an 'HTTP POST'.
* If a system wants to replace something in another system use an 'HTTP PUT'
* to do a partial update use 'PATCH'.

## SuperAgent
SuperAgent is light-weight progressive ajax API crafted for flexibility, readability, and a low learning curve after being frustrated with many of the existing request APIs. It also works with Node.js!

### Request basics
A request can be initiated by invoking the appropriate method on the 'request' object, then calling '.then()'
