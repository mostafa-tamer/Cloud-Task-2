pipeline {
    agent any

    stages {
        stage('Run Bash Script') {
            steps {
                script {
                    echo "Mostafa Tamer"
                    
                    sh 'chmod +x ./list_contents.sh'
                    def output = sh(script: './list_contents.sh', returnStdout: true).trim()
                    echo "Output: ${output}"
                }
            }
        }
    }
}
