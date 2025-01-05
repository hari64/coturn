# coturn
coturn with docker-compose

``` docker compose up -d ```

Turn-server configuration

1. Enable port 3478 and 5349 at line 18 and 30
2. Entert your server IP listening-ip, external-ip and relay-ip at line 60, 61 and 62.
3. Enable min-port and max-port at line 159 and 169 (min-port=49152
max-port=65535)
4. Enable fingerprint and lt-cred-mech
5. Enter user and Password at line 263
6. Enter your domain at line 360 (realm=yourdomain.com)
7. Enable logging at line 527 also enable syslog at line 531

Update your configuration according to your need
