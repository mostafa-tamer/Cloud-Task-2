pipeline {
    agent any

    stages {
        stage('Run Bash Script') {
            steps {
                script {
                    def output = sh(script: './list_contents.sh', returnStdout: true).trim()
                    echo "Output: ${output}"
                }
            }
        }
    }
}
