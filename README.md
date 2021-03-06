# Prisma Boilerplate with Docker & PostgreSQL

## Routes
Add data to your database by running `yarn run prisma studio`
```
Domain:
http://localhost:8080

> GET /users/
```

## Run
```
1. 👉 yarn install

2. 👉 bash start.sh

❗ WAIT, DON'T REQUEST ANYTHING YET ❗

3. 👉 yarn migrate

3. ✔️ READY TO RECEIVE REQUESTS!
```

## Edit
You must first generate the Prisma client library before you can edit this example. 
You can generate the Prisma client by executing the following command:
```
👉 yarn run prisma generate
```

## Prisma Commands
```
# Initialize Prisma in project
1. 👉 yarn run prisma init 

# Push schema to database
2. 👉 yarn migrate

# Alter Prisma data
3. 👉 yarn run prisma studio

# Generate Prisma client library
4. 👉 yarn run prisma generate
```
