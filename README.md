# hosts  

## Note  
每日自动更新 github, docker 和 tinyMediaManager 的 IP 地址。  

hosts Url:   
Raw Url: ``` https://raw.githubusercontent.com/heyue07/hosts/main/hosts ```  
CDN Url: ``` https://gcore.jsdelivr.net/gh/heyue07/hosts@main/hosts ```  
CDN Url: ``` https://cdn.staticaly.com/gh/heyue07/hosts/main/hosts ```    ```(推荐)```  

## Used  
Windows/MacOS:  
```
推荐使用 SwitchHosts, 官网查看：https://swh.app/zh
```
![image](https://github.com/heyue07/hosts/raw/main/1.png)

Linux:
```
# 删除
sudo sed -i '/# ING Hosts Start/,/# ING Hosts End/d' /etc/hosts
# 添加
curl -s -L https://raw.githubusercontent.com/heyue07/hosts/main/hosts | sudo tee -a /etc/hosts
```
