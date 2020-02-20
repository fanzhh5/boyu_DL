直接使用

```python
nltk.download(...)
```

会报requests.exceptions.SSLError



参考https://blog.csdn.net/sinat_34615726/article/details/73274720中的方法

命令台中下载首先要注意环境变量中的python是否Anaconda中的

但这两种方法都不work





work的方法：

下载地址：

https://github.com/explosion/spaCy

https://github.com/explosion/spacy-models/releases/tag/en_core_web_sm-2.2.0



将解压后的en_core_web_sm和en_core_web_sm.egg-info复制到Anaconda\Lib\site-packages下



重启pycharm或jupyter



load成功