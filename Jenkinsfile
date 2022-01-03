pipeline {
    agent any

    stages {
        stage('Hello') {
            steps {
                sh " curl -O -H 'Authorization: Bearer eyJtopkToken' 'https://jotain.io/yoo.tar.gz'"
                sh "md5sum yoo.tar.gz"
            }
        }
    }
}
