LLM for WhatsApp
Description
LLM for WhatsApp is an application designed to automate responses to WhatsApp messages using an LLM. I created this for fun and to engage with and potentially wasting the time of scammers. I have used it several times when I was approach by scammers and was a blast. In the end, my goal is to have my phone number banned on all scamming lists, marked as "useless". Of course can be used for any kind of autoresponding needs, it has fully customizable system prompt and list of contacts to interacat with.

Please note that LLM for WhatsApp is using whatsapp.js that is using automation on the Whatsapp web client, a method that is not officially supported by Meta. For any business purposes, it is recommeded to apply for business API access and use the Whatsapp business API instead of this.

The application integrates with OpenAI's models via API or any custom LLM that's compatible with OpenAI's API interface. For a very quick setup, I recommend Oobabooga with OpenAI extension and as a model, for English, I recommend Mistral 7B.

Features
Automated responses to WhatsApp messages.
Support for OpenAI API via API key.
Support for custom LLMs for complete privacy.
Customizable for various scenarios where automated messaging via Whatsapp are required.
Start it for any contact or group and let LLM to continue conversation.
Give directions to the LLM via the customizable system prompt
Custom message to start conversation.
Stop the conversation and resume with custom message
Getting Started
Use released binaries
Easiest way to start is to download binaries for your OS

Build from sources
Or you can build from sources followint those steps

Prerequisites
Before you can run or build LLM for WhatsApp, ensure you have the following installed:

Node.js
Yarn package manager
Installation
Clone the repository:

git clone https://github.com/iongpt/LLM-for-Whatsapp.git
Navigate to the application directory:

cd LLM-for-Whatsapp
Install the necessary packages:

yarn install
Run the preinstall script for extra libraries defined in the app folder:

yarn run preinstall
Rename app/settings.json.example to app/settings.json

Usage
Running in Development Mode
To run the application in development mode:

yarn run dev
Building the Application
You can build the application for various operating systems using the following commands:

For Windows:

yarn run build:win
For macOS (Intel):

yarn run build:osx
For macOS (M1):

yarn run build:osxm1
For Linux (x64):

yarn run build:linux
For Linux (32-bit):

yarn run build:linux32
For Linux (ARMv7l):

yarn run build:linuxarmv7l
After application starts
Authorize Whatsapp client by scanning the QR code with the phone
Go to the LLM Setting menu (in the top menu bar) select Settings and fill the config in the window (either OpenAI API key, eitther URL for local LLM API)
Contributing
Contributions to LLM for WhatsApp are welcome. Please read the CONTRIBUTING.md file for guidelines on how to contribute.

Issues
If you encounter any issues or have feature suggestions, please submit them to the issues page.

Known issues
It gets stuck at loading if you have no contacts on Whatsapp. At least one contact is required to load the app
I only tested it on Mac M1 and Windows x64, it is confirmed to work on Windows, but it will require permission for the app to interact with Chrome
License
This project is licensed under the MIT License - see the LICENSE.md file for details.

Author
Developed by IonGPT.

