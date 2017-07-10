node {
   stage('Preparation') {
      git 'https://github.com/priscillaboyd/SimpleWebApp.git'
   }
   stage('Build') {
      sh "./gradlew clean test"
   }
}