# github-ci

## 知识点

1. [不同job之间传值](./docs/value.yml)

## 常用git命令

测试`github ci`的时候用

``` bash
git tag -d v1
git push origin :refs/tags/v1

git add .
git commit --amend --no-edit
git push origin main -f

git tag v1
git push origin v1


```