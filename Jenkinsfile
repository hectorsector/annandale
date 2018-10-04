pipeline {
    agent any 
    stages {
        stage('Build') { 
            steps {
                gem install bundler
                bundle install
                bundle exec jekyll build
            }
        }
        stage('Test') { 
            steps {
                // 
            }
        }
        stage('Deploy') { 
            steps {
                // 
            }
        }
    }
}