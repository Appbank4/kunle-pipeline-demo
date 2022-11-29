pipeline{
	agent any
		stages{
			stage('1-make RepoClone'){
				steps{
					checkout([$class: 'GitSCM', branches: [[name: '*/main']], extensions: [], userRemoteConfigs: [[url: 'https://github.com/Appbank4/kunle-pipeline-demo.git']]])
				}
			}
			stage('2-make right on a yellow line'){
				steps{
					sh 'df -h'
                    sh 'whoami'
				}
			}
			stage('3-make left turn on adjercent line'){
				steps{
					sh 'free -g'
                    sh 'free -m'
				}
			}
			stage('4-crossover the pedenstrian bridge to opposite side'){
				steps{
					sh 'lscpu'
				}
			}
            stage('5-you have arrived'){
                steps{
					sh 'cat /etc/os-release'
					
                }
            }
		}
}