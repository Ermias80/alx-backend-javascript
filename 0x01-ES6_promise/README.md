 0x01. ES6 Promises
**JavaScript ES6**
![](https://s3.amazonaws.com/alx-intranet.hbtn.io/uploads/medias/2019/12/75862d67ca51a042003c.jpeg)
## Resources
**Read or watch:**

* [PROMISE](https://intranet.alxswe.com/rltoken/j_0FTFbkTg42JMcAbNPOVQ "PROMISE")
* [Javascript Promise: An introduction](https://intranet.alxswe.com/rltoken/2Q2LzNFokcUwpA2u3FKG6Q "Javascript Promise: An introduction")
* [Await](https://intranet.alxswe.com/rltoken/UXb3S2PMBe-SLJ55isMcow "Await")
* [Async](https://intranet.alxswe.com/rltoken/_K0C7pgEjwaIzU9RpwCb8g "Async")
* [Throw/Try](https://intranet.alxswe.com/rltoken/UTjDgvKk5l892Xslh0vqcQ "Throw/Try")
### Learning Objectives
At the end of this project, you are expected to be able to explain to anyone, without the help of Google:
* Promises (how, why, and what)
* How to use the then, resolve, catch methods
* How to use every method of the Promise object
* Throw / Try
* The await operator
* How to use an async function
## Requirements
**General**
* All your files will be executed on `Ubuntu 18.04 LTS` using `NodeJS 12.11.x`
* Allowed editors: `vi, vim, emacs, Visual Studio Code`
* All your files should end with a new line
* A README.md file, at the root of the folder of the project, is mandatory
* Your code should use the `js` extension
* Your code will be tested using Jest and the command `npm run test`
* Your code will be verified against lint using ESLint
* All of your functions must be exported
## Setup
### Install NodeJS 12.11.x
(in your home directory):
```
curl -sL https://deb.nodesource.com/setup_12.x -o nodesource_setup.sh
sudo bash nodesource_setup.sh
sudo apt install nodejs -y
```
```
$ nodejs -v
v12.11.1
$ npm -v
6.11.3
```
### Install Jest, Babel, and ESLint
In your project directory, install Jest, Babel and ESList by using the supplied `package.json` and run `npm install`.
## Configuration files
Add the files below to your project directory
`package.json`
Click here to show/hide file contents
`babel.config.js`
Click here to show/hide file contents
`utils.js`
Use when you get to tasks requiring uploadPhoto and createUser.
Click to show/hide file contents
`.eslintrc.js`
Click here to show/hide file contents
**and…**
Don’t forget to run `npm install` from the terminal of your project folder to install all necessary project dependencies.
## Response Data Format
`uploadPhoto` returns a response with the format
```
{
  status: 200,
  body: 'photo-profile-1',
}
```
createUser returns a response with the format
```
{
  firstName: 'Guillaume',
  lastName: 'Salva',
}
```
