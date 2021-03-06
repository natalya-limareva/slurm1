### Список практик

[1. Build](1.build/README.md)

[2. Test and cleanup](2.test_and_cleanup/README.md)

[3. Push](3.push/README.md)

[4.1 Prepare Cluster](4.deploy/4.1.prepare_cluster/README.md)

[4.2 Deploy](4.deploy/4.2.deploy/README.md)

### Все работы проводим под рутом на master-1

Подключение к master-1 производится с сервера `sbox.slurm.io`. Для подлключения к master-1 выполните команду, заменив `sXXXXXX` на номер своего студента:

```bash
ssh master-1.sXXXXXX
```

### Если ключ SSH еще не добавлен в Gitlab

> Добавляем свой публичный SSH ключ в Gitlab.
> Для этого заходим в gitlab.slurm.io
> В правом верхнем углу нажимаем на значок своей учетной записи.
> В выпадающем меню нажимаем Settings.
> Дальше в левом меню выбираем раздел SSH Keys
> И в поле key вставляем свой ПУБЛИЧНЫЙ SSH ключ.

### Форк проекта

> Открываем в браузере репозиторий xpaste. Он находится по адресу
```bash
https://gitlab.slurm.io/slurm/xpaste
```

> Справа на одной линии с названием проекта видим кнопку fork. Нажимаем ее.
> Выбираем в качестве нэймспэйса в следующем окне свой логин.
> И дожидаемся окончания процесса форка.
> Последним шагом клонируем получившийся форк к себе на админбокс.
```bash
git clone git@gitlab.slurm.io:s<номер своего логина>/xpaste.git
```
