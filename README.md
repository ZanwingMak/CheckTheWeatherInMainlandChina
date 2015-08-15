# CheckTheWeatherInMainlandChina
Check the weather in mainland China 查看中国大陆地区天气

程序运行的第一步是获取本机外网ip,然后再获取ip的物理地址(城市),
最后把城市传给天气api,将json转换成dict(字典)后取值输出，
手动输入城市则省去前面两个步骤。
