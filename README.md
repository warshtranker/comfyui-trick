# comfyui-trick


ComfyUI can't install impact-pack, was-node-suite, florence2 or anotehr nodes:

- navigate to ..\ComfyUI\user\default\ComfyUI-Manager\startup-scripts\install-scripts.txt file
- add --no-cache-dir between pip and install, example: 'pip', '--no-cache-dir', 'install', 
