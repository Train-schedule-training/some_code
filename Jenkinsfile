
pipeline {
  agent any
  triggers {
   cron('H/15 * * * *')
  }
  stages {
    stage('echo') {
      steps {
        echo 'hello from the trigger which was completed by me. Call me when you have a jenkins job'
      }
    }

  }
}
