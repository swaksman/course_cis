- hosts: localhost
  tasks:
  - name: install git
    yum: name=git state=latest
    become: yes
    become_method: sudo
  - name: clone petclinic
    git: repo=https://github.com/shimib/spring-petclinic.git dest=~/spring-petclinic
  - name: clone course
    git: repo=https://github.com/shimib/course_cis.git dest=~/course
