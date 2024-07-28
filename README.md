[English](#english) | [简体中文](#%E7%AE%80%E4%BD%93%E4%B8%AD%E6%96%87)

<br>

# English

This repository is a deployment example of Clash-Parser-Online on Vercel.

For details, please refer to the original repository: https://github.com/InoryS/Clash-Parser-Online

### Warning

> When deploying with Vercel, request query parameters will be logged in error responses, and your subscription information might be exposed to me.
> 
> Additionally, with just one more line of code, it's possible to view recorded query parameters in Vercel without needing an error response.
> 
> Therefore, it's strongly recommended that you deploy your own example rather than using someone else's service.
>
> Although this repository doesn't include such features, I still recommend using your own code. Of course, if you're willing to intentionally create erroneous requests and share them with me, that's even better (just kidding).
>
> Also, you need to pay attention to vercel.json, I use the redirection feature in vercel.json to protect sensitive files from external access, you may want to make sure it is applied correctly.

### Deployment Guide

1. Fork this repository and set it as a private repository.
2. Log in to your Vercel account and import the forked repository.
3. Select Other for the framework preset and keep the default build settings unchanged.
4. Wait for the deployment to finish.
5. Once completed, the service will be available.

Alternatively, you can organize the files following this repository's structure and deploy them manually.

### Notes

1. I am too lazy to update this warehouse code. Please get the latest code from the original warehouse. Generally, copy the main program code from the original git repository and update it to your repository.
2. When deploying on Vercel, the request path should be in the form of `https://example.com/api?` or `https://example.com/api/?`, not the root directory.
3. Example request path: `https://clash-parser-online-vercel.vercel.app/api?source=jynb&mixin=jynb`
4. You can visit to see what will be returned. The source.txt contains the original subscription link, which is obtained by [subscription conversion](https://github.com/tindy2013/subconverter) in the clash.yaml of this repository.

### Comparison
Request separately
Original link:
```
https://sub.xeton.dev/sub?target=clash&url=https%3A%2F%2Fraw.githubusercontent.com%2FInoryS%2FClash-Parser-Online-Vercel%2Fmain%2Fclash.yaml&insert=false&config=https%3A%2F%2Fraw.githubusercontent.com%2FACL4SSR%2FACL4SSR%2Fmaster%2FClash%2Fconfig%2FACL4SSR _Online_Full_MultiMode.ini&emoji=true&list=false&tfo=true&fdn=false&sort=true&clash.doh=true&new_name=true&append_type=true&udp=true&interval=43200&tls13=true&scv=false
```
Links processed by this repository:
```
https://clash-parser-online-vercel.vercel.app/api?source=jynb&mixin=jynb
```

See what the difference is

<br>
<br>
<br>
<br>
<br>
<br>


# 简体中文

此仓库是 Clash-Parser-Online 的 Vercel 的部署示例。

有关详细信息，请参考原仓库：https://github.com/InoryS/Clash-Parser-Online

### 警告

> 使用 Vercel 部署时，请求的查询参数在错误响应中会被记录，您的订阅信息有可能会泄露给我。
> 
> 此外只需要增加 1 行代码，即可在 Vercel 中看到记录查询参数，而无需是错误响应。
> 
> 因此，强烈建议您部署自己的示例，而不要使用他人搭建的服务。
>
> 虽然本仓库代码不含此功能，但我还是建议使用你自己的，当然你愿意故意构造错误请求分享给我看见就更好了（不是）
>
> 另外，你需要留意 vercel.json，我使用 vercel.json 中的重定向功能来保护敏感文件不可被外部访问，你可能想要确认其被正确应用。

### 部署指南
1. Fork 本仓库，并将其设置为私有仓库。
2. 使用您的 Vercel 账户登录并导入刚刚 Fork 的仓库。
3. 框架预设选择 Other，保持默认的构建设置不变。
4. 等待部署完成。
5. 部署完成后即可使用。

或者，您也可以按照本仓库的文件结构组织文件，然后手动部署。

### 注意事项

1. 我懒得更新此仓库代码，最新代码请从原仓库获取，一般从原仓库复制一下主程序代码然后更新到你的仓库即可。
2. 在 Vercel 部署时，请求路径应形如 `https://example.com/api?` 或 `https://example.com/api/?`，而非根目录。
3. 请求路径例：`https://clash-parser-online-vercel.vercel.app/api?source=jynb&mixin=jynb` 
4. 你可以访问查看会返回什么，source.txt 内有原订阅连接，该订阅连接是由本仓库的 clash.yaml 进行[订阅转换](https://github.com/tindy2013/subconverter)得到的。


### 对比
分别请求

原链接：
```
https://sub.xeton.dev/sub?target=clash&url=https%3A%2F%2Fraw.githubusercontent.com%2FInoryS%2FClash-Parser-Online-Vercel%2Fmain%2Fclash.yaml&insert=false&config=https%3A%2F%2Fraw.githubusercontent.com%2FACL4SSR%2FACL4SSR%2Fmaster%2FClash%2Fconfig%2FACL4SSR_Online_Full_MultiMode.ini&emoji=true&list=false&tfo=true&fdn=false&sort=true&clash.doh=true&new_name=true&append_type=true&udp=true&interval=43200&tls13=true&scv=false
```
和本仓库处理过的链接：
```
https://clash-parser-online-vercel.vercel.app/api?source=jynb&mixin=jynb
```

看看有什么不同

