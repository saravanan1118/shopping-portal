pipeline{

    agent any

// uncomment the following lines by removing /* and */ to enable
    tools{
       nodejs 'nodejs' 
    }
  

    stages{
        stage('Build'){
            steps{
                echo 'this is the build job'
                sh 'npm install'
              }
        }
        stage('Test'){
            steps{
                echo 'this is the test job'
                sh 'npm test'
            }
        }
        stage('package'){
            steps{
                echo 'this is the package job'
                sh 'npm run package'
            }
        }
    }
    
