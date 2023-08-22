# NOVAKIN.DedicatedServer

These are simple instructions to setup a NOVAKIN Dedicated Server

1) Run the DedicatedServer batch file, it will open a command prompt and download the required files.
2) After the file download has completed, the server will automatically start. Close the command prompt window.
3) Browse to the NOVAKIN\_CommonRedist folder and install all the crap in there.
4) Browse to the NOVAKIN\NOVAKIN_Data\StreamingAssets\Config\ folder. Open the serverConfig.json file with any text editor.
5) Modify the config file to suit your needs, then Save.
6) Return back to the folder with the DedicatedServer batch file and run it again.

The server should now start. Make sure to configure your firewall and router for port forwarding!
The port is specified in the serverConfig.json file you modified earlier, 26016 is the defaut.

Everytime you run the DedicatedServer batch file it will automatically download any needed updates.

If you need additional help, contact us on Discord at https://discordapp.com/invite/0j6SAwMNL7uUlmBp
