pipeline{
    agent any
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
