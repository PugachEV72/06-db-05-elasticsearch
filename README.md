# Домашнее задание к занятию 5. «Elasticsearch» - Пугач Евгений.


---

## `Задание 1`

В ответе приведите:

- текст Dockerfile-манифеста,
- ссылку на образ в репозитории dockerhub,
- ответ Elasticsearch на запрос пути / в json-виде.

### Ответ:

`Текст Dockerfile-манифеста`

![Скриншот 1](https://github.com/PugachEV72/Images/blob/master/2023-07-18_23-57-15.png)

`Ход выполнения задания`

![Скриншот 2](https://github.com/PugachEV72/Images/blob/master/2023-07-19_00-20-44.png)

`Ссылка на образ в репозитории dockerhub`

https://hub.docker.com/repository/docker/pugachev72/my-es-image/general

`Ответ Elasticsearch на запрос пути / в json-виде`

![Скриншот 3](https://github.com/PugachEV72/Images/blob/master/2023-07-19_00-24-21.png)

---

## `Задание 2`

В ответе приведите:

- список индексов и их статусов,
- состояние кластера Elasticsearch,
- удаление индексов.

Объясните, почему часть индексов и кластер находятся в состоянии yellow?

### Ответ:

`Ход выполнения задания`

![Скриншот 4](https://github.com/PugachEV72/Images/blob/master/2023-07-19_00-35-25.png)

![Скриншот 5](https://github.com/PugachEV72/Images/blob/master/2023-07-19_00-37-11.png)

![Скриншот 6](https://github.com/PugachEV72/Images/blob/master/2023-07-19_00-42-38.png)

`Кластер и часть индексов находятся в состоянии yellow, так как нода одна и есть риск потери данных.`

---

## `Задание 3`

В ответе приведите:

- запрос API и результат вызова API для создания репозитория,
- список индексов, после создания индекса test,
- список файлов в директории со snapshot,
- список индексов, после удаления индекса test и создания индекса test-2,
- запрос к API восстановления и итоговый список индексов.

### Ответ:

`Ход выполнения задания`

![Скриншот 7](https://github.com/PugachEV72/Images/blob/master/2023-07-19_01-44-29.png)

![Скриншот 8](https://github.com/PugachEV72/Images/blob/master/2023-07-19_04-17-01.png)

---
