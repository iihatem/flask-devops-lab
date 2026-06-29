# Flask DevOps Lab

A small Flask diagnostic app used to practice Git, GitHub, and Docker workflows.

## Usage

```bash
source .venv/bin/activate
pip install -r requirements.txt
python app.py
```

The app exposes the following diagnostic endpoints:

- `/api/health` — returns `{"status": "ok"}` for liveness checks.
- `/api/config` — returns the contents of `config.json` (app name, version, targets).
- `/api/report` — returns the hostname, Python version, and uptime in seconds.
