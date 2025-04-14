WEB DEVELOPMENT
WEB DEVELOPMENT

Frontend development :: building the user facing part of the website

Key Concepts

HTML : Hyper Text Markup Language : - create the webpage structure and layout - uses html elements to create content

CSS : Cascading stylesheets : - styling of HTML elements - frameworks to speed up the design process i.e. bootstrap , tailwind css

JS : JavaScript : - adding interactiveness and dynamic features through the Document Object Model

Responsive Design - ensure the website looks good on various screen sizes (desktops , tablets and mobiles phones) - Techniques , - bootstrap - css media queries

backend development :: deals with the server side of a website :: scripting files , databases (MySQL) - the application is the code that contains the logic of the website or web app - Database : used to store and manage the data - Python / Django - PHP / Laravel , Javascript / Node , Ruby / Ruby on rails , Java

Front End -> <-Web Services <-> Backend

Terminal :: management of files , directories and processes.

Version Control Systems : systems used in programming to track changes in code. and also facilitate collaboration amongst multiple developers

GIT : a VCS , provided to access on platforms GITHUB / BITBUCKET / GITLAB

TERMINAL : COMMON COMMANDS FOR DIRECTORY MANAGEMENT IN WEB DEVELOPMENT / GIT BASH / Terminal

project : Emobilis Web Development Page : info on the program , course outline , about

decision on the project structure
RootDirectory -> index.html , CSS/ PUBLIC/ ASSETS/ JS/
Print Working Document : pwd

list : ls

change directory : cd 'directory name' : navigate in cd .. : navigate out

clear : to clear out commands on terminal

mkdir : make directory :: mkdir 'emobilis web' mkdir emobilisWeb

touch : create a file : touch filename

cp : copy ,

mv: move

cat : allow create files

rm -rf directoryname

GITHUB PROCESS
Prerequiste
a. Terminal knowledge b. github account c. ## configure the github on terminal

Configuration steps
git init
git config user.email 'x@example.com' {here use the email you registered to github with}
git config user.name 'josephbill' {github account username}
when the project is new
git init
git remote add origin https://github.com/josephbill/emobilisWebPage.git {get your url origin from github}
git remote -v {to check if above origin was added}
git status : {red : rep. files that are not yet added to be committed} {green rep. files that are ready to be committed}
git add . git add filename/foldername
git commit -m "add commit message"
git push origin branchname(master/main)
when the project is not new
git status : {red : rep. files that are not yet added to be committed} {green rep. files that are ready to be committed}
git add . git add filename/foldername
git commit -m "add commit message"
git push origin branchname(master/main)
HTML
HTML elements : an html element will defined with a start tag , some content and then an end tag <> content </> </> :: enclosing tag.
Nature of the element ::
Block level element :: occupies entire width of the canvas
Inline element :: occupies only necessary width required by the elements
HTML Attributes :: more info. about the element every single html element can have an attribute
CSS
cascading stylesheets
Key Concepts

How to write CSS ....
inline css : css directly written on the element : style attribute
internal css : css script written inside the html document : style element
external css : css script is an external linked to the html document
Syntax identifier/selector : { property: value; }
How to select element to style
inline css : the element is the selection
id attribute : unique identifier for our elements
class attribute : grouping identifier for our elements
tag elements : identifying the element to style using its html element name
CSS GRID
                                        1. Navbar navbar
2.Courses List 3. video playing about emobilis 4.Some content 5.ShortCoures List 6. Course application form 7.Some content 8. Footer footer

Parent container
