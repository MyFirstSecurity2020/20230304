# SecurityFoscusOnline2023 上課資訊
# 課程宗旨:
- 讓全台灣的學生都有機會快速學到底下基本技術
  - 一點點的資安與CTF技術
  - 一點點的LINUX
  - 一點點的Python程式開發與在資安的應用

# SecurityFoscusOnline2023課程模組
- 從CTF實戰學習資訊安全測試
  - A1_MyFirstSecurity資安入門的第一堂課
  - A2_Linux資安技術入門
  - A3_Python程式與資安應用入門 


# 上課平台
- [線上上課(Google Meet)](https://meet.google.com/anw-awov-hsw)
- [CTF平台解題(平常沒開放~)](https://120.114.62.215/)
- [Discord課程討論區：https://discord.gg/fdp6d699](https://discord.gg/fdp6d699)
- 上課簽到
  - [2/11 簽到簿](https://forms.gle/TjzKdoCwXRt9wTzb7)
  - [2/12 簽到簿](https://forms.gle/TCjCFFqQ7ayccNLN8)
- [問卷調查](https://forms.gle/WT1vQ3x7HC9FD7Gu6)
  - (最後填寫!一定要填寫) 


# 開場白與上課模式
# 第一天上課時程
## 早上 A1_MyFirstSecurity資安入門的第一堂課
- CTF 入門:透過參與CTF搶旗大賽學習資安實務 [線上課程]
  - CTF搶旗大賽
  - 註冊與登入CTF
  - 起手式---文件隱寫術之word隱身術{隱寫術101::STEG1}
    - 另一種解法 請參閱 [如何在Word中快速顯示或隱藏所有隱藏的文本？](https://zh-tw.extendoffice.com/documents/word/906-word-show-hide-hidden-text.html) 
  - 自己動手解{隱寫術101::STEG2_Secret in PDF}
- 網站安全初體驗 == > Web101
  - Web101::Web-1:source code(隱藏在註解裡的FLAG)
  - Web101::Web-2:Easy_Robots.txt(Robot.txt的奧秘)
  - Web101::web-3:Robots.txt
  - Web101::web-4:Curl-1:URL redirection的破招 [[線上解答]](./A1_MyFirstSecurity資安入門的第一堂課/web-4解答.md) [[YOUYUBE教學錄影]](https://youtu.be/Lwyp3tv66KQ)
  - Web101::web-5:HTTP method (HTTP method的奧義)[[線上解答]](./A1_MyFirstSecurity資安入門的第一堂課/web-5解答.md)
- 編碼與解碼 == >  編碼101
  - Ascii 編碼與解碼[線上課程] {編碼101:Ascii}
  - 請完成 {編碼101}另外四題
  - 【自行完成】編碼101:第一堂Unicode
- 古典密碼學之破密分析 == > Crypto101  
  - 善用線上工具進行破密分析
  - 凱薩密碼 與【暴力破解法】{Crypto101::CRY1}
  - 【自行完成】{Crypto101::CRY2_凱撒密碼part2}
  - 【自行完成】{Crypto101::CRY3_ROT 13} 
  - 密碼棒加解密 Scytale [英文WIKI說明](https://en.wikipedia.org/wiki/Scytale) [中文WIKI的說明](https://zh.m.wikipedia.org/zh-tw/%E5%AF%86%E7%A2%BC%E6%A3%92)
    - 題目:Crypto101::CRY4 SCYTCRYPTO 密碼棒破密}  [[YOUYUBE教學錄影]](https://youtu.be/8XbZSa-1GkE)
  - Vigenère cipher  
    - 基本觀念 [課程線上教材](https://github.com/MyFirstSecurity2020/SecurityFoscusOnline2023/blob/main/A1_MyFirstSecurity%E8%B3%87%E5%AE%89%E5%85%A5%E9%96%80%E7%9A%84%E7%AC%AC%E4%B8%80%E5%A0%82%E8%AA%B2/Vigen%C3%A8recipher.md) [[YOUYUBE教學錄影]]()
    - Crypto101::CRY5題目解答[[YOUYUBE教學錄影]](https://youtu.be/P2fCkFC2eRA)
  - 【頻率分析法】的破密技術{Crypto101::CRY6}
  - 【自行完成】{Crypto101::CRY7_Rail Fence Cipher}
  - 【自行完成】{Crypto101::CRY8_ROT47}


## 下午 A2_Linux資安技術入門
- 預先作業
  - 首先完成你的 [github](https://github.com/) 申請
  - 在你的電腦下載 [virtual box](https://www.virtualbox.org/wiki/Downloads) 並安裝完成 [Virtualbox安裝:YOUTUBE影片](https://youtu.be/FC0CX71aGnc)
  - 匯入你要用的linux  [YOUTUBE影片](https://youtu.be/GTpQR7fZcwE)
  - 資料下載點(請先下載這些龐大的系統)
    - Kali Linux [下載點](https://drive.google.com/file/d/1m620Z7KAOSUOLdFH92FYLE2NINb-vJsn/view?usp=sharing)
    - Python會用到的Ubuntu Linux 18.04 LTS(已安裝好pwntools)  [下載點](https://drive.google.com/file/d/1aP-qCFP6jKsGYXtKy9ahwZleQSENEi7C/view?usp=sharing)
- Linux作業系統 [本課程線上教材](https://github.com/MyFirstSecurity2020/SecurityFoscusOnline2023/blob/main/A2_Linux%E8%B3%87%E5%AE%89%E6%8A%80%E8%A1%93%E5%85%A5%E9%96%80/1.%E5%9F%BA%E7%A4%8Elinux%E5%85%A5%E9%96%80.MD) [[YOUYUBE教學錄影]]
- LINUX指令(commands) == >  Linux 101 + Linux 102
  - [如何透過Windows連線到CTF平台解題](https://github.com/MyFirstSecurity2020/SecurityFoscusOnline2023/blob/main/A2_Linux%E8%B3%87%E5%AE%89%E6%8A%80%E8%A1%93%E5%85%A5%E9%96%80/%E5%A6%82%E4%BD%95%E9%80%8F%E9%81%8EWindows%E9%80%A3%E7%B7%9A%E5%88%B0CTF%E5%B9%B3%E5%8F%B0%E8%A7%A3%E9%A1%8C.md)
  - [LINUX CTF 101解答 ](https://github.com/MyFirstSecurity2020/SecurityFoscusOnline2023/blob/main/A2_Linux%E8%B3%87%E5%AE%89%E6%8A%80%E8%A1%93%E5%85%A5%E9%96%80/2_1_Linux101%E8%A7%A3%E7%AD%94.md)
  - [LINUX CTF 102解答](https://github.com/MyFirstSecurity2020/SecurityFoscusOnline2023/blob/main/A2_Linux%E8%B3%87%E5%AE%89%E6%8A%80%E8%A1%93%E5%85%A5%E9%96%80/2_2_Linux%20102%E8%A7%A3%E7%AD%94.md) 
  - 作業1:完成底下[linux練習](https://overthewire.org/wargames/bandit/)
- 隱寫術(Steganography) == >  隱寫術101
  - 1_認識 隱寫術(Steganography)  [[課程線上教材]](https://github.com/MyFirstSecurity2020/SecurityFoscusOnline2023/blob/main/A2_Linux%E8%B3%87%E5%AE%89%E6%8A%80%E8%A1%93%E5%85%A5%E9%96%80/2.%E9%9A%B1%E5%AF%AB%E8%A1%93%E5%85%A5%E9%96%80/1_%E8%AA%8D%E8%AD%98%E9%9A%B1%E5%AF%AB%E8%A1%93%20Steganography.md) [[YOUTUBE教學影片]](https://youtu.be/EJk3l64WPsQ)
  - 2_圖片隱寫術之1:基本入門技_使用linux 基本指令file|strings|grep{隱寫術101::STEG3} [解答](https://github.com/MyFirstSecurity2020/SecurityFoscusOnline2023/blob/main/A2_Linux%E8%B3%87%E5%AE%89%E6%8A%80%E8%A1%93%E5%85%A5%E9%96%80/2.%E9%9A%B1%E5%AF%AB%E8%A1%93%E5%85%A5%E9%96%80/2_%E5%9C%96%E7%89%87%E9%9A%B1%E5%AF%AB%E8%A1%93%E5%9F%BA%E6%9C%AC%E5%85%A5%E9%96%80%E6%8A%80.md) [[YOUTUBE教學影片]](https://youtu.be/farL-eOUXZs)
  - 3_圖片隱寫術之2:圖片內嵌`含解答圖片`的解題 
    - 題目:隱寫術101::STEG4  [題目檔案](https://raw.githubusercontent.com/MyFirstSecurity2020/backup/main/steg/steg101/carter.jpg) [解答](https://github.com/MyFirstSecurity2020/SecurityFoscusOnline2023/edit/main/A2_Linux%E8%B3%87%E5%AE%89%E6%8A%80%E8%A1%93%E5%85%A5%E9%96%80/2.%E9%9A%B1%E5%AF%AB%E8%A1%93%E5%85%A5%E9%96%80/3_%E5%9C%96%E7%89%87%E9%9A%B1%E5%AF%AB%E8%A1%93%E4%B9%8B2_%E5%9C%96%E7%89%87%E5%85%A7%E5%B5%8C%E8%A7%A3%E7%AD%94%E5%9C%96%E7%89%87%E7%9A%84%E8%A7%A3%E9%A1%8C.md) [[YOUTUBE教學影片]](https://youtu.be/GLpg4rTmiqg)
  - 4_圖片隱寫術之3:圖片的metadata{隱寫術101::STEG5} [解答](https://github.com/MyFirstSecurity2020/SecurityFoscusOnline2023/blob/main/A2_Linux%E8%B3%87%E5%AE%89%E6%8A%80%E8%A1%93%E5%85%A5%E9%96%80/2.%E9%9A%B1%E5%AF%AB%E8%A1%93%E5%85%A5%E9%96%80/4_%E5%9C%96%E7%89%87%E9%9A%B1%E5%AF%AB%E8%A1%93%E4%B9%8B3_%E5%9C%96%E7%89%87%E7%9A%84metadata.md)
- Linux 鑑識分析入門 == >  Network101
  - 1.認識wireshark
  - 2.網路鑑識分析第一步:使用file | strings | grep 指令進行分析[解答](https://github.com/MyFirstSecurity2020/SecurityFoscusOnline2023/tree/main/A2_Linux%E8%B3%87%E5%AE%89%E6%8A%80%E8%A1%93%E5%85%A5%E9%96%80/3_Linux%20%E9%91%91%E8%AD%98%E5%88%86%E6%9E%90%E5%85%A5%E9%96%80)
    - Network101::NET1
    - Network101::NET2
  - 3.wireshark封包分析 == >HTTP Basic Authentication(認證)封包{Network101::NET3} [解答](https://github.com/MyFirstSecurity2020/SecurityFoscusOnline2023/blob/main/A2_Linux%E8%B3%87%E5%AE%89%E6%8A%80%E8%A1%93%E5%85%A5%E9%96%80/3_Linux%20%E9%91%91%E8%AD%98%E5%88%86%E6%9E%90%E5%85%A5%E9%96%80/3_%E4%BD%BF%E7%94%A8wireshark%E5%88%86%E6%9E%90HTTP%20Basic%20Authentication(%E8%AA%8D%E8%AD%89)%E5%B0%81%E5%8C%85.md)
  - 4.wireshark封包分析 == >檢視出user使用的瀏覽器版本號{Network101::NET4} [解答](https://github.com/MyFirstSecurity2020/SecurityFoscusOnline2023/blob/main/A2_Linux%E8%B3%87%E5%AE%89%E6%8A%80%E8%A1%93%E5%85%A5%E9%96%80/3_Linux%20%E9%91%91%E8%AD%98%E5%88%86%E6%9E%90%E5%85%A5%E9%96%80/4_%E4%BD%BF%E7%94%A8wireshark%E6%AA%A2%E8%A6%96%E5%87%BAuser%E4%BD%BF%E7%94%A8%E7%9A%84%E7%80%8F%E8%A6%BD%E5%99%A8%E7%89%88%E6%9C%AC%E8%99%9F.md)
  - 5.wireshark封包分析 == >UDP 封包中的FLAG{Network101::NET5}
# 第二天上課時程 A3_Python程式與資安應用入門 
## 早上: Python 快速上手
- 1.開發環境與基本輸入與輸出 
  - python開發環境 [線上教材](./A3_Python程式與資安應用入門/A_Python程式入門/0_python開發環境.md) [[YOUTUBE教學影片]](https://youtu.be/9Doo0hgbpow)
  - 基本輸入與輸出 格式化輸出 [線上教材](./A3_Python程式與資安應用入門/A_Python程式入門/1_基本輸入與輸出.md)  
- 2.Python資料型態(data Type)及其各種運算 [線上教材](./A3_Python程式與資安應用入門/A_Python程式入門/2_資料型態及其運算.md)  [[YOUTUBE教學影片]](https://youtu.be/zCfVPuJWRg8) 
- 3.python決策與選擇結構 [線上教材](./A3_Python程式與資安應用入門/A_Python程式入門/3_python決策與選擇結構.md) [YOUTUBE預錄影片]() 
- 4.廻圈(loop) [線上教材](./A3_Python程式與資安應用入門/A_Python程式入門/4_廻圈loop.md) [[YOUTUBE教學影片]](https://youtu.be/12I7eNHQpgY) 
- 5.函數(function) [線上教材](./A3_Python程式與資安應用入門/A_Python程式入門/5_函數.md) [[YOUTUBE教學影片]](https://youtu.be/tRtsxZ73LVk) 

## 下午: Python 資安應用
- 1.使用Python求解編碼與解碼問題
  - 使用Python程式與內建函數進行ASCII的編碼與解碼 [[YOUTUBE教學影片]](https://youtu.be/0Tr-X0Lpi7g)
  - 使用Python標準函式庫進行BASE64的編碼與解碼 [[YOUTUBE教學影片]](https://youtu.be/z2jxjkl5X-4) 
  - 編碼102_Internetwache CTF 2016_The hidden message [解答]()
  - 編碼102:SECCON CTF 2014: Easy Cipher [解答]()
- 2.使用Python求解古典密碼破密分析問題 Crypto102
  - 【自行完成】{Crypto102::CRY11_PythonCrypto} [解答]()
  - 使用Python求解變形caesar密碼{Crypto102::CRY12_變形caesar密碼} [解答]()
  - 使用Python求解affine-cipher{Crypto102::CRY13_affine-cipher} [解答](https://github.com/MyFirstSecurity2020/SecurityFoscusOnline2023/blob/main/A3_Python%E7%A8%8B%E5%BC%8F%E8%88%87%E8%B3%87%E5%AE%89%E6%87%89%E7%94%A8%E5%85%A5%E9%96%80/B_Python%E8%B3%87%E5%AE%89%E6%87%89%E7%94%A8%E5%85%A5%E9%96%80/3_Python%E5%8F%A4%E5%85%B8%E7%A0%B4%E5%AF%86%E6%B3%95/2_%E4%BD%BF%E7%94%A8Python%E6%B1%82%E8%A7%A3affine-cipher.md)
- 3.使用Python求解PPC(Professional Program Code)問題
  - PPC(Professional Program Code)之使用 nc 遠端連線{PPC101::PPC1_hello world} [線上教材](https://github.com/MyFirstSecurity2020/SecurityFoscusOnline2023/blob/main/A3_Python%E7%A8%8B%E5%BC%8F%E8%88%87%E8%B3%87%E5%AE%89%E6%87%89%E7%94%A8%E5%85%A5%E9%96%80/B_Python%E8%B3%87%E5%AE%89%E6%87%89%E7%94%A8%E5%85%A5%E9%96%80/4_Python%20%20PPC%E5%AF%A6%E6%88%B0%E6%8A%80/PPC(Professional%20Program%20Code)%E4%B9%8B%E4%BD%BF%E7%94%A8%20nc%20%E9%81%A0%E7%AB%AF%E9%80%A3%E7%B7%9A%7BPPC101::PPC1_hello%20world%7D.md)  [[教學影片]](https://youtu.be/zJF4LBBHHrE)
  - PPC(Professional Program Code)之pwntools快速入門與示範解題{PPC101::PPC2_3rd} [線上教材](https://github.com/MyFirstSecurity2020/SecurityFoscusOnline2023/blob/main/A3_Python%E7%A8%8B%E5%BC%8F%E8%88%87%E8%B3%87%E5%AE%89%E6%87%89%E7%94%A8%E5%85%A5%E9%96%80/B_Python%E8%B3%87%E5%AE%89%E6%87%89%E7%94%A8%E5%85%A5%E9%96%80/4_Python%20%20PPC%E5%AF%A6%E6%88%B0%E6%8A%80/PPC(Professional%20Program%20Code)%E4%B9%8Bpwntools%E5%BF%AB%E9%80%9F%E5%85%A5%E9%96%80%E8%88%87%E7%A4%BA%E7%AF%84%E8%A7%A3%E9%A1%8C.md) [[教學影片]](https://youtu.be/XVRYjrbBYw4)
  - PPC101::PPC3_beautify解答 [線上教材](https://github.com/MyFirstSecurity2020/SecurityFoscusOnline2023/blob/main/A3_Python%E7%A8%8B%E5%BC%8F%E8%88%87%E8%B3%87%E5%AE%89%E6%87%89%E7%94%A8%E5%85%A5%E9%96%80/B_Python%E8%B3%87%E5%AE%89%E6%87%89%E7%94%A8%E5%85%A5%E9%96%80/4_Python%20%20PPC%E5%AF%A6%E6%88%B0%E6%8A%80/PPC101::PPC3_beautify%E8%A7%A3%E7%AD%94.md)
  - 【自行完成】自行完成 PPC101::PPC4_count[線上教材](https://github.com/MyFirstSecurity2020/SecurityFoscusOnline2023/blob/main/A3_Python%E7%A8%8B%E5%BC%8F%E8%88%87%E8%B3%87%E5%AE%89%E6%87%89%E7%94%A8%E5%85%A5%E9%96%80/B_Python%E8%B3%87%E5%AE%89%E6%87%89%E7%94%A8%E5%85%A5%E9%96%80/4_Python%20%20PPC%E5%AF%A6%E6%88%B0%E6%8A%80/PPC101::PPC4_count%E8%A7%A3%E7%AD%94.md)
  - PPC101::PPC5_lambda解答 [線上教材](https://github.com/MyFirstSecurity2020/SecurityFoscusOnline2023/blob/main/A3_Python%E7%A8%8B%E5%BC%8F%E8%88%87%E8%B3%87%E5%AE%89%E6%87%89%E7%94%A8%E5%85%A5%E9%96%80/B_Python%E8%B3%87%E5%AE%89%E6%87%89%E7%94%A8%E5%85%A5%E9%96%80/4_Python%20%20PPC%E5%AF%A6%E6%88%B0%E6%8A%80/PPC101::PPC5_lambda%E7%AD%94%E6%A1%88.md)
  - PPC101::PPC6_money解答 [線上教材](https://github.com/MyFirstSecurity2020/SecurityFoscusOnline2023/blob/main/A3_Python%E7%A8%8B%E5%BC%8F%E8%88%87%E8%B3%87%E5%AE%89%E6%87%89%E7%94%A8%E5%85%A5%E9%96%80/B_Python%E8%B3%87%E5%AE%89%E6%87%89%E7%94%A8%E5%85%A5%E9%96%80/4_Python%20%20PPC%E5%AF%A6%E6%88%B0%E6%8A%80/PPC101::PPC6_money%E7%AD%94%E6%A1%88.md)
  - PPC101::PPC7_calendar解答 [線上教材](https://github.com/MyFirstSecurity2020/SecurityFoscusOnline2023/blob/main/A3_Python%E7%A8%8B%E5%BC%8F%E8%88%87%E8%B3%87%E5%AE%89%E6%87%89%E7%94%A8%E5%85%A5%E9%96%80/B_Python%E8%B3%87%E5%AE%89%E6%87%89%E7%94%A8%E5%85%A5%E9%96%80/4_Python%20%20PPC%E5%AF%A6%E6%88%B0%E6%8A%80/PPC101::PPC7_calendar%E8%A7%A3%E7%AD%94.md)
  - PPC101::PPC8_temperature答案 [線上教材](https://github.com/MyFirstSecurity2020/SecurityFoscusOnline2023/blob/main/A3_Python%E7%A8%8B%E5%BC%8F%E8%88%87%E8%B3%87%E5%AE%89%E6%87%89%E7%94%A8%E5%85%A5%E9%96%80/B_Python%E8%B3%87%E5%AE%89%E6%87%89%E7%94%A8%E5%85%A5%E9%96%80/4_Python%20%20PPC%E5%AF%A6%E6%88%B0%E6%8A%80/PPC101::PPC8_temperature%E7%AD%94%E6%A1%88.md)  [[教學影片]](https://youtu.be/_YGpD7wXGOo)




