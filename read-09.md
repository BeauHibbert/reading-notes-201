# Forms and JS Events
## Forms
Notes from Chapter 7: Forms, from Jon Duckett’s HTML and CSS book
* To collect information from visitors, a form will be needed and to do that you use the <form> element. This element should always carry the action attribute and will usually have a method and id attribute too.
* Information from a form is sent in name/value pairs
* Each form control is given a name, and the text the user types in or the values of the options they select are sent to the server
* HTML5 introduces new form elements which make it easier for visitors to fill in forms
* When a message is given when a form control has not been filled in correctly, that is known as form validation
* You can use several different types of form controls to collect information from visitors
  - Adding text: Text inputs, password inputs, text areas
  - Making choices: Radio buttons, check boxes, drop-down boxes
  - Submitting forms: Submit buttons, image buttons, file uploads

## Lists, Tables and Forms
Notes from Chapter 14: Lists, tables and forms from Jon Duckett’s HTML and CSS book
* List-style-type and list-style image properties can be used as list markers to give different appearances 
* Table cells can have different borders and spacing in different browsers but there are properties you can use to control them and make them more consistent
* Forms are easier to control when they are vertically aligned using CSS
* Forms benefit from styles that make them feel more interactive
* The list-style-type bullet point allows you to control the shape or style of a bullet point (aka a marker)
* The list-style-image property can be used to specify an image to act as a bullet point
* Table properties
- Width
- Padding
- Text-transform
- Letter-spacing, font size
- Border-top, border bottom 
- Text-align
- Background-color
- Hover

## EVENTS
Notes from Chapter 6: Events, from Jon Duckett’s Javascript book
* Events are the way the browser indicates when something has happened.
* Binding is the process of stating which e ent you are waiting to happen, and which element you are waiting for that to happen upon
* When an event occurs on an element it can trigger a javascript functionv The webpage then feels more interactive because it has responded to the user
* Event delegation can be used to monitor for events that happen on all of the children of an element
* The most commonly used events are W3C DOM events, although there are others in the HTML5 specifications as well as browser-specific events
* Event listeners are a more recent approach to handling events. They can also deal with more than one function at a time
* HTML elements nest inside other elements. If you hover over or click on a link, you will also be hovering or clicking on its parent elements
* The flow of events only really matters when your code has event handlers on an element and one of its ancestor or descendant elements