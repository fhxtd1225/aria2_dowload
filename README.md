# 对于国内用户 下载huggingface模型的方法
为了节省时间，我把作者中说明精简了一下。
## 下载moirx（单文件版本就可以了）
  - 查看rpc监听端口与token
## py文件里设置rpc内容，把huggingface的mode名称复制设置“model_id”
```python
server_url = "http://localhost:19628/rpc"
token = '113113'
root_path = "f:/downloads"
model_id = "THUDM/chatglm2-6b"
rpc = RPCSender(server_url, token, download_root_path=root_path)
```
## 依次运行就运行就可以了
