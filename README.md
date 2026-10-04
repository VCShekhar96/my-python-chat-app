# Python Chat App

A real-time Flask chat application using Flask-SocketIO for browser-based messaging.

## Features

- Real-time chat over WebSockets
- Temporary usernames and generated avatars
- User join/leave events
- Username updates
- Flask template-based web interface

## Tech Stack

- Python
- Flask
- Flask-SocketIO
- HTML/CSS/JavaScript

## Getting Started

```bash
git clone https://github.com/VCShekhar96/my-python-chat-app.git
cd my-python-chat-app
python -m venv .venv
```

Activate the environment and install dependencies:

```bash
pip install -r requirements.txt
python app.py
```

Open the local Flask address in your browser.

## Project Structure

```text
.
├── app.py
├── wsgi.py
├── requirements.txt
├── templates/
└── .gitignore
```

## Notes

Connected-user state is stored in memory and is reset when the process restarts. Avatar URLs are generated through an external avatar service.

## Future Improvements

- Persistent storage
- Authentication
- Chat rooms and private messaging
- Validation and rate limiting
- Automated tests
- Production deployment configuration

## Security

Keep credentials and secrets out of source control. Prefer environment variables for sensitive configuration.

## License

No license is currently declared.
