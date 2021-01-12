
## Forms
HTML Forms are required, when you want to collect some data from the site visitor. For example, during user registration you would like to collect information such as name, email address, credit card, etc.

A form will take input from the site visitor and then will post it to a back-end application such as CGI, ASP Script or PHP script etc. The back-end application will perform required processing on the passed data based on defined business logic inside the application.

There are various form elements available like text fields, textarea fields, drop-down menus, radio buttons, checkboxes, etc.

The HTML <form> tag is used to create an HTML form and it has following syntax −
# Example:

<form action = "Script URL" method = "GET|POST">
   form elements like input, textarea etc.
</form>
- Whenever you want to collect information from
visitors you will need a form, which lives inside a
<form> element.
- Information from a form is sent in name/value pairs.
- Each form control is given a name, and the text the
user types in or the values of the options they select
are sent to the server.
- HTML5 introduces new form elements which make it
easier for visitors to fill in forms.

## Lists, Tables & Forms:
Many web pages use multiple columns in their design. This is achieved by using a <div> element to represent each column. The following three CSS properties are used to position the columns next to each other:width
This sets the width of thecolumns.
float
This positions the columns next to each other.
margin
This creates a gap between the columns. 

A two-column layout like the one shown on this page would need two <div> elements, one for the main content of the page and one for the sidebar.
Inside each of the <div> elements there can be headings, paragraphs, images, and even other <div> elements.
 ## Events
 Events are actions or occurrences that happen in the system you are programming, which the system tells you about so you can respond to them in some way if desired. For example, if the user selects a button on a webpage, you might want to respond to that action by displaying an information box. In this article, we discuss some important concepts surrounding events, and look at how they work in browsers. This won't be an exhaustive study; just what you need to know at this stage.
 Events are the browser's way of indicating when
something has happened (such as when a page has
finished loading or a button has been clicked).
Binding is the process of stating which event you are
waiting to happen, and which element you are waiting
for that event to happen upon.
When an event occurs on an element, it can trigger a
JavaScript function. When this function then changes
the web page in some way, it feels interactive because
it has responded to the user.
You can use event delegation to monitor for events
that happen on all of the children of an element.
The most commonly used events are W3C DOM
events, although there are others in the HTMLS
specification as well as browser-specific events. 