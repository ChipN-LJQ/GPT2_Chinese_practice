# GPT2_Chinese_practice
<p align="center">
A GPT2 model with BERT tokenizers and trained with Doupo
</p>
这是一个使用BERT Tokenizers的中文GPT2模型，使用小说《斗破苍穹》全文进行训练，可以生成一段稍有逻辑的中国话（'^')

About setup<br>
cd到项目的根目录并运行"pip install -r requirements.txt"来完成包的配置<br>
如果你想训练一个全新的模型，请修改data/train.json中的文字为你自己的语料，并保持文件名“train.json”不变

About model<br>
你可以在[这里](https://pan.baidu.com/s/1cHO6XPgQqDCb2jhQnG7x0A?pwd=fine "fine")找到我已经训练好的模型文件<br>
model.zip内包含了10轮训练的模型和一个最终模型，使用它们只需将压缩包解压到项目的根目录，并确保为"your_project_path/model/final_model(...)"

About my train<br>
使用斗破苍穹语料，
