ARG VARIANT="ubuntu20.04"
ARG CUDA_VERSION="12.0.0"
FROM nvidia/cuda:${CUDA_VERSION}-devel-${VARIANT}

# [Optional] Change mirror to tuna mirror
# https://mirrors.tuna.tsinghua.edu.cn/help/ubuntu/
RUN sed -i "s@http://.*archive.ubuntu.com@https://mirrors.tuna.tsinghua.edu.cn@g" /etc/apt/sources.list

# [Optional] Uncomment this section to install additional OS packages.
# RUN apt-get update && export DEBIAN_FRONTEND=noninteractive \
#     && apt-get -y install --no-install-recommends <packages>
