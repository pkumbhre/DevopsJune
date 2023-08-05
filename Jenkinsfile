pipeline                        //Jenkinsfile always starts with keyword pipeline
{
    agent any                  //agent any menas: any available executor
    stages                     // it contains all the stages
    {
        stage ('dislpay hello')                     //name of stage
        {steps                                      //ot tells jenkins what do
         {sh 'echo hi_henkins'}                    //sh: execute the shell script/command
         }
        stage ('Build')                     //name of stage
        {steps                                      //ot tells jenkins what do
         {sh 'echo hi_building'}                    //sh: execute the shell script/command
         }
        stage ('Test')                     //name of stage
        {steps                                      //ot tells jenkins what do
         {sh 'echo hi_Testing'}                    //sh: execute the shell script/command
         }

    }


}