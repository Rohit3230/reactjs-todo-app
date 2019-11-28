# React Todo App

This is a sample react todo app done step-by-step.
This sample app was a part of react workshop.

You can check the slides [here](https://speakerdeck.com/kabirbaidhya/frontend-development-with-react).

Check the demo hosted on heroku https://simplest-react-todo-app.herokuapp.com/.


## Instructions

First clone this repository.
```bash
$ git clone https://github.com/kabirbaidhya/react-todo-app.git
```

Install dependencies. Make sure you already have [`nodejs`](https://nodejs.org/en/) & [`npm`](https://www.npmjs.com/) installed in your system.
```bash
$ npm install # or yarn
```

Run it
```bash
$ npm start # or yarn start
```

## Steps
Each step is a branch. Check out to the step you want to test.

```bash
$ git checkout <step-number>    # eg: git checkout step-1
```
* [step-0](https://github.com/kabirbaidhya/react-todo-app/commits/step-0) - Setup app using `create-react-app`.
* [step-1](https://github.com/kabirbaidhya/react-todo-app/commits/step-1) - React Hello World.
* [step-2](https://github.com/kabirbaidhya/react-todo-app/commits/step-2) - Add some JSX for the todoapp.
* [step-3](https://github.com/kabirbaidhya/react-todo-app/commits/step-3) - List todo items dynamically.
* [step-4](https://github.com/kabirbaidhya/react-todo-app/commits/step-4) - Create `TodoList` component.
* [step-5](https://github.com/kabirbaidhya/react-todo-app/commits/step-5) - Extract more components: `TodoItem`, & `Header`.
* [step-6](https://github.com/kabirbaidhya/react-todo-app/commits/step-6) - Add `Footer` component to display count.
* [step-7](https://github.com/kabirbaidhya/react-todo-app/commits/step-7) - Add `InputBox` component.
* [step-8](https://github.com/kabirbaidhya/react-todo-app/commits/step-8) - Convert to stateful components.
* [step-9](https://github.com/kabirbaidhya/react-todo-app/commits/step-9) - Add new todo item.
* [step-10](https://github.com/kabirbaidhya/react-todo-app/commits/step-10) - Add todo list filter.
* [step-11](https://github.com/kabirbaidhya/react-todo-app/commits/step-11) - Refactor code by moving logic to services.
* [step-12](https://github.com/kabirbaidhya/react-todo-app/commits/step-12) - Make check/uncheck change the todo item status to completed/pending.
* [step-13](https://github.com/kabirbaidhya/react-todo-app/commits/step-13) - Refactor code and design improvements.
* [step-14](https://github.com/kabirbaidhya/react-todo-app/commits/step-14) - Refactor and separate UI & stateful components.
* [step-15](https://github.com/kabirbaidhya/react-todo-app/commits/step-15) - Finalization of TodoApp.





***************************************************************
Main URL:-
https://github.com/kabirbaidhya/react-todo-app
Demo:-
https://simplest-react-todo-app.herokuapp.com/
***************************************************************


***************************************************************
Steps For Changing Port:-
1. Setting environment variable
2. Modifying package.json
3. Creating .env file

1. On terminal hit commnad :-   export PORT=8000
    We then restart the development server again with “npm start”.
        This approach, however, is less preferred for an environment with several active projects. The environment variable PORT is arguably a generic, non-assuming variable name that can be used by other systems. Remember that by setting an environment variable via an export, that variable will be available for the all processes accessing or spawned by the shell. It will be better to localize the port assignment specific to React as shown in the remaining approaches.

2.  Modify in scripts object change start of package.json.
"scripts": {
    "start": “PORT=8000 react-scripts start",
    "build": "react-scripts build",
    "test": "react-scripts test --env=jsdom",
    "eject": "react-scripts eject"
  }

  3. create and .env file on root level.
    Enter following line:-   PORT=3005
***************************************************************