node {
    checkout scm

    docker.withRegistry('https://hub.docker.com/repository/docker/shridhar2test/nodeapplication', 'nodeapplication') {

        def customImage = docker.build("shridhar2test/Nodeapplication")

        /* Push the container to the custom Registry */
        customImage.push()
    }
}
