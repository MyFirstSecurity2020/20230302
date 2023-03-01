# 3_鑑識分析與wireshark入門

## 數位鑑識(Digital Forensics)
- [Wiki 英文版說明Digital forensics](https://en.wikipedia.org/wiki/Digital_forensics)
- [Wiki 中文版說明Digital forensics](https://zh.wikipedia.org/wiki/%E6%95%B8%E4%BD%8D%E9%91%91%E8%AD%98)
- 數位鑑識|數位鑑識科學|數位取證
  - 是鑑識科學(Forensics)的其中一個分支，主要在針對數位裝置(電腦|手機)中的內容進行調查與復原

## 常見的數位鑑識(Digital Forensics)
- 1_電腦鑑識(Computer Forensics) [英文版wiki說明](https://en.wikipedia.org/wiki/Computer_forensics)
  - 自電腦系統或其它類似的儲存媒體中，尋找罪行相關物證或間接物證
  - 常用工具:[autospy](https://www.autopsy.com/) [下載autospy](https://www.autopsy.com/download/)
- 2_網路鑑識(Network Forensics) 
  - 自側錄的網路流量中尋找相關證據
  - 常用工具:[wireshark](https://www.wireshark.org/) [下載wireshark](https://www.wireshark.org/#download)
  - 本次課程使用linux上的wireshark  
  - 同學可以下載 windows版本的wireshark 
- 3_記憶體鑑識(Memory Forensics)
  - 自記憶體中尋找相關證據  
  - [英文版Wiki說明: forensic analysis of a computer's memory dump](https://en.wikipedia.org/wiki/Memory_forensics)
  - 常用工具:[Volatility (使用python程式開發的)](https://www.volatilityfoundation.org/)

## 網路鑑識(Network Forensics)工具:wireshark
- Wireshark（前稱Ethereal）是一個免費開源的網路封包分析(network protocol analyzer)軟體
- 最常見功能就是截取(capture)網路封包，並盡可能顯示出最為詳細的網路封包資料。

## Wireshark使用情境:
- 網路管理員使用Wireshark來檢測網路問題
- 網路安全工程師使用Wireshark來檢查資訊安全相關問題
- 開發者使用Wireshark來為新的通訊協定除錯
- 普通使用者使用Wireshark來學習網路協定的相關知識

## 本課程將使用linux版的Wireshark進行分析

## Wireshark官方資源 ...恩!英文要好好學
- [官方網址](https://www.wireshark.org/)
- [官方使用者指南Wireshark User’s Guide](https://www.wireshark.org/docs/wsug_html_chunked/)


# 後續延伸研讀
- [實戰封包分析｜使用 Wireshark, 3/e (支援IPv6與Wifi)](https://www.tenlong.com.tw/products/9789864766574?list_name=trs-t)
- [網路分析完全實戰手冊 ─ 使用 Wireshark, 2/e](https://www.tenlong.com.tw/products/9789864343973?list_name=srh)
