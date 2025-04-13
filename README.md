# comfyui-trick

To use another models, loras and other locations:
- open C:\Users\<user>\AppData\Local\Programs\@comfyorgcomfyui-electron\resources\ComfyUI\extra_model_paths.yaml
- uncomment a111 section
- set base path to your a111 path, for example: base_path: C:\sb-webui
- uncomment lines checkpoint, configs, vae, loras...


ComfyUI hangs on installing impact-pack, was-node-suite, florence2 or other nodes:

- navigate to ..\ComfyUI\user\default\ComfyUI-Manager\startup-scripts\install-scripts.txt file
- add --no-cache-dir to every line with pip command betwen pip and install, example: 'pip', '--no-cache-dir', 'install',
- you cann add -v to get more information whyle process: 'pip', '-v', '--no-cache-dir', 'install',
