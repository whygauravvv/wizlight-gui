# Wiz light GUI interface for computers 

This is a GUI interface to interact with the Philips Wiz Bulbs and other products in that range. It uses the pywizlight library to control the bulbs. The GUI is written and developed in TKinter.

## Setup

1. If you don’t have Python installed, [install it from here](https://www.python.org/downloads/).

2. Clone this repository.

3. Navigate into the project directory:

   ```bash
   $ cd wizlight-gui
   ```

4. Create a new virtual environment:

   ```bash
   $ python -m venv venv
   $ . venv/bin/activate
   ```

5. Install the requirements:

   ```bash
   $ pip install -r requirements.txt
   ```

6. Make a copy of the example environment variables file:

   ```bash
   $ cp .env.example .env
   ```

7. Add your bulb's IP adress to the newly created `.env` file.

8. Run the app:

   ```bash
   $ python gui.py
   ```
