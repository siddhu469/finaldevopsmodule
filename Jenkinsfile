pipeline{
  agent any
  stages{
    stage{"Deploy"}{
      steps{
        echo "Test sucessful"
        bat"mvn compile"
  }
}
    stage("Build"){
          steps{
            echo "Build sucessful"
            bat"mvn build"}
          }  stage("Test"){
          steps{
            echo "BUild sucessful"
            bat"mvn test"}
    }}}
          
