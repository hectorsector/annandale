pipeline {
    agent any 
    stages {
        stage ('Install dependencies') {
            withRvm('ruby-2.3.1') {
                sh 'gem install bundler'
                sh 'bundle install'
            }
        }
    }
}