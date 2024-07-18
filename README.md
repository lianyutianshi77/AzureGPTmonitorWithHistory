安装： sh init_app.sh

# 获取 Azure OpenAI 的资源列表
# cd $app_home 
# . .venv/bin/activate
# python utils/fetch_all_aoai_resources.py # 将配置保存在表格中
# python utils/insert_gpt_resources_to_db.py # 将表格中配置保存到sqlite的data/data.db中，若要从文件中读取配置，可不执行，将 utils/gpt_request.py 文件的 168 行和 251 行 的 'db' 改为 'file'

# 修改图片的链接，可访问的图片的url
# utils/gpt_request.py 的 171 行的 images = []

启动： sh server_call.sh start

效果展示：
![image](https://github.com/user-attachments/assets/1e6d590d-b0f5-4a08-a43c-f75b1e0d247c)
