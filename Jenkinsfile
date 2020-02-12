pipeline{
    agent none
    stages{
        stage('codecheckout'){
            agent{label 'master'}
            steps{
                script{
                    sh "echo hi helo how  are u"
                }
            }
        }
        stage('build'){
            agent{label 'master'}
            steps{
                script{
                    sh "echo here is doing build the code"
                }
            }
        }
        stage('test'){
            agent{label 'master'}
            steps{
                script{
                    sh "echo hi hello here testing"
                }
            }
        }
        stage('deploy'){
            agent{label 'master'}
            steps{
                script{
                    sh "echo hi hello hoe are you deployment"
                }
            }
        }
        stage('delivery'){
            agent{label'master'}
            steps{
                script{
                    sh "echo hi hello hers delivery the code finally"
                }
            }
        }
    }
}
