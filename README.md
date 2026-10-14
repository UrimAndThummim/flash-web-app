# flash-web-app

使用 Flask 编写的 Web 示例项目，通过 GitHub Actions 自动测试并经 SSH 部署到头歌服务器。

## 本地运行

```bash
pip install -r requirements.txt
python src/app.py
```

## 本地测试

```bash
pip install pytest
pytest tests/ -v
```
