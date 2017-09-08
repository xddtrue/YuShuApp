**`登陆接口`**：/interface/public/yushuapp/?service=User.login&account=12104A&pwd=888888 

**`首页获取信息接口`**：/interface/public/yushuapp/?service=Index.getIndexInfo 

**`业主申请接口`**：/interface/public/yushuapp/?service=User.register&user_name=ssdf&user_floor=21&user_room=504 

**`更新用户信息接口`**：/interface/public/yushuapp/?service=User.updateUserInfo&user_id=7&user_nickname=&user_name=&user_name_set=&user_sex=&user_headpic=&user_tel=&user_tel_set=&user_birthday=

**`根据userID获取用户信息接口`**：/interface/public/yushuapp/?service=User.getBaseInfo&user_id=5

**`所有视频接口`**：/interface/public/yushuapp/?service=Index.getAllVideos

**`所有图片接口`**：/interface/public/yushuapp/?service=Index.getAllImages

**`群主公告接口`**：/interface/public/yushuapp/?service=Index.getAdminnoticeInfo&user_id=5,其中字段praise_id为null时表示尚未点赞

**`物业人事接口`**：/interface/public/yushuapp/?service=Index.getpersonnelInfo

**`小区公约webview`**：/admin/webview/convention_display

**`轮播图webview`**：/admin/webview/slide_display/slide_id/8

**`群主公告webview`**：/admin/webview/adminnotice_display/adminnotice_id/2