pipeline {
    agent {
        docker {
            image 'ruby' 
        }
    }
    stages {
        stage('Build') { 
            steps {
                sh 'gem install bundler'
                sh 'bundle install' 
            }
        }
    }
}