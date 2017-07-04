# Meteor Todo

## Env

- meteor v1.5

## Deploy

```
# Install dependencies
meteor npm install

# Running the app
meteor

# Database shell
meteor mongo
> db.tasks.insert({ text: "Hello world!", createdAt: new Date() });

# Testing Server
meteor test --driver-package practicalmeteor:mocha
```