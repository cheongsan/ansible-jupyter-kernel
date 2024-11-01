# Ansible Jupyter Kernel (Python 3.12 Fork)

This is a modified version of [ansible-jupyter-kernel](https://github.com/ansible/ansible-jupyter-kernel) that has been updated to work with Python 3.12.

## Overview

This fork includes the following improvements:
- Updated dependencies to support Python 3.12
- Fixed IPython directory permission issues
- Maintained all original functionality while ensuring compatibility with modern Python versions

## Quick Start with Docker

Run the Jupyter notebook server with Ansible kernel using:

```bash
docker run -p 8888:8888 cheongsan/ansible-jupyter-kernel:latest
# or
docker run -p 8888:8888 cheongsan/ansible-jupyter-kernel:python3.12