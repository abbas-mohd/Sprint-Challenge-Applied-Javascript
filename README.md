

## Self-Study Questions

1-What is the DOM? The DOM stands for Document Object Model and it is basically an object representation of the html elements on a given webpage. It's an interface that allows us to manipulate data, change styling, and interact with a webpage. Each element in a DOM is a tree node which is similar in structure to the tree structure of objects.

2-What is an event? An event or event object is made every time a user interacts with the webpage in some way - mousover, click, etc. The event object then carries info about the event so it can be handled by anything that is upstream of that given point in the DOM tree.

3-What is an event listener? An event listener is when an element can listen for an event, and when the event happens on that element, it can do something about that given event that occurs - kind of like a reaction to a trigger (the event).

4-Why would we convert a NodeList into an Array? Converting a NodeList into an Array is done primarily for accessibility purposes. When the information is in the NodeList format, it cannot all be as easily accessed as it can be when in an Array format. When we are trying to use components, callbacks, etc. and dynamic styling, being able to access each of the elements easily is incredibly important. Arrays also have methods which are not possible to use with NodeList (i.e. you can map over an array while you cannot map over a NodeList).

5-What is a component? A component is a piece of code that can be reused and can be used to build elemnts which share functionality/styling and are often used when working with dynamic JS/web applications/frameworks.

