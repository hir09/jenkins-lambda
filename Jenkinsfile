pipeline {
    agent any
    environment {
        
        PATH ='/bin/mvn'
        //PATH = "/usr/local/bin:$PATH"
        JAVA_HOME = '/opt/usr/lib/jvm/java-openjdk'
    }
    stages {
        stage('Build') {
            steps {
                sh 'git clone https://https://github.com/hir09/jenkins-lambda.git'
                echo 'Hello world!'
                sh 'mvn -Duser.home=/tmp clean package'
            }
        }
    }
}
