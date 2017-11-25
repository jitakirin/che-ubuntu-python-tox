# che-ubuntu-python-tox

A docker image for [Che] Python [Tox] stack.

[Tox] is a generic virtualenv management and test command line tool you
can use for:

- checking your package installs correctly with different Python
  versions and interpreters
- running your tests in each of the environments, configuring your test
  tool of choice
- acting as a frontend to Continuous Integration servers, greatly
  reducing boilerplate and merging CI and shell-based testing

##

This image is based on [Che]
[eclipse/stack-base](https://github.com/eclipse/che-dockerfiles/tree/master/recipes/stack-base/ubuntu)
image,
[eclipse/ubuntu_python](https://github.com/eclipse/che-dockerfiles/tree/master/recipes/ubuntu_python)
image and [Tox] integration is based on
[n42org/tox](https://store.docker.com/community/images/n42org/tox) docker image.


[Che]: https://www.eclipse.org/che/
[Tox]: https://tox.readthedocs.io/en/latest/
