# Supplementary Information #

## Ad Fraud Type ##
We would like to clarify that,  all the nine Ad fraud types are actually summarised from the regulations of app markets and ad networks, which have explicit policies to disallow app developers to distribute ADs in the summarised nine ways (i.e., the nine ad fraud types).


| Ad Fraud Type     | Markets/ad networks that have related   policies | Policy Link                                                  |
| ----------------- | ------------------------------------------------ | ------------------------------------------------------------ |
| Hidden            | Google Admob                                     | <https://support.google.com/admob#topic=2745287>             |
| Hidden            | Wandoujia/Ali App Distribution Network           | <http://aliapp.open.uc.cn/wiki/?p=140>                       |
| Size              | Google Admob Behavior Policy                     | https://support.google.com/admob#topic=2745287               |
| Size              | Tencent Myapp Market                             | <http://wiki.open.qq.com/wiki/%E5%BA%94%E7%94%A8%E4%B8%8A%E6%9E%B6%E8%A7%84%E5%88%99#3.2_.E5.B9.BF.E5.91.8A.E4.BF.A1.E6.81.AF> |
| Size              | 360 App Market                                   | <http://dev.360.cn/wiki/index/id/18>                         |
| Size              | Wandoujia/Ali App Distribution Network           | <http://aliapp.open.uc.cn/wiki/?p=140>                       |
| Number            | DoubleClick/Google Admob                         | https://support.google.com/adxseller/answer/2728052?hl=en    |
| Number            | Microsoft                                        | <https://pubcenter.microsoft.com/customermanagement/customer/tc.html> |
| Overlap           | Google Admob                                     | <https://support.google.com/admob#topic=2745287>             |
| Overlap           | Wandoujia/Ali App Distribution Network           | <http://aliapp.open.uc.cn/wiki/?p=140>                       |
| Interaction       | Google Admob                                     | <https://support.google.com/admob#topic=2745287>             |
| Interaction       | Xiaomi Market                                    | <https://dev.mi.com/console/doc/detail?pId=879>              |
| Interaction       | Huawei Market                                    | <http://developer.huawei.com/consumer/cn/devservice/doc/50104> |
| Interaction       | Wandoujia/Ali App Distribution Network           | <http://aliapp.open.uc.cn/wiki/?p=140>                       |
| Drive-by Download | CCSA                                             | http://www.ccsa.org.cn/tc/baopi.php?baopi_id=5244            |
| Drive-by Download | 360 App Market                                   | <http://dev.360.cn/wiki/index/id/18>                         |
| Drive-by Download | Wandoujia/Ali App Distribution Network           | <http://aliapp.open.uc.cn/wiki/?p=140>                       |
| Outside           | Google Admob                                     | https://support.google.com/admob#topic=2745287               |
| Outside           | Tencent Myapp Market                             | <http://wiki.open.qq.com/wiki/%E5%BA%94%E7%94%A8%E4%B8%8A%E6%9E%B6%E8%A7%84%E5%88%99#3.2_.E5.B9.BF.E5.91.8A.E4.BF.A1.E6.81.AF> |
| Outside           | 360 App Market                                   | http://dev.360.cn/wiki/index/id/18                           |
| Outside           | Wandoujia/Ali App Distribution Network           | <http://aliapp.open.uc.cn/wiki/?p=140>                       |
| Outside           | Google Play                                      | <https://play.google.com/intl/en-GB_ALL/about/monetization-ads/ads/interfering/> |
| Outside           | Huawei Market                                    | <http://developer.huawei.com/consumer/cn/devservice/doc/50104> |
| Frequent          | Google Admob                                     | https://support.google.com/admob#topic=2745287               |
| Frequent          | OPPO App Market                                  | <https://open.oppomobile.com/wiki/index#id=73486>            |
| Frequent          | Xiaomi App Market                                | <https://dev.mi.com/console/doc/detail?pId=879>              |
| Frequent          | Huawei Market                                    | <http://developer.huawei.com/consumer/cn/devservice/doc/50104> |
| Non-content       | Google Admob                                     | <https://support.google.com/admob#topic=2745287>             |
| Non-content       | Google Play                                      | <https://play.google.com/intl/en-GB_ALL/about/monetization-ads/ads/interfering/> |

## Precision/Recall by fraud type ##

| Ad Fraud   Name        | True Positive(TP) | False Positive(FP) | True Negative(TN) | False Negative(FN) | Precision | Recall |
| ---------------------- | ----------------- | ------------------ | ----------------- | ------------------ | --------- | ------ |
| #1   Hidden            | 2                 | 2                  | 96                | 0                  | 50%       | 100%   |
| #2 Size                | 3                 | 0                  | 97                | 0                  | 100%      | 100%   |
| #3   Number            | 2                 | 0                  | 98                | 0                  | 100%      | 100%   |
| #4   Overlap           | 1                 | 1                  | 97                | 1                  | 50%       | 50%    |
| #5   Interaction       | 5                 | 0                  | 95                | 0                  | 100%      | 100%   |
| #6   Drive-by download | 30                | 0                  | 67                | 3                  | 100%      | 90.91% |
| #7   Outside           | 2                 | 0                  | 98                | 0                  | 100%      | 100%   |
| #8   Frequent          | 2                 | 0                  | 98                | 0                  | 100%      | 100%   |
| #9   Non-content       | 3                 | 0                  | 97                | 0                  | 100%      | 100%   |
| Total                  | 46                | 3                  | 47                | 4                  | 93.88%    | 92%    |