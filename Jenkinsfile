pipeline{
        agent any
        stages{
            stage('Make Directory'){
                steps{
                    sh "if [ ! -d ~/jenkins-tutorial-test ]; then mkdir ~/jenkins-tutorial-test; fi;"
                }
            }
            stage('Make Files'){
                steps{
                    sh "touch ~/jenkins-tutorial-test/file1 ~/jenkins-tutorial-test/file2"
                }
            }
        }
}
