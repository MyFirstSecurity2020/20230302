# Linux資安技術入門 [[請先點選觀看~課程說明與進行方式()]]()
- 本次課程協助學生使用虛擬化技術(在Windows作業系統上安裝Virtualbox,然後匯入linux)學習linux
- 完整的SecurityFoscusOnline2023課程 ~ 請參閱 [完整上課資訊](./Full.md)
- 預先作業自建實體教學環境:本課程使用虛擬機匯入Kali Linux進行教學
  - 步驟1:在你的電腦下載 [virtual box](https://www.virtualbox.org/wiki/Downloads) 並安裝完成 [Virtualbox安裝:YOUTUBE影片](https://youtu.be/FC0CX71aGnc)
  - 步驟2:點選資料下載點, 下載這些龐大的系統
    - 本課程會用到的Kali Linux(比較舊的版本2019) [下載點](https://drive.google.com/file/d/1m620Z7KAOSUOLdFH92FYLE2NINb-vJsn/view?usp=sharing)
    - Python會用到的Ubuntu Linux 18.04 LTS(已安裝好pwntools)  [下載點](https://drive.google.com/file/d/1aP-qCFP6jKsGYXtKy9ahwZleQSENEi7C/view?usp=sharing)
    - [其他linux版本下載](https://ksunextcloud.duckdns.org/index.php/s/mXWBcNaYMrcoL9Y) 
      - Ubuntu 22.04 Desktop.ova  | CentOS 7 Desktop.ova  | Kali Linux.ova(2022.4)
  - 步驟3:匯入你要用的linux  [[YOUTUBE教學錄影]](https://youtu.be/GTpQR7fZcwE)
- 學生預先作業:請學生預先申請你的 [github](https://github.com/)  ~ 請上網Google 一下申請辦法

# 上課所使用的平台:請參看你的錄取通知書
- CTF平台解題(平常沒開放~只有上課期間才會開放):請參看你的錄取通知書
- Discord課程討論區:請參看你的錄取通知書
  - 嚴格禁止上傳答案(違背者取消證書|且不得參與後續研習活動)
- 上課簽到簿:請每日上課不要遲到
- 問卷調查:上完課後再填寫!一定要填寫,不然沒有證書 
  - 問卷調查須正確填寫CTF註冊的使用者ID 以供驗證解題數作為通過課程考核的依據

### CTF 入門: 
- 如果你從沒上過CTF課程,就請先學習 ~ 如果學過 ==> 可以掠過此部分
- CTF 入門:透過參與CTF搶旗大賽學習資安實務 [[線上教材]](./CTF.md) [[YOUTUBE教學錄影]](https://youtu.be/Bcxyx3lJG8w)
- 起手式---文件隱寫術之word隱身術{隱寫術101::STEG1}[[YOUTUBE教學錄影]](https://youtu.be/aeXnuZi3XOk)
  - 另一種解法 請參閱 [如何在Word中快速顯示或隱藏所有隱藏的文本？](https://zh-tw.extendoffice.com/documents/word/906-word-show-hide-hidden-text.html) 
- 【自行完成】{隱寫術101::STEG2_Secret in PDF}

## Linux資安技術入門:  教學環境 ==> 本課程使用Kali Linux
## 1.快速認識Linux作業系統 [線上教材](./Linux/1.基礎linux入門.MD) [[YOUTUBE教學錄影]](https://youtu.be/0T4o81Vghio)
  - 幾種學習LINUX的方式:
    - 連線到LINUX CTF去學習[本次課程會用到]
    - 使用虛擬機匯入LINUX學習[本次課程會用到]
    - 使用線上工具 [Online Linux Terminal](https://www.tutorialspoint.com/linux_terminal_online.php)
    - 使用Google Colab
  - 學習LINUX基本指令(commands) == > 完成 Linux 101 + Linux 102 解題
    - [如何透過Windows連線到CTF平台解題](https://github.com/MyFirstSecurity2020/SecurityFoscusOnline2023/blob/main/A2_Linux%E8%B3%87%E5%AE%89%E6%8A%80%E8%A1%93%E5%85%A5%E9%96%80/%E5%A6%82%E4%BD%95%E9%80%8F%E9%81%8EWindows%E9%80%A3%E7%B7%9A%E5%88%B0CTF%E5%B9%B3%E5%8F%B0%E8%A7%A3%E9%A1%8C.md) [[YOUTUBE教學錄影]](https://youtu.be/cULwZeGliuA)
    - Linux指令入門[線上教材](https://github.com/MyFirstSecurity2020/20230211/blob/main/Linux/2_0_.Linux%E5%9F%BA%E6%9C%AC%E6%8C%87%E4%BB%A4.MD)
    - Linux CTF 參考解答
      - [LINUX CTF 101解答 ](https://github.com/MyFirstSecurity2020/SecurityFoscusOnline2023/blob/main/A2_Linux%E8%B3%87%E5%AE%89%E6%8A%80%E8%A1%93%E5%85%A5%E9%96%80/2_1_Linux101%E8%A7%A3%E7%AD%94.md)  [[Linux1_教學錄影]](https://youtu.be/zLeU0XJAtws)
      - [LINUX CTF 102解答](https://github.com/MyFirstSecurity2020/SecurityFoscusOnline2023/blob/main/A2_Linux%E8%B3%87%E5%AE%89%E6%8A%80%E8%A1%93%E5%85%A5%E9%96%80/2_2_Linux%20102%E8%A7%A3%E7%AD%94.md) [[Linux6_教學錄影]](https://youtu.be/-xzdAZJnZM4)[[Linux7_教學錄影]](https://youtu.be/mdtYXAk3mAs)[[Linux8_教學錄影]](https://youtu.be/SW1dMD2vyrA) [[Linux9_教學錄影]](https://youtu.be/nKrWjw10O_U) [[Linux10_教學錄影]]()
  - 【延續學習建議】
    - 完成底下[linux練習](https://overthewire.org/wargames/bandit/) ~ 不會解可以上網參看別人的解法
      - 課後你可以增加國外Linux的練習經驗喔 ~  
    - [學習更多Linux指令](./LearningLinux1.md)
    - [LINUX 進階學習](./LearningLinux2.md)
    - 參加後續舉辦的【程式安全分析入門】課程
## 2.隱寫術(Steganography) == >   完成 【隱寫術101】 解題
  - 2.1_認識 隱寫術(Steganography)  [[線上教材]](./Linux/2.%E9%9A%B1%E5%AF%AB%E8%A1%93%E5%85%A5%E9%96%80/1_%E8%AA%8D%E8%AD%98%E9%9A%B1%E5%AF%AB%E8%A1%93%20Steganography.md) [[YOUTUBE教學影片]](https://youtu.be/EJk3l64WPsQ)
  - 2.2_圖片隱寫術之1:基本入門技_使用linux 基本指令file|strings|grep{隱寫術101::STEG3} [解答](https://github.com/MyFirstSecurity2020/SecurityFoscusOnline2023/blob/main/A2_Linux%E8%B3%87%E5%AE%89%E6%8A%80%E8%A1%93%E5%85%A5%E9%96%80/2.%E9%9A%B1%E5%AF%AB%E8%A1%93%E5%85%A5%E9%96%80/2_%E5%9C%96%E7%89%87%E9%9A%B1%E5%AF%AB%E8%A1%93%E5%9F%BA%E6%9C%AC%E5%85%A5%E9%96%80%E6%8A%80.md) [[YOUTUBE教學影片]](https://youtu.be/farL-eOUXZs)
  - 👍2.3_圖片隱寫術之2:圖片內嵌`含解答圖片`的解題 
    - 題目:隱寫術101::STEG4  [題目檔案](https://raw.githubusercontent.com/MyFirstSecurity2020/backup/main/steg/steg101/carter.jpg) [解答](https://github.com/MyFirstSecurity2020/SecurityFoscusOnline2023/edit/main/A2_Linux%E8%B3%87%E5%AE%89%E6%8A%80%E8%A1%93%E5%85%A5%E9%96%80/2.%E9%9A%B1%E5%AF%AB%E8%A1%93%E5%85%A5%E9%96%80/3_%E5%9C%96%E7%89%87%E9%9A%B1%E5%AF%AB%E8%A1%93%E4%B9%8B2_%E5%9C%96%E7%89%87%E5%85%A7%E5%B5%8C%E8%A7%A3%E7%AD%94%E5%9C%96%E7%89%87%E7%9A%84%E8%A7%A3%E9%A1%8C.md) [[YOUTUBE教學影片]](https://youtu.be/GLpg4rTmiqg)
  - 2.4_圖片隱寫術之3:圖片的metadata{隱寫術101::STEG5} [解答](https://github.com/MyFirstSecurity2020/SecurityFoscusOnline2023/blob/main/A2_Linux%E8%B3%87%E5%AE%89%E6%8A%80%E8%A1%93%E5%85%A5%E9%96%80/2.%E9%9A%B1%E5%AF%AB%E8%A1%93%E5%85%A5%E9%96%80/4_%E5%9C%96%E7%89%87%E9%9A%B1%E5%AF%AB%E8%A1%93%E4%B9%8B3_%E5%9C%96%E7%89%87%E7%9A%84metadata.md)
## 3.Linux 鑑識分析入門 == >  完成 【Network101 】 解題
  - 3.1.鑑識分析與Wireshark入門 [線上教材](./Linux/3_1_鑑識分析與Wireshark入門.md)
  - 3.2.網路鑑識分析第一步:使用linux指令進行分析[線上教材](./Linux/3_2_網路鑑識分析第一步_使用linux基本指令進行分析.md) [[YOUTUBE教學影片]](https://youtu.be/IL0R7u7W9dk)
    - linux指令: file | strings | grep
    - Network101::NET1
    - Network101::NET2
  - 👍3.3.HTTP Basic Authentication(認證)封包分析{Network101::NET3} [線上教材](./Linux/3_3_使用wireshark分析HTTPBasicAuthentication.md) [[YOUTUBE教學影片]](https://youtu.be/IH3Q7jdDX5s)
  - 3.4.HTTP封包分析之檢視出user使用的瀏覽器版本號{Network101::NET4} [線上教材](./Linux/3_4_使用wireshark檢視出user使用的瀏覽器版本號.md) [[YOUTUBE教學影片]](https://youtu.be/GnufKfXOSG4)


