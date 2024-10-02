## Starting a json-server project

1. Create a new folder json-server
2. from CLI: npm init -y / yarn init -y
3. npm install json-server / yarn add json-server
4. Create a new folder named db and put inside the db.json file
5. Open package.json and add in scripts section:
  "start": "json-server --watch db/db.json"
6. From CLI exec: npm start / yarn start

