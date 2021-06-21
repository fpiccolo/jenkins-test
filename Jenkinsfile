pipeline {
    agent any 
    stages {
        stage('Stage 1') {
            steps {
                echo 'Hello world!' 
            }
        }
        stage('Stage 2') {
            steps {
                echo 'Ciao mondo'
            }
        }
        stage('Stage Parallel'){
            parallel{
                stage('parallel-1'){
                    steps {
                        echo '1'
                        echo '2'
                        echo '3'
                        echo '4'
                    }
                }
                stage('parallel-2'){
                    steps {
                        echo '1'
                        echo '2'
                        echo '3'
                        echo '4'
                    }
                }
                stage('parallel-3'){
                    steps {
                        echo '1'
                        echo '2'
                        echo '3'
                        echo '4'
                    }
                }
                stage('parallel-4'){
                    steps {
                        echo '1'
                        echo '2'
                        echo '3'
                        echo '4'
                    }
                }
            }
        }
    }
}
