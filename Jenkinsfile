pipeline{
    stages{
        stage('Pipeline test'){
            steps{
                echo('Pipeline running !!')
            }
        }
        stage('Pipeline triggred'){
            step{
                echo('Pipeline triggred !!')
            }
        }
    }
    post{
        success{
            echo('Pipeline completed !')
        }
        failure{
            echo('Pipeline failed !!')
        }
    }
}