
## Quick Start

<details>
<summary>Demo</summary>

Step1. just run by demo.py, note: relative path of 'exps' & 'weight'.

Step2. Use either -n or -f to specify your detector's config. For example:

```shell
 python tools/demo.py --demo image -f exps/default/yolox_s.py -c weights/yolox_s.pth --path assets/dog.jpg --conf 0.25 --nms 0.45 --tsize 640 --save_result --device cpu
```
or
```shell
python tools/demo.py image -f exps/default/yolox_s.py -c /path/to/your/yolox_s.pth --path assets/dog.jpg --conf 0.25 --nms 0.45 --tsize 640 --save_result --device [cpu/gpu]
```
Demo for video:
```shell
python tools/demo.py video -n yolox-s -c /path/to/your/yolox_s.pth --path /path/to/your/video --conf 0.25 --nms 0.45 --tsize 640 --save_result --device [cpu/gpu]
```
</details>
