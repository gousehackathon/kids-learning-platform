# Kids Learning Platform

A monorepo for the Kids Learning Platform.

## Structure

- `frontend/`: Angular application (initialization pending).
- `backend/`: FastAPI service, organized by API version and domain module.
- `docs/`: Architecture notes and architecture decision records.

## Backend

Create a virtual environment, install dependencies from `backend/requirements.txt`, then run the API from the repository root:

```sh
python -m venv .venv
. .venv/bin/activate
pip install -r backend/requirements.txt
uvicorn app.main:app --app-dir backend --reload
```

The health check is available at `/health`.
