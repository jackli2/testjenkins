node {

    stage("Pull GIT Repo") {
            checkout scm
    }

    stage("Build and start test image") {
            echo "start test"
	    makdir test
            rm -rf test
    }
}
