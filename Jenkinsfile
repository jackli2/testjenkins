node {

    stage("Pull GIT Repo") {
            checkout scm
    }

    stage("Build and start test image") {
            echo 'start test'
	    sh 'mkdir test'
            sh 'git clone https://github.com/jackli2/testjenkins.git'
            sh 'cd testjenkins'
            sh 'cd test'
            sh 'node test.js'
            sh 'rm -rf test'
            echo 'test finished'
    }
}
