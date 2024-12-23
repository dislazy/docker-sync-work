## 懒人版镜像同步页面
日常自用aliyun镜像仓库，所以镜像有需要将dockerhub的镜像同步到aliyun仓库的需求，所有有了这个仓库，`work.js`的大佬源码copy自[ali_dockerhub](https://github.com/zouzonghao/ali_dockerhub)项目。

## 本仓库ENV配置
```
- DOCKER_USERNAME  目标镜像仓库用户名
- DOCKER_PASSWORD  目标镜像仓库密码
```

## work.js的ENV配置
```
- GITHUB_TOKEN  // github的请求api权限token
- REPO_OWNER  //github用户名
- REPO_NAME  //github仓库名
- CHECK_TOKEN  //自己填充的token，防刷
```