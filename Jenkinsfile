pipeline {
    agent none 
    stages {
        stage('Deploy to dev') { 
            when {
                branch 'dev'
            }
            steps {
                echo "Deploy on dev environment"
                echo "add feature"
            }
        }
        stage('Deploy to prod') { 
            when {
                branch 'master'
            }
            steps {
                echo "Deploy on prod environment"
                echo "Hotfix"
            }
        }
    }
}
