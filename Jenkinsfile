// step 1
node {
  stage ('SCM Checkout'){
    git 'https://github.com/zikdev44/my-app'
  }
  stage('compile-package'){
    sh 'mvn clean package -Dmaven.test.skip'
  }
}
