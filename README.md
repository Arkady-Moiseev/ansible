# Первые шаги с Ansible

Подготовить стенд на Vagrant. Используя Ansible необходимо развернуть nginx со следующими условиями:
- необходимо использовать модуль yum/apt
- конфигурационные файлы должны быть взяты из шаблона jinja2 с переменными
- после установки nginx должен быть в режиме enabled в systemd
- должен быть использован notify для старта nginx после установки
- сайт должен слушать на нестандартном порту - 8080, для этого использовать переменные в Ansible
---

![img_1](https://github.com/Arkady1996/ansible/blob/main/images/1.png)

![img_2](https://github.com/Arkady1996/ansible/blob/main/images/2.png)

![img_3](https://github.com/Arkady1996/ansible/blob/main/images/3.png)

![img_4](https://github.com/Arkady1996/ansible/blob/main/images/4.png)

![img_5](https://github.com/Arkady1996/ansible/blob/main/images/5.png)

![img_6](https://github.com/Arkady1996/ansible/blob/main/images/6.png)
