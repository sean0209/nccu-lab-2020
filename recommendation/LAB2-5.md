# Lab2-5 設定 Pipeline (Demo)
在此步驟我們將設定LAB2-4完成 Jenkinsfile 至 OpenShift執行，體驗 CI/CD 的整個執行過程。
![Image lab-env](https://raw.githubusercontent.com/j3ffk3/nccu-lab-2020/main/imgs/build-success.PNG)

### 1.設定 Pipeline 讀取 LAB2-4完成的 Jenkinsfile
- 進入 OpenShift UI 點選 Builds > BuildConfigs > recommendation-pipeline > yaml
- 將${GIT_URL}修改為你GIT的位置
![Image lab-env](https://raw.githubusercontent.com/j3ffk3/nccu-lab-2020/main/imgs/lab2-5-1.PNG)

### 2.嘗試執行CI/CD流程
進入 OpenShift 點選 start build 按鈕。
![Image lab-env](https://raw.githubusercontent.com/j3ffk3/nccu-lab-2020/main/imgs/lab2-start-build.PNG)

### 3.驗證
可以看到流程正常執行完畢
![Image lab-env](https://raw.githubusercontent.com/j3ffk3/nccu-lab-2020/main/imgs/build-success.PNG)
