pipeline{
     agent none
     stages{
         stage ('codecheckout'){
            agent {label 'master'}
            steps{
               script{
                   sh "echo hi hell how are you"
               }
            }
         }
         stage ('build'){
            agent {label 'master'}
            steps{
               script{
                   sh "echo hi hello what are doing"
                }
             }
          }
          stage ('test'){
              agent {label 'master'}
              steps{
                 script{
                     sh "echo hi where are you now"
                  }
               }
           }
           stage ('deploy'){
              agent {label 'master'}
              steps{
                 script{
                      sh "echo hi heloo how are uuuuuuuu"
                 }
               }
            }
            stage ('delivery'){
                agent {label 'master'}
                stpes{
                   script{
                       sh "echo hi hello"
                    }
                 }
             }
         }
     }    
            
                      
                      
                  

                   
                  
            
