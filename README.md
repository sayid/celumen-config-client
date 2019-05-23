# lumen-config-client
本项目为基于spring cloud config公共配置中心的php客户端，lumen框架中引入composer包后，启动Swoole服务即可使用

1、在.env中配置
```
CONFIG_HOST=http://config.service.gouuse.cn:38080
CONFIG_FILE=zqdl-scrm-dev.yml
```
2、在代码中使用GEnv($key, $default)获取配置内容
