piepline {
  agent any
  stages {
    stage ('Build') {
      steps {
        echo 'Running build automation'
        sh './gredlew build --no-demon'
        archiveArtifacts artifacts: 'dist/trainSchedule.zip' 
      }
    }
  }
}
