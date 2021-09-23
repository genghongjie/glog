# glog
- logrus
- 简单log组件，使用简单
- 日志文件分割，以json格式记录日志


## 使用方法

- 初始化

```go
//默认初始化 日志路径为 ./logs ,日志名称为 app.log
glog.Init(nil)
```

```go
//制定路径与文件名
glog.Init(&log.Config{LogSavePath: "log path", LogSaveName: "log name"})
```

- 使用方法
```go
glog.Info("Test log init success")
glog.Infof("%s 载人登月成功", "中国")
glog.Warn("Test log init success")
glog.Warnf("%s 载人登月成功", "中国")
glog.Debug("Test log init success")
glog.Debugf("%s 载人登月成功", "中国")
```# glog
