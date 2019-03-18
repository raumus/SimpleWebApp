node {
   stage('Preparation') {
      git 'https://github.com/raumus/SimpleWebApp.git'
   }
   stage('Build') {
      sh "./gradlew clean test"
   }
}