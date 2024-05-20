pipeline {
  agent any
  stages {
    stage ("Build"){
      steps {
        echo "Running build automation"
        sh "./gradlew build"
        archiveArtifacts artifacts: "dest/trainSchedule.zip"
      }
    }
  }
}
