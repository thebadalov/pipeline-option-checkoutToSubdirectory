pipeline{
    agent any
    options {
      checkoutToSubdirectory('someSubDir')
    }
    stages{
        stage("Build"){
           steps{
               timestamps {
                   echo "Hello World" 
               }
           }
        }
    }
}
