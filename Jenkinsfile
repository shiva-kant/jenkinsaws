pipeline {
    agent none
    stages {
        stage('test') {
            agent{label 'L1'}
            steps {
                echo 'Testing'
            }
        }
        stage('build') {
            agent{label 'L2'}
            steps {
                echo 'Building'
            }
        }
        stage('Deploye') {
            agent{label 'L1'}
            steps {
                echo 'Deploying'
            }
        }
        stage('run') {
            agent{label 'L2'}
            steps {
                echo 'running'
            }
        }
    }
}
