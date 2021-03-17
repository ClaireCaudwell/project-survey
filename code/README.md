# Build a survey project 📜
For this project we were tasked to build a survey using React and practice using React useState hook.
We had free reign to choose what our survey should be about, but we were asked to fill the basic requirements:
1. The survey should consist of at least 3 questions.
2. At least one question should consist of radio buttons and the select dropdown.
3. There should be a submit button, which when pressed should hide the form and reveal a summary of the data inputted by the user.
4. The site should follow accessibility guidelines. 

## What I achieved 🏵️
1. Used React to create different components and the useState hook to submit data inputted by the user and render components dynamically depending if the state is true or false. 
2. Store data inputted by user using useState and use useState to render components dynamically depending if the state is true or false based on if the user has submitted the specific form or not.
3. Pass data inputted by the user into the different components rendered via props. With all the data inputted sent to the Summary.js component to render all data inputted by the user.
4. Used text input, radio buttons(custom), checkboxes(custom) and dropdown input for different questions.
5. Use onClick event for home button to navigate the user back to the homepage.
6. Use map method to map through array elements and return a new array of the elements for specifc JSX, used for example on the array of craft beer types.
7. Implemented basic accessibility for users who use screen readers and keyboards. This includes using semantic HTML, aria-labels and tab-index. 
8. Used React tooltip library as I was having issues with the required input attribute not showing a message if the user tries to go to the next question before selecting an option from the form. The tooltip gives the user a specific message asking them to take an action. 
9. I also had to use React useRef hook and the JavaScript focus() method to focus on the input. This was because when the user is using the keyboard to navigate using the tab key and enters a new form the "next question" button is focused on. Targeting the JSX for the form using the useRef in combination with the JavaScript focus() method in the useEffect before the component is mounted allows for the form to be the first thing focused.
7. Styled the page and made it responsive for mobile, tablet and desktop.

## What tools 🛠️ I used:
1. NPM package manager.
2. The React starter App that cam included in this project repo.
3. Package.json.
4. JavaScript, React.js, React useState and useRef hook.
5. React tooltip.
5. CSS.
7. Googaling, Technigo videos and lectures.

## View it live 💻: 
https://flamboyant-poitras-c5efb2.netlify.app/

