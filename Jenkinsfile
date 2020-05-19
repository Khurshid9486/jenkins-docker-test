pipeline {
    agent any
        docker {
            image 'centos'
        } //docker
    } //agent
    stages {
        stage("Check hostname of docker container") {
            steps {
                sh """
                    cat /etc/hostname
                """
            } //steps
        } //stage
    } //stages
//pipeline
