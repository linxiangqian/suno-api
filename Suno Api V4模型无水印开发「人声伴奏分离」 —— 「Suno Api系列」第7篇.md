

历史文章

Suno AI API接入 - 将AI音乐接入到自己的产品中，支持120并发任务

Suno Api V4模型无水印开发「灵感模式」 —— 「Suno Api系列」第1篇

Suno Api V4模型无水印开发「自定义模式」 —— 「Suno Api系列」第2篇

Suno Api V4模型无水印开发「AI生成歌词」 —— 「Suno Api系列」第3篇

Suno Api V4模型无水印开发「续写」 —— 「Suno Api系列」第4篇

Suno Api V4模型无水印开发「获取整首歌」 —— 「Suno Api系列」第5篇

Suno Api V4模型无水印开发「高清音频WAV下载」 —— 「Suno Api系列」第6篇





导读

今天来看下Suno Api的人声伴奏分离。

人声伴奏分离顾名思义就是将人声和伴奏（乐器）的声音分离成两个音频文件。

这个功能对于各大音乐平台要证明是原创有很大的作用，所以这个功能相当的重要。





申请和使用

「已经有API的，可以跳过此步骤」

要使用Suno AI API，首先可以先登录到站点：

https://suno4.cn/#/?i=8NCBS8_WXTT

点击头像昵称旁边的… ,点击API接入






然后获取请求所需要的凭证：






如果你尚未登录或注册，会自动跳转到登录页面邀请您来注册和登录，登录注册之后会自动返回当前页面。

接口文档

接口文档地址：

https://doc.apipost.net/docs/3769af043c83000?locale=zh-cn







人声伴奏分离

人声伴奏分离，只需要传入歌曲id参数：








响应成功的话，会返回创作任务信息。








获取创作任务

获取分离任务，通过和音乐创作进度相同的接口即可获取最终的合并状态：








响应数据如下：






最终可以获取到两个mp3文件，一个人声Mp3，一个伴奏mp3。





历史文章

Suno AI API接入 - 将AI音乐接入到自己的产品中，支持120并发任务

Suno Api V4模型无水印开发「灵感模式」 —— 「Suno Api系列」第1篇

Suno Api V4模型无水印开发「自定义模式」 —— 「Suno Api系列」第2篇

Suno Api V4模型无水印开发「AI生成歌词」 —— 「Suno Api系列」第3篇

Suno Api V4模型无水印开发「续写」 —— 「Suno Api系列」第4篇

Suno Api V4模型无水印开发「获取整首歌」 —— 「Suno Api系列」第5篇

Suno Api V4模型无水印开发「高清音频WAV下载」 —— 「Suno Api系列」第6篇

