pipeline
{
    agent any
    stages
    {
        stage('ContinuousDownload_master')
        {
            steps
            {
                git 'https://github.com/intelliqittrainings/maven.git'
            }
        }
        stage('ContinuousBuild_master')
        {
            steps
            {
                sh 'mvn package'
            }
         }
