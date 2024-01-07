# XENBLOCKS - Effortless GPU Mining on VAST.AI 
URL: [Vast.ai](https://cloud.vast.ai/?ref_id=87730)

   
**购买算力**
- 注册 [Vast.ai](https://vast.ai?ref_id=87730) 你自己的账号
- 充值 [https://cloud.vast.ai/billing/](https://cloud.vast.ai/billing/?ref_id=87730) (选择coinbase充值模式)
- 跳转到链接 [https://cloud.vast.ai/templates/](https://cloud.vast.ai/templates/?ref_id=87730)
- 选择   Cuda:12.0.1-Devel-Ubuntu20.04 模版:  

![image](https://github.com/JozefJarosciak/xgpu/assets/3492464/cf8fb6fa-3747-4777-aafc-5d025f4f12ce)

- 按需选择GPU服务器的配置(其中"unverified machines" 表示该GPU机器没有通过vast的测试,但是价格低一半左右,但有可能有稳定性问题,比如算力低/运行过程算力下降等)
![image](https://github.com/JozefJarosciak/xgpu/assets/3492464/1d7a937c-8f64-453b-8ff1-b8b169f427df)

- 点击"RENT"按钮服务器将出现在您租用的实例列表中 at: [https://cloud.vast.ai/instances/](https://cloud.vast.ai/instances/?ref_id=87730).   

- 点击"CONNECT"按钮,使用ssh命令行工具链接到你的服务器:

  linux shh客户端使用方法: [https://cloud.vast.ai/templates/](https://vast.ai/faq#how-do-i-connect-to-an-ssh-instance-on-linuxmac](https://vast.ai/faq#how-do-i-connect-to-an-ssh-instance-on-linuxmac?ref_id=87730)

  Windows shh客户端使用方法: [https://vast.ai/docs/guides/windows-ssh-scp-guide](https://vast.ai/docs/guides/windows-ssh-scp-guide?ref_id=87730)

- 完成后，单击"CONNECT"按钮，复制连接 URL 并将其粘贴到您选择的命令行工具中.
 

**开启服务**

-  把命令中的0xC89091210113E922c2Fd7f0DFFebbc9F0dd08ECE地址替换成您的个人地址
     
  1XGPU用vast.sh:
  ```
  sudo apt update && sudo apt -y install wget && sudo wget https://raw.githubusercontent.com/szin5535/xgpu/main/vast.sh && sudo chmod +x vast.sh &&  sudo ./vast.sh 0xC89091210113E922c2Fd7f0DFFebbc9F0dd08ECE
  ```

  2XGPU用vast2.sh:
  ```
    sudo apt update && sudo apt -y install wget && sudo wget https://raw.githubusercontent.com/szin5535/xgpu/main/vast2.sh && sudo chmod +x vast2.sh && &&  sudo ./vast2.sh 0xC89091210113E922c2Fd7f0DFFebbc9F0dd08ECE
  ```      

  4XGPU用vast4.sh:
  ```
  sudo apt update && sudo apt -y install wget && sudo wget https://raw.githubusercontent.com/szin5535/xgpu/main/vast4.sh && sudo chmod +x vast4.sh && &&  sudo ./vast4.sh 0xC89091210113E922c2Fd7f0DFFebbc9F0dd08ECE
  ```      

  8XGPU用vast8.sh:
 
  ```
  sudo apt update && sudo apt -y install wget && sudo wget https://raw.githubusercontent.com/szin5535/xgpu/main/vast8.sh && sudo chmod +x vast8.sh && &&  sudo ./vast8.sh 0xC89091210113E922c2Fd7f0DFFebbc9F0dd08ECE
  ```

  12XGPU用vast12.sh:
  ```
  sudo apt update && sudo apt -y install wget && sudo wget https://raw.githubusercontent.com/szin5535/xgpu/main/vast12.sh && sudo chmod +x vast12.sh && &&  sudo ./vast12.sh 0xC89091210113E922c2Fd7f0DFFebbc9F0dd08ECE
  ```

  14XGPU用vast14.sh::
  ```
  sudo apt update && sudo apt -y install wget && sudo wget https://raw.githubusercontent.com/szin5535/xgpu/main/vast14.sh && sudo chmod +x vast14.sh && &&  sudo ./vast14.sh 0xC89091210113E922c2Fd7f0DFFebbc9F0dd08ECE
  ```      
