# Moguci feature-i
- Kapacitivno sensanje kad si uhvatio cunj
- Rucni odabir i pokretanje animacija
- Mali oled ekran
- Kapacitivni gumbi oko sredine
- Punjenje preko usb-a - mikro usb / mini usb / usbc / neki magnetni kontakti ?
- vrijeme rada / velicina baterije
- wireless DMX
- Komunikacija preko BT i USB-a
- Akcelerometar

# Tehnicka pitanja
- Brzina updateanja + koliko cesto + finalni utjecanj na snimanje kamerom i gledanje
- RTOS ili ne
    RTOS ili na ruke protothreadovi?
- Koji RTOS
    Mynewt
    Zephyr
    nesto trece
- FW napisati u nekom relativno modernom C++ -u
- Odabir led tehnologije
    Vjerojatno WS2513B - najnovije od adresabilnih i naj naprednije - Ako crkne jedna u lancu imaju nacin da nastave komunikaciju prema onima koje su iza
- Protokol
    - Definiranje zahtjeva protokola
    - Definiranje komandi
    - Kako ostaviti protokol fleksibilnim i prosirivim?
- U sto zapakirati protokol? ---> U protobuf
- Smisljanje mehanicke konfiguracije
- FOSS
    - HW
    - FW
    - SW
- Animiranje
    - koje sve mogucnosti mogu biti
        - slozimo tako da imamo sampleove, ali spremamo samo diffove (ako se nesto ne mjenja od proslog stanja to nekako oznacimo i ustedimo malo mjesta)
        - prijelaz na slijedeci korak osim vremena moze biti i neki drugi impuls (uhvatio si cunj u ruku, impuls izvana koji bi se slao u syncu sa muzikom ili necim drugim)
    - kako spremati animacije
- Boje
    - Istraziti one color space-ove i translacije izmedju njih

# Zanimljivi URLovi - in no perticular order
- Visualise color spaces - http://colorizer.org/
- HSV - RGB transformation - https://mattlockyer.github.io/iat455/documents/rgb-hsv.pdf 
- Color transformations libs 
    - https://github.com/dmilos/color
    - https://github.com/ratkins/RGBConverter
- AdaFruit Feather NRF52 Full Usermanual - https://cdn-learn.adafruit.com/downloads/pdf/bluefruit-nrf52-feather-learning-guide.pdf
- NRF52382 module - https://cdn-learn.adafruit.com/assets/assets/000/040/357/original/MDBT42Q-Version_B.pdf?1490125904
