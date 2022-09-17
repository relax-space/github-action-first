# github-ci

## 知识点

1. [不同job之间传值](./docs/value.yml)
2. 不同的触发点

``` yml
on:
  workflow_dispatch:
    branches: [main]

on:
  push:
    branches: [ master ]
  pull_request:
    branches: [ master ]

on:
  schedule:
    - cron: '30 1 * * *'
```

## 常用git命令

测试`github ci`的时候用

``` bash
git add .
git commit --amend --no-edit
git push origin main -f

```

## 引用

https://github.com/marketplace?type=actions&query=python+

https://docs.github.com/cn/actions/quickstart