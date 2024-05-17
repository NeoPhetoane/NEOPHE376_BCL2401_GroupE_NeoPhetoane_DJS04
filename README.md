# DJS04 Project Brief: Book Connect - Web components

**Overview**

The code includes a Web Component called BookPreview that represents a book preview element. This component is created using the HTMLElement class and contains HTML structure and styles of its own.

To create the book-preview component, I followed these steps:

.Defined the component's observed attributes using the observedAttributes static getter.
.Created a constructor function to initialize the component's shadow root.
.Implemented the connectedCallback method to render the component's HTML structure when it's connected to the DOM.
.Implemented the attributeChangedCallback method to update the component's HTML structure when its attributes change.
.Defined the component's HTML structure and styles using a template literal.
.Registered the component using the customElements.define method.

**Challenges Faced**

One of the challenges I faced was ensuring that the component's styles were properly scoped to the component's shadow root. To overcome this, I used the :host pseudo-class to target the component's host element and apply styles to it.

Another challenge was ensuring that the component's attributes were properly updated when they changed. To overcome this, I used the attributeChangedCallback method to update the component's HTML structure when its attributes changed.


**Advantages and Disadvantages of Web Components**

**Advantages**

Encapsulation: Web Components provide a way to encapsulate HTML, CSS, and JavaScript into a single, reusable unit. This helps to keep code organized.
Reusability: Web Components can be easily reused across different projects and web applications, reducing development time and effort.
Improved performance: Web Components can improve performance by reducing the amount of DOM manipulation required to build complex user interfaces.

**Disadvantages**
Browser compatibility: Web Components are sometimes not fully supported in all browsers.
Complexity: Web Components can introduce additional complexity to a project regarding the HTML, CSS and JavaScript being in the same place instead of neatly different files.
