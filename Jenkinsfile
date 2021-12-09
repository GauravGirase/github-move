pipeline {
    agent any
    stages {
        
        stage ('Shell Script') {
            steps {
                git url: "git@github.com:GauravGirase/test_repo_62899.git", branch: "main",
                sh "cat README.md"
            }
    
        }
    }
}
