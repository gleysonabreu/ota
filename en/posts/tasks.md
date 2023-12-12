![img](https://raw.githubusercontent.com/gleysonabreu/ota/main/imgs/tasks.png)

### About the project

Tasks is an application built to store and organize your day-to-day tasks. With it, you can create and remove task groups, add and remove individual tasks, mark tasks as completed or not, make your profile public to share with others, among other functionalities.

This application was divided into two parts:

In the first part, the construction was carried out using Next, where all the design, pages, and connections to an external API were developed. Additionally, NextAuth was used to handle all user authentication communication.

In the second part, the external API was developed using Nest as the framework. We utilized Prisma ORM for the database connection and to execute queries. Most of the code was tested using Jest. In building the API, SOLID principles and some aspects of clean architecture were applied.

[Tasks backend](https://github.com/gleysonabreu/to-do)

In the end, this application provided me with a lot of learning experiences.

### Technologies

- Typescript
- Next.js
- Tailwindcss
- Nest
- NextAuth
- Shadcn/ui
