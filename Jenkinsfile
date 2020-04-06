pipeline{
     agent {node{label''}}
    stages{
	    stage('checkout'){
		steps{
		      checkout changelog: false, poll: false, scm: [$class: 'GitSCM', branches: [[name: 'master']], doGenerateSubmoduleConfigurations: false, extensions: [], submoduleCfg: [], userRemoteConfigs: [[credentialsId: '3f8d5a75-e8b9-426a-a7bd-9057837782b1', url: 'https://github.com/gitclass2020/src.git']]]
			}
	   }
	}
}