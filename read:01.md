This is read:01, code:201
# HTML & css design and build web sites:
## Capter: 1 introduction (pp.2-11)
### How people access the web:
- **web browsers**: People access websites using software called a web browser. examples include Firefox, Internet Explorer, Safari,
Chrome, and Opera.
- **A web server** is a special computer  which hosts the website. <br >
Web servers are special computers that are constantly connected to the Internet, and are optimized to send web pages out to people who request them.
- **Screen readers** are programs that read out the contents of a computer screen to a user. They are commonly used by people with visual impairments.
### How websites are created:
- Most websites are written using HTML and SCC. whereas HTML is used for structuring and bulding web sites, SCC is used for styling.
### HOW the web works:
- When you visit a website, your browser will first connect
to a Domain Name System (DNS) server. (The prime aim of the DNS is to find the IP address associated with the requested domain name) the DNS returns a special number that allows your browser to contact the web server that hosts the website you requested.The web server then sends the page you requested back to your web browser. 
***
## Chapter: 2  structure (pp.12-39)
### How Pages Use Structure:
- stories in a newspaper are usually comprised of haedline, text,and possibly some images and subhaedings. <br > 
The use of headings and subheadings in any document often reflects a hierarchy of information. For example, a document might start with a large heading, followed by an introduction or the most important information. <br >
Web pages are therefore structured the same kind of way.
### HTML Describes the Structure of Pages: 
- To structure a web page, we add code to we add code to the words we want to appear on the page.
- **Elements** are made up of characters that live inside angled
brackets. Elements usually have two tags: an opening tag and a closing tag. (The closing tag has an extra forward slash in it.) Each HTML element tells the browser something about the information that sits between its opening and closing tags. 
### HTML Uses Elements to Describe the Structure of Pages:
* There are a number of elements that tell the browser something about the information inside them: 
    1. **html** element to indicate that anything inside ot is an HTML code.
    2. **body** element indicates that anything inside it should be shown inside the main browser window.
    2. **h1** is a main heading and it descend all the way to **h6** to indicate subheading
    3. **P** is a paragraph text.
### Attributes Tell Us More About Elements: 
- Attributes provide additional information about the contents of an element. They appear on the opening tag of the element and are
made up of two parts: a name and a value, separated by an equals sign.
### Body, Head & Title: 
* **body** Everything inside this element is shown inside the main browser window.
- **head** element contains information about the page. There is also the **title** element inside the **haed** elemnet. 
- **title** element content's  are either shown in the top of the browser, above where you usually type in the URL of the page you want to visit, or on the tab for that page. 
*** 
## Chapter: 8 Extra Markup (p.176-199)
### DOCTYPES:
- DOCTYPE declaration tells the browser which version of HTML is being used. for example,
    1. HTML5 <br >
    !DOCTYPE html 
    2. HTML 4 <br >
    !DOCTYPE html PUBLIC
    "-//W3C//DTD HTML 4.01 Transitional//EN"
    "http://www.w3.org/TR/html4/loose.dtd"
    3. Transitional XHTML 1.0 <br >
    !DOCTYPE html PUBLIC
    "-//W3C//DTD XHTML 1.0 Transitional//EN"
    "http://www.w3.org/TR/xhtml1/DTD/
     xhtml1-transitional.dtd"
    4. Strict XHTML 1.0 <br >
    !DOCTYPE html PUBLIC
    "-//W3C//DTD XHTML 1.0 Strict//EN"
    "http://www.w3.org/TR/xhtml1/DTD/
     xhtml1-strict.dtd"
     5. XML Declaration <br >
     ?xml version="1.0" ?
### Comments in HTML
- !-- -- to add a comment to your HTML code. Comments do not appear on the main browser window. 
### ID Attribute
-  Attributes are used to uniquely identify an element from other elements on the page. their value should start with a letter or an underscore. The id attribute is known as a global attribute because it can be used on any element.
### Class Attribute 
Class attributes identify several elements as being different from the other elements on the page. The class attribute on any
element can share the same value. By default, using these attributes does not affect the presentation of an element. It will only change their appearance if there is a CSS rule that indicates it should be displayed differently.
