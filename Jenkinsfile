def externalScript = load 'newfile.groovy'

pipeline {
    agent any

    stages {
        stage('Execute External Script') {
            steps {
                script {
                    externalScript.run()
                }
            }
        }
    }
}
