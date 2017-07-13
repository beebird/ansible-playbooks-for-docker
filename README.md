ansible-playbooks-for-docker

Deploy ``docker-ce`` and ``kernel-ml`` on CentOS with Ansible



The default Linux kernels shipped with CentOS distributions are usually a bit old and don't support some new docker feature unless we upgrade the kernel to ``kernel-ml``. Besides, the latest docker binary has been moved to ``docker-ce`` which is maintained in another Yum repository. 

So the playbook and roles are created to automate the procedure.

