# Traefik部署
- ingress-deployment配置说明
> kubernetes.endpoint 参数可以指定traefik与apiserver交互时是使用http还是https
- 自定义头信息
> metadata-annotations

`ingress.kubernetes.io/custom-request-headers: "X-Full-Uri:https://www.baidu.com"`
