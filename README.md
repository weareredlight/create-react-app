React App Boilerplate
===========
Redlight Software

<br />

## What

This is a fork of create-react-app.

It includes a number of tools in rls-react-scripts ready to use. From this branch we create a React-Redux and a React-Redux-GraphQL boilerplates branches.

<br />

## How

<br/>

### install dependencies (package.json)

```npm install -g create-react-app``` or ```yarn global add create-react-app```

```create-react-app test-app --scripts-version rls-react-scripts```

### run

```npm start``` or ```yarn start```

### test

```npm test``` or ```yarn test```

<br />

## Tools

<br/>

### eslint

A react-script lint command was added and you can run it with:

```npm run lint``` or ```yarn lint```


<br />

### dotenv

You can add keys to the ".env" file, and the name should follow this pattern:

REACT\_APP_[key]=[value]

<br />

### SASS

This boilerplate already includes a sass loader

<br/>

### CSS Modules

This project uses CSS Modules.

> What are CSS Modules?
>
> According to the repo, CSS modules are:
>
> CSS files in which all class names and animation names are scoped locally by default.

You can read more about CSS Modules here -> [Part 1](https://css-tricks.com/css-modules-part-1-need/), [Part 2](https://css-tricks.com/css-modules-part-2-getting-started/) and [Part 3](https://css-tricks.com/css-modules-part-3-react/).

<br />

### CI

There's a Wercker pre-configured to automatically test your code using eslint and jest. Don't forget to setup Wercker on your repo and account.

---

This project was bootstrapped with [Create React App](https://github.com/facebookincubator/create-react-app).
