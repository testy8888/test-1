pipeline {
    agent any 
    stages {
        stage('Hello') {
            steps {
                echo 'Hello World'
            }
        }
        stage('cat README'){
         when {
           branch "dev-*"
         }
         steps {
           sh 'cat README.md'
}
}
    }
}
