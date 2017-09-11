**`登陆接口`**：/interface/public/yushuapp/?service=User.login&account=12104A&pwd=888888 

**`首页获取信息接口`**：/interface/public/yushuapp/?service=Index.getIndexInfo 

**`业主申请接口`**：/interface/public/yushuapp/?service=User.register&user_name=ssdf&user_floor=21&user_room=504 

**`更新用户信息接口`**：/interface/public/yushuapp/?service=User.updateUserInfo&user_id=7&user_nickname=&user_name=&user_name_set=&user_sex=&user_headpic=&user_tel=&user_tel_set=&user_birthday=

**`根据userID获取用户信息接口`**：/interface/public/yushuapp/?service=User.getBaseInfo&user_id=21

**`所有视频接口`**：/interface/public/yushuapp/?service=Index.getAllVideos

**`所有图片接口`**：/interface/public/yushuapp/?service=Index.getAllImages

**`图片上传接口`**：/interface/public/yushuapp/?service=Upload.Go

**`图片上传测试页面`**：/interface/public/yushuapp/upload.html

**`群主公告接口`**：/interface/public/yushuapp/?service=Index.getAdminnoticeInfo&user_id=21,其中字段praise_id为null时表示尚未点赞

**`物业人事接口`**：/interface/public/yushuapp/?service=Index.getpersonnelInfo

**`所有投票接口`**：/interface/public/yushuapp/?service=Index.getVoteInfo&user_id=21&page=1,其中字段praise_id为null时表示尚未点赞

**`获取投票详情`**：/interface/public/yushuapp/?service=Index.getVoteInfoById&vote_id=21&user_id=21

**`投票操作`**：/interface/public/yushuapp/?service=Index.doVote&user_id=21&vote_id=5&&vote_option_id=49

**`点赞操作`**：/interface/public/yushuapp/?service=Index.doPraise&user_id=21&praise_type=vote&&praise_item_id=1,
其中praise_type:装修指南-guide,民意投票-vote,闲置转让-transfer,御墅论坛-post

**`评论操作`**：/interface/public/yushuapp/?service=Index.doComment&user_id=21&comment_type=adminnotice&&comment_item_id=2&comment_desc=sdfd,
           其中comment_type:装修指南-guide,民意投票-vote,闲置转让-transfer,御墅论坛-post

**`获取评论列表`**：/interface/public/yushuapp/?service=Index.getCommentList&user_id=21&type=adminnotice&item_id=1&page=1

**`小区公约webview`**：/admin/webview/convention_display

**`轮播图webview`**：/admin/webview/slide_display/slide_id/8

**`群主公告webview`**：/admin/webview/adminnotice_display/adminnotice_id/2