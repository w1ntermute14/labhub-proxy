# LabHub Proxy API

## 📌 Описание

Этот проект реализует HTTP API-прокси на языке Go. Он принимает GET-запрос с параметрами лабораторных данных, преобразует их в JSON и отправляет POST-запрос в ML API, который возвращает предсказанный уровень HbA1c.

## 🚀 Как запустить

1. Установите Go: https://go.dev/doc/install
2. Склонируйте репозиторий:
   ```bash
   git clone https://github.com/ВАШ-ЛОГИН/labhub-proxy.git
   cd labhub-proxy
3. Запустите сервер:go run main.go
