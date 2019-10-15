pipeline {
    agent any 
    stages {
        stage(‘Build’) {
            steps {
                she ‘echo “Hello World”’
                she ‘“
                         echo “Multiline shell steps works too”
                         ls -lah
                    “‘
            }
        }
    }
}
