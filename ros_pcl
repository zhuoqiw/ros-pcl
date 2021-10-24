# Install PCL on ROS
FROM ros:galactic

RUN apt-get update && apt-get install -y --no-install-recommends \
  libpcl-dev=1.10.0+dfsg-5ubuntu1 \
  && rm -rf /var/lib/apt/lists/*
