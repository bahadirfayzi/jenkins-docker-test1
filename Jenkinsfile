pipeline {
    agent {
        docker {
            image 'python'
            
        } //docker
    } //agent
    stages {
        stage("Run Hello World") {
            steps {
                sh """
                    python helloworld.py
                """    
            } //steps
        } //stage
    } //stages
} //pipeline