
pipeline {
    parameters {
    choice(name: 'CHOICE', choices: ['One', 'Two', 'Three'], description: 'Pick something')
            }
    environment {
        BRANCH  = 'main'
        GIT_URL = 'https://github.com/MadhusudhanShetty/testJenkinsM.git'
    }
    agent any 
    stages {
        stage('Stage1') { 
            steps {
                sh'''
                ls -lrth
                ''' 
            }
        }
        stage('Stage2') { 
            steps {
                // 
            }
        }
        stage('Stage3') { 
            steps {
                // 
            }
        }
        stage('Stage4') { 
            steps {
                // 
            }
        }
    }
}