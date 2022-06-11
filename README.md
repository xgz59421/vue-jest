## vue jest
[![codecov](https://codecov.io/gh/xgz59421/vue-jest/branch/main/graph/badge.svg?token=ZH46IKP2Q0)](https://codecov.io/gh/xgz59421/vue-jest)

#### test:unit
npm run test:unit
开发时: 
vue-cli-service test:unit -- --watch

#### 代码覆盖率统计
```js
1. 然后安装 Codecov
npm i -g codecov

2. 生成测试覆盖率报告
npm run coverage
进入到 https://app.codecov.io/gh
https://app.codecov.io/gh/xgz59421/notes-web/new
复制 Codecov Token=
7f532ae1-9451-42b3-9064-833ae8c5bbcf

3. 运行项目安装的 codecov 上传报告
npx codecov --token=7f532ae1-9451-42b3-9064-833ae8c5bbcf
codecov --token=7f532ae1-9451-42b3-9064-833ae8c5bbcf
4. 重新查看 Codecov 可以看到报告分析
https://app.codecov.io/analytics/gh/xgz59421 -->Analytics

5. codecov 徽章
https://app.codecov.io/gh/xgz59421/notes-web
Settings --> Badge 
README.md 中可以展示 codecov 徽章
显示测试覆盖率，可以让其他开发者了解应用是否安全可靠
```

#### 自动化测试和持续集成
```
可供选择的持续集成工具有 Gitlab CI、 Travis CI 、 Circle CI、GitHub Actions 等
本项目使用 Github Actions 实现持续集成

配置 Github Actions
项目根目录新建目录和文件 .github/workflows/main.yml：
最后，将所有修改提交到远程仓库的 master 分支上，就可以看到 GitHub Actions 正在自动构建

 git代码变更提交后, https://github.com/xgz59421/vue-jest/actions中查看构建过程
展示 GitHub Actions 徽章


```


https://app.codecov.io/gh/xgz59421/vue-jest/new
token: 4c3746f4-ca56-4449-a6cd-5765bf4ce0f8