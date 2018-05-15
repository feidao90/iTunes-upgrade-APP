# iTunes-upgrade-APP
利用 iTunes 接口检查 App 版本更新
这是 iTunes 接口地址 ，有兴趣可以看一下，我们要用到的接口如下，xxx 处换成自己 App 的 AppId ，AppId 可以在 iTunes Connect 里面看到。
http://itunes.apple.com/lookup?id=xxx

{
    "resultCount" : 1,
    "results" : [{
        "artistId" : "开发者 ID",
        "artistName" : "开发者名称",
        "trackCensoredName" : "审查名称",
        "trackContentRating" : "评级",
        "trackId" : "应用程序 ID",
        "trackName" = "应用程序名称",
        "trackViewUrl" = "应用程序下载网址",
        "userRatingCount" = "用户评论数量",
        "userRatingCountForCurrentVersion" = "当前版本的用户评论数量",
        "version" = "版本号"
    }]
}
