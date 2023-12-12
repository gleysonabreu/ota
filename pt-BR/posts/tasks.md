![img](https://raw.githubusercontent.com/gleysonabreu/ota/main/imgs/tasks.png)

### Sobre o projeto

Tasks é uma aplicação construída para armazenar e organizar suas tarefas do dia a dia. Com ela, você pode criar e remover grupos de tarefas, adicionar e remover tarefas individuais, marcar tarefas como concluídas ou não, tornar seu perfil público para compartilhar com outras pessoas, entre outras funcionalidades.

Este aplicativo foi dividido em duas partes:

Na primeira parte, foi realizada a construção através do Next, onde todo o design, as páginas e as conexões com uma API externa foram desenvolvidos. Além disso, utilizamos o NextAuth para lidar com toda a comunicação de autenticação do usuário.

Na segunda parte, foi desenvolvida a API externa utilizando o Nest como framework. Utilizamos o Prisma ORM para a conexão com o banco de dados e para realizar as queries. A maior parte do código foi testada utilizando o Jest. Na construção da API, foram aplicados os princípios do SOLID e um pouco da arquitetura limpa (clean architecture).

[Tasks backend](https://github.com/gleysonabreu/to-do)

Ao final, este aplicativo me proporcionou muitos aprendizados.

### Tecnologias

- Typescript
- Next.js
- Tailwindcss
- Nest
- NextAuth
- Shadcn/ui
