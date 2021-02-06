pipeline {
    agent any
    triggers {
      cron("* 1 * * *")
    }
    stages{
      stage("Build") {
        steps {
	      sh "dotnet build Jenkins101.sln"
              unstable	"Build phase not implemented"
        }
      }
      stage("Test") {
        steps {
              unstable	"Test phase not implemented"
        }
      }
      stage("Deliver") {
        steps {
              unstable	"Deliver phase not implemented"
      }
    }
  } 
}
