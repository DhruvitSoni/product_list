pipeline{
    agent{
        label'dev-clickit'
    }
    stages{
        stage('build'){
            steps{
                 sh '''
                  npm i
                  pm2 restart clickit
                  echo build done
                 '''
            }
        }
       
    }
   
}
