pipeline {
    agent { docker { image 'golang' } }
    stages {
        stage('build') {
            steps {
                 bash '''#!/bin/bash
                        sleep 10
                        echo "cla 0"
                 '''
            }
        }
        stage('Setting the variables values') {
            steps {
                 bash '''#!/bin/bash
                        sleep 10
                        echo "bla blup 1"
                 '''
            }
        }
    }
}
