pipeline{
    agent any

    stages{
        stage("compile"){
            bat 'javac Test.java'
        }
        stage("run"){
            bat 'java Test'
        }
    }

}