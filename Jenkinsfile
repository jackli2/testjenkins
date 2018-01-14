
de {

    stage("Pull GIT Repo") {
            checkout scm
    }

    stage("Build and start test image") {
            app = docker.build docker_image
    }
}
