pipeline {
    agent any
    stages {
        
        stage ('Shell Script') {
            steps {
                git url: "https://github.com/GauravGirase/sample-repo-62899-9-dec.git", branch: "main"
                readFile 'README.md'
            }
            
    
        }
    }
}
