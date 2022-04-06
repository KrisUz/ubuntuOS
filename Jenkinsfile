pipeline {
    agent any

    stages {
        stage('Build') 
        {
            steps 
            {
                echo 'Build App'
            }
        }
        
         stage('Test') 
        {
            steps 
            {
                echo 'QA APP'
            }
        }
        
         stage('Review') 
        {
            steps 
            {
                echo 'Review App'
            }
        }
        
         stage('Approval') 
        {
            steps 
            {
                echo 'Approve App'
            }
        }
        
         stage('Deploy') 
        {
            steps 
            {
                echo 'Deploy App'
            }
        }
    }
    
    post
    {
        
        always
        {
            emailext body: 'testing pipeline', subject: 'pipeline  status', to: 'notify@unknown.com'
        }
    }
}
