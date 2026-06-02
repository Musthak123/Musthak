pipeline {
    agent any

    stages {
        stage('Execute External Script') {
            steps {
                script {
                    def externalScript = load 'newfile.groovy'
                    externalScript.executeMessage()
                }
            }
        }
    }
}
