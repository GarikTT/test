script --timing=time_loading_lesson_log loading_lesson.log
scriptreplay --timing=time_loading_lesson_log loading_lesson.log -d 20
1. Запускаем два сервера.
2. Заходим - Vagrant up host1
3. Устанавливаем ansible:
	1. yum install epel-release -y
	2. yum install ansible -y
	3. ansible --version
	ansible 2.9.27
	config file = /etc/ansible/ansible.cfg
	configured module search path = [u'/root/.ansible/plugins/modules', u'/usr/share/ansible/plugins/modules']
	ansible python module location = /usr/lib/python2.7/site-packages/ansible
	executable location = /bin/ansible
	python version = 2.7.5 (default, Apr  2 2020, 13:16:51) [GCC 4.8.5 20150623 (Red Hat 4.8.5-39)]

ansible-galaxy init fail2ban
