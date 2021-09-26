---
name: Bug report
about: Create a report to help us improve
title: ''
labels: ''
assignees: ''

---

**Describe the bug**
A clear and concise description of what the bug is.

**Parameters used**
Paste in the parameters you used
e.g.
key_frames = True #@param {type:"boolean"}
text_prompts = "10:(Apple: 1| Orange: 0), 20: (Apple: 0| Orange: 1| Peach: 1)" #@param {type:"string"}
width =  400#@param {type:"number"}
height =  400#@param {type:"number"}
model = "vqgan_imagenet_f16_16384" #@param ["vqgan_imagenet_f16_16384", "vqgan_imagenet_f16_1024", "wikiart_16384", "coco", "faceshq", "sflckr"]
interval =  1#@param {type:"number"}
initial_image = ""#@param {type:"string"}
target_images = ""#@param {type:"string"}
seed = 1#@param {type:"number"}
max_frames = 50#@param {type:"number"}
angle = "10: (0), 30: (10), 50: (0)"#@param {type:"string"}
zoom = "10: (1), 30: (1.2), 50: (1)"#@param {type:"string"}
translation_x = "0: (0)"#@param {type:"string"}
translation_y = "0: (0)"#@param {type:"string"}
iterations_per_frame = "0: (10)"#@param {type:"string"}
save_all_iterations = False#@param {type:"boolean"}

**Which cell you saw the error in**
e.g. "Actually do the run"

**Error message**
Paste in the traceback you saw

**Screenshots**
If applicable, add screenshots to help explain your problem.

**Additional context**
Add any other context about the problem here. e.g. Had you restarted to use only the video generation cells? Are you using google drive?
