# NEXYS Vodoměr Firmware

Veřejný repozitář pro OTA aktualizace firmware zařízení **NEXYS Vodoměr**.

Zařízení je určeno pro integraci s **Home Assistant** a využívá OTA aktualizace pomocí veřejně dostupného manifestu a firmware souborů publikovaných v GitHub Releases.

## Účel repozitáře

Tento repozitář slouží pouze pro distribuci firmware souborů `.bin` a OTA manifestu.

Obsahuje:

- `firmware/manifest.json` – aktuální OTA manifest
- GitHub Releases – binární firmware soubory `.bin`

Neobsahuje interní ESPHome YAML konfiguraci ani vývojové soubory.

## OTA manifest

Aktuální manifest je dostupný na adrese:

```text
https://raw.githubusercontent.com/nexys-cz/NEXYS-vodomer/main/firmware/manifest.json
