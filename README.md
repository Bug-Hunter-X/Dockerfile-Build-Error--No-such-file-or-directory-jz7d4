# Dockerfile Build Error: No such file or directory
This repository demonstrates a common Dockerfile error and its solution.

The problem is that the Dockerfile tries to execute a Python script (main.py) that is not included in the build context. This results in a 'No such file or directory' error during the build process.

The solution involves ensuring that the main.py file is included in the context and correctly copied to the image.