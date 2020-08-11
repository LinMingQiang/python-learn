配置依赖库
生成requirement文件
pip config set global.index-url https://mirrors.aliyun.com/pypi/simple/
pip install pipreqs
pipreqs --use-local ./
pip install -r requirements.txt

