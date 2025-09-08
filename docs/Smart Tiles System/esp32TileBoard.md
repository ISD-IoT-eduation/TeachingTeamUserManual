# ESP32 Tile Board

## Code Source
Code is available at: [ESP32 Tile Decentralized](https://github.com/ISD-IoT-eduation/esp32TileDecentralized)

## Version 2 - Decentralized Tiles (Currently in use)
Where each tile only communicates with its neighbors directly and individually sends edge connection to web to reconstruct. This avoids the need for relaying messages back to a central hub which long distance can cause the message to be corrupted

1. Set your device to the same network and manually set to fixed IP `192.168.1.100`

    ```c
    // Wifi Configuration
    const char WIFI_SSID[] = "ISD-Project-22Fall";
    const char WIFI_PASSWORD[] = "isd@2022Fall";
    // Set your device IP to static 192.168.1.100
    const String HOST_NAME = "http://192.168.1.100:8080";
    const String PATH_NAME = "/console/";
    ```

2. Use the code at `/TileBoard/TileBoard.ino` for all tiles
3. Remember to change the Board ID for each tile when compiling and uploading
    ```c
    // Tile Configuration
    int myBoardID = 1;  // Unique ID for each tile board
    ```
    - Tile boards for the final demo arena should be labelled with ID from 1 - 25 (25 in total)
    - Tile boards for the testing field should be labelled with 26 - 31 (6 in total)

    
## Version 1 - Core and Non-Core Tiles (Not in use currently)

