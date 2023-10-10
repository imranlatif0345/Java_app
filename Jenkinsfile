pipeline{
    agent any
    environment{
        demoVar='TestVariable123'
    }
    stages{
        stage ('build'){
            steps{
                script{
                    deployDemo.test()
                }
            }
        stage ('deploy'){
            steps{
                script{
                    deployDemo.test()
                }
            }
        }
    }
}
