# FundraisingSplit
集資分帳處理系統


# 預計功能
* /建立集資項目 => 回應集資項目
* 輸入集資項目 => 回應集資目標金額
* 輸入集資目標金額 => 集資目標期限日
* 輸入集資目標期限日 => 集資報表日期(預設為空)
* 輸入報表日期(cron格式) => 顯示集資編號
* /加入集資 <%編號%> => 回應請輸入集資金額 (可輸入負值，負值為降低集資金額 ，負到最低為0表示不參與集資)
* 輸入參與集資金額 => 回應加入集資成功
* /修改集資項目 <%集資編號%> 金額 <%金額%>
* /修改集資項目 <%集資編號%> 期限日 <%金額%>
* /修改集資項目 <%集資編號%> 報表週期 <%cron%>
* /Info => 顯示目前參與的所有集資
* /Info <%集資編號%> => 顯示該集資資訊
* /計算出金 <%集資編號%> => 顯示幕前可出金金額，並請輸入出金金額
* 輸入出金金額 => 顯示出金後剩餘金額
* /出金 <%集資編號%> => 顯示幕前可出金金額，並請輸入出金金額
* 輸入出金金額 => 顯示出金後剩餘金額，並在集資內扣除金額
* /清算 <%集資編號%> => 結算集資項目，立即產生所有參與者出金報告，並將集資關閉

# 使用TG 作為通知處理
## TG 機器人教學文件
https://telegrambots.github.io/book/1/example-bot.html
