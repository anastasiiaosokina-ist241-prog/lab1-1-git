# Проєкт: Калькулятор та CI/CD Пайплайн
[![Python CI Application](https://github.com/anastasiiaosokina-ist241-prog/lab1-1-git/actions/workflows/python-app.yml/badge.svg)](https://github.com/anastasiiaosokina-ist241-prog/lab1-1-git/actions/workflows/python-app.yml)

## Опис проєкту
Навчальний проєкт для демонстрації роботи CI/CD пайплайну на базі GitHub Actions, лінтерингу вихідного коду за допомогою flake8 та запуску модульних тестів unittest.

## Функціонал
- Математичні операції додавання та віднімання
- Автоматизована перевірка якості коду за стандартом PEP8
- Модульне тестування функцій

## Запуск тестів локально
```bash
python -m unittest test_calculator.py
