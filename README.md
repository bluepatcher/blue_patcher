blue_patcher
============

Informal fork of https://github.com/stschake/blue_patcher/ in order to track https://github.com/evemuproject/evemu_server client version, currently 360229


INSTRUCTIONS:
=============

1) copy the blue_patcher.exe into your EVE client directory where you will find blue.dll, which should be the /bin directory

2) run blue_patcher.exe, you should get success

3) edit common.ini in your client directory, replace the line with "cryptoPack=CryptoAPI"  with  "cryptoPack=Placebo", without the quotes of course

4) save common.ini and close it

5) edit start.ini in your client directory, replace the line with "server=Tranquility"  with  "server=<your_server_url_or_domain>", <your_server_url_or_domain> should be 127.0.0.1 or localhost if testing on the SAME machine as your server or some other IP address or URL

6) save start.ini and close it

7) alternatively, you can edit your EVE shortcut on your desktop to include the command line switch /server:<your_server_IP_address>, such as /server:127.0.0.1

8) you're DONE!

