pipeline {
    agent any

    stages {
        stage('Run Bash Script') {
            steps {
                script {
                    cd ..
                    ls

                    // chmod +x ./list_contents.sh
                    // def output = sh(script: './list_contents.sh', returnStdout: true).trim()
                    // echo "Files:\n======\n${output}"
                }
            }
        }
    }
}
