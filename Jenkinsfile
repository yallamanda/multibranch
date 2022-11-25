@Library('mylibrary')_
pipeline
{
    agent any
    stages
    {
        stage("Continuous Download_Loans")
        {
            steps
            {
                script
                {
                    cicd.newGit('https://github.com/yallamanda/multibranch.git' )


                }

            }
        }

        stage("Continuous Build_Loans")
        {
            steps
            {
                script
                {
                    sh 'mvn package'


                }

            }
        }

        


    }




}
