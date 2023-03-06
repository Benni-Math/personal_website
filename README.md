# Ben's Personal Website

My personal website.

Built using
 - [NextJS](https://nextjs.org)
 - [TypeScript](https://www.typescriptlang.org)
 - [Prisma](https://prisma.io)
 - [tRPC](https://trpc.io)
 - [Chakra UI](https://chakra-ui.com)

For deployment, I plan on using:
 - [Terraform](https://www.terraform.io)
 - [NGINX](https://www.nginx.com)
 - [SQLite](https://www.sqlite.org/index.html)
 - [AWS](https://aws.amazon.com) (ECS, Lambda, Route 53, etc.)
 - [Docker](https://www.docker.com)

I've integrated a plethora of developer tools, like
 - [VSCode](https://code.visualstudio.com)
 - [EditorConfig](https://editorconfig.org)
 - [dotenv](https://github.com/motdotla/dotenv)
 - [ESLint](https://eslint.org)
 - [nvm](https://github.com/nvm-sh/nvm)
 - [create-t3-app](https://create.t3.gg/)


## Development Guide

To develop the website locally, make sure to have npm installed,
and then use the following commands to run it:
 1. `npm install`
 1. `npx prisma db push`
 1. `npm run dev`
