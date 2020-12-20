library identifier: 'pipeline-library-demo@master',
    //'master' refers to a valid git-ref
    //'mylibraryname' can be any name you like
    retriever: modernSCM([
      $class: 'GitSCMSource',
      credentialsId: '	c614bc89-ea95-485c-a53d-ad5bbf4b73b7',
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
