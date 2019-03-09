pipeline {
  agent any
  stages {
    stage ('Build') {
      steps {
        echo 'Running Build automation like Van Halen'
        sh './gradlew build --no-daemon'
        archiveArtifacts artifacts: 'dist/trainSchedule.zip'
      }
    }
  }
}
