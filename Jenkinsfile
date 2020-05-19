pipeline {
    agent {
        docker {
            image 'centos'
            any
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
} //pipeline
