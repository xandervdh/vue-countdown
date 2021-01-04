# Vue.js Countdown

In this challenge we are going to make a countdown app in Vue.js

## Let's get to it

1. ### Install vue.js
- Install the vue CLI by opening a terminal and entering following command:
```text
sudo npm install -g @vue/cli
```
2. ### Create a new Vue project
- Go to the folder where you want your vue project to be created and use following command in the terminal:
```text
vue create <app name>
```

- Optionally you can install [tailwind CSS](https://tailwindcss.com/) to use for styling by using following command in the root of your project:
```text
vue add tailwind
```
3. ### Start the local server
- In your project root run the following command to start the local server:
```
npm run serve
```
4. ### Create the basics
- Make sure you have a views folder in the src directory, if not create one.
- Create a Home.vue file in the views folder, create the boilerplate by using: vbase and tab (you need the vue.js plugin for this)
- In App.vue delete all styling and replace Helloworld in the components with Home, make sure to import it.
- Show the Home component in the template
- Clear the components folder and create a new file Counter.vue with the boilerplate
- Import Counter.vue in Home.vue and show it in the template

5. ### Coding the counter
- Inside of the counter file put in some default **DATA** in the script
    - days, hours, minutes and seconds are 0 by default
- Now show the values inside of the **template**
- We are going to add some **computed properties** in the script for the seconds, minutes, hours and days
  - the values will be how many milliseconds there are in a second, minute, hour and day
- Let's start with the logic, make a new **method** "showRemaining", in here you will create the logic to make the countdown working
  - If you think it's better to split the method you can do that too
  
6. ### Extras
- Use properties to fill in the end date dynamically
- Show a sentence above the timer that changes on counter end

7. ### Extra extras
- Let the user fill in the end date
- make it look good using tailwind

### Usefull info
- [the vue handbook](https://www.freecodecamp.org/news/the-vue-handbook-a-thorough-introduction-to-vue-js-1e86835d8446/)

![I know vue.js](images/vuejs.jpeg)

[the solution](https://github.com/xandervdh/countdown-vue)
