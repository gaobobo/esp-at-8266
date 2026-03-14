# ESP-AT-8266

> [!IMPORTANT]
>
> 本项目不是官方项目，不与乐鑫科技有任何关系。
>
> This project is NOT official, and it has NO relation to Espressif Systems.

Firmware for the ESP8266 series, based on the official [`esp-at/v2.3.0.0_esp8266`](https://github.com/espressif/esp-at/tree/v2.3.0.0_esp8266).
This project provides all firmware versions for the ESP8266:

适用于ESP8266系列的固件，基于官方的[`esp-at/v2.3.0.0_esp8266`](https://github.com/espressif/esp-at/tree/v2.3.0.0_esp8266)。
本项目提供ESP8266的所有固件版本：

- ESP8266-WROOM-02_AT_Bin
- ESP8266-WROOM-5V2L_AT_Bin
- ESP8266_1MB_AT_Bin
- ESP8266-WROOM-02-N_AT_Bin

另外还提供了`ESP8266_1MB-UNREMAP`，其RX、TX引脚为GPIO3、GPIO1。
因此，对于像ESP-01S的模块可直接刷写，获得MQTT等原厂固件或早期固件不支持的功能。

具体指引请参阅[官方说明](https://docs.espressif.com/projects/esp-at/en/release-v2.3.0.0_esp8266/Compile_and_Develop/How_to_understand_the_differences_of_each_type_of_module.html)。

Additionally, `ESP8266_1MB-UNREMAP` is provided, with its RX and TX pins being GPIO3 and GPIO1, respectively.
Therefore, modules like the ESP-01S can be directly flashed to obtain features such as MQTT that are not supported by the original firmware or earlier firmware.

Please refer to the [official instructions](https://docs.espressif.com/projects/esp-at/en/release-v2.3.0.0_esp8266/Compile_and_Develop/How_to_understand_the_differences_of_each_type_of_module.html) for detailed guidance.
