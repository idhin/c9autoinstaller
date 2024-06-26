# c9autoinstaller

--> c9 Auto Installer in Ubuntu <--

1. Enter the screen session 

`screen`

2. Paste one shot one kill command

`apt update -y && apt install build-essential git nodejs python2.7 -y && git clone https://github.com/c9/core.git c9sdk && cd c9sdk && scripts/install-sdk.sh && nodejs server.js -p 8080 -l 0.0.0.0 -a user:pass -w /local`

Jangan lupa ganti `User` dan `pass`

3. Done. You can close the remote SSH and open C9 in the browser
