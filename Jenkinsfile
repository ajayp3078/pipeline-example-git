pipeline{
    agent any

    stages{
        stage("compile"){
            steps{
                bat 'javac Test.java'
            }
        }
        stage("run"){
            steps{
                bat 'java Test'
            }
        }
    }
    post{
        always{
            bat 'echo "always"'
        }
        success{
            bat 'echo "success"'
        }
        failure{
            bat 'echo "failure"'
        }
    }

}