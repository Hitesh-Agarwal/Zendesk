# Ticket Viewer for Zendesk

## Installation

Before you start, you must have Python 3.5+ on your system.

Go to this project's root directory above the shell and run the code below:
```bash
pip install -r requirements.txt
```

And make a new file named `.env` on this project's root directory and type below:
```
SECRET_KEY=HardToGuessSecretString
ZENDESK_SUBDOMAIN=<Subdomain of Zendesk Support Page>
ZENDESK_AGENT_EMAIL=<Agent E-mail>
ZENDESK_AGENT_PASSWORD=<Agent Password>
```

If your support page's URL is hitesh.zendesk.com, your value of `ZENDESK_SUBDOMAIN` is `hitesh`.

## Test and run
You can run the unit test with this code below:
```bash
python ticketviewer.py test
```

And you can run the server with this code below:
```bash
python ticketviewer.py run
```

After running the server, go to http://localhost:5000 to use this system.

