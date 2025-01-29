# Gaia_Net_Hackathon_24

The first step is to install the GAIA Net, the following command does it:
curl -sSfL 'https://github.com/GaiaNet-AI/gaianet-node/releases/latest/download/install.sh' | bash

Then, follow the prompt on your screen to set up the environment path. The command line will begin with "source"
For Example:  source/Users/"Your UserName"/.zshrc. It means CLI tool available in the current shell


Use the following command to initialize the Gaia node according to the configuration options in $HOME/gaianet/config.json. Initialize the node. It will download the model files and vector database files specified in the $HOME/gaianet/config.json file, and it could take a few minutes since the files are large.

gaianet init

Use the following command to start your node:
gaianet start


After starting your node
A successful start prints a public URL for the node. Opening a browser to that URL will display the node information and allow you to chat with the AI agent on the node. 

You can start the node for local use. It will be only accessible via localhost and not available on any of the GaiaNet domain's public URLs.

gaianet start --local-only

We can customize the config.json file
