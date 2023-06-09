# Spongebob-back-end -->(https://github.com/spongebob-back-end/spongebob-back-end)

During my apprenticeship, I had numerous opportunities to build projects that provided me with a profound understanding of how enterprise apps work. One particular project enabled me to learn and implement robust security measures for applications, ensuring that only authorized users are eligible to access the data.

The idea behind our application is to enable full CRUD functionality for Users and Quotes.I was responsible of Authentication and Authorization using: bcryptjs, JWT Each request must include the appropriate token and user credentials for validation. We have implemented authorization functionality, ensuring that specific endpoints can only be accessed by users with the ADMIN role. To achieve this, we utilized node.js and Sequelize. Additionally, we decided to use SpongeBob quotes as the dataset, and we tested the endpoints using the Thunder Clients extension provided by VS Code.

During the process of creating our app, we encountered numerous obstacles. Some of these challenges were related to time constraints and technical issues. For example, there was an issue where users without admin authority were able to access all functionalities. Another problem we faced was working on the main branch, which caused conflicts and hindered progress. However, we overcame these challenges by scheduling additional meetings outside of our regular training time, extensively testing and making multiple changes to resolve the issues, and adopting a practice of not working simultaneously on the same main branch.

# How to run the app:

## 1/First install the following pakages:
npm install , npm install bcrypt,npm install JWT

## 2/Run the command:
npm run server-dev
Nodmon will run because we specified it in the JSON file.

![hgjghj](https://github.com/riadh796/Portfolio/assets/62479005/8df7c133-6008-4031-b0ea-c6e5a7d9d6cb)

## 3/Open Thunder Clients extension provided by VS Code:

First thing you need to register a user as admin (just exemple)

![5555](https://github.com/riadh796/Portfolio/assets/62479005/0d54345e-f98e-4a66-9da9-6d04bd193d42)

Now you can see that you have been successfully registered, and we have obtained a token that allows you to access the quotes.

other way to check using"https://sqliteonline.com/"(pic below)

![Capture](https://github.com/riadh796/Portfolio/assets/62479005/7e45f83c-6291-4c04-9456-b71f58f525bf)

Now, to login, you need to enter username and password. Once we verify that the entered credentials match with a registered user, you will be granted access.

![jhgjk](https://github.com/riadh796/Portfolio/assets/62479005/87d24ac2-a44e-48b3-ba03-cbfc8188d46c)

Finally, we retrieve all the data by using the same username, and we ensure that we use the provided token for authentication.

![Capturecvbcvbvc](https://github.com/riadh796/Portfolio/assets/62479005/5a84f3bb-8a07-4e6b-8e9b-3790918ac82f)

Now, let's try to use an incorrect token (in this example, I deleted the last letter and got)

![fffff](https://github.com/riadh796/Portfolio/assets/62479005/dfbc7def-5234-4fdf-a6e5-181d85f84802)



