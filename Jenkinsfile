pipeline{
	agent any
		stages{
			stage('git-clone'){
				steps{
					sh 'git clone https://github.com/akudogithub/jenkins-demo-repo.git'
				}
			}
			stage('system resource check'){
				steps{
					sh 'lscpu'
					sh 'free -m'
					sh 'free -g'
				}
			}
			stage('user-verify'){
				steps{
					sh 'cat /etc/passwd'
					sh 'id ubuntu'
					sh 'id jenkins'
				}
			}
			stage('build-status'){
				steps{
					sh 'echo "jenkins pipeline has run successfully" '
				}
			}
		}

}