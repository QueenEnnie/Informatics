## Отчет по лабораторной работе №1

1. Создаем новый файл `script.bash`

```bash
touch script.bash
```
![1](https://github.com/user-attachments/assets/12b6681f-3285-412f-8044-e581c8654656)

2. Открываем созданный нами файл с помощью `gedit`

```bash
gedit script.bash
```
![2](https://github.com/user-attachments/assets/cd2df576-efa9-4cb8-b59f-cb18a93acbad)

У нас появляется следующее окно:

![3](https://github.com/user-attachments/assets/772b5ee6-34c9-4b16-8e84-e87782a1a651)

3. Мы вписываем в файл это скрипт:

```bash
#!/bin/bash

echo "Welcome to ITMO University"
```

![4](https://github.com/user-attachments/assets/ba55a278-eb6d-403b-9c9a-d27140ff20a3)

4. Сохраняем файл, закрываем `gedit` и запускаем bash-скрипт в терминале:

```bash
bash script.bash
```

![5](https://github.com/user-attachments/assets/66eed10a-d42b-48ff-b331-6b1aa3934f41)

5. Снова открываем файл и изменяем его, чтобы от соответствовал поставленной задаче:

```bash
#!/bin/bash

echo "Welcome, $@"
```

![6](https://github.com/user-attachments/assets/319ebeb6-9b76-420e-8ac7-4fedf768c420)

Используем "$@", чтобы получить все переменные

6. Запустим bash-скрипт в терминале и посмотрим на результат:

![7](https://github.com/user-attachments/assets/1dbce0db-b1d6-4124-b67a-c956d26302cb)

7. Запустим скрипт для более сложного имени:

![8](https://github.com/user-attachments/assets/629072cf-aa47-42e0-a26f-2b31d7a32263)
