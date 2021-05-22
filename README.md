# 台灣高鐵時刻表
## 2021/05/21

### 路徑格式：時刻表生效年月日，例如 `2021/05/21`

### 檔案格式： CSV

### 欄位說明

#### 車次
 * 0xxx, 1xxx: 指定日行駛，見「行駛日」欄位
 * x1xx: 停靠南港、台北、板橋、台中、左營站
 * x2xx: 停靠南港、台北、板橋、台中、台南、左營站（0203, 0295, 1202 車次除外）
 * 0203: 停靠台北、板橋、台中、嘉義、台南、左營站（不停南港）
 * 0295: 停靠南港、台北、桃園、台中、嘉義、台南、左營站（不停板橋）
 * 1202: 停靠南港、台北、台中、嘉義、台南、左營站（不停板橋）
 * x3xx: 停靠南港、台北、桃園、台中～左營間各站
 * x5xx: 停靠南港～台中間各站（0583, 0598 車次除外）
 * 0583, 0598: 停靠台中～左營間各站
 * x6xx: 停靠南港～新竹間各站及台中、嘉義、台南、左營等站（0696 車次除外）
 * 0696: 停靠台北～新竹間各站及台中、嘉義、台南、左營等站（不停南港）
 * x8xx: 停靠南港～左營間各站
 * 奇數：南下列車
 * 偶數：北上列車

#### 行駛日
 * 借用航空業標示法，以 `1` `2` `3` `4` `5` `6` `7` 分別代表星期一至星期日，若當日列車並無行駛，則以 `-` 表示。例： `12345--` 代表星期一至五行駛。

#### 各車站時刻：
 * 採用 24 小時制表示，即 `HH:MM` 。若欄位為 `xxxxx` ，代表該列車表定並未通過該站；若欄位為 `--:--` ，表示該列車通過該站不停靠。
 * 除終點站為到達時刻外，其他各站均為開車時刻。

## 關於本時刻表
 * 本時刻表僅供參考，若和[官方時刻表](https://www.thsrc.com.tw/ArticleContent/a3b630bb-1066-4352-a1ef-58c7b4e8ef7c)有所出入，請以官方時刻表為準。
