# E-commerce-backend

## Description

This backend app was created using the skills I've obtained throughout my journey of learning backend development. This project came with starter code, the only thing I modified were the routes, models and server.js files, so that the application would run nice and smoothly. The hardest part of this project was a goal I could not obtain. I tried to make all the post/get/delete/put routes using only async functions, however the product routes for this proved difficult, since the code needed to update all categories within that product tag and tag. I ended up having to move on from that portion due to time, and left it as a promise functions. It was interesting learning about one to many and how you can connect different models through this method. I hope to come back to this project in the future, with more knowledge and skills, so that I may fix the mistakes I've left behind.

## Usage 

https://drive.google.com/file/d/1z4xI5X-o-xn78PqBcZSR7HZqgw3PFLf9/view

This application has no front end, so it must be run in insomnia or post man. The above link provides a mock up of how it would run in insomnia. Simply open the package.json in the integrated terminal, run "npm i" to install all packages. After, run "mysql -u root -p" to initialize mysql, log in and run "SOURCE db/schema.sql;" to import the database, then run "quit" to exit mysql. Finally, run "node seeds/index.js" and after the seeds have been executed, run "node server.js". Open the local host on either insomnia/postman to see the magic happen! All routes should lead you to your desired option for each category, tag and product. Thank you for taking the time to review my code!

## License

MIT License

Copyright (c) [2023] [ValerieRojas]

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.