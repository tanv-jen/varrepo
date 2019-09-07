@Library('dcube-library@master') _
pipeline {
  agent any
  stages {
   stage('Git Checkout') {
     steps{
    gitCheckout(
        branch: "master",
        url: "https://github.com/tanv-jen/varrepo.git"
    )
     }
   }
    stage('completed') {
      steps {
        echo 'hhhjgj'
      }
    }
  }
}
