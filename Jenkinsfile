pipeline{   
   agent none
    stages{

         stage("dve") {
            when{ branch 'main' }   
             steps{
                  echo 'hello'
                 }   
            }
          stage("hello"){  
             when { branch 'swathi-*' }
                       steps{ echo 'hello evryone' }
                     }

      }
}
