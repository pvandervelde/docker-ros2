# althack/ros2

These are the docker images I use for developing ROS2 code.

## Usage

```bash
docker pull pvandervelde/ros2:rolling-base
```

## Organization

The main docker image tags are:

rolling

* [rolling-base](https://github.com/athackst/dockerfiles/blob/main/ros2/rolling.Dockerfile)
* [rolling-dev](https://github.com/athackst/dockerfiles/blob/main/ros2/rolling.Dockerfile)
* [rolling-full](https://github.com/athackst/dockerfiles/blob/main/ros2/rolling.Dockerfile)
* [rolling-gazebo](https://github.com/athackst/dockerfiles/blob/main/ros2/rolling.Dockerfile)

jazzy

* [jazzy-base](https://github.com/athackst/dockerfiles/blob/main/ros2/jazzy.Dockerfile)
* [jazzy-dev](https://github.com/athackst/dockerfiles/blob/main/ros2/jazzy.Dockerfile)
* [jazzy-full](https://github.com/athackst/dockerfiles/blob/main/ros2/jazzy.Dockerfile)
* [jazzy-gazebo](https://github.com/athackst/dockerfiles/blob/main/ros2/jazzy.Dockerfile)

humble

* [humble-base](https://github.com/athackst/dockerfiles/blob/main/ros2/humble.Dockerfile)
* [humble-dev](https://github.com/athackst/dockerfiles/blob/main/ros2/humble.Dockerfile)
* [humble-full](https://github.com/athackst/dockerfiles/blob/main/ros2/humble.Dockerfile)
* [humble-gazebo](https://github.com/athackst/dockerfiles/blob/main/ros2/humble.Dockerfile)

Each image is additionally tagged with the date of creation, which lets you peg to a specific version of packages.

The format is {image-name}-{year}-{month}-{day}
