# Tile Server

## Code Source
Code is available at: [Decentralized Tile Server](https://github.com/ISD-IoT-eduation/decentralized_tile_server)

## Version 2 - Tile Server using Nice GUI

Since now each tile individually reports its connection info of its 4 neighbors, the tile server needs to aggregate and process all the connections, and then reconstruct the map layout.


### Preparation
1. Install the Python packages needed
```
fastapi==0.116.1
nicegui==2.23.3
```
2. Connect your device to WiFi and manually assign static IP to `192.168.110.100` as this is the host IP configured for all tile boards

### Run

1. Run `main.py`
2. Then visit `http://localhost:8080`

### Sub pages 

- Visit `http://localhost:8080/shape-config` to configure the shapes for different tiles (please pay attention to the orientation)
- Visit `http://localhost:8080/map` to view the live map
- Homepage at `http://localhost:8080/` shows the connectivity of each individual tile boards and their active ports



