node {

    checkout scm

    docker.withRegistry('https://registry.hub.docker.com', 'dockerhub') {

        def customImage = docker.build("171477/demorep")

        /* Push the container to the custom Registry !!!!!!!!!!!!! */
        customImage.push()
    }
}
