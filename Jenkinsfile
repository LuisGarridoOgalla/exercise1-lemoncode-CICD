pipeline{
    agent any
    stages{
        stage('Compile'){   
            steps{
                
             sh '''
                chmod +x gradlew
                ./gradlew compileJava'''
            }
        }
        stage('Unit Test'){
            steps{
                
                sh '''
                chmod +x gradlew
                ./gradlew test
                '''
            }
        }
    
    }
}
