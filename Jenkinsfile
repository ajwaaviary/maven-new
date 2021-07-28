node('master') 
{
   stage('ContinousDownload_master')
   {
       git 'https://github.com/intelliqittrainings/maven.git'
   }
   stage('ContinousBuild_master')
   {
      sh 'mvn package'
   }  
