# Docker machine driver for [Hetzner Cloud](https://www.hetzner.com/cloud)

## Installation

Use go get github.com/ednikolenko/docker-machine-hetzner and make sure that docker-machine-hetzner is located somwhere in your PATH

## Usage

    $ docker-machine create \
      --driver hetzner \
      --hetzner-access-token=<YOU_ACCESS_TOKEN> \
      my-machine

## Options

| Parameter                    | Env                    | Default                      |
| ---------------------------- | ---------------------- | ---------------------------- |
| **`--hetzner-access-token`** | `HETZNER_ACCESS_TOKEN` | -                            |
| **`--hetzner-image`**        | `HETZNER_IMAGE`        | `debian-9`                   |
| **`--hetzner-location`**     | `HETZNER_LOCATION`     | `fsn1`                       |
| **`--hetzner-server-type`**  | `HETZNER_SERVER_TYPE`  | `cx11`                       |

## License

MIT © [Ed Nikolenko](https://github.com/ednikolenko)
