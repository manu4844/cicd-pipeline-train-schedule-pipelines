tpipeline{
  agent any
  stages{
    stage('Build'){
      steps{
        echo 'Building the project inside multi branch pipleline automation'
        sh './gradlew build --no-daemon'
        archiveArtifacts artifcats: 'dist/trainSchedule.zip'
      }
    }
  }
}
