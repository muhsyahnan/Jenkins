pipeline {
    agent {
        node {
            label "Windows && Java11"
        }
    }
    stages {
        stage ("Hello"){
            steps {
                echo("Hello Pipeline")
            }
        }
    }

    post {
        always {
            echo "I Will always say Hello Agai!"
        }
        succes{
            echo "yay, secces"
        }
        failure {
            echo "oh o, failure"
        }
        cleanup {
            echo "don't care succes or error"
        }
    }
    
}