# Flomo Dify Plugin

This plugin integrates Flomo with Dify, allowing users to send notes to Flomo directly through Dify workflows.

## Features
- Send notes to Flomo from Dify
- Easy configuration via YAML files
- Supports custom note content and tags

## Installation
1. Clone this repository:
   ```bash
   git clone https://github.com/crazywoola/dify-plugin-flomo.git
   ```
2. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```
3. Configure your Flomo API key in `provider/flomo.yaml` and `tools/flomo.yaml`.

## Usage
- Use the provided Python scripts and YAML configuration to send notes to Flomo.
- Integrate with Dify workflows as needed.

## File Structure
- `main.py`: Main entry point for the plugin
- `provider/flomo.py`, `tools/flomo.py`: Flomo integration logic
- `utils/flomo_utils.py`: Utility functions
- `manifest.yaml`: Plugin manifest
- `requirements.txt`: Python dependencies
- `_assets/flomo.png`: Flomo logo

## License
This project is licensed under the MIT License.

## Privacy
See `PRIVACY.md` for details on data handling and privacy.
