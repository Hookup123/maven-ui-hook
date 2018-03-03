node {
    stage('Git Checkout') { // for display purposes
     echo 'Checout Code and clone it inside jenkins workspace..'
     git 'https://github.com/Cenovus123/maven-ui-hook.git'
     checkout scm
   }
   tools{
        maven 'maven 3.5'
        jdk 'jdk1.8'
        }
   }
