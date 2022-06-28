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
                echo "hello dwnld only Loans"
                echo "version nu is ${NEW_VERSION}"
                git 'https://github.com/intelliqittrainings/maven.git'
            }
        }
        stage('ContinuousBuild')
        {
            steps
            {
                echo "hello build_Loans"
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
