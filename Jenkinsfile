pipeline {
  agent any
  stages {
    stage('Stage 1') {
      steps {
        sleep 3
        echo 'Stage1 / Step 2'
        sleep 3
        echo 'Stage 1 / Step 3'
        sleep 3
        echo 'Stage 1 / Step 1'
      }
    }

    stage('Stage 2') {
      steps {
        sleep 3
        echo 'Stage 2 / Step 1'
        echo 'Stage 2 / Step 2'
        sleep 3
      }
    }

    stage('Stage 3') {
      steps {
        sleep 3
        echo 'Stage 3 / Step 1'
        sleep 3
        echo 'Stage 3 / Step 2'
        sleep 3
        echo 'Stage 3 / Step 3'
        sleep 3
        echo 'Stage 3 / Step 4'
      }
    }

  }
}