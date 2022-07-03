# hackernews

Built as a part of `typescript-apollo Tutorial`

## Overview

GraphQL is a rising star in the domain of API development. It is gaining significant ground over REST as an API design paradigm and is becoming one of the standards for exposing the data and functionality of a web server.

In this tutorial, you’ll learn how to build an idiomatic GraphQL server entirely from scratch. You are going to use the following technologies:
- TypeScript: Strongly typed superset of JavaScript that can be transpiled back to JavaScript. TypeScript has enjoyed significant adoption and love in the developer community for the type-safety and improved developer experience it provides.
- Apollo Server: Fully-featured GraphQL Server with focus on easy setup, performance and great developer experience.
- Nexus: A library for creating robust, type-safe GraphQL schemas using JavaScript/TypeScript.
- Prisma: Next-generation Node.js and TypeScript ORM. You can use Prisma Client to access your database inside of GraphQL resolvers.

## What this tutorial will cover

The goal of this tutorial is to build an API for a Hacker News clone. Here is a quick rundown of what to expect.

You’ll start by learning how a GraphQL server works. Then you will define the GraphQL schema for your server using Nexus and write the corresponding resolver functions. In the beginning, these resolvers will only work with data that’s stored in-memory — so nothing will persist beyond the runtime of the server.

Nobody wants a server that’s not able to store and persist data, right? Not to worry! Afterwards, you’re going to add a SQLite database to the project which will be managed with Prisma.

Once you have the database connected, you are going to add more advanced features to the API.

You’ll start by implementing signup/login functionality that enables users to authenticate against the API. This will also allow you to check the permissions of your users for certain API operations.

Then, you’re going to add a vote feature.

Afterwards, you’re going to learn about custom GraphQL scalars and how to add custom scalars to your application.

Then, you’ll allow the consumers of the API to constrain the list of items they retrieve from the API by adding sorting, filtering and pagination capabalities to it.

Finally you will learn how to create a automatic deployment pipeline for the API to a cloud provider (Heroku) using GitHub Actions.

Throughout the tutorial you will learn GraphQL bit by bit, through theory, writing code and reading external resources. You’ll learn not just the how of various technology choices, but also the why, including their pros, cons and tradeoffs. 
