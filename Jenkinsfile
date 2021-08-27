pipeline {
  agent any
  stages{
    stage("build"){
      steps{
        echo 'Building Initiated'
        pytest get_links.py
      }
    }
  }
}
