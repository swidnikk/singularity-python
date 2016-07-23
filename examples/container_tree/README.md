# Container Tree

What's inside that container? Right now, the main way to answer this question is to do some equivalent of ssh. I decided to make a simple function for rendering a view to (immediately) show the contents of an image (folders and files) in your web browser:

      shub --tree --image /home/vanessa/Desktop/ubuntu:latest-2016-04-06.img.zip

This will open up something that looks like this:

![../../img/files.png](../../img/files.png)

An [interactive demo](https://singularityware.github.io/singularity-python/examples/container_tree) is also available: