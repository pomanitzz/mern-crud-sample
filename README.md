Simple MERN (Mongo, Express, React, Node) project with CRUD operations.

## How to run:

1. Clone project
2. From root folder 'mern-crud-sample' run: ```npm i```

     It will install all needed dependencies for ui-app (react-dependencies)
3. cd backend/
4. From a folder 'backend' run: ```npm i```

     It will install all needed dependencies for backend-app (nodejs-dependencies)
     
5. Go to file ../backend/.env and set property ATLAS_URI
Need to set value for connection to MongoDB.

    https://www.mongodb.com/

    Sing up, create a cluster etc. 
    Finally, you should have something like this: ```
                                                  ATLAS_URI=mongodb+srv://<db-username>:<db-password>@<cluster-name>.gcp.mongodb.net
                                                  ```

6. Run this command in terminal from 'backend' folder: ```nodemon sever```
7. Run this command in terminal from root 'mern-crud-sample' folder: ```npm start```
8. Open in a browser: http://localhost:3000 (port 3000 - by default), and you will see UI-part of application.
Backend part of application started on port 5000 by default.


