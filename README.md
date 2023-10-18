# dianping
美团点评北极星开放平台SDK



## 关于如何使用的示例如下：

```

$config = [
    'app_key' => 'YOUR APP KEY',
    'app_secret' => 'YOUR APP SECRET',
];
$app = new \Demokn\Dianping\Application($config);

//获取商家授权链接
$app->oauth->getMerchantAuthUrl(...);
//session换取
$app->oauth->code2Session(...);
//POI搜索
$app->poi->search(...);
//POI店铺详情
$app->poi->detail(...);
//消费数据
$app->merchant_data->consumption(...);
//团单消费详情
$app->merchant_data->dealGroupsConsumption(...);
//预约数
$app->merchant_data->booking(...);
...
//可以查看源码或通过IDE的自动补全提示查看已经实现的接口
```
