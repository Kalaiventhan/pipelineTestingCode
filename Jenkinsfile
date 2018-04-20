pipeline {
  agent any
  stages {
    stage('build') {
      steps {
        echo 'Build stage'
        build(job: 'BudgetJobs', wait: true, quietPeriod: 10)
      }
    }
  }
}