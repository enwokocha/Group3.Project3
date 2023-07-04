pipeline {
    agent any

    stages {
        stage('Nwokocha') {
            steps {
                echo "Executing ps -ef"
                sh "ps -ef"
                echo "Executing sudo systemctl status Jenkins"
                sh "sudo systemctl status jenkins"
            }
        }
        
        // Repeat the above 'stage' block for each member
        
        // stage('Member N') {
        //     steps {
        //         echo "Executing ps -ef"
        //         sh "ps -ef"
        //         echo "Executing sudo systemctl status Jenkins"
        //         sh "sudo systemctl status jenkins"
        //     }
        // }
    }
}
