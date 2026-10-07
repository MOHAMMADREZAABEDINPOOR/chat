<div align="center">

<img src="assets/readme/hero.gif" width="1200" alt="PIMX CHAT · DJANGO — rotating 3D geometry" />

**[English](README.md) · [فارسی](README.fa.md)**

<img src="assets/readme/identity.svg" width="1200" alt="ai / English and Persian documentation" />

</div>

# PIMX CHAT · DJANGO

A Django chat application with account management, persisted conversations, static assets and an AI response integration.

[GitHub](https://github.com/MOHAMMADREZAABEDINPOOR/chat) · [PIMX / Profile](https://github.com/MOHAMMADREZAABEDINPOOR) · [Static artwork](assets/readme/hero.png)

## Features

- Account and chat Django applications
- Conversation models and template-based interface
- Static assets and deployment-oriented dependencies
- Google AI package in the dependency manifest

## Stack

| Tool | Version / source |
|---|---|
| Django==4.2.7 | `requirements.txt` |
| djangorestframework==3.14.0 | `requirements.txt` |
| django-cors-headers==4.3.1 | `requirements.txt` |
| django-allauth==0.57.0 | `requirements.txt` |
| Pillow==10.1.0 | `requirements.txt` |
| django-celery-beat==2.5.0 | `requirements.txt` |
| django-celery-results==2.5.1 | `requirements.txt` |
| django-extensions==3.2.3 | `requirements.txt` |
| django-debug-toolbar==4.2.0 | `requirements.txt` |
| django-storages==1.14.2 | `requirements.txt` |
| django-redis==5.4.0 | `requirements.txt` |
| django-user-agents==0.4.0 | `requirements.txt` |

## Getting started

Python 3; a desktop/Tk installation for Tkinter or turtle examples. Tkinter is provided by the Python installation, not pip. Legacy dependencies may need a compatible Python version.

```bash
git clone https://github.com/MOHAMMADREZAABEDINPOOR/chat.git
cd chat

python -m venv .venv
# Windows: .venv\Scripts\Activate.ps1; macOS/Linux: source .venv/bin/activate
python -m pip install -r requirements.txt
python manage.py migrate
python manage.py runserver
```

## Configuration

These names are found in the example configuration or source; not all are required. Check their defaults/usage in those files and supply secrets only in your local or hosting environment.

| Name | Role |
|---|---|
| `DJANGO_ALLOW_MEDIA` | Application setting; inspect its definition |

## Usage

Install requirements in a Python virtual environment, inspect config/settings.py and the AI settings, run migrations and start the local server.

## Project structure

| Path | Role |
|---|---|
| [`accounts/`](accounts/) | Account application |
| [`assets/`](assets/) | Brand/media/README assets |
| [`pimxchat/`](pimxchat/) | Chat/web modules |
| [`static/`](static/) | Static web assets |
| [`templates/`](templates/) | Server-rendered templates |
| [`manage.py`](manage.py) | Project entry/configuration file |

## Commands and checks

```bash
python manage.py check
python manage.py test
```

## Deployment

Configure production secrets, HTTPS, an independent database and allowed hosts. PHP hosting must use public/ as document root; Django needs static-file and WSGI/ASGI configuration. Development servers are for local use.

## Limitations

The tracked snapshot includes development data/configuration and mismatched historical version comments. Use a clean local database and review secrets, allowed hosts and static-file handling before hosting.

## Troubleshooting

- Missing packages: install dependencies using the project’s package manager.
- API/network failure: check the configured origin, provider and hosting bindings.
- Old assets: rebuild when a build script exists, then clear the browser cache.

## Contributing

Create a focused branch, verify the affected behavior and explain the change clearly. Keep private data, build outputs and local databases out of commits.

## License

No repository-level license file is included in this snapshot. Public visibility alone does not grant reuse rights; contact the repository owner for terms.

---

Part of **PIMX** · Documentation in English and Persian.
