node {
    stage('Git Checkout') { // for display purposes
     echo 'Checout Code and clone it inside jenkins workspace..'
     git 'https://github.com/manee2k6/DeepriRepo.git'
      checkout scm
   }
   stage('Build Test & Package') {
      echo 'Build the package'
      echo 'this will run now'
      sh 'mvn clean compile package'
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
