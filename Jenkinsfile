pipeline {
      agent any
           stages {
               stage ( "Git clone") {
                   steps{
                       checkout([$class: 'GitSCM', branches: [[name: '**']], extensions: [], userRemoteConfigs: [[credentialsId: '7865230e-98ef-41eb-84b0-407bf1924b41', url: 'https://github.com/sodexkings/tomcat_installation']]])
		           }
               }
           }
}
