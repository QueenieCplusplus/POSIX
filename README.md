# POSIX
Portable OS Interface, 可攜式作業系統介面

早期 Unix 的發展，不但要擁有其它 Unix 所擁有的功能，還要保證與新版的相容性。爾後，在這漫長的發展中，電器電子協會 IEEE 也參與了，故開始了標準化的趨勢，即 POSIX，然而在市面上其實消費者也接觸不到，主要是常見的 Linux 與 POSIX 擁有相容性，故也產生了 Linux 是否取代 POISX 成為標準的爭議了！

然而即便符合共同標準的 Unix 們也有之間的差異性，所以同指令，是否支援選項 options，例如 -n 換行是預設關閉抑或開啟，還是 \c 支援記憶體序列的溢出？ 這對同樣指令是否產生相同結果，產生跨平台彼此之間不同的差異結果。

當然，大家期望不同 Unix 系統之間，同樣腳本仍然能產生一致的行為，故將指令發展成跨平台系統標準化顯得非常重要了～

# Script

執行命令環境有很多種，例如：

https://github.com/QueenieCplusplus/LinuxShell_cmd/blob/master/README.md#execution-執行

* bash

* sh

* zsh

* ksh

* pdksh

* ash

* dash

* csh

* tcsh

* osh

建立腳本的方式有兩種：

-[X] 獨立執行的腳本

-[X] 函式檔案（可提供其他腳本呼叫）
