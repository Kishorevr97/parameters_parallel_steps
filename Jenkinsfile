properties([
                        parameters([
                            choice(
                                choices: ['kishore', 'arjun', 'sneha', 'kowshalya'], 
                                name: 'Employeename'
                            ),
                            string(
                                defaultValue: '', 
                                name: 'desgniation', 
                                trim: true
                            )
                        ])
  ])

pipeline {
  agent any
  stages {
    stage('demo') {
      steps {
        echo "hello $Employeename,you are a $desgniation"
      }
    }
  }
}
