node('master') 
{
    stage('CD-S1-GIt-Multipieline') 
	{
      git 'https://github.com/BABJI-AWS-DEVOPS/WARFILE-43-44-10am.git'
    }
}

node('master') 
{
   stage('S2-CB-Multipieline') 
   {
    sh 'mvn package'
   }
}
