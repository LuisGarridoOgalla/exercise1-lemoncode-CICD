pipeline{
    agent any
    stages{
        stage('Compile'){   
            steps{
                
             sh '''
                chmod 755 gradlew
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
