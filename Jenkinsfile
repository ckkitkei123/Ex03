library identifier: 'pipeline-library-demo@master',
    //'master' refers to a valid git-ref
    //'mylibraryname' can be any name you like
    retriever: modernSCM([
      $class: 'GitSCMSource',
      credentialsId: 'ckkitkei123',
      remote: 'https://github.com/ckkitkei123/pipeline-library-demo'
])

pipeline {
    agent any
    stages {
        stage('Demo') {
            steps {
                echo 'Hello world'
                sayHello 'Dave'
            }
        }
    }
}
