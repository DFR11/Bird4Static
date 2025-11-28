# Bird4Static
以下是 bird 與 antifilter.download、antifilter.network 和 re:filter 服務配合使用的檔案。

有 3 種操作模式：從所需服務下載檔案、與某個服務建立 BGP 連線、僅處理使用者檔案。

可以設定一個 VPN，也可以設定兩個 VPN（一個主 VPN，另一個備用 VPN + 使用者重新導向到特定 VPN）。

專為安裝了 entware 的 Keenetic 路由器以及任何安裝了 opkg 軟體包且系統位於 */opt/ 目錄下的系統而設計
安裝

SSH 和 entware

執行：
    ```bash
    opkg install git git-http
    git clone https://github.com/DFR11/Bird4Static.git
    chmod +x ./Bird4Static/*.sh
    ./Bird4Static/install.sh 
    ```
    Далее выбирать нужные параметры.

Более подробная инструкция установки и описание [тут](https://github.com/DFR11/Bird4Static/wiki/Установка)

---
Веб-интерфейс: [web4static](https://github.com/spatiumstas/web4static)

Канал в телеграме: [тут](https://t.me/bird4static)

Чат в телеграме: [тут](https://t.me/bird4static_chat)

Поддержать проект можно через [yoomoney](https://yoomoney.ru/to/41001872039390) и [cloudtips](https://pay.cloudtips.ru/p/76ea7dde)
