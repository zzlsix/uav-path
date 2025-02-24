# quick start
在[reference](#reference)中下载大疆官方示模型，[main.py](main.py)文件中修改 `MODEL_PATH` 变量为模型路径，运行即可  

注意：
+ `MODEL_PATH` 的值修改为本地`.obj`3D模型文件的路径
+ 路径最好不要有中文，否则可能不兼容，出现解码错误

# dependence
```python
pip install open3d
```
# reference
+ [大疆官方示例模型下载链接](https://terra-1-g.djicdn.com/71a7d383e71a4fb8887a310eb746b47f/terra-cloud-api/v1.0/Three-Dimension-3D.zip)
+ https://gist.github.com/kylevedder/33fafceb5a32917270b5e555d3591439