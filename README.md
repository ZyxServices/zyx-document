# zyx-document
# 返回参数-1.0

###活动

> 接口-/v2/activity/query  /v2/my/activity/create/list -- 返回注释

id 活动ID<br />
user 创建者 <br />
title 活动标题<br />
imgUrls 活动图片<br />
activityType 活动分类(0 求约, 1 求带)<br />
startTime 活动开始时间<br />
endTime 活动结束时间<br />
lastTime 报名截至时间<br />
maxPeople 活动人数上限<br />
paymentType 付费类型（0奖励 1免费 2AA）<br />
memberPeople 活动报名人数<br />
price 活动价格<br />
zan 点赞<br />
commentNumber 评论<br />

> 接口--/v2/activity/activityById  -- 返回注释

id<br />
user 创建者(用户ID) <br />
title 活动标题<br />
descContent 活动描述<br />
imgUrls 活动图片<br />
activityType 活动分类 （0 求约, 1 求带）<br />
activityModule 预留<br />
startTime 活动开始时间<br />
endTime 活动结束时间<br />
lastTime 报名截至时间<br />
maxPeople 活动人数上限<br />
address 活动地址<br />
city 活动发布城市<br />
paymentType 付费类型（0奖励 1免费 2AA）<br />
price 活动价格<br />
targetUrl 线上地址 <br />
createTime 创建时间<br />
editDescImgUrl 预留<br />

###场馆
>接口- /v2/venue/findVenue  /v2/venue/findVenueById -- 返回注释

id<br />
type 场馆类型（1-室内 2-室外）<br />
name 场馆名称<br />
longitude 经度<br />
latitude 纬度<br />
city 冗余标注所属城市便于展示<br />
mark 描述标签<br />
description 场馆介绍<br />
phone 联系电话<br />
address 场馆地址<br />
imgUrls 场馆封面<br />
level 场馆综合难度<br />
create_time 创建时间<br />
distance 距离当前位置多少米<br />
pnumber 到过场馆的人数<br />
