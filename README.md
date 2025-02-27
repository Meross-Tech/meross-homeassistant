# meross-homeassistant

## Installation

### Custom Repositories in HACS (recommended)
- Make sure the [HACS integration](https://hacs.xyz/) is properly installed for your instance of home assistant.
- Reference [Custom Repositories](https://hacs.xyz/docs/faq/custom_repositories),In the HACS UI go to "Integrations", click on "+" in the lower right corner".
- Paste https://github.com/Meross-Tech/meross-homeassistant into the field that says "Add custom repository URL", select "Integration" from "Category" dropdown and click "Add".
- You should now see a card with the Meross integration in the HACS -> "Integrations" section. Click "Install".
- Select the latest version from the dropdown and click "Install".
- Restart Home Assistant.

### Manual installation
- Using the tool of choice open the directory for your HA configuration (where you find configuration.yaml).
- If you do not have a custom_components directory there, you need to create it.
- In releases(https://github.com/Meross-Tech/meross-homeassistant/releases), download the version you need.
- In the downloaded file, locate meross_scan directory and copy it to the custom_components directory.
- Restart Home Assistant.

## Configuration
- In the HA UI go to "Configuration" -> "Integrations", click "+", search for "Meross", and select the "Meross" integration from the list.
  Or click here: [![Start Config Flow](https://my.home-assistant.io/badges/config_flow_start.svg)](https://my.home-assistant.io/redirect/config_flow_start?domain=meross_scan)

## Supported device models

| Model                               | Version            |             
|-------------------------------------|--------------------|
| `Meross Smart Energy Monitor, EM06` | `v2.3.8 and above` |
| `Meross Smart Energy Monitor, EM16` | `v3.1.7 and above` |

