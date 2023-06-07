pipeline {
    agent any
    stages {
        stage('Example') {
            steps {
                echo 'Hello World'
            }
            
        }
    }
    post { curl -X POST http://localhost:8080/job/multi-branches/build --user ohurassa:xxxx
        always { 
            echo 'I will always say Hello again!'
        }
    }
}
