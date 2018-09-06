
pipeline {
   agent any

   stages {
     stage('Git Checkout'){
        steps {
            git branch: 'feature/Build-Pipeline-Codes', credentialsId: '1e5c15e0-5802-4d49-9991-523e20c40702', url: 'https://gitlab.adelaide.edu.au/integration/spring-boot-examples/spring-boot-camel-helloworld.git'
        }
     }
     stage('Build') {
        steps {
           echo 'Building this project....'
          
        }
     }
   }
}
