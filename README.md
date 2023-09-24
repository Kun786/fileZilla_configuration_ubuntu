# fileZilla_configuration_ubuntu
fileZilla_configuration_ubuntu

##It works for ssh-key ED25519 or Idrsa or any type 
### Steps:
1 key-gen ssh-keygen -t ed25519 -C "fileZilla" (pwd: ~./ssh/yourKey)

2 Open File Zilla

3 create new-site   file>site-manager>new site

4 Make sure you are in general tab then change protocol to SFTP

5 Add Host

6 Add port (default 22)

7 LogonType (select interractive)

8 User add user name (default root)

9 Press ok button and your site is saved


![image](https://github.com/Kun786/fileZilla_configuration_ubuntu/assets/12573912/109195a2-73fa-4c9a-8085-1bcfd4d74100)


10 go to edit>settings

11 Connection>SFTP

12 Add key and browse to the key location and select it

13 Ok to save settings

14 now connect your site and you have connected Hurray !!!!
