--inbrowser    		Automatically open the url in browser, if --share is used, the public url will be automatically open instead

--server_port    	Choose a specific server port, default=7860 (example --server_port 420    so the local url will be:  http://127.0.0.1:420)

--share				Creates a public URL

--model_path		Name of the sdxl model from huggingface   (the default model example: --model_path stablediffusionapi/juggernaut-xl-v8     diffuser model you can find here: https://huggingface.co/stablediffusionapi/juggernaut-xl-v8

--size			    Setup max and min size of image. Default is `1280 1024`, uses around 13GB. If you want to use less, set: `--size 832 640`, or your own values.



---
title: InstantID
emoji: 😻
colorFrom: gray
colorTo: gray
sdk: gradio
sdk_version: 4.15.0
app_file: app.py
pinned: false
license: apache-2.0
---

Check out the configuration reference at https://huggingface.co/docs/hub/spaces-config-reference
