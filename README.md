# manticoresearch chart

全文搜索引擎，官方地址：https://manticoresearch.com/

## 打包
```
helm package .
```

## 安装
```
helm install ./manticoresearch-0.0.1.tgz \
         --version=0.0.1 \
         --name manticore \
         --namespace manticore-test
```         
