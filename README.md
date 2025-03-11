GeekbleMini-ESP32C3
=============
GeekbleMini-ESP32C3 문서에 오신것을 환영합니다

아두이노 IDE에서 쉽게 사용할 수 있는 Geekble Mini를 통해 WiFi, Bluetooth 기능을 여러분의 프로젝트에 구현할 수 있습니다

Geekble Mini 핀맵
-------------
![GEEKBLE Mini-ESP32@2x](https://github.com/SooDragon/GeekbleMini-ESP32C3/blob/main/GEEKBLE%20Mini_V2_PinMap.png)
GeekbleMini PinMap

Geekble Mini 회로도
-------------
![GeekbleMini Schematic](https://github.com/SooDragon/GeekbleMini-ESP32C3/blob/main/GeekbleMini_V2_Schematic.png)
GeekbleMini Schematic

Geekble Mini 치수도
-------------
![Dimension](https://github.com/SooDragon/GeekbleMini-ESP32C3/assets/82627949/7f9556da-58ea-45cf-b5bf-8bbe3479398c)
GeekbleMini Dimension

Geekble Mini KiCad 라이브러리 by [@Alcyone-0022](https://github.com/Alcyone-0022)
-------------
![Symbol](https://github.com/SooDragon/GeekbleMini-ESP32C3/blob/main/GeekbleMini_Symbol.png)    
![Footprint](https://github.com/SooDragon/GeekbleMini-ESP32C3/blob/main/GeekbleMini_Footprint.png)    
KiCad 프로젝트에 사용 가능한 Footprint가 존재합니다.    
**Geekble Mini ESP32C3FH4.pretty** 폴더와 **Geekble Mini ESP32C3FH4.kicad_sym** 파일을 KiCad 프로젝트 폴더에 옮긴 뒤,    
각각 풋프린트 에디터→파일→라이브러리 추가→프로젝트 선택→확인→**Geekble Mini ESP32C3FH4.pretty** 폴더 선택,    
심볼 에디터→파일→라이브러리 추가→프로젝트 선택→확인→**Geekble Mini ESP32C3FH4.kicad_sym** 파일 선택하여 추가하신 뒤 사용해 주세요.

Geekble Mini Version Log
-------------
- Ver.1.0.0: 최초 공개 버전
- Ver.1.1.0: Vin/VUSB 설계 변경, VUSB에서 Vin 방향으로 전류가 흐르지 않도록 회로 및 아트웍 수정, Vin에 배터리가 연결 된 상태에서 USB를 연결할 수 있다
- Ver.1.1.1: 핀헤더에 의해 실크가 가려지지 않게 배치 수정
- Ver.2.0: A5(ADC1)핀 D5핀으로 재배치, 재배치에 따른 핀 위치 수정
