Создание каталогов:
```bash
mkdir -p MySurname/practice_1/catalog1
mkdir -p MySurname/practice_1/catalog2/catalog3
```

Создание файлов:

```bash
echo "MySurname $(date)" > MySurname/practice_1/file1
cd MySurname/practice_1/catalog2
touch file2 file3
man less > catalog3/file4
```

Создание ссылок:

```bash
ln MySurname/practice_1/file1 file1_link
ln -d catalog2 catalog2_link   # жесткая ссылка на каталог
ln -s catalog3/file4 s_link    # символическая ссылка
```

Просмотр структуры каталогов:

```bash
tree -a MySurname/practice_1
yaml
```


Копировать код
