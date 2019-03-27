# ECS Docker applications

This repository contains some of the apps that use Docker, that will be deployed in AWS environments.

## Dependencies

To run the apps, your ```local```,```Jenkins``` or ```bastion``` instance needs the [aws-cli](https://aws.amazon.com/pt/cli/) and [ecs-cli](https://docs.aws.amazon.com/AmazonECS/latest/developerguide/ECS_CLI_installation.html) to interact with AWS resources .

```bash
pip install aws-cli
```

```bash
sudo curl -o /usr/local/bin/ecs-cli https://s3.amazonaws.com/amazon-ecs-cli/ecs-cli-linux-amd64-latest

sudo chmod +x /usr/local/bin/ecs-cli
```

## Usage

You can deploy the applications using a Jenkins server or using your own terminal, with the **CLIs** mentioned above.


## Contributing
Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change.

Please make sure to update tests as appropriate.

## License
[OpenBSD](https://www.openbsd.org/policy.html)
