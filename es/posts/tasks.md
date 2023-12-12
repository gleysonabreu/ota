![img](https://raw.githubusercontent.com/gleysonabreu/ota/main/imgs/tasks.png)

### Sobre el proyecto

Tasks es una aplicación creada para almacenar y organizar tus tareas diarias. Con ella, puedes crear y eliminar grupos de tareas, añadir y quitar tareas individuales, marcar tareas como completadas o no, hacer público tu perfil para compartirlo con otras personas, entre otras funcionalidades.

Esta aplicación se dividió en dos partes:

En la primera parte, se llevó a cabo la construcción a través de Next, donde se desarrolló todo el diseño, las páginas y las conexiones con una API externa. Además, se utilizó NextAuth para manejar toda la comunicación de autenticación del usuario.

En la segunda parte, se desarrolló la API externa utilizando Nest como framework. Se empleó Prisma ORM para la conexión con la base de datos y para realizar las consultas. La mayor parte del código fue probada utilizando Jest. En la construcción de la API, se aplicaron los principios de SOLID y un poco de arquitectura limpia (clean architecture).

[Tasks backend](https://github.com/gleysonabreu/to-do)

Al final, esta aplicación me brindó muchas experiencias de aprendizaje.

### Tecnologías

- Typescript
- Next.js
- Tailwindcss
- Nest
- NextAuth
- Shadcn/ui
