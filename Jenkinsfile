pipeline {
    agent any
    stages {
        stage('Example') {
            steps {
                echo 'Hello World'
            }
            
        }
    }
    post { curl -X POST http://localhost:8080/job/first-project/build --user ohurassa:11bf8134eb9eaf9c22a02f8ae595765b7c
        always { 
            echo 'I will always say Hello again!'
        }
    }
}
