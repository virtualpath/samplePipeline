node ('cloud') {

    stage ('Checkout Code') {
          checkout scm
    }
    stage ('Run Script') {
      sh "sh simple.sh"
    }
    stage ('Success') {
        sh "echo 'Success'"
      }
}
