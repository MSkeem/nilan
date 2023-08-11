# Nilan Graphics for Home Assistant (Lovelace)

This repository contains graphics for Nilan ventilation, designed to be used with Home Assistant's Lovelace UI.

## Features

- **Air-Flow Visualization**: Displays the speed and direction of the airflow.
- **Dynamic Coloring**: The color changes to reflect the current state of Cooling, Heating, or Standby.
- **Compatibility**: The graphics are designed for Nilan VPL15 (air-heating/cooling only, without water-heating). If you have a different model, you may need to modify the YAML file.

## Installation

### 1. Upload the Graphics

From your Home Assistant folder, upload the image files into a sub-folder called `nilan` within the `www` folder in Home Assistant. Ensure that all additional folders are added, as they contain the actual graphics.

### 2. Modify Your Lovelace Configuration

Add the suggested code from `lovelace.yaml` to your own `ui-lovelace.yaml` file.

### Prerequisites

- Connection to Nilan through EspHome: [EspHome Components](https://github.com/Jopand/esphome_components)
- Config-template-card from [Iantrich's Repository](https://github.com/iantrich/config-template-card)

## Customization and Animation

The animations were created using PowerPoint and then exported to animated GIFs, refined using Photoshop. All the source files created in PowerPoint and Photoshop are included in this repository.

Feel free to use these assets and make your own customizations. If you have any findings, suggestions, results, etc., you are welcome to share them in the [Facebook Group](https://www.facebook.com/groups/667765647316443).

## Support

For questions, feedback, or support, please refer to the [Facebook Group](https://www.facebook.com/groups/667765647316443).
