node
{
    stage('checkout')
    {
        checkout([$class: 'GitSCM', branches: [[name: '*/master'], [name: '*/origin1'], [name: '*/origin2'], [name: '*/master']], doGenerateSubmoduleConfigurations: false, extensions: [], submoduleCfg: [], userRemoteConfigs: [[credentialsId: '7c7ed58b-bd66-4402-bf77-86a0dfe40318', url: 'https://github.com/avraindia/Test_sk.git']]])
    }
    stage('build')
    {
        echo "build is done"
    }
    stage('testing')
    {
        echo "testing is done"
    }
    stage('deploy')
    {
        echo "deployment is done"
    }
}
