pipeline{
    agent any
    tools {
        maven 'localmaven'
        jdk 'jdk1.8'
    }
    stages{
        stage('build'){
            steps{
                echo "building a maven project"
                sh 'mvn compile'
                 }
        }
        
        stage('test'){
            steps{
                echo "testing the maven proj"
                sh 'mvn test'
                
                 }
        }
    }
}
