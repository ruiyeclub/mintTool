## 抢nft原理
    通过监听合约是否开启公售，进行提前mint，不受网页影响。
    示例中，先查看铸造minSAC的代码，找到开启公售的按钮flipPublicSaleState  
    
## 配置
    1.修改config.js
    2.配置：https://dashboard.alchemy.com/    
    3.修改public.js，找到铸造函数和开启公售函数
    4.修改abi.json
    
## 启动
    node public.js    