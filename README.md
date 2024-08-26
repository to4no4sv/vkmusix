# VKMusix [![PyPI version](https://d25lcipzij17d.cloudfront.net/badge.svg?id=py&r=r&ts=1683906897&type=6e&v=3.3.1&x2=0)](https://pypi.org/project/vkmusix)

## Основные возможности

**• Интуитивно понятные названия функций, классов и атрибутов, а также подробная вложенная документация**

**• Работа с несколькими аккаунтами благодаря поддержке прокси.**

**• Получайте доступ к трекам в приватных плейлистах и музыке пользователей или групп через авторизацию в аккаунт.**

**• Лёгкий и простой поиск исполнителей, альбомов, треков, плейлистов и другого контента — всего, что нужно, в пару строк кода**

**• Доступ к текстам песен, прямым ссылкам на MP3 и обложкам в формате JPG для треков, альбомов и плейлистов**

**• Управляйте своей музыкальной коллекцией и музыкой сообществ: добавляйте или удаляйте треки, альбомы и плейлисты легко и быстро.**

**• Загрузите свои аудиофайлы на платформу за считанные секунды.**

**• Клонируйте альбомы и плейлисты других пользователей, создавая собственные плейлисты одной строчкой кода**

## Установка и обновление
```bash
pip install --upgrade vkmusix
```

## Быстрый старт
```python
from vkmusix import Client

client = Client()

result = client.searchArtists("prombl")
print(result)

client.close()
```
