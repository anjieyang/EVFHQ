# EVFHQ

EVFHQ (Extended VFHQ) is an expansion of the [VFHQ dataset](https://liangbinxie.github.io/projects/vfhq/), which offers a significantly larger and more diverse collection of high-quality video face data.

## Components

EVFHQ consists of the following Dockerized components:

- [EVFHQ-Database](https://github.com/anjieyang/EVFHQ-Database): Manages a PostgreSQL database that stores video metadata and processing results.
- [EVFHQ-Fetcher](https://github.com/anjieyang/EVFHQ-Fetcher): Responsible for gathering video metadata from YouTube.
- [EVFHQ-Assigner](https://github.com/anjieyang/EVFHQ-Assigner): Distributes video download tasks across multiple servers to optimize load and efficiency.
- [EVFHQ-Downloader](https://github.com/anjieyang/EVFHQ-Downloader): Handles the downloading of video files from YouTube.
- EVFHQ-Processor (Coming Soon): Specializes in extracting facial clips from the downloaded videos.
