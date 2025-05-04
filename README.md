# local-db

## Overview

This repository contains a lightweight local database solution designed for quick prototyping and development purposes. It provides an easy-to-use interface for storing and retrieving data without the need for a full-fledged database server.

## Features

- Simple setup and usage
- Lightweight and fast
- No external dependencies
- Ideal for local development and testing

## Installation

Clone the repository:

```bash
git clone https://github.com/your-username/local-db.git
cd local-db
```

## Usage

1. Create `.env` file with at least (add your own variables from the docker postgres image):

```env
- POSTGRES_PASSWORD
- POSTGRES_USER
- POSTGRES_DB
```

2. Start the database server:

```bash
docker-compose up -d
```

3. Access the database using your preferred client or through the provided API.
4. To stop the server, run:

```bash
docker-compose down
```
