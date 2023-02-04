pipeline { 
    agent any 
    options {
        skipStagesAfterUnstable()
    }
    stages {
        stage('Build') { 
            steps { 
                echo 'iOS Build'
		echo 'Android Build'
		echo 'iPadOS Build' 
            }
        }
        stage('Test'){
            steps {
                echo 'Testing: iOS 14 - iPhone 8 Pro'
		echo 'Testing: iOS 15.4 - iPhone 13 Pro Max'
		echo 'Testing: iOS 15.3 - iPhone 11 Pro'
		echo 'Other tests'
            }
        }
        stage('Deploy') {
            steps {
                echo "Maybe deploy"
            }
        }
    }
}

