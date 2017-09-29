
**`---------------------------------------------用户-------------------------------------------------`**

**`登陆接口`**：/interface/public/yushuapp/?service=User.login&account=12104A&pwd=888888 

**`业主申请接口`**：/interface/public/yushuapp/?service=User.register&user_name=ssdf&user_floor=21&user_room=504

**`更新用户信息接口`**：/interface/public/yushuapp/?service=User.updateUserInfo&user_id=7&user_nickname=&user_name=&user_name_set=&user_sex=&user_headpic=&user_tel=&user_tel_set=&user_birthday=

**`根据userID获取用户信息接口`**：/interface/public/yushuapp/?service=User.getBaseInfo&user_id=21



**`---------------------------------------------首页-------------------------------------------------`**

**`首页获取信息接口`**：/interface/public/yushuapp/?service=Index.getIndexInfo 

**`所有视频接口`**：/interface/public/yushuapp/?service=Index.getAllVideos

**`所有图片接口`**：/interface/public/yushuapp/?service=Index.getAllImages

**`图片上传接口`**：/interface/public/yushuapp/?service=Upload.Go

**`图片上传测试页面`**：/interface/public/yushuapp/upload.html

**`群主公告接口`**：/interface/public/yushuapp/?service=Index.getAdminnoticeInfo&user_id=21&page=1&type=1,其中type-1:群主公告 2：民政汇总

**`物业人事接口`**：/interface/public/yushuapp/?service=Index.getpersonnelInfo

**`所有投票接口`**：/interface/public/yushuapp/?service=Index.getVoteInfo&user_id=21&page=1

**`获取投票详情`**：/interface/public/yushuapp/?service=Index.getVoteInfoById&vote_id=21&user_id=21



**`获取头部信息`**：/interface/public/yushuapp/?service=Index.getHeadInfo&type=vote,其中type- 物业人事：personnel 民意投票：vote 邻里：user 图片：image 视频：video

**`小区公约webview`**：/admin/webview/convention_display

**`轮播图webview`**：/admin/webview/slide_display/slide_id/8

**`群主公告webview`**：/admin/webview/adminnotice_display/adminnotice_id/2

**`获取闲置转让列表`**：/interface/public/yushuapp/?service=Index.getTransferInfo&page=1

**`闲置转让发帖`**：/interface/public/yushuapp/?service=Index.doTransfer&transfer_title=aa&transfer_desc=33&transfer_type=1&user_id=21
,其中transfer_type-1:馈赠2：置换，图片支持多文件上传name为filelist[]



**`获取最新动态或公共建议列表`**：/interface/public/yushuapp/?service=Index.getPostInfo&page=1&post_type=1,其中post_type-1:最新动态2：公共建议

**`最新动态或公共建议发帖`**：/interface/public/yushuapp/?service=Index.doPost&post_title=aa&post_desc=33&post_type=1&user_id=21，图片支持多文件上传name为filelist[]

**`闲置转让测试发帖地址`**：/interface/public/yushuapp/uploadmulti.html

**`根据类别获取装修指南标签`**：/interface/public/yushuapp/?service=Index.getGuideTypeInfo&category=1

**`获取装修指南`**：/interface/public/yushuapp/?service=Index.getGuideInfo&page=1&guide_type_id=1

**`装修指南webview`**:/admin//webview/guide_display/guide_id/4


**`---------------------------------------------邻里----------------------------------------------------`**

**`获取楼号列表`**：/interface/public/yushuapp/?service=User.getFloorInfo

**`根据楼号获取户列表`**：/interface/public/yushuapp/?service=User.getRoomListByFloor&user_floor=21

**`根据户获取用户列表`**：/interface/public/yushuapp/?service=User.getUserListByRoom&user_floor=21&user_room=504

**`---------------------------------------------个人中心----------------------------------------------------`**

**`我的收藏`**：/interface/public/yushuapp/?service=User.getMyCollection&user_id=21&page=1

**`我的发布`**：/interface/public/yushuapp/?service=User.getMyPost&type=3&user_id=21,其中type-1:最新动态 2:闲置转让 3:公共建议

**`删除我的发布`**：/interface/public/yushuapp/?service=Index.deletePost&&item_id=1&user_id=21&type=post

**`------------------------------------------投票，点赞，评论,收藏,删除（操作）--------------------------------------`**

**`获取评论列表`**：/interface/public/yushuapp/?service=Index.getCommentList&user_id=21&type=adminnotice&item_id=1&page=1

**`获取点赞列表`**：/interface/public/yushuapp/?service=Index.getPraiseList&user_id=21&type=adminnotice&item_id=2

**`投票操作`**：/interface/public/yushuapp/?service=Index.doVote&user_id=21&vote_id=5&&vote_option_id=49

**`点赞操作`**：/interface/public/yushuapp/?service=Index.doPraise&user_id=21&praise_type=vote&praise_item_id=1&cancle=0,
其中praise_type:装修指南-guide,民意投票-vote,闲置转让-transfer,御墅论坛-post,cancle :0-点赞 1-取消点赞

**`评论操作`**：/interface/public/yushuapp/?service=Index.doComment&user_id=21&comment_type=adminnotice&&comment_item_id=2&comment_desc=sdfd,
其中comment_type:装修指南-guide,民意投票-vote,闲置转让-transfer,御墅论坛-post
           
**`收藏操作`**：/interface/public/yushuapp/?service=Index.doCollection&user_id=21&collection_type=vote&&collection_item_id=1&cancle=0,
 其中collection_type:装修指南-guide,民意投票-vote,闲置转让-transfer,御墅论坛-post  cancle :0-点赞 1-取消点赞
         
**`删除评论操作`**： /interface/public/yushuapp/?service=Index.deleteComment&&comment_id=1&user_id=21       

**`获取是否点赞和收藏`**：/interface/public/yushuapp/?service=Index.getMyRelationWithItem&&item_id=2&user_id=21&type=adminnotice



