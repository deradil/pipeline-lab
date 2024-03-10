pipeline {
    agent none
    stages {
        stage('Build') { 
            agent {label 'serverclientLinux'}
            steps {
                sh 'mvn -B -DskipTests clean package' 
            }
        }
    }
}
