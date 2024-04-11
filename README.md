# APC-PDES-bramirez

Repository that will contain the project for the subject 'Prácticas de Desarrollo de Software'.

## Stack

### Backend

- Nodejs v20.12.1
- Typescript 5.1.3
- Nest Core 10.0

### Frontend

- React 18.2
- Typescript 5.2.2
- Vite 5.2


### Database

- PostgreSQL

## Instructions for app launching

1. Clone this repository with the following command:

```
git clone --recurse-submodules git@github.com:ramirez7358/apc-pdes-bramirez.git
```

2. Go to the backend submodule and install the dependencies with:

```
yarn install
```

3. Clone the file ```.env.template``` and rename it to ```.env```.

4. Change environment variables.

5. Go to the frontend submodule and install the dependencies with:

```
yarn install
```

6. Go to the repository root and execute the command:

```
docker compose up -d
```

This will raise all the services in docker for the app to work.