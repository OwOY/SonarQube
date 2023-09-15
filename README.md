<p align="center"><img src="img/Sonarqube.png"></p>

## Introduction
SonarQube 是一款基於 Java 開發的原始碼檢測與品質管理系統，因著 Java 的關係，Server 與 Client 都是跨平台的。

SonarQube 透過分析原始碼，找出程式碼中的 Bug、Code Smell、Security Vulnerability、Code Coverage 等問題，並提供 Dashboard、Report、警告通知等功能，讓開發者可以更容易地維護程式碼品質。

SonarQube 提供許多功能：    
1. Web 化操作介面
2. 可分析多種程式語言，並可加購以支援更多種類
3. 檢測安全漏洞
4. 分析可靠性、重覆性、技術債務、測試覆蓋率
5. 提供問題標註資訊以及程式碼改善建議
6. 提供追蹤修訂機制，可以了解問題改善歷程
7. 支援團隊協作，以及權限機制
8. 可以細部調整程式分析的策略
9. 整合 GitHub、Gitlab、LDAP、AD 等驗證機制
10. 成熟的更新中心，可方便的升級系統與安裝外掛套件
11. 中文操作介面

## Install
1. 安裝 Java11
    - linux
    >> sudo apt install openjdk-11-jdk
    - macOS
    >> brew install openjdk@11
    - Windows
    >> [Java](!https://www.oracle.com/java/technologies/javase-jdk11-downloads.html)

2. 至官網下載  
[SonarQube載點](!https://www.sonarsource.com/products/sonarqube/downloads/success-download-community-edition/)

3. 執行程式
    - linux  
    >> bin/linux-x86-64/sonar.sh start 
    - macOS  
    >> bin/macosx-universal-64/sonar.sh start
    - Windows   
    >> bin\windows-x86-64\StartSonar.bat 

4. 開啟瀏覽器，輸入 http://localhost:9000/ ，進入 SonarQube 首頁

5. 進入sonarQube並輸入帳號密碼(預設admin:admin) 

6. 匯入專案並設定完成

7. 下載 SonarScanner(內附載點)

8. 解壓縮後將bin目錄加入環境變數

9. 執行指令即可查看報表
