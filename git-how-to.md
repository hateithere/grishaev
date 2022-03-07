# Git HowTo

## Как создать ssh-ключ

```
ssh-keygen -t rsa -b 4096 -C "your_email@example.com"
```
Выбираем имя файла ключа и пароль для его защиты.

## Как добавить ключ в аккаунт Github

Открываем настройки аккаунта ->SSH and GPG keys->New SSH key
Копируем содержимое файла ~/.ssh/git_phystech.pub
Где git_phystech - имя файла файла, заданное на первом шагу.

## Как скопировать репозиторий

Открываем созданный репозиторий, находим там зеленую кнопку Code->SSH, берем оттуда ссылку.
```
git clone git@github.com:hateithere/grishaev.git
```
Репозиторий окажется в текущем каталоге в grishaev (в моем случае).
