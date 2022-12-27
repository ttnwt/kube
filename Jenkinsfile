pipeline {

        agent any
        // tools 'Terraform'

        stages {
        
            stage('Checkout') {
                steps {
                    git branch: 'main', credentialsId: 'kuber', url: 'https://github.com/ttnwt/kube.git'
                }
            }
            stage ("Deploy") {
                steps {
                    sh 
                }
            }
            
       }
}
