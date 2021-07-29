# JsWorkspace

This is the javascript workspace to share the code for 1107 PR review. 

```javascript
let frontEndQuestion = [...questions];
```
***
## let getStarted = frontEndQuestion[0]

[How to write a .md document (in Chinese)](https://sspai.com/post/45816)

[How to write a .md document (英文版)](hhttps://www.w3schools.io/file/markdown-introduction/)

question format can be like blow:

```markdown
0. ### Who are the members of 1107 ?

    <details>
    <summary>Answer</summary>

    Jason, Poli, Travis

</details>

 **[⬆ Back to Top](#table-of-contents)**
```


***
## let day1 = frontEndQuestion[1]

1. ### What is spread syntax and what is rest syntax (parameters) ?

    <details>
    <summary>Answer</summary>

    [Spread syntax](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Operators/Spread_syntax) (...) allows an iterable such as an array expression or string to be expanded in places where zero or more arguments (for function calls) or elements (for array literals) are expected, or an object expression to be expanded in places where zero or more key-value pairs (for object literals) are expected.

    [Rest syntax](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Functions/rest_parameters) looks exactly like spread syntax. In a way, rest syntax is the opposite of spread syntax.The rest parameter syntax allows a function to accept an indefinite number of arguments as an array

</details>

 **[⬆ Back to Top](#table-of-contents)**


2. ### What is Flux and how it different from Redux?

    <details>
    <summary>Answer</summary>

    The Flux architecture is based on the following components:

    + Store/ Stores: Serves as a container for the app   state & logic
    + Action: Enables data passing to the dispatcher
    + View: Same as the view in MVC architecture, but in the context of React components
    + Dispatcher – Coordinates actions & updates to stores
    

    ![png1](https://www.clariontech.com/hs-fs/hubfs/Image2-61.png?width=770&name=Image2-61.png)

    In the Flux architecture, when a user clicks on something, the view creates actions. Action can create new data and send it to the dispatcher. The dispatcher then dispatches the action result to the appropriate store. The store updates the state based on the result and sends an update to the view.
    
    </br>

    Redux is a library, which implements the idea of Flux but in quite a different way. Redux architecture introduces new components like:

    + Reducer: Logic that decides how your data changes exist in pure functions
    + Centralized store: Holds a state object that denotes the state of the entire app

    ![png2](https://www.clariontech.com/hs-fs/hubfs/Image3-43.png?width=626&name=Image3-43.png)

    In Redux architecture, application event is denoted as an Action, which is dispatched to the reducer, the pure function. Then reducer updates the centralized store with new data based on the kind of action it receives. Store creates a new state and sends an update to view. At that time, the view was recreated to reflect the update.

</details>

 **[⬆ Back to Top](#table-of-contents)**




