link to AI:

https://chat.openai.com/c/14426d70-9262-425d-95e0-ff40af8c4e99

link to folder

/c/Users/glads/Downloads/Access-a-Components-props/access-props


link to cocademy

https://www.codecademy.com/courses/react-101/lessons/this-props/exercises/access-props


### PROPS

**Access a Component's props**

Every component has something called props.

A component’s props is an object. It holds information about that component.

You’ve seen this before, but you might not have realized it! Let’s take a look at the HTML button tag. There are several pieces of information we can pass to the button tag, such as the type of the button.
```
<button type="submit" value="Submit"> Submit </button> 
```
In this example, we’ve passed two pieces of information to the button tag, a type and a value. Depending on what type attribute we give to the <button> element, it will treat the form differently. In the same way, we can pass information to our own components to specify how they behave!

Props serve the same purpose for components as arguments do for functions.

To access a component’s props object, you can reference the props object and the dot notation for its properties. Here’s an example:
```
props.name
```
This would retrieve the name property from the props object.

