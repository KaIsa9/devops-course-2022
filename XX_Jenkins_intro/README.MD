#Jenkins part 1
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
6. 