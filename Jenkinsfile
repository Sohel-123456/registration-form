pipeline {
    agent any

    stages {
        stage('deploy') {
            steps {
                publishHTML([allowMissing: false, alwaysLinkToLastBuild: false, icon: '', keepAll: false, reportDir: 'https://github.com/Sohel-123456/registration-form.git', reportFiles: 'registration-form.html', reportName: 'HTML Report', reportTitles: '', useWrapperFileDirectly: true])
            }
        }
    }
}
