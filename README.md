# DriveX – Distributed File Storage System

DriveX is a scalable distributed file storage platform inspired by Google Drive and Dropbox.

## Features

- Distributed File Storage
- Chunk-Based Storage
- Replication
- Redis Caching
- JWT Authentication
- File Sharing
- FastAPI Backend

## Architecture

```text
Client
 ↓
FastAPI
 ↓
Authentication Service
 ↓
Storage Service
 ↓
Chunk Service
 ↓
Replication Service
 ↓
PostgreSQL + Redis
```

## Tech Stack

- Python
- FastAPI
- PostgreSQL
- Redis
- Docker
- JWT
