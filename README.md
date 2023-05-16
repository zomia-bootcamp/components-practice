# components-project

## Objective: 

The objective of this task is to create a simple user interface using React components.

## Instructions:

1. Create a new React project using Create React App or any preferred method.
2. Open the project in your code editor.
3. Inside the `src` folder, locate the existing `App.js` file.
4. Open the `App.js` file and locate the `return` statement inside the `App` component.
5. Modify the existing JSX structure to create a simple user interface.
6. Add a `div` element with the class name `container` to act as the main container for your UI components.
7. Inside the `container` element, add the following elements:
   - An `h1` element with the text "Welcome to My Simple UI"
   - A `p` element with a short description of your UI
   - A custom component called `ButtonComponent`
   - Another custom component called `ImageComponent`
8. Save the changes to `App.js`.
9. Create a new file called `ButtonComponent.js` inside the `src` folder.
10. In `ButtonComponent.js`, define a functional component called `ButtonComponent` that returns a `button` element with the text "Click Me!"
11. Export the `ButtonComponent` as the default export from `ButtonComponent.js`.
12. Create another new file called `ImageComponent.js` inside the `src` folder.
13. In `ImageComponent.js`, define a functional component called `ImageComponent` that returns an `img` element with a source URL pointing to an image of your choice.
14. Export the `ImageComponent` as the default export from `ImageComponent.js`.
15. In `App.js`, import the `ButtonComponent` and `ImageComponent` at the top of the file.
16. Use the imported components within the `return` statement of the `App` component, replacing the previous placeholders for the custom components.
17. Save the changes to `App.js`.
18. In the `src` folder, locate the existing `index.js` file.
19. If you created additional components, import them into `index.js` as needed.
20. Use the `ReactDOM.render()` method to render the `App` component to the root DOM element (e.g., `document.getElementById('root')`).
21. Save the changes to `index.js`.
22. Start the development server to see the rendered UI in your browser.

## Expected Result:
When you run the React development server, you should see your simple user interface rendered in the browser with the following elements:
- An `h1` heading displaying "Welcome to My Simple UI"
- A `p` paragraph with a short description of your UI
- A button labeled "Click Me!" rendered by the `ButtonComponent`
- An image rendered by the `ImageComponent`

## Task Extension:
Once you've completed the task, you can further enhance the UI by adding interactivity or additional components. For example, you can add an event handler to the button component to display an alert message when clicked, or you can create a form component to collect user input. Explore different React features and concepts to make your UI more interactive and engaging.

Remember to consult the official React documentation or other learning resources for guidance and assistance while completing this task. 

Good luck!
