# comfyui-trick


ComfyUI can't install impact-pack, was-node-suite, florence2 or anotehr nodes:

- navigate to ..\ComfyUI\user\default\ComfyUI-Manager\startup-scripts\install-scripts.txt file
- add --no-cache-dir to every line with pip command betwen pip and install, example: 'pip', '--no-cache-dir', 'install',
- you cann add -v to get more information whyle process: 'pip', '-v', '--no-cache-dir', 'install',
