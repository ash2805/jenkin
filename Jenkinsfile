stages("DEPLOY CONTAINER"){
        steps {
            script {
                    sh """
                    #!/bin/bash
                    sudo ssh ec2-user@18.118.49.30 << EOF
                    sudo rm -rf /home/ec2-user/jenkin
                    git clone https://github.com/ash2805/jenkin.git
                    sudo cp jenkin/index.html /var/www/html/
                    sudo cp jenkin/index.html /var/www/html/
                    << EOF
                    """
                }
        }
    }
