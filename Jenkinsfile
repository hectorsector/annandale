stage ('Install dependencies') {
    node {
        withRvm('ruby-2.3.1') {
            sh 'gem install bundler'
            sh 'bundle install'
        }
    }
}