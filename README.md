# 如何使用 FFmpeg 进行视频转码

FFmpeg 是一个使用广泛的开源多媒体编解码器，其一大用途就是进行音频或视频的编码及格式转换。

FFmpeg 并不像它表面看上去那么高端，那么难。只是中文的资料实在太少，才造成了这样的表象。所以，我决定动手开启这个计划，为中文用户提供一个更简单易学的 FFmpeg 教程。

不过本教程只能让你成为 FFmpeg 用户，不能让你成为 FFmpeg 专家，专家的那些东西我也不明白。不过就大多数情况而言，你一辈子也用不到那些专家的东西。即使偶然用到， Google 足够作为你的伙伴了。

## 开始阅读

本书作者为 [@FiveYellowMice](https://github.com/FiveYellowMice)，可以在其 [Wiki](https://wiki.fiveyellowmice.com/wiki/%E5%A6%82%E4%BD%95%E4%BD%BF%E7%94%A8_FFmpeg_%E8%BF%9B%E8%A1%8C%E8%A7%86%E9%A2%91%E8%BD%AC%E7%A0%81:%E9%A6%96%E9%A1%B5) 上查看最新的版本。
同时 @gloomy-ghost 维护了一份 [GitBook](https://www.gitbook.com/book/gloomy-ghost/-ffmpeg/details) 镜像，在线阅读的体验会更好一些，甚至可以直接下载电子书以便离线阅读。镜像的更新频率相比 Wiki 会稍有延迟，同时请不要在 GitBook 上建议修改（因为不能保证上游能采纳啊）。

## 支持

如果你有意见或建议，请按照[这些步骤](etc/feedback/README.md)来提交问题。

如果你觉得我值得鼓励，点一下右上方的 Star 吧！

----------------------

![CC-BY-SA](image/by-sa.png)  
本作品采用知识共享 署名-相同方式共享 4.0 国际 许可协议进行许可，你可以在署名并采用相同条款的情况下自由复制、传播、再演绎本作品而无需通知作者。访问 <http://creativecommons.org/licenses/by-sa/4.0/> 查看该许可协议。
