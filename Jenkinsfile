pipeline {
    agent any

    stages {
        stage('One') {
            steps {
                echo 'Step 1'
                sleep 3
            }
        }
        stage('Two') {
            steps {
                echo 'Step 2'
                sleep 9
            }
        }   
        stage('Three') {
            steps {
                echo 'Step 3'
                sleep 5
                echo 'Step 3a'
                sleep 5
            }
        }          
    }
    post{
        always{
            echo 'This pipeline is completed.'
        }
    }
}
