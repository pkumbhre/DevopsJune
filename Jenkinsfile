pipeline                        //Jenkinsfile always starts with keyword pipeline
{
    agent any                  //agent any menas: any available executor
    stages                     // it contains all the stages
    {
        stage ('Git SCM Checkout')                     //name of stage
        {steps                                      //ot tells jenkins what do
         {sh 'echo download'}                    //sh: execute the shell script/command
         }
        stage ('Execute Unit test case')                     //name of stage
        {steps                                      //ot tells jenkins what do
         {sh 'echo Executing unit test cases'}                    //sh: execute the shell script/command
         }
        stage ('Code buid ')                     //name of stage
        {steps                                      //ot tells jenkins what do
         {sh 'echo Executing lbuilding stage'}                    //sh: execute the shell script/command
         }

    }


}
