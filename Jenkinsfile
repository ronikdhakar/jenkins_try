pipeline{
    agent any
    stages{
        stage("check node version"){
            steps{
                sh "node--version"    
            }
        }
        stage("install depecdencies"){
            steps{
				sh "npm--version"
                sh "npm install"
            }
        }
        stage("test"){
            steps{
                sh "node app.js"
            }
        }
        stage("release version"){
            steps{
                echo "release version"
            }
        }
    }
}