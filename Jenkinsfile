post {
   always {
     jiraSendBuildInfo site: 'YOUR-ORGINIZATION.atlassian.net'
   }
   success {
     script {
       println "All the tests passed."
     }
   }
   failure {
       println "There are some failing tests."
   }
 }