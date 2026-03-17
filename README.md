# 找工作平台

这是一个用Python Flask构建的简单找工作平台，用户可以通过表单发布任务，其他用户可以通过内置聊天功能与发布者留言。

## 功能

- 发布任务：任何人都可以填写表单发布工作任务。
- 查看任务：浏览所有发布的任务。
- 聊天留言：每个任务下有留言功能，用户可以给发布者发送消息。

## 安装和运行

1. 克隆仓库：
   ```
   git clone https://github.com/ruyizhang1989/FreeInternet.git
   cd FreeInternet
   ```

2. 创建虚拟环境：
   ```
   python3 -m venv venv
   source venv/bin/activate
   ```

3. 安装依赖：
   ```
   pip install -r requirements.txt
   ```

4. 运行应用：
   ```
   python app.py
   ```

5. 打开浏览器访问 `http://127.0.0.1:5000/`

## 技术栈

- 后端：Flask
- 数据库：SQLite (通过SQLAlchemy)
- 前端：HTML, CSS, Jinja2模板