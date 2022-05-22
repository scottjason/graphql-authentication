# Full Stack Boilerplate with JWT Authentication

### Database: Mongo, Mongoose ODM

## Description

Full Stack boilerplate with JWT authentication.

Built with React, Typescript, Node, Express, GraphQL, MongoDB, Mongoose, and Webpack.

Uses custom hooks and code splitting optimization via route-based component lazy loading with the Suspense component.

Unexpired tokens on sign-out are stored in a Mongo collection and checked against on all authentication attempts.

## Deployed App

[Deployed on heroku, open app.](https://ts-auth-graphql-mongodb.herokuapp.com)

## Installation

Clone the repo:

```bash
git clone https://github.com/scottjason/ts-boilerplate-graphql-mongodb.git
```

Then cd into the root directory and run `npm install`

## License

MIT License

Copyright (c) 2022 Scott Jason

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.
