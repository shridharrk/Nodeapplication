node {
    checkout scm

    docker.withRegistry('https://registry.hub.docker.com', 'nodeapplication') {

        def customImage = docker.build("shridhar2test/Nodeapplication")

        /* Push the container to the custom Registry */
        customImage.push()
    }
}
