pipeline {
    agent any

    stages {
        stage ('Compile Stage') {

            steps {
                sh 'echo "Hello World MS"'
                sh 'echo "Variables: "'
                sh 'echo $GIT_URL'
                sh 'echo $CHAANG_ID'
                sh 'echo $JOB_BASE_NAME'
                sh 'echo $BUILD_TAG'
                sh 'echo $GIT_URL'
                sh 'echo $MERCURIAL_REVISION'
                sh 'echo $SVN_REVISION'
                sh 'echo $CHANGE_AUTHOR'
                sh 'echo $CHANGE_TARGET'
                sh 'echo $BUILD_NUMBER'
                sh 'eccho "--- end ---"'
            }
        }
    }
}
