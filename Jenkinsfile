node {
    stage ('Checkout Code'){
   checkout([$class: 'GitSCM', branches: [[name: '*/master']], doGenerateSubmoduleConfigurations: false, extensions: [], submoduleCfg: [], userRemoteConfigs: [[credentialsId: 'ssp-git-creds', url: 'https://github.com/awsdevopsssp/vpt-demo1.git']]])
 }
stage ('Run Script'){
    sh "sh simple.sh"
}
stage ('Success'){
sh "echo 'Success'"
}
}
