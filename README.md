This is a project to learn html and css.  The google-homepage will be deconstructed and recreated.  I will practice how to use git from the command line, and how to use html and css on a basic page.

First problem on the Mac was the file .DStouch .gitignore and add .DS_Store, need this to be ignored by git.
    touch .gitignore
    add /.DS_Store to the file



Decided to analyse some people's code to see how they'd done it, after trying to make the site with little success - looked at these solutions.  Some have used inline styles, others have done a style sheet.

Then got all the content on to the page, but nothing in the correct font, size or position.  Remembering html is for structure, css for style, so should look after things like fonts.  

It seems we have tthe following rows:-
    1   Links (About, Store, GMail, Images, Popout menu, Identity)
    2   Google logo
    3   Search box with
        "Search" and "feeling lucky" buttons
    4   Location bar tells you you are in e.g. United Kingdom
    5   Links
    6   Links

So we need a body to accomodate this within the <html>

Each row needs to be within an element so we can manipulate and style that element.  Question now is what are the most suitable elements for each?

1   Header
2   img
3   
4
5   nav
6   footer