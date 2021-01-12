node() {
    def STC_INSTALL = "/opt/STC_CLIENT/Spirent_TestCenter_5.16/Spirent_TestCenter_Application_Linux64Client/"
    def os = System.properties['os.name'].toLowerCase()
    try {
	    println "All the tests passed."
		}
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