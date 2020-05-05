pipeline {
  agent any
  stages {
    stage('Upload to production') {
      steps {
        sh 'rsync -yrzhe "ssh -o StrictHostKeyChecking=no" --exclude .git/ . prj09102@rex2.uni-regensburg.de:/homepages/prj09102/public_html/60217c/so2020'
      }
    }

  }
}