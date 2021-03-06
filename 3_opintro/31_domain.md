

# 域名管理
![](/images/15971409870678.jpg)


### 添加域名
![](/images/15971410007465.jpg)

#### 参数说明

  - 域名：用户的网站域名
  - 源站IP：对应的网站源站地址 ，协议类型 ，端口设置
  - 部署区域：UWAF为受保护域名的配置生成区域
  - 使用独享IP：是否为该域名独立分配一个IP
  - 获取真实IP设置：可以指定字段，以此为根据，得到第三方代理的真实IP
  - SSL证书：需要上传（如果是在USSL购买的证书，则默认提供证书自动同步的功能）
  - HTTPS强制跳转：是否开启HTTP转HTTPS的强制跳转（该服务开启后，不可配置80端口业务）

### 域名列表
![](/images/15971409870678.jpg)

#### 参数说明

  - 域名：防护的域名。
  - CNAME：UWAF返回的CNAME别名，添加域名成功后，使用此CNAME域名更改dns的解析，参见帮助。
  - 业务可用性：提示http和https的连通性。
  - 解析状态：当前UWAF DNS解析记录是否正常。
  - 部署区域：UWAF为受保护域名的配置生成区域。
  - 工作模式：记录但不拦截，指对攻击行为只进行记录不进行拦截。启用防护规则，指对攻击行为按配置的规则和系统默认规则进行拦截。
  - 今日攻击数：统计当天发生的攻击总数。
  - 功能状态：显示是cc防护和网页防篡改功能是开启还是关闭的状态
  - 操作：
    * 安全报表 （跳转至安全报表页面）
    * 防护设置 （跳转至防护设置页面）
    * 功能设置 （跳转至功能设置页面）
    * 编辑 （进入域名配置编辑界面）
    * 删除 （删除该域名记录）
    * 更多
       * 回源设置
       * 监控设置
