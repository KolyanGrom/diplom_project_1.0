# Отчет по итогам тестирования

## Описание

Реализовано автоматизированное тестирование функциональности "покупка тура", в соответствии
с [планом тестирования](https://github.com/KolyanGrom/diplom_project_1.0/blob/main/documents/Plan.md).

***Общее количество тестов:*** 80.

## Итоги тестирования

### При подключении к СУБД PostgreSQL

- Passed test 80%
- Failed test 20%

![Screenshot_176](https://github.com/KolyanGrom/diplom_project_1.0/assets/154681009/bb95ed90-3691-4119-a1a4-baa9b9afd71a)
![Screenshot_177](https://github.com/KolyanGrom/diplom_project_1.0/assets/154681009/5125ca13-d9d4-4a47-a5f9-b8950209a151)
![Screenshot_178](https://github.com/KolyanGrom/diplom_project_1.0/assets/154681009/865a80d2-2ab4-4c8b-beeb-85ea55040a10)
![Screenshot_179](https://github.com/KolyanGrom/diplom_project_1.0/assets/154681009/82251f9d-a1d1-4f70-8a6d-5d07dbe254e0)
![Screenshot_180](https://github.com/KolyanGrom/diplom_project_1.0/assets/154681009/461a1911-1eaa-47de-a03b-1f57eac5a8bc)

### При подключении к СУБД MySQL

- Passed test 80%
- Failed test 20%
![1](https://github.com/KolyanGrom/diplom_project_1.0/assets/154681009/7c071913-04e0-42c9-bb36-8963591a0fe5)
![2](https://github.com/KolyanGrom/diplom_project_1.0/assets/154681009/ea3508ca-0b82-4203-b57d-4a1d9f6fc0ae)
![3](https://github.com/KolyanGrom/diplom_project_1.0/assets/154681009/c238b88d-75b9-45c0-bfb4-77ef090f710f)
![4](https://github.com/KolyanGrom/diplom_project_1.0/assets/154681009/b60f08bb-8264-4396-99b2-823456931e74)
![5](https://github.com/KolyanGrom/diplom_project_1.0/assets/154681009/02d0ecf4-d674-4c03-8e5f-b0e6f01c75b3)

  На все обнаруженные дефекты заведены [баг-репорты](https://github.com/KolyanGrom/diplom_project_1.0/issues)

## Общие рекомендации

1. Добавить тестовые метки к html коду страницы, что добавит стабильности в будущих использованиях тестов.
2. Исправить найденные дефекты.
3. Выбрать только 1 СУБД для работы, так как на данный момент работа с 2 СУБД выполняет одинаковую задачу.
4. Добавить больше конкретизации в описании к требованиям по функционалу.
