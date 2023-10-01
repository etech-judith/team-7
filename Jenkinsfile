
 pipeline {
	agent any 
	stages {
		stage ("stage1-gitclone"){
            steps{
                sh 'uname -a'
            }
        }
                
        stage( '2 test'){
        		steps{
        			sh 'df -h'

        	}
        }
        
		stage ('3-deploy'){
            steps{
                sh 'whoami'
            }
        }
		
		stage ('4-build'){
            steps{
                sh 'free -m'
			}
		}
        stage('5-security check'){
            steps{
                sh 'cat /etc/os-release'
            }
        }
        stage('parallel'){
            parallel{
                stage('6-deploy'){
                    steps{
                        sh 'lscpu'
                    }

                }
                stage(7-artifactbuild){
                    steps{
                        echo "end of session"
                    }
                }
            }
        }
	}
}		




	

     
    
