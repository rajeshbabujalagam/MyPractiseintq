pipeline
{
    agent any
    environment {
        NEW_VERSION = '1.2.3'
    }
    stages
    {
        stage('ContinuousDownload')
        {
            steps
            {
                echo "hello dwnld"
                echo "version nu is ${NEW_VERSION}"
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
        stage('cTest')
        {
            steps
            {
                echo "test"

            }
        }
       
        
    
    }

}
