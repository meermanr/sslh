# sslh

Credit: [GitHub - yrutschle/sslh: Applicative Protocol Multiplexer (e.g. share SSH and HTTPS on the same port)](https://github.com/yrutschle/sslh)

## Installation

```
sudo ln -s $PWD/sslh.service /etc/systemd/system/
sudo systemctl daemon-reload
sudo systemctl enable sslh.service
sudo systemctl start sslh.service
```
