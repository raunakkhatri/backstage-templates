# ${{values.app_name}}

Node.js Express application generated from Backstage template.

## Overview

This is a simple Express.js application that provides:
- Basic web server on port 3000
- Health check endpoint at `/health`
- Static file serving

## Environment

- **Environment**: ${{values.app_env}}
- **Runtime**: Node.js 18+
- **Framework**: Express.js

## Development

```bash
npm install
npm run dev
```

## Production

```bash
npm start
```

## Docker

```bash
docker build -t ${{values.app_name}} .
docker run -p 3000:3000 ${{values.app_name}}
```