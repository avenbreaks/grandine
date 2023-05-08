## Beacon Node API

Grandine supports standard [Beacon Node API](https://ethereum.github.io/beacon-APIs/). This API is extensively tested against other CL validator clients and other Beacon Node API consumers such as [Vouch](https://github.com/attestantio/vouch). API is enabled by default.

### Relevant command line options:

* `--http-port` - sets API listen port (default: `5052`);
* `--http-address` - sets API listen address (default: `127.0.0.1`);
* `--timeout` - sets API timeout in miliseconds (default: `10000`).
