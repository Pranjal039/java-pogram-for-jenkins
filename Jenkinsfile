pipeline{

    agent any

    stages{
        
        stage("compile"){
            steps{
                 sh "javac main.java"
            }
           
        
        }

         stage("run"){

            steps{
                sh "java main"
            }
        
        }
    }
}