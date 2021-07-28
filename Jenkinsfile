node('master') 
{
   stage('ContinousDownload_loans')
   {
       git 'https://github.com/intelliqittrainings/maven.git'
   }
   stage('ContinousBuild_loans')
   {
      sh 'mvn package'
   }  
   }
