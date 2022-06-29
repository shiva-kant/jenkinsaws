pipeline {
    agent none
    stages {
        stage('seq') {
            agent{label 'L1'}
            steps {
                echo 'Testing'
            }
        }
        stage('parallel') {
            parallel{
                stage('V1')   {
                     agent{label 'L2'}
                    steps{
                    
                    echo 'Hello';
                    }
            }
                stage('V2'){
                     agent{label 'L2'}
                    steps{
                    
                    echo 'V2';
                    }
                    
                }
        }
    }
}
    
    
}
