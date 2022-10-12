pipeline {
    agent any
properties([buildDiscarder(logRotator(artifactDaysToKeepStr: '', artifactNumToKeepStr: '', daysToKeepStr: '3', numToKeepStr: '5')), disableConcurrentBuilds(), gitLabConnection(gitLabConnection: 'https://github.com/udi1990/terrraform-eks', jobCredentialId: '')])        stage('Hello1') {
            steps {
               sh '''
            ls
            pwd
            touch udibato
            mkdir evral
               '''
            }
        }
    
    stage('Hello2') {
            steps {
                sh '''
                uname -r
                '''
            }
        }
    
    
    stage('Hello3') {
            steps {
                sh '''
                ls -l
                nproc
                '''
            }
        }
    
    
    
    }


}
