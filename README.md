# scm-ansible
Software Configuration Management Tool  Ansible 
# Description about Repo  
For a devops engineer its very difficult remember  the sytanx and script of all tools in mind. so here I  have keep all my scripts that we are using in our regular projects. And also it will help to others, who facing the same issue 

# Basic Nots 
1) What and why  is ansible  ?
its a configuration management tools help to IT guy to automate the IT task for large number of server.
It is a push-based configuration tool. It helps to automate the entire IT infrastructure by providing large productivity gains. Ansible generally connects through SSH, remote PowerShell or via other remote APIs.

The IT tasks, that you control by ansible are   -
  - Regular activities like backup & restore, restart of server, logs collection and cleaning , security check , hotfixes & OS update. 
  - Upgrade the version of specific tools / prodction/ application / software. example like docker version, java version , web application version 
2) How its work in backend ? 
  - There is contoller machine, it may be a laptop or computer where IT guy sit and control the server through remotely. 
  - This IT guy  make a one time setup of ssh connectiity  between all server and the controller machine 
  - Once the stetup completed , the IT guy write a yaml script and mentioned all the above task that he required to be perfom in server

4)  What is  host inventory , roles, playbook, task, variable, modules, notify and handler 
  - host inventory : Register for group of host ips and names 
  - roles :  Group of playbook dedicated to specific unit like - project01 , project02 and more.. 
  - Playbook : collection of Task, that you want to perform  in specific group of  host 
  - variable : we store the value that we want in many task   
  - modules : Modules are the small program to perform specific task
  - notify : its a trigger  to activate the handler task. 
  - handler : its only run if  trigger changed the state mention in notify section
  
