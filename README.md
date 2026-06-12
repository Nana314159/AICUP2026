# AICUP2026
AI CUP 2026 基於時序資料之桌球戰術與結果預測競賽

檔案說明：

best.py  程式碼

test_new.csv 測試集

train.csv 資料集

sample_submission.csv 提交結果格式範例

使用LSTM來進行預測，根據資料集提供的每一個小分(rally_uid)的前n-1擊球資訊，來預測第n拍的球種與落點，及該小分(rally_uid)的最終勝負。
