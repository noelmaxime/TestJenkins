

node {

    stage('clone') {
        git 'https://github.com/noelmaxime/TestJenkins'
    }
    stage('test') {
        sh 'python3 pytest.py'
    }
}
