# meetup-auto-rsvp
# Meetup Auto-RSVP

A code which automatically RSVPs in your [Meetup](https://meetup.com) groups' upcoming events.

# Prerequisites
- Have valid Chrome Webdriver instlled.
- Have Selenium installed

# Instructions

- Clone and navigate into the repository directory:
- Create a `config.json` file containing your **email** and **password**. A sample `config.json` is given:

```json
{
  "email": "<YOUR EMAIL ID>",
  "password": "<YOUR PASSWORD>"
}
```

A `config.json` file has been included in the repository for testing. 

- Run the script:

```bash
python3 main.py
```

The script will check for any new event in your joined groups every *30 minutes*, and automatically confirm your attendance for that event. It **will** notify you upon any confirmation.
