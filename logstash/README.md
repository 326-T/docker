# Logstash

## 説明

- 言語を日本語に設定
- タイムゾーンを日本時間に設定
- postgresql のドライバをインストール

## 使い方

```bash
$ DOCKER_DEFAULT_PLATFORM=linux/amd64 docker build --tag=logstash_jp_jdbc:8.15.1 .
```
