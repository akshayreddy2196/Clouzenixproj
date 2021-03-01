
pipeline{
   agent any
        stages{ 
        stage('---clean---')
        steps{
        sh "mvn clean"
      }
     }
     stage{
     stage('---test---')
     steps{
     sh "mvn test"
     }
    }
    stages{
    stage('---pacjage---')
    steps{
    sh "mvn package"
    }
   }
  }
 }
