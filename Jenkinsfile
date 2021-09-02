def releaseBranch = "main"

node {
    stage('Preparation') {
      if(currentBuild.result != 'FAILURE' && env.BRANCH_NAME == releaseBranch){
        println "${env.BRANCH_NAME}"
      }
    }
}
