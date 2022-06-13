# final-1
本题选择的开源模型为BiSeNetV2

对视频进行语义分割：
```sh
$ python tools/demo_video.py --config configs/bisenetv2_city.py --weight-path pretrained/model_final_v2_city.pth --input ./video.mp4 --output res.mp4
```
