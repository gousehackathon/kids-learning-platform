# Architecture

The repository is split into an Angular frontend and a Python FastAPI backend. The backend exposes versioned HTTP APIs under `app/api/v1/` and groups domain behavior under `app/modules/`.

The initial backend entry point is `backend/app/main.py`. Persistence, identity, authorization, curriculum, learning, progress, and rewards are reserved as separate areas so they can evolve independently.
