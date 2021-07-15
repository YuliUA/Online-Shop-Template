This simple site tamplate was made : 
#just proxy for github.com
git config --global http.https://github.com.proxy socks5://127.0.0.1:1080
git config --global http.https://github.com.sslVerify false
git config --global https.https://github.com.proxy socks5://127.0.0.1:1080
git config --global https.https://github.com.sslVerify false

#cancel proxy
git config --global --unset http.https://github.com.proxy
git config --global --unset http.https://github.com.sslVerify
git config --global --unset https.https://github.com.proxy
git config --global --unset https.https://github.com.sslVerify
