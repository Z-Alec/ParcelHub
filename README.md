# ParcelHub (WIP)

ParcelHub is a simple web app which scrapes your Gmail messages for deliveries, and consolidates the information in a convenient UI, allowing you to monitor all your incoming/outgoing packages in one place.

## Progress (13/02/2022)

Basic quickstart implemented; OAuth + Inbox Access - [Scaffold](https://developers.google.com/gmail/api/quickstart/python).

## Installation

Using venv/pyenv is preferable. Install the dependencies and run quickstart.py. You will need do the initial Google API and credential setup as described [here](https://developers.google.com/gmail/api/quickstart/python).

```bash
pip install -r requirements.txt
python src/quickstart.py
```

## Contributing
Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change.

Please make sure to update tests as appropriate.

## License
[MIT](https://choosealicense.com/licenses/mit/)