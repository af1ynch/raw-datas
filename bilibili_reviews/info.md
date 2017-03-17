## 声明：本次公开的数据，仅限学习交流使用，未经允许不得作为商业用途，谢谢！

### 详细内容
4万条b站视频信息以及对应的视频弹幕文件
视频信息的存储格式为json，信息编码为：utf-8
格式如下：
'''js
{
    "allow_feed" : 0,
    "spid" : null,
    "partname" : "",
    "pic" : "http://i2.hdslb.com/bfs/archive/3f077d46f3793ac3ca1b1db72feae34dceeb6821.jpg",
    "tag" : "游戏集锦,少女さとり,YOUTUBE搬运,第四远古巨坟,东方,东方PROJECT,弹幕风,东方弾幕风,AV12",
    "face" : "http://i1.hdslb.com/bfs/face/268773dcd5b86f57e895f1983c973aa0f53ab086.jpg",
    "title" : "[東方弾幕風]音乐与弹幕同步 3.⑤",
    "review" : "1841",
    "coins" : "308",
    "mid" : "4694544",
    "arctype" : "Copy",
    "allow_download" : 1,
    "play" : "480955",
    "description" : "⑤/250",
    "tid" : 63,
    "cid" : 5925828,
    "video_review" : "1301",
    "favorites" : "3375",
    "pages" : 1,
    "src" : "c",
    "created" : 1246619416,
    "allow_bp" : 0,
    "created_at" : "2009-07-03 19:10",
    "author" : "AR-Gent",
    "offsite" : "http://share.acg.tv/flash.swf?aid=12&page=1",
    "typename" : "实况解说",
    "credit" : "145",
    ......
}
'''
视频弹幕按照视频所属的typename分类，存储格式为plaintext，文本编码为：utf-8
