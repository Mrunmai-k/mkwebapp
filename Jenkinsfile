pipeline 
{
    agent any 
    tools 
    {
        nodejs 'node'
    }

    stages 
    {
        stage('Build') 
        {
            steps 
            {
                sh 'node --version'
            }
        }
        stage('Test') 
        {
            steps 
            {
                echo 'Testing...'
            }
        }
        stage('Deploy') 
        {
            steps 
            {
                echo 'Deploying....'
            }
        }
    }
}

