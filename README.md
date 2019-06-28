# cookbook-marketing
Marketing page for Secret Family Recipe Cookbook

Welcome to this Repo.

I will break down how the website has been structured so you may able to modify
and tweak accordingly.

There are two HTML pages, 'index.html' is the main page and it's linked to 'about-us.html', which is another page exploring details of the team who worked on overall project.

Configuration of this Repo:

There are 4 project folders which consists of:
    - css - index.css is generated via LESS Compiler
    - img - contains all the pictures used in the project
    - less - LESS preprocessor was used in this project to generate the CSS
    - components - a reuseable component built via JavaScript using DOM and classes

The HTML files are at the root of the repo.

INDEX.HTML

    Semantic properties have been applied so it is easier to understand the structure. The structure consists of header, sections, footer.

    Within the header and footer, a nav bar exists too. 

    In the div with class name "section", it has entire reuseable component which breaks down top 'Tabs' and its respective content 'Tabs-items'

    Within the 'Tab-items' is a div with class name "detail-section", this features a picture along with a list.

    You can identify all the divs easily via browser inspector.

ABOUT-US.HTML

    This page has alternating way of presenting information on the screen via class 'alternate' which comprises of flex-direction of reverse. Otherwise everything else is quite similar to index.html.

STYLES

    Lot of styles were imported from previous projects but most of new styles are implemented in 'main-page.less' 

    In addition, this site is tweaked for optimized viewing for 500px mobile devices and 1000px desktop devices. Flex Box and font sizing via rem scale was used to achieve this.

JAVASCRIPT

    Component functionality was done via DOM selection, Event listener and JavaScript classes & its methods


