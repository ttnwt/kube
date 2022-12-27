pipeline {

        agent any
        // tools 'Terraform'

        stages {
        
            stage('Checkout') {
                steps {
                    git branch: 'main', credentialsId: 'me', url: 'https://github.com/ttnwt/kube.git'
                }
            }
            stage ("Deploy") {
                steps {
                    sh 
                }
            }
            
       }
}
