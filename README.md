# Marketplace product catalog

A seller admin built for a CommentSold-style assessment: log in, manage products, track inventory and view orders.

## `commonSold-backend`

Node.js + Express REST API on MySQL (Sequelize) with JWT authentication. Modules: authentication, products, inventories, orders.

```bash
cd commonSold-backend
cp .env.example .env   # database and JWT settings
npm install
node app.js
```

## `commentSold-frontend`

React with Material UI, Formik + Joi validation, react-data-table-component, and tests with Testing Library.

```bash
cd commentSold-frontend
npm install
npm start
```
