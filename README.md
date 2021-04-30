# kncp (K Node Create Project)

By using this command you can easily create a node project without writing any code and with some dependencies installed.
So you don't need to write any boilerplate code and then making directories and files for your project.
<b> kncp</b> will take care of everything.

## Prerequisite

-> Node must be installed.

## Installation

Use the package manager [npm](https://www.npmjs.com/) to install kncp globally.

```bash
npm install kncp -g
```

| INFO: Install this package globally so that you can make node projects in future also without installing kncp again and again. |
| ------------------------------------------------------------------------------------------------------------------------------ |

## Which files with code will be included in your project ?

-> Database config file<br>
-> User Model file<br>
-> User controller file<br>
-> User routes <br>
-> Database Error handler file<br>
-> Middlerware authentication file<br>
-> Main server file<br>

## Which dependencies will be installed in your project ?

#### Dependencies:

1. bcryptjs<br>
2. express<br>
3. express-validator<br>
4. jsonwebtoken <br>
5. lodash<br>
6. mongoose<br>

#### DevDependencies:

1. concurrently<br>
2. nodemon<br>

## Usage

```bash
kncp [Project_Name]
```

### Example

```bash
kncp books_api
```

## Output

-> The following directories and files will be created with some predefined code.

<img src="https://user-images.githubusercontent.com/64951569/116698483-11b96d80-a9e2-11eb-9954-a58774285be5.png"></img>

## How to run the project ?

1. Replace YOUR_MONGODB_URI with your mongoDB url in ./config/db.js file.
2. On your shell write

```bash
npm run server
```

3. 😊 Enjoy...

## License

[MIT](https://github.com/Akshit-Zatakia/kncp/blob/main/LICENSE)
