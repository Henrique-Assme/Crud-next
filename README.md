# Crud-next
CRUD using Next.js
#How to run it locally
First you will need to create a project at firebase https://firebase.google.com/?hl=pt.
Then, clone the repository.
```bash
gic clone https://github.com/Henrique-Assme/Crud-next.git
```
Here create a file named .env.local and create those 3 enviroment variables
```bash
NEXT_PUBLIC_FIREBASE_API_KEY=
NEXT_PUBLIC_FIREBASE_AUTH_DOMAIN=
NEXT_PUBLIC_FIREBASE_PROJECT_ID=
```
To get the value for those variables go to "Project Overview" -> "Project settings" and copy this into .env.local

![Firebase](https://github.com/Henrique-Assme/Crud-next/assets/69920692/f9d0fafc-2194-4ec2-b910-84270cc18d07)

Lastly, just run
```bash
npm install
npm run dev
```
