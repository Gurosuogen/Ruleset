# Providers

Clash Providers 专用

- 模板
```yamal
  Ruleset_:
    type: http
    behavior: classical
    path: ./rule/Ruleset_.yaml
    url: ""
    interval: 86400
```

- 使用 jsDiliver 加速国内访问
https://cdn.jsdelivr.net/gh/Gurosuogen/Ruleset@master/Providers/xxx.yaml

- 强制刷新缓存
https://purge.jsdelivr.net/gh/Gurosuogen/Ruleset@master/Providers/xxx.yaml

页面返回 json 中状态 status 为 finished 即为刷新缓存成功
