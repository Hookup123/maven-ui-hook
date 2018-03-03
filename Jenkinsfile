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
 
    stages {
        stage ("initialize") {
            steps {
                    sh '''
                    echo "PATH = ${PATH}"
                    echo "M2_HOME = ${M2_HOME}"
                    '''
    }
   stage('Build Test & Package') {
      echo 'Build the package'
      echo 'mvn clean compile package'
   }
   stage('Results') {
       echo 'Test Results are reported..'
   
   }
   stage('Deploy to Dev'){
       echo 'Deploy to Dev environment'
   }
   stage('Deploy to Test'){
       echo 'Deploy to Test environment'
   }
      stage('Test Automation'){
       echo 'Deploy to Dev environment'
   }
   
}
