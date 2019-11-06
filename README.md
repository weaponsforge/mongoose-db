## mongodb-testing

> Experiments and tests using mongodb and mongoose.



### Prerequisites

1. **MongoDB**  
MongoDB Community Server v4.2.0, OS Windows x64 x64 was used for this project
2. **NodeJS**  
v10.16.3 was used for this project
3. **Nodemon** (Optional)  
Install this utility globally if you want to monitor server updates without restarting the server:  
`npm install -g nodemon`



## Usage

1. Create and start a local mongodb server from a local directory.  
   - Set the MongoDB data path only once  
      `mongod --dbpath="<PATH_TO_LOCAL_DIR>"`  
   - (or set to mongodb's default data directory)  
      `mongod --dbpath=`

2. Clone this repository  
`git clone https://github.com/ciatph/mongodb-testing.git`

3. Install dependencies.  
`npm install`

4. Run the web server.  
   - Normal command: `npm run start`
   - If **nodemon** is installed (for debugging):  
      `npm run dev:server`

20190106