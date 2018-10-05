pipeline {
 agent any
   stages{
    stage ("Build") {
      steps {
        echo "Building..."
         sh './gradlew build --no-daemon --debug'
         archiveArtifacts artifacts:build/test.jar
            }
                    }
           }
           }
