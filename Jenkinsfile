pipeline {
    agent any

    stages {
        stage('test trigger') {
            steps {
                echo 'github push'
            }
        }
        /*
        stage('wxWidgets') {
            steps {
                sh script: '''
                #!/bin/bash
                cd wxWidgets
                mkdir buildgtk
                cd buildgtk
                echo cmake --version
                ../configure --with-cxx=14 --with-gtk=2
                sudo make install
                cd ../../
                '''
            }
        }
        
        
        stage('audacity') {
            steps {
                sh script: '''
                #!/bin/bash
                cd audacity
                
                cd build
                
                '''
            }
        }
        */
        /*
        stage('test build') {
            steps {
                sh script: '''
                #!/bin/bash
                cd audacity/build/bin/Release
                pwd
                '''
            }
        }
        stage('install audacity') {
            steps {
                sh script: '''
                #!/bin/bash
                cd audacity/build
                pwd
                
                '''
            }
        }
        */
    }
}
