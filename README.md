# Getting Started with Laravel on Deckrun

This is an example of a Laravel application that uses Deckrun to build and deploy it.

## Prerequisites

- Deckrun CLI installed and set up
- Docker installed
- A Cluster created on Deckrun

## Deploy the Application

### 1. Clone this repository

```bash
git clone git@github.com:deckrun/laravel-getting-started.git
```

### 2. Change into the project directory

```bash
cd laravel-getting-started
```

### 3. Create a New App on Deckrun

```bash
deck init
```

### 4. Create and Link a MySQL Database

```bash
deck service create
```

### 5. Deploy the application

```bash
deck deploy
```

### 6. Open the application in your browser

Use the URL provided in the output of the `deck deploy` command.
