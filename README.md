## ngrok_start.sh

Allow SSH access to the system by running ngrok as a background process. Supports dockerised ngrok instance.

### Installation

See knowledge base article for ngrok installation.

### Usage

Non-dockerised ngrok:

`sudo bash ngrok_start.sh`

Dockerised ngrok:

`sudo bash ngrok_start.sh docker`

### Output

The script will output the ngrok connection details

**N.B. this script used to reside in the [workstation_housekeeping](https://github.com/moka-guys/workstation_housekeeping) repository**