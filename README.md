# GPT2-Chinese
原项目：https://github.com/Morizeyao/GPT2-Chinese

### update:

支持transformers==4.27.1

gpt2使用./config/model_config_small.json 配置时，在colab上15G的GPU中运行时，会报内存不足。
所以改用 ./config/model_config_small.json。

运行命令：
python train.py  \
--raw --num_pieces=1 \
--model_config='config/model_config_test.json' \
--epochs=5