Website viewer bot - An amazing project

1. brew install tor (mac) / sudo apt-get install tor (ubuntu)
2. brew services start tor (mac) / sudo service tor start (ubuntu)
3. sudo pip install requests
4. pip install torrequest==0.1.0
5. goto /etc/tor/torrc file and add  ControlPort 9051 and remove .sample extension of the file
6. brew services restart tor (mac) / sudo service tor restart
7. python site-view-bot.py
8. give full url link and number of views you need.
