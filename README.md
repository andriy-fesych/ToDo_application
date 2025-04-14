This is an example of a ToDo application.
It`s purpose is to create and store a list of user's tasks.

[Live preview (DEMO LINK)](https://andriy-fesych.github.io/ToDo_application/)

📌 Key technologies and frameworks used in the project:<br/>
⭐ HTML<br/>
⭐ CSS<br/>
⭐ SCSS<br/>
🌐 React<br/>
🌐 TypeScript<br/>

Follow these steps to set up this project locally:<br/>
1. Clone the repo<br/>
git clone https://github.com/andriy-fesych/ToDo_application.git<br/>
2. This project was build on node version 14.21.3, but running completely fine on v20<br/>
If You are using node version 20+, skip step 3. Otherwise, to easily switch between node versions I recommend using NVM:<br/>
[Node Version Manager install guide](https://www.freecodecamp.org/news/node-version-manager-nvm-install-guide/)<br/>
Using this guide ☝️ choose NVM v1.1.12 [from here](https://github.com/coreybutler/nvm-windows/releases/tag/1.1.12), as it is more stable<br/>
3. Now to use correct node version:<br/>
nvm install 20.19.0<br/>
nvm use 20.19.0<br/>
4. Install dependencies:<br/>
npm install<br/>
or<br/>
yarn install<br/>
5. Run the project locally:<br/>
npm start<br/>
or<br/>
yarn start<br/>
6. Congratulations! You are now set! 😊<br/>


Features:<br/>
🔥 Routing made with React Router<br/>
💾 Two ways to store ToDos<br/>
&emsp;&emsp;⭐ Local Todos stored in local storage, on the machine you are using.<br/>
&emsp;&emsp;🌐 Cloud Todos stored on the server, and accessible from any device, if you remember your email (serves as a unique identifier).<br/>
⚡ Registration Form available for new users:<br/>
&emsp;&emsp;📀 if You are a registered user, just press login in the top right, and enter your email;<br/>
&emsp;&emsp;💿 if You are not registered, just type in your email, and press Enter - a registration form will appear, for You to create an account;<br/>
🗃️ You can filter todos based on their completion status.<br/>
🧽 You may also wipe completed todos from the list ("Clear completed" button).<br/>
