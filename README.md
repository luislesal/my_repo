“Primer fichero en el primer repositorio de Luis Escobar Salvador”
![PlantUML model](http://www.plantuml.com/plantuml/png/RLB1JiCm33tFNs7j19DM0SUTjXLn1ePszrflAygI4IS8gUBVSPjED0EfX_hv-RrdAqi9v4Cy6QWCYU2MRI3Pi3JEjh2o_4N-MHbDJJUti3Rk8_8O-GOOJmwD5fwQT_AFB3KhQSE6gqeLTTAp_YYMf7Mevjfv1LvY4pBWpGKofGewow9roTxtX92ChGkClZaS0xfzPhzO_Dh3f8naQuV2k5SKsM3TDL2_S-8ZJBIhoSXKqP15umGzsOCJPVNLvv2B1VGFEsyOhPwQhzr82zMG6JPnr_ZH1gjpr9299jdnUkZ2RA4F24UIG4eQE6NiLhnujK19JIzwIXSTQafAkMVfTluVU4kcBzUaQrUSCetV0Bhv7ATtHM6dsOaHichMiUuxLduCo2gS5KLYvGjVirGiN_QFMQVoSAM2YvImVpUmr55zrZy0)

```mermaid
sequenceDiagram
Alice -> Bob: Authentication Request
Bob --> Alice: Authentication Response
Alice -> Bob:Another authentication Response
Bob --> Alice: Another authentication Response
```

```plantuml
Alice -> Bob: Authentication Request
Bob --> Alice: Authentication Response
   
Alice -> Bob: Another authentication Request
Alice <-- Bob: Another authentication Response
```
