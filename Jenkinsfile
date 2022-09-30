pipeline{
    agent any
    stages{
        stage('Compile'){   
            steps{
                
             sh '''
                chmod 755 gradlew
                gradle wrapper
                ./gradlew compileJava'''
            }
        }
    
    }
}
