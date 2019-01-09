# schulzimmer-wetterstation-TTN

Library: https://github.com/matthijskooijman/arduino-lmic

Example: ttn-abp

pin definition für TTGO: 

const lmic_pinmap lmic_pins = {
  .nss = 18, 
  .rxtx = LMIC_UNUSED_PIN,
  .rst = 14,
  .dio = {/*dio0*/ 26, /*dio1*/ 33, /*dio2*/ 32}
}; 

