# Umbral

A NuCypher API for applying proxy-reencription on the decentraminds marketplace

### Installation

1. Run a local fleet of Ursulas

   ```bash
    git clone https://github.com/nucypher/nucypher.git
    cd nucypher
    sh scripts/local_fleet/run_local_fleet.sh

   ```

2. Install the required libraries

  ```bash
   cd umbral
   pip install -r requirements.txt
  ```
4. Start the python server

   ```bash
    python app.py
   ```