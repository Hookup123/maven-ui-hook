node {
    stage('Git Checkout') { // for display purposes
     echo 'Checout Code and clone it inside jenkins workspace..'
     git 'https://github.com/Cenovus123/maven-ui-hook.git'
     checkout scm
   }
   stage('Build Test & Package') {
      echo 'Build the package'
       sh 'echo "$PATH = ${PATH}"'
       sh 'echo "$M2_HOME = ${M2_HOME}"'
       sh 'mvn clean install'
   }
   }
