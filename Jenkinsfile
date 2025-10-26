pipeline {
    agent { label 'java' }
    stages {
        stage('Build') {
            steps {
                sh 'mvn clean install -DskipTests -Dcheck.skip-rat=true'
            }
        }
    }
}
