pipeline {
 agent any 
    stages {
      stage ('git checkout') {
        steps {
          git branch: 'main', url: 'https://github.com/udaysk37/Hello-world.git'
      }
    }
      stage ('unit test') { 
        steps{
            sh 'mvn install'
        }
      }
   }     
}  
  
