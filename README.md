# Eat-Da-Burger

## Description
Eat-Da-Burger is a restaurant app that lets users input the names of burgers they'd like to eat (with MySQL, Node, Express, Handlebars and a homemade ORM).  
* Whenever a user submits a burger's name, your app will display the burger on the left side of the page -- waiting to be devoured.
* Each burger in the waiting area also has a Devour it! button.  When the user clicks it, the burger will move the right side of the page.
* The app will store every burger in a database, whether devoured or not.

## Requirements
### Prerequistes
* Node.js
* MySQL Workbench
* NPM Packages:
    * Express
    * Express-handlers
    * Body-Parser
    * MySQL
    * dotenv

### Other applications used
* Visual Studio Code
* Git Bash
* Chrome

### Directory Structure
All the recommended files and directories from the steps above should look like the following structure:

<!-- ![image] () -->
![Directory Structure](./public/assets/img/Directory_Structure-half.jpg)

## Installations
### Setup
#### App Setup
1. Fork a copy to your GitHub repo and clone it to your computer.

1. Get to your Git Bash and get into the folder EatDaBurger.

1. To get all the npm packages required to run this app - type into the command line `npm install`

1. Create a server.js file.

#### Database Setup
1. On your computer, open MySQL Workbench and login to a local server you have to set up.

1. Open a new SQL tab for executing queries.

1. Then go back to your chosen Visual Studio Code (or a text editor of your choosing) and open your `EatDaBurger` folder.

1. Inside the `EatDaBurger` folder you will find a folder called `db`.

1. In the `db` folder, open the file called `schema.sql`.  Copy the code in the file and paste it to the new SQL tab you opened in MySQL Workbench.

1. Go back to the `db` folder in your Visual Code Studio (or a text editor of your choosing) and open the `seeds.sql` file and copy the code and paste it into the open tab in MySQL Workbench and execute the code.

#### .env file Setup
1. In the command line of the main folder of `EatDaBurger` type `touch.env`.

1. In your Visual Studio code (or a text editor of your choosing), open the `.env` file and type `MYSQL_PASSWORD = "enter your MySQL password"`

#### Open the app in browser
1. In the Git Bash go into main folder of `EatDaBurger`.

1. Type `node server.js` and hit enter.

1. Go to your browser and open a new tab and type `localhost:3000` then hit enter.

### Using the app
<!-- ![image] () -->
**Eat-Da-Burger Option**
<!-- [Watch the video for Eat-Da-Burger demo - Option] -->

**Order a burger**
<!-- [Watch the video for Eat-Da-Burger demo - Order] -->

**Reordering a burger**
<!-- [Watch the video for Eat-Da-Burger demo - Reodering] -->

## Deployment
This application is deployed at [https://frozen-anchorage-69675.herokuapp.com/](https://frozen-anchorage-69675.herokuapp.com/)

## Contributing 
Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change.

Please make sure to update tests as appropriate.

## Authors
### Meta
Paoge Moua - primary author
* Contact info: paoge.moua@gmail.com OR pobzeb.m@gmail.com
* Portfolio address: https://paogemoua.github.io/
* GitHub: https://github.com/paogemoua

## Reference
* [Bob's Burgers - Burger of the Day]

## Project Status
12.31.18 Project open - in progress
1.7.19 Initial files commited to GitHub - fail attempt
1.8.19 Attempt to commit new files - in progress

<!-- Linked -->
[MIT]: https://choosealicense.com/licenses/mit/
[Node.js]: https://nodejs.org/en/
[MySQL Workbench]: https://www.mysql.com/products/workbench/
[Express]: https://www.npmjs.com/package/express
[Express-handlers]: https://www.npmjs.com/package/express-handlebars
[Body-Parser]: https://www.npmjs.com/package/body-parser
[MySQL]: https://www.npmjs.com/package/mysql
[dotenv]: https://www.npmjs.com/package/dotenv
[Visual Studio Code]: https://code.visualstudio.com/download
[Git Bash]: https://git-scm.com/downloads
[Chrome]: https://www.google.com/chrome/
<!-- [Watch the video for Eat-Da-Burger demo - Option]: 
[Watch the video for Eat-Da-Burger demo - Order]: 
[Watch the video for Eat-Da-Burger demo - Reodering]: -->
[Bob's Burgers - Burger of the Day]: http://bobs-burgers.wikia.com/wiki/Burger_of_the_Day