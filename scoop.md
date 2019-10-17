# SCOOP
## 配布元
- https://scoop.sh/

## 概要
windows用パッケージマネージャ。主にlinuxも使っている開発者向けっぽい。
Windowsのお作法を無視して，ユーザーディレクトリ下にSCOOP本体やアプリをインストールするのでうっとうしいUACがでない。
kustomizeやk9sもインストールできる。Chocolateyよりよさげ。

## インストール
インストール前に環境変数SCOOP=d:\home\kamo\.scoopとしておくとscoop本体や各種アプリのインストール先を決められる。

## extras
```
scoop bucket add extras
```

## Java
```
scoop bucket add java
scoop install adopt8-hotspot
scoop install adopt11-hotspot

# 利用するjavaを変更したいときはreset
#scoop reset adopt11-hotspot
```
