# nestjs app on fly.dev
`yarn run start:dev` runs on `http://localhost:3000/`

`flyctl deploy` deploys to `https://wild-sunset-3697.fly.dev/`
## A Fly Example

This is a simple application used in the [fly.io Getting Started](https://fly.io/docs/getting-started/node/)  documentation showing how to deploy a Node application using Flyctl's builtin Nodejs deployment option.

* Run flyctl init
* When prompted for a builder, select builtin Nodejs.
* Run flyctl deploy



On M1 mac - had to turn off docker on my machine so that fly wouldn't try to build image on my machine

[this example repo helped](https://github.com/fly-apps/fly-nestjs)