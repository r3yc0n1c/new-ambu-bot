# Ambubot

**Ambubot** is a chatbot service that allows users to quickly get ambulances during urgent hours through WhatsApp.

## Features

- **WhatsApp Integration**: Users can request an ambulance by simply sending a message on WhatsApp.
- **Real-time Response**: The service immediately processes the request and dispatches the nearest available ambulance.
- **Web Scraping**: Utilizes Beautiful Soup to gather and update information about available ambulance services.
- **Twilio API**: Sends and receives WhatsApp messages using Twilio's powerful messaging service.

## Tech Stack

- Python
- Flask
- Beautiful Soup
- Twilio

## Setup

1. Clone the repository:

```sh
git clone https://github.com/yourusername/abubot.git
cd abubot
```
2. Create a virtual environment:

```sh
python -m venv venv
source venv/bin/activate  # On Windows use `venv\Scripts\activate`
```
3. Install dependencies:

```sh
pip install -r requirements.txt
```
4. Set up environment variables:

- **TWILIO_ACCOUNT_SID**
- **TWILIO_AUTH_TOKEN**

5. Run the application:
```sh
flask run
```

## Usage
1. **Send a 'hi' WhatsApp message** to the Twilio WhatsApp number you set up.
2. **Follow the prompts** to provide your location and any additional details.
3. **Receive confirmation** when an ambulance is dispatched to your location.


## Contributing
Contributions are welcome! Please fork this repository and submit a pull request if you'd like to contribute to Abubot.

## License
This project is licensed under the the GNU General Public License, Version 3 - see the [LICENSE](./LICENSE) file for details.

## Contact
For any inquiries, please contact [@r3yc0n1c](https://github.com/r3yc0n1c).