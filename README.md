## 微信公众号定时发送模版消息

### ./config.json 是配置文件
```json
{
  "mod": "prod",    // mod 设置为 test 立即发送模版消息，不执行定时任务
  "cron": "*/1 * * * *", // 定时设置
  "love_start_date": "2022-08-21", // 在一起的时间
  "birth_date": "08-23", // 生日
  "wechat_official": { // 公众号配置
    "app_id": "wxxxxxxxxxxx",
    "app_secret": "xxxxxxxx",
    "open_ids": [  // 接收消息的 open_id, 支持多个
      "xxxxxxx"
    ],
    "template_id": "xxxxxxxxxx" // 公众号消息模版id
  },
  "yiketianqi": { // 天气配置 https://www.yiketianqi.com/
    "appid": "xxxxx",
    "appsecret": "xxxxx",
    "cityid": "101050101"
  },
  "colors": {
    "qinghua": "#550038" // 情话字体颜色
  }
}
```
