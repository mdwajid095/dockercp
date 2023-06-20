# dockercp
A CLI tool to copy docker container images from one repository to other repository.

./dockercp
Version: v1.0
run 'dockercp -h,--help'       :for instruction manual

#dockercp -h command for user manual
./dockercp -h
USAGE:
  dockercp                    : show the user manual and version
  dockercp -h,--help          : show this message
  dockercp -f,--file          : Will take input a file in below format, i.e json.

Example json file:
        {
          "destination": "europe-west3-docker.pkg.dev/PROJECT/DIR/",
          "source": "docker.io/mdwajid095/",
          "images": [
            "kcctl:v1.1",
            "curl-jq-git:v1.1",
            "ubuntu:latest"
          ]
        }

![image](https://github.com/mdwajid095/dockercp/assets/55093597/87a91e10-bb49-4cbd-bd7f-0d4336fdfc45)
