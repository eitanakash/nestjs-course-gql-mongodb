
## Description

[Nest](https://github.com/nestjs/nest) framework TypeScript starter repository.

## Installation

```bash
$ npm install
```

## Running the app
1. npm run start:dev
2. go to localhost:port/graphql
use:

- mutation {
  createLesson(
    createLessonInput: {
      name: "typeScript"
      startDate: "2020-10-05T14:00:00.000Z"
      endDate: "2021-10-05T14:00:00.000Z"
      students:[
        "9a8f61c9-1973-4e91-80f8-1ced8d69238a",
        "9fbdb198-df50-4e0a-b26b-c67bde532456"
      ]
    }) {
    name
  }
}

- mutation {
  createStudent (
    createStudentInput: {
      firstName: "dan",
      lastName: "ba"
    }
  ) {
    firstName
    lastName
    id
  }
}



## Test

```bash
# unit tests
$ npm run test

# e2e tests
$ npm run test:e2e

# test coverage
$ npm run test:cov
```

## Support

Nest is an MIT-licensed open source project. It can grow thanks to the sponsors and support by the amazing backers. If you'd like to join them, please [read more here](https://docs.nestjs.com/support).

## Stay in touch

- Author - [Kamil Myśliwiec](https://kamilmysliwiec.com)
- Website - [https://nestjs.com](https://nestjs.com/)
- Twitter - [@nestframework](https://twitter.com/nestframework)

## License

  Nest is [MIT licensed](LICENSE).
