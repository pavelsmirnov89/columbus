
# Bitrix
Файлы для битрикса

Установка .gitignore:
```
wget -O .gitignore https://raw.githubusercontent.com/MashinaMashina/Bitrix/master/gitignore
```

Чтобы закрыть доступ к папке в битрикс, зайдя в нее, пропишите в консоли:
```
wget https://raw.githubusercontent.com/MashinaMashina/Bitrix/master/.access.php
```

Хук с сообщением автора коммита
```
wget -P .git/hooks https://raw.githubusercontent.com/MashinaMashina/Bitrix/master/commit-msg && chmod +x .git/hooks/commit-msg
```

Хук с добавлением имени ветки в сообщение коммита
```
wget -P .git/hooks https://raw.githubusercontent.com/MashinaMashina/Bitrix/master/prepare-commit-msg && chmod +x .git/hooks/prepare-commit-msg
```

[Настройка git в Битрикс](https://r-morozov.ru/bitrix/nastrojka-git-gitignore-dlya-bitriks/)
