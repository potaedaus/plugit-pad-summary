# plugit-pad-summary
Power Automate Desktop Flow summarizing offline chargers from PlugIT CSMS panel and invalid active sessions from KC. It then sends it to email with a pregenerated message-link for WhatsApp. Coded with free version of Power Automate Desktop.

1. How to build:
- Copy the code in the .txt file into clipboard.
- Paste into Power Automate Desktop workspace.

2. Prepping the 'config.json' file. Download the 'config.json' template and edit with your own details following the same format:

- KC active sessions URL.
- PlugIT location URLS.
- Input sender email, receiver email and WhatsApp phone number.
- Duration of an invalid active session in minutes. Eg, 720 minutes = 12 hours. Only sessions more than 12 hours will be flagged.
- If there are ignored locations, replace 'LOCATION 1', 'LOCATION 2', etc with the actual location names.
