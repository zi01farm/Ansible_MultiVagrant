This is a file describing the usage for the Multi_Vagrant Ansible app.

No extra configuration is needed, all you need to do is:
1. download the files in this repo and put into a folder
2. go into your folder using Git for Windows (GitBash) (may need to run as Administrator)
3. type the command "vagrant up"

after a few minutes of set up you should finally get a message telling you that the app is running.

you can access the app page with the URL "/development.local"
you can access the posts for the app with the url "/development.local/posts"

to stop the app follow these steps:
1. press Ctrl+C in your git where the app is running
2. type "vagrant ssh app" to enter the virtual machine
3. when inside the virtual machine type "kill -9 -1", this should kill the app process and
automatically take you out of the virtual machine
4. then type "vagrant destroy -f" to remove the virtual machines