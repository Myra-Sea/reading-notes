# 🦉 Forms and JS Events 🦉

## 📝 Homework Assignments:

❓ Why are forms so important in web development?

They are one of the main points of interaction between a user and a website or app.  Forms allow users to enter data.  That data, in turn, is used for processing and storage, or used to immediately update the interface in some way.  Two real world examples of how a user's input might be critical to fulfilling a webpage's purpose would be the forms used withing website user registration or on an online shopping cart's checkout screen. 

❓ When designing a form, what are some key things to keep in mind when it comes to user experience?

* Keep it simple and easy to understand
* Keep the amount of reading requried short in length
* Stay focused with questions. Keep the amount of information to be entered short in length (ask only for what you need).
* Make sure it is accessible, including easy to read

❓ List 5 form elements and explain their importance.

1. `<textarea>` collects multi-line text so that users can input longer content.  An example would be user comments.
2. `<button>` creates the visible button that the user clicks on. Buttons may be set up to `submit` a user's data to the server for processing, or it may instead be a `reset` button for clearning the form of its content.
3. `<form>` formally defines the start of a form on the page.  It is a container element in the same way that a `<section>` or `<footer>` is.  It is standard practice to always set at least the `action` and `method` attributes of a form.
4. `"checkbox"` allow a user to select one or more options from a list of choices. An example would be a multiple choice question on a test.
5. `<fieldset>` groups and labels a set of related form controls (for example, radio buttons or text input fields). By creating a visual and semantic grouping of the elements, it makes it easier for a user to understand the relationship between them.  It is often accompanied by a `<legend>` element which provides a title label description for the group.

<br>

❓ How would you describe events to a non-technical friend?

It is similar to when we talk about a "noteworthy event" having happened to us in life.  It's like when your senses alert you that something is significant and worthy of drawing your attention.  Like a sudden loud noise or a flash of like.  Like the neurons in your brain firing, when an event happens to a computer system it sends a signal for an action to be taken as a reaction.

❓ When using the addEventListener() method, what 2 arguments will you need to provide?

1. The string that indicates what event it is we want to pay attention to
2. A function to call when the event happens

❓ Describe the event object. Why is the target within the event object useful?

A parameter (inside of an event handler function) that is automatically passed to event handlers to provide extra features and information.  An event object represents that an event has occurred and therefore contain information such as the source, timestamp, and other data about the event.

The target property identifies the specific element or object that triggered the event, and thereby provides essential information for event handling.

❓ What is the difference between event bubbling and event capturing?

They describe two different directions that events can be processed in the DOM of a web browser when multiple elements are nested within each other and an event occurs on one of those elements.  Bubbling is typically the default behavior, and it is the phase during which the event starts from the target element and travels upward thru the DOM tree to the root.  Event capturing is sometimes called "event trickling" and means that the event starts from the root of the document and trickles down to the target element that triggered the event.

<br>

<br>

## 📚 Links to the Assigned Reading:

[HTML Forms](https://developer.mozilla.org/en-US/docs/Learn/Forms)

[Your first Web Form](https://developer.mozilla.org/en-US/docs/Learn/Forms/Your_first_form)

[How To Structure A Web Form](https://developer.mozilla.org/en-US/docs/Learn/Forms/How_to_structure_a_web_form)

[Learn JS](https://developer.mozilla.org/en-US/docs/Learn/JavaScript)

[Introduction To Events](https://developer.mozilla.org/en-US/docs/Learn/JavaScript/Building_blocks/Events)

[HTML5 Input Types](https://developer.mozilla.org/en-US/docs/Learn/Forms/HTML5_input_types)

[Event Reference and listings](https://developer.mozilla.org/en-US/docs/Web/Events)
