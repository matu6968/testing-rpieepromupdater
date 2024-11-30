# Raspberry Pi5 bootloader EEPROM release notes

## 2024-12-01: (test of not listing other fw versions)

* testing
* testing

## 2024-11-30: rp1fw: Add FIFO_STATE & DRAIN_TX, fix CAN_ADD_PROGRAM (default)

* rp1fw: Add FIFO_STATE & DRAIN_TX, fix CAN_ADD_PROGRAM
  RP1 firmware eb39cfd516f8c90628aa9d91f52370aade5d0a55 adds methods
  to drain the TX FIFO and retrieve the state of both FIFOs. It also
  fixes the CAN_ADD_PROGRAM implementation, which was fatally broken.
* network-install - Update the UI to display the board model / variant.
