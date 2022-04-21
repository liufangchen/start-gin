# Gin case

<toc>

<p align="center"><b> <a href="./readme.md"> 中文 </a> | English </b></p>

- [Quick start](#Quick-start)
    - [Deploy via command line tool](#Deploy-via-command-line-tools)
- [Application details](#Application-details)
- [About Us](#About-Us)

</toc>

# Quick start

- [:octocat: source](https://github.com/liufangchen/start-gin)
- [:earth_africa: Effect Preview](http://start-gin.demoservice.1401662146685254.cn-hangzhou.fc.devsapp.net/)

## Deploy via command line tools

> Before starting, you need to install the Serverless Devs developer tools: `npm install @serverless-devs/s -g`, for more installation methods, please refer to [Serverless Devs Installation Documentation](https://www.serverless-devs.com/serverless-devs/install) , you also need to configure key information for Alibaba Cloud. For the method of configuring key information, please refer to [Alibaba Cloud Key Configuration Document](https://www.serverless-devs.com/fc/config)
- Initialize the project: `s init start-gin -d start-gin`
    > It involves determining the selection of the key, the determination of the service name, the determination of the function name, and the determination of the container image
- Enter the project: `cd start-gin`
- Deploy the project: `s deploy -y`
- Invoke： According to the returned `url` information, you can make a request in the browser

# Application details

This project is to deploy the very popular static site framework `Gin` to Aliyun Serverless platform (Function Compute FC).

> The fastest full-featured web framework for Go。

By Serverless Devs developer tools, you only need a few steps to experience the technical bonus of reducing costs and improving efficiency brought by Serverless architecture.

 After the deployment is completed, you can see the case address returned to you by the system, for example:

![Picture alt](https://github.com/liufangchen/Resource/raw/start-gin/url.png)

At this time, open the case address and you can see the application details of the test:

![Picture alt](https://github.com/liufangchen/Resource/raw/start-gin/view.png)


# Links
- Serverless Devs Tools:
    - Repository: [https://www.github.com/serverless-devs/serverless-devs](https://www.github.com/serverless-devs/serverless-devs)
    - Official website: [https://www.serverless-devs.com/](https://www.serverless-devs.com/)
- Alibaba Cloud Function Compute components:
    - Repository: [https://github.com/devsapp/fc](https://github.com/devsapp/fc)
    - Help document: [https://www.serverless-devs.com/fc/readme](https://www.serverless-devs.com/fc/readme)
- Gin：
    - Repository：[https://github.com/gin-gonic/gin](https://github.com/gin-gonic/gin)
    - Official website：[https://gin-gonic.com/](https://gin-gonic.com/)