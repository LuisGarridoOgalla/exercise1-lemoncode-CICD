pipeline{
    agent any
    stages{
        stage('Compile'){   
            steps{
                
             sh '''
                ./gradlew compileJava'''
            }
        }
        stage('Unit Test'){
            steps{
                
                sh '''
                chmod +x gradlew
                ./gradlew test'''
            }
        }
    
    }
}
