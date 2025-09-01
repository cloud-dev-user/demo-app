pipeline{  
                 agent any; 
              parameters {
                          string description: 'this will be variable for repository to be built', name: 'repo_name'
                              }

                 stages { 
                             stage("checkout my code") {
                                        steps {
                                                   echo " checkout code from $repo_name" 
                                                }
                                        }
                                stage ("build my code") {
                                       steps{
                                                  echo " build my code " 
                                               }
                                         }
                                 stage ("test my code") {
                                       steps{
                                                  echo " test my code " 
                                               }
                                         }
                          }
     }
