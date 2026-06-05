pipeline{
    agent any
    stages{
        stage('Checkout Code'){
            steps{
               git 'https://github.com/mrahman2-vt/NTN_LEO_mega-constellation-demo' 
            }
            
        }
        stage('Build'){
            steps{
                sh 'echo "Building the app"'
            }
            
        }
        stage('Test'){
            steps{
                sh 'echo "Running the test"'
            }
            
        }
        stage('Deploy'){
            steps{
                sh 'echo "Deploying"'
            }
            
        }
    }
}
