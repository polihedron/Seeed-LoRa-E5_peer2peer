# Seeed-LoRa-E5_peer2peer
LoRa-E5 base station and sensor, peer to peer LoRa range test device.
This is a basic device made to test LoRa network.
It's built from danak6jq repo https://github.com/danak6jq/Seeed-LoRa-E5, converted from LoRaWAN to SubGHz_Phy application, and 
then merge with MOOC - STM32WL workshop: https://www.youtube.com/watch?v=n7OoTStkczs

To add mode sensors change node address in SubGHz_Phy\App\subghz_phy_app.h

#define NODE_ID  (uint8_t)(0x03)  /* Node address */

Base station ID is 0x01.
