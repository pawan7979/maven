pipeline {
   
       agent any
       
    stages {
        stage('SCM') {
            steps {
                git 'https://github.com/Kumarbgm16/maven.git'
               
            }
           
        }
       
        stage('Build by Maven Package') {
            steps {
                sh 'mvn clean package'
            }
           
        }
    }
   
}
