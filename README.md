# V2free自动签到
v2free checkin
## 使用教程
点击Fork按钮将项目Fork到自己仓库

## 配置参数

依次点击上栏【Setting】->【Security】->【Secrets and variables】->【Actions】->【New repository secrets】
在【Name】栏填写USER后在【Secret】栏填写账号，然后点击【Add secret】
再次点击【New repository secrets】，在【Name】栏填写PWD后在【Secret】栏填写密码，然后点击【Add secret】

## 说明
* 支持多账号，账号之间与密码之间用半角逗号分隔（如下所示），账号与密码的个数和位置要对应。

    |USER   |123@qq.com,567@outlook.com|
    |PWD    |ccc,aaa                   |

* 脚本会在北京时间08:00执行一次(Github定时任务会有20min左右延迟)，或者自己action亦可手动执行一次(无延迟)。
