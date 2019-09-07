pipeline {
  agent any
  stages {
    stage('buildAsstes') {
      steps {
        echo 'welll hello'
      }
    }
   stage('Git Checkout') {
    gitCheckout(
        branch: "master",
        url: "https://github.com/tanv-jen/varrepo.git"
    )
   }
    stage('completed') {
      steps {
        echo 'kjkhk'
      }
    }
  }
}
