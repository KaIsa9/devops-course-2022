# Alliedium DevOps course 2022
##Jenkins part 1
Prerequisites.

1. Linux (Manjaro)
2. Install Jenkins. [Instructions](https://www.geeksforgeeks.org/installing-and-configuring-jenkins-on-arch-based-linux-distributions-manjaro/)
   update and upgrade your system
    ''' sudo pacman -Syu'''
    install Java runtime environment
    ''' sudo pacman -S jdk17-openjdk'''
    set the default JRE version
    '''sudo archlinux-java set java-17-openjdk/jre'''
    '''sudo pacman -S jenkins'''
    '''sudo systemctl start jenkins'''
    '''sudo systemctl status jenkins'''
    '''sudo systemctl status jenkins'''
3. Navigate to http://localhost:8090. Find the default password in '''sudo cat /var/lib/jenkins/secrets/initialAdminPassword'''
4. Create admin user
5. Install suggested plugins
 
## Linux ubuntu
1. Clone project ansible-jenkins
2. Initiate submodules with ansible roles: 'git submodule init'
3. Run ansible playbook ansible ansible-playbook playbooks/install0jenkins-plugins.yml -i ./inventory
4. Check that Jenkins is available al http://localhost:8090/ Your credentials are admin/admin 

## Add project to the Jenkins
