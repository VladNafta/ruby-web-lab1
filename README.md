# laba_1 — Лабораторна робота №1 з дисципліни «Мови програмування для web»

Тема: встановлення інтерпретатора Ruby та сервера Ruby on Rails.
Виконав: Мельник В.Я., ІП-23-2.

## Середовище
- Ubuntu 24.04.5 LTS у віртуальній машині VirtualBox 7.1, RVM 1.29.12-next (master)
- Ruby 3.4.9, Rails 8.1.4, Node.js 24.21.0

## Запуск
```bash
cd laba_1
bundle install
bin/rails s
```
Сторінка «Hello, Rails!» доступна за адресами http://localhost:3000/ та http://localhost:3000/welcome/index.

## Що зроблено
- `rails new laba_1` — створено проєкт;
- `rails generate controller Welcome index` — контролер і представлення;
- `app/views/welcome/index.html.erb` — заголовок `<h1>Hello, Rails!</h1>`;
- `config/routes.rb` — додано кореневий маршрут `root "welcome#index"`.
