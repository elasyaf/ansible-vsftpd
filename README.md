What is this ?
=========

Automation for vsftpd installation


How to use
=========

ansible-playbook (your playbook)


How does it work
=========

- Install vsftpd latest version
- Create new user for FTP login


To Remember
=========

* This ansible roles just support for Ubuntu / Debian ansible_distribution
* The user created on the roles goes to /usr/sbin/nologin. If you can not login into FTP with this user check this out:
  https://serverfault.com/questions/358324/ftp-doesnt-allow-usr-sbin-nologin-user
