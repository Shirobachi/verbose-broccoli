# Verbose brocoli 🥦

## Description 📙
Hey, thanks for using this package! This script will help you make server on hetzner with all needed staff for beginners. You can watch below video to get more information about this script or keep reading 📖
Video will be added soon ;)

## Secret variables 🤫
---
| Variable | Description | Mandatory | Default | How to get |
|-|-|-|-|-|
|HETZNER_TOKEN | Token from hetzner use for creating server and retrieve them | True | N/A | [Click me](https://imgur.com/a/VhHQjJ9) |
|HETZNER_SERVER_TYPE | The type of server to be made | False | cx11 | [There is list with all codes!](https://www.hetzner.com/cloud) | 
|HETZNER_SERVER_NAME | The name of server what will appear in hetzner dashboard. | False | server | N/A | 
|HETZNER_SERVER_LOCATION | The location of the server. | False | hel1 | [There is list of all locations.](https://docs.hetzner.com/cloud/general/locations/) |
|HETZNER_SSH_NAME | The name of your ssh key in the hetzner account | True | N/A | [Click me](https://imgur.com/OstY28w) |
|SSH_KEY | The private key, used for login to server | True | N/A | First generate key pair as for `HETZNER_SSH_NAME` then do [this](https://imgur.com/SSdm85z) |
|CLOUDFLARE_TOKEN | Token used for setting DNS record | False | None | [Click me!](https://imgur.com/brNK4nv) |
|CLOUDFLARE_ZONE | Cloudflare zone where record will be added | Only if passed `CLOUDFLARE_TOKEN` | None | [Click me](https://i.imgur.com/GwSNcp1.png) |
|CLOUDFLARE_EMAIL | Cloudflare user's email | Only if passed `CLOUDFLARE_TOKEN` | None | [Click me](https://i.imgur.com/TSMDFgM.png) |
|CLOUDFLARE_RECORD | Name of the record to be add | False | server | N/A |
|USERNAME | Username to be made on the server | False | user | N/A |
|SWAP_SIZE | How many GB of swap | False | 2 | N/A |

## Usage 🪝
Fork this repo and set all mandatory (or more variables as you wish) variables. Then go to GitHub repo / actions and run the action.

## License 📝
MIT

## Contributing 🧰 
If you want to contribute to this repo, please open an issue or create a pull request.