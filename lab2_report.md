University: ITMO University  
Faculty: FTMI  
Course: Введение в веб технологии  
Year: 2026/2027  
Group: U4225  
Author: Soldatov Egor  
Lab: Lab2

**1. Подготовка проекта и настройка GitHub Actions**
В репозитории созданы файлы: app.py, requirements.txt, Dockerfile, docker-build.yml  
<img width="561" height="1027" alt="image" src="https://github.com/user-attachments/assets/0eca340b-67d3-4eed-97e7-4b7b257c891a" />  
репозиторий запушен на GitHub  
<img width="788" height="359" alt="image" src="https://github.com/user-attachments/assets/4ce0e526-126d-4ed9-9e25-73eee2916ba5" />

Создан аккаунт в Docker Hub  
<img width="1920" height="832" alt="image" src="https://github.com/user-attachments/assets/063559ac-b79f-4512-83aa-99473d14f912" />

Создан репозиторий в Docker Hub  
<img width="1896" height="864" alt="image" src="https://github.com/user-attachments/assets/0131599e-4552-40e1-a4c6-7a3314105349" />

**2. Настройка секретов**  
Добавлены секреты с юзернеймом и паролем от Docker Hub  
<img width="1194" height="279" alt="image" src="https://github.com/user-attachments/assets/2532109e-8e80-45e4-851a-95f663f387d4" />

**3. Проверка пайплайна**
Пайплайн выполнен (наконец-то)  
<img width="1902" height="916" alt="image" src="https://github.com/user-attachments/assets/a80618f2-e96e-4ab4-9941-7bcaa8e1b257" />  
Docker Hub заменил заглавную букву в юзернейме на строчную, так что пришлось повозиться с секретом и файлом docker-build.yml

Образ есть на Docker Hub  
<img width="1896" height="904" alt="image" src="https://github.com/user-attachments/assets/506fbe89-a061-4941-ba01-8c7825ad0c8d" />  

После внесения изменений в app.py, коммита и пуша на GitHub Actions запустился новый пайплайн, а образ в Docker Hub обновился

**Вывод**  
В ходе лабораторной работы был настроен полноценный CI/CD пайплайн с использованием GitHub Actions и Docker Hub.
