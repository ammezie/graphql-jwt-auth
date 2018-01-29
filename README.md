# graphql-jwt-auth

 Adding authentication with JWT to a GraphQL server

## Getting Started

Clone the project repository by running the command below if you use SSH

```bash
git clone git@github.com:ammezie/graphql-jwt-auth.git
```

If you use https, use this instead

```bash
git clone https://github.com/ammezie/graphql-jwt-auth.git
```

After cloning, run:

```bash
npm install
```

Rename `.env.example` to `.env` then fill in your database detail and your JWT secret:

```txt
NODE_ENV=development
DB_HOST=localhost
DB_USERNAME=root
DB_PASSWORD=
DB_NAME=graphql_jwt_auth
JWT_SECRET=
```

Then run the migration:

```bash
sequelize db:migrate
```

And finally, start the application:

```bash
npm start
```

The server will be running on [http://localhost:3000/api](http://localhost:3000/api).
