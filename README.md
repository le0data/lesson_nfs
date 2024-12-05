# Стенд
2 хоста в Yandex.Cloud:

Под NFS сервер используется:
* OS - Ubuntu 24.01;
* Платформа - Intel Ice Lake
* ​vCPU - 2
* RAM - 2 ГБ
* HDD - 27 Гб (система на 20 Гб-ом диске)
![Server NFS](https://github.com/user-attachments/assets/733c0a42-8185-49b6-89b8-650c323dd58c)

Под NFS клиент используется:
* OS - Ubuntu 24.01;
* Платформа - Intel Ice Lake
* ​vCPU - 1
* RAM - 2 ГБ
* HDD - 20 Гб
  
 ![Client NFS](https://github.com/user-attachments/assets/2a4637f9-7e76-4706-87c5-85e6dc9f1c33)

# Выполненные работы
Были написаны 2 плейбука 1 для сервера, 2 для клиента.

Так же применен шаблон .j2 для передачи актуальных IP-адресов.

Результат выполнения на сервере:

![Result_server_nfs](https://github.com/user-attachments/assets/9bf363e1-b556-409a-bb7c-0c47ff3664ed)


Результат выполнения на клиенте:


![Result_client_nfs](https://github.com/user-attachments/assets/0c5b18f9-832b-4375-8867-3c92b50c7ebf)
