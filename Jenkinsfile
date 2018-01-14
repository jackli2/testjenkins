node {

    stage("Pull GIT Repo") {
            checkout scm
    }

    stage("Build and start test image") {
            echo 'start test'
	    sh 'mkdir test'
            sh 'rm -rf test'
            echo 'test finished'
    }
}
