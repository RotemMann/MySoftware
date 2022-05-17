properties([pipelineTriggers([cron('* * * * *')])])
pipeline {
    
    agent any

    stages {
        stage('stage1') {
            steps {
                bat '''
                     dir
                     python py1b.py
                     python py1s.py
                    ''' 
            }
        }
    }
}
