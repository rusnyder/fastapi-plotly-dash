# FastAPI + Dash Sample App
Sample application that runs a Dash app mounted inside a FastAPI webserver.

## Quickstart

1. Install dependencies
   ```bash
   uv sync
   ```
2. Run webserver
   ```bash
   uv run fastapi dev
   ```
3. Load up in browser: http://localhost:8000

## Routes

| Route       | Description                      | Link                         |
|-------------|----------------------------------|------------------------------|
| GET /       | Base route (tests shared prefix) | http://localhost:8000/       |
| GET /status | Non-Dash route                   | http://localhost:8000/status |
| GET /dash   | Dash app                         | http://localhost:8000/dash   |
