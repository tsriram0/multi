node('master') 
{
    stage('ContinuousDownload_loans') 
    {
      git 'https://github.com/selenium-saikrishna/maven.git'
    }
    
    stage('ContinuousBuild')
    {
        sh label: '', script: 'mvn package'
    }
   
    
    
}
