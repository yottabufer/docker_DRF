## О данном проекте 
* Показать умение работать с Docker и Celery+Redis


### Запуск
1. Клонируем проект с репозитория
```python
https://github.com/yottabufer/docker_DRF.git
```
2. Переходим в папку созданную папку
```python
cd docker_DRF
```
3. Создаём билд проекта
```python
docker-compose build
```
4. Создаём и применяем миграции 
```python
docker-compose run --rm web-app sh -c 'python manage.py makemigrations'
```
```python
docker-compose run --rm web-app sh -c 'python manage.py migrate'
```
5. Поднимаем docker
```python
docker-compose up
```
