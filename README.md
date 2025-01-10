## 利用 Github Action 实现 Garmin CN 到 Global 的数据同步

1. 注册 Garmin 中国区和国际区账号；
2. Fork repository [GarminCN2Global](https://github.com/thekingofcool/GarminCN2Global), 将各自账号密码填入 Repository secrets:

```
GARMIN_GLOBAL_USERNAME
GARMIN_GLOBAL_PASSWORD
GARMIN_CN_USERNAME
GARMIN_CN_PASSWORD
SIZE
```
3. Actions 中点击 Run workflow，同步完成。

Follow my [Strava](https://www.strava.com/athletes/thekingofcool).
