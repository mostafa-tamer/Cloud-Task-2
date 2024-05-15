pipeline {
    agent any

    stages {
        stage('Run Bash Script') {
            steps {
                script {
                    echo "Mostafa tamer"
                    def output = sh(script: './list_contents.sh', returnStdout: true).trim()
                    echo "Output: ${output}"
                }
            }
        }
    }
}
