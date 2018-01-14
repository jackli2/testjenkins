node {

    stage("Pull GIT Repo") {
            checkout scm
    }

    stage("Build and start test image") {
            echo 'start test'
	    sh 'makdir test'
            sh 'rm -rf test'
            echo 'test finished'
    }
}
