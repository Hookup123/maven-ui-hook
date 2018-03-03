node {
    environment {
    JAVA_HOME=/usr/lib/jvm/java-8-openjdk-amd64/"
    PATH =/opt/maven/bin:$PATH
  }
    stage('Git Checkout') { // for display purposes
     echo 'Checout Code and clone it inside jenkins workspace..'
     git 'https://github.com/Cenovus123/maven-ui-hook.git'
     checkout scm
   }
   stage('Build Test & Package') {
      echo 'Build the package'
       sh 'echo "$PATH = ${PATH}"'
       sh 'echo "$M2_HOME = ${M2_HOME}"'
       echo "PATH is: $PATH"
   }
   }
