pipeline {
    agent any
    environment {
        
       
         PATH = "/usr/local/bin:$PATH"
        JAVA_HOME = '/opt/usr/lib/jvm/java-openjdk'
    }
    stages {
        stage('Build') {
            steps {
               sh "${mvnCMD} clean package"
                echo 'Hello world!'
                
            }
        }
    }
}
