pipeline{
    stages{
        stage('Pipeline test'){
            steps{
                echo('Pipeline running !!')
            }
        }
        state('Pipeline triggred'){
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