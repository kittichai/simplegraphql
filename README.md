# Simplegraphql
Simple graphql is running on nodejs. 

Getting Started

```sh
git clone https://github.com/kittichai/simplegraphql
cd simplegraphql
npm install
npm run dev
```
You should be able to see the app running at http://localhost:3000
and able to use graphqltool at http://localhost:3000/graghqlqi


Project information
--------------------
- `index.js` starts the Express server.
- The `models` folder contains the three models: User, Project and Task. They are created using the `sequelize` ORM.
- The `rest` folder contains the logic to create the associated `/api/users`, `/api/projects` and `/api/tasks` endpoints.
- The `graphql` folder contains the schema and resolvers for GraphQL.
- `db.sqlite` contains the database.

--------------------
