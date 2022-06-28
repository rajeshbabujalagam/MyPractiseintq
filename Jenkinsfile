pipeline
{
    agent any
    stages
    {
        stage('ContinuousDownload')
        {
            steps
            {
                echo "hello dwnld"
                git 'https://github.com/intelliqittrainings/maven.git'
            }
        }
        stage('ContinuousBuild')
        {
            steps
            {
                echo "hello build"
                sh 'mvn package'
            }
        }
       
        
    
    }

    
    
    
    
}
