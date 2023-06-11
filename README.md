# Configure LAMP through Ansible

Requirement
====================================

1. Total 3 VM you need. One is for master & Two VM for worker
2. Choose centos9 image while creating VM
3. Document root : /home/myongraph/www
4. Create user: ongraph & home directory should be: /home/myongraph
5. Server name: devops.ongraph.com
6. Web server (Apache)
   should link to mysql 
( NOTE: If you want to run this playbook put woker's ip in inventory file & set your path in ansible.cfg file )
