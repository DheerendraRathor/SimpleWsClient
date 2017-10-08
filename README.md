GoWsClient
==========

A simple websocket client in Golang to debug websocket server. 

Features:
- Awesome logging. Every action taken and every event registered is logged.
- Takes care of sending pong.
- Send received message back to server
- In case of binary message, it logs base64 encoded message.

Installation:
- Download latest exe/binary for required platform from Github releases
- **OR** if go is installed then use `go get -u github.com/DheerendraRathor/GoWsClient`

Usages:
```bash
# If installed from Github releases
.\SimpleWsClient --addr=wss://echo.websocket.org

# If used go get
.\GoWsClient --addr=wss://echo.websocket.org
```