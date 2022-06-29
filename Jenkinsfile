pipeline {
    agent none
    stages {
        stage('build') {
            agent{label 'L1'}
            steps {
                echo 'Building'
            }
        }
        stage('deploy') {
            agent{label 'L2'}
            steps {
                echo 'Deployinh'
            }
        }
    }
}
