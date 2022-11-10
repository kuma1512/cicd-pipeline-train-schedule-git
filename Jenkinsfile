pipeline {
  agent any
  stages {
    stage('Build'){
      steps {
        echo 'Running automation buils !!'
        sh './gradlew build --no-daemon'
        archiveArtifacts artifact: 'dist/trainSchedule.zip'
      }
    }
  }
}
