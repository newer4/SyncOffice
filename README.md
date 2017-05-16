# <b>协同办公平台</b>
## <b>简介：</b>

> 这是一个具备集群管理，消息组播和单播，文件管理和传输，等主要功能的工具。
 具体来说当你正式注册进入这个工具的时候，你就已经具备了用户，组员，集团管理员这三种身份。该项目并没有引入好友这个概念，原因如下，这是一个以协同办公为主要目标的程序，该项目定位的受众为公司集团。

## <b>关系：</b>
 你可以选择加入某个已经存在的集团，或者自己创建属于自己的集团并且邀请他人加入你的集团，如果你加入了某个集团而你自己也同样拥有自己的集团，那么 你可以设置自己的子集团是否归属于父集团。如果允许归属，那么父集团与子集团即建立了双向继承的关系。

## <b>双向继承：</b>
> 如果你加入的集团，被归属于其他的集团了，你自己可以设置自己是否归属于你所属集团的父集团，以及你的集团是否归属于你的父集团，如果你的集团已经归 属于你的父集团了，那么你的集团将被归属于你父集团的父集团。

<hr>

## <b>管理：</b>
<hr>

- ##  当你担任组员这一角色的时候：
> 你所在集团的集团管理员可以向你发出任务，需求，提醒，新闻发布等，当你的集团管理员向你请求获取你的归属权和消息接收权的时候，你可以选择给予权限 或者拒绝，你可以向你的集团管理员提交你的任务和请求，需要通过集团管理员的审批。你可以同你的组内成员，进行消息互通，里面包含文本传输，图像传输，文件传输（暂定如下，详情细说），如果你所在的集团被归属于某父集团，那么你也同样可以同他们进行沟通（双向继承），当然你也可以设置不被当前集团外 的成员骚扰。

- ## 当你担任管理员之一角色的时候：

> 你可以向你所拥有的集团发送任何的需求，提醒，以及下发任务。你可以选择哪一类人或者那一个人无法接收到你的组播消息，因为有时候消息发布是针对某一部门的。你当然也可以同你集团内的成员以普通成员的身份进行消息互通。对于在集团的从属问题上，你可以向你的成员请求权限，或者在加入集团的时候就要求其提供后期所需要的权限，也就是成员允许管理员将其划分到任何集团，如果对方不给予你权限，你可以选择将其踢出集团，当然就算同意你也可以踢（管理员无条件踢人）。当你加入了其他集团的时候，你可以设置你自己的集团是否拥有被你所加入的集团访问的权限，当你允许了访问权限的时候，你所加入的集团将可以直接向你的组员下发需求，提醒，任务等，你的组员们也同样可以同你加入的集团的成员们互通消息，如果你拥有了你组员的归属权和消息接收权，那么你所加入的集团管理员将拥有你所有的权利，接着你将失去你的权利，直到你退出你所加入的集团。如果你拒绝的父集团的访问权限，你依旧可以就收到父集团所下发的消息，并且可以将其转发给你的集团或个人。如果你退出了你所加入的集团并且你将自己的集团归属了进去，你可以选择将你的集团一同退出，此时你将恢复你之前所有的权限，如果你以个人身份退出的话，你将永久失去你的权限，你的组员将留在之前的公司内。

<hr>

## <b>分工：</b>
<hr>

## 小组成员：

### <b>裴鉴湘：</b>
项目架构，整体的设计，数据库开发，后台架构，部分前端开发。其中：项目架构主要采用MVC模式，整体的设计需要考虑到项目需求和实际的应用以及技术限制，数据库开发需要将所有的查询封装成存储过程，将所有的数据操作封装成事务，主动响应触发器。后台架构主要是对各个业务逻辑的封装，让三层结构清晰。前段开发我主要负责相关的特效处理和兼容性适配。

### <b>易永杰：</b>
后端开发和前端开发，主要负责大量的前端工作，对各个特效的把控和对数据循环呈现的实现，封装一部分项目需要的前端相关结构。负责前后端交互的结构。负责的页面包括起始页和主页，需要操作的部分是相关js脚本，和网页部分结构。

### <b>刘欢：</b>
后端开发和前端开发，主要负责大量的后端工作，将各个数据访问层提供的数据封装成相应的对象，完成业务逻辑操作，提供一个功能性的后台核心，同时需要保障数据传递的健全稳定和数据处理的精确应需。

### <b>王鹏：</b>
后端开发和前端开发，主要负责大量的后端工作，将各个数据访问层提供的数据封装成相应的对象，完成业务逻辑操作，提供一个功能性的后台核心，同时需要保障数据传递的健全稳定和数据处理的精确应需。

<hr>

## <b>结语：</b>
本项目的所有模块全部属于原创，除开框架外的所有代码都是自己所为，不存在任何抄袭，也没有套用任何的模板。主要开发工具为VSCode，Vim，Sublime等富文本编辑器，这个项目是小组成员辛勤的劳动成果。现阶段还有大部分的结构和计划没有确定，还有大部分的工作没有完成。到时候还会多出几个版本，对各个版本进行性能调优，debug之后，再优选出最佳作品作为我们的最终项目。

## <b>声明：</b>
本项目为纯粹的开源项目，本项目遵循GPLv3协议，如果你有任何的需要，欢迎采用我们的项目。如果需要进行修改和发布，请注明出处并且遵守GPLv3协议公开源代码。
我们的项目发布地址：
[https://github.com/InNoob/SyncOffice.git](https://github.com/InNoob/SyncOffice.git)
<font align="right">
#  协同办公项目小组敬上
## 2017年05月13日
</font>