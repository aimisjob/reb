pipeline{
 agent any
 options{
   skipStagesAfterUnstable()
   }
 stages{
 stage('build'){
   steps{
     echo "setting curent build to unstable
     script{
       currentBuild.result="UNSTABLE"
      }
    }
   }
   stage('deploy'){
    steps{
    echo "deploy is runnig"
    }
 }
}
}

