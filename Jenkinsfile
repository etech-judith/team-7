
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
	}
}		




	

     
    
