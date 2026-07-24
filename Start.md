git第一次配置说明网址：https://git-scm.com/book/en/v2/Getting-Started-First-Time-Git-Setup
git config --global user.name "John Doe"
git config --global user.email johndoe@example.com

上传失败需要代理：搜索git set proxy
设置：
git config --global http.proxy http://xxx.xxx.xxx:8888
git config --global https.proxy https://xxx.xxx.xxx:8888
查看：
git config --get http.proxy
git config --get https.proxy
取消：
git config --global --unset http.proxy
git config --global --unset https.proxy