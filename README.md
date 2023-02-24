# ORM-ECom-Backend

## Table of Contents

- [Description](#description)
- [Usage](#usage)
- [Credits](#credits)
- [License](#license)

## Description
This application simulates the backend of an e-commerce type store using MySQL, Node, Express, and Sequelize packages. It also uses Insomnia to test routes.

## Usage
Clone the repository from github here --> https://github.com/Sephadeus/ORM-ECom-Backend

Then, navigate to the project directory and install dependencies:
```
npm install
```

Next, connect to MySQL using:
```
mysql -u root -p
```

Then run:
```
source db/schema.sql
```

Then:
```
exit
```

Once you're back in the project directory, seed the database:
```
npm run seed
```

Then: 
```
npm run start
```

Copy the URL from the command line and paste it into Insomnia.
Here is a video demonstrating the functionality of the application:
https://user-images.githubusercontent.com/90430093/221305056-f38cc4f7-1236-4a4d-9280-70dd157582d5.mp4

## Credits
The majority of code including the POST and PUT routes in api/product-routes was written by @Xandromus (Xander Rapstine) and @Dependabot, while the GET all, GET one and DELETE routes in the same file were contributed by Sephadeus (JP Labadia) along with the GET all, GET one, POST, PUT, and DELETE routes in the other api/*-route files.

## License
This project has no license and was completed for educational purposes.
