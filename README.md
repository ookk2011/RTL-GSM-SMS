# gsmsms_sdr
使用sdr嗅探gsm短信

## 环境
- ubuntu 16.04

## 安装依赖
- apt-get install python-mysqldb

## 文件列表
- sms_forward.py: 转发sdr来的数据。
- gsmsms_sniff.py:解码和显示短信内容。
- gsmsms_sniff_mysql.py:解码和显示短信内容,并存入sql数据库。
- sms.sql
