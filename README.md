莉莉的问答系统
==============

    给莉莉做的《程序设计基础》网上答疑系统，基于Node.js（初学Node.js之作）

登录注册
--------

   + 登录模块（分学生、教师、管理员）
   + 注册模块 (注册只是学生注册，教师&管理员帐号由后台添加)
   + 忘记密码

学生模块
--------

   + 首页

      一个公告 + 提问的图标数据统计

   + 我要提问

      + 问机器人

         自动读取数据库拥有的数据进行反馈，若没有，记录这个问题

      + 提问老师

         问题、分类、章节、专题以及提问给谁（指老师），提问后会给相应的老师发送一封通知邮件

      + 问题中心

         查看所有的问题库

   + 我提问的

     + 已解决 

       + 当老师回答这个问题后，自动推送一条页内通知，类似微博的私信通知

     + 未解决

       + 问题未解决状态时，问题可以进行 修改&删除

     + 机器人

   + 个人资料

     + 学生的个人信息 查看&修改

教师模块
--------

  + 首页

    一个公告 + 被提问的图标数据统计

  + 邀请我回答的
  
    + 已解决

    + 未解决

      + 当未解决时，自动推送一条页内通知，类似微博的私信通知

      + 解决后，会给相应的提问的学生发送一封通知邮件

  + 个人资料

    + 老师的个人信息 查看&修改


问题管理模块
------------
   
   老师&管理员 有权限进行问题的管理

   + 问题列表
     
     + 所有的问题，包括 有答案和没有答案

   + 分类列表
    
     + 问题分类子目，可以进行问题分类的 查看&修改&删除

   + 章节列表

     + 问题章节子目，可以进行问题章节的 查看&修改&删除

   + 专题列表

     + 问题专题子目，可以进行问题专题的 查看&修改&删除

   + 搜索功能

     + 根据相应的 分类|章节|专题|关键字 检索问题

公告模块
--------

  公告的发布，前台公告中，会显示有效期内最后的一条公告

  公告由管理员进行操作和管理

用户模块
--------

  用户信息列表，可以进行信息的查看&修改&删除

  管理员进行操作和管理

  + 学生 （用户名、邮箱、性别、注册时间、最后登入时间）

  + 老师 （真实姓名、用户名、邮箱、性别、所属学校、最近登入时间）

    只能由后台进行添加新老师

  + 管理员 （用户名、邮箱、级别、最近登入时间）

     只能由后台进行添加新管理员

友情链接模块
------------
  
   友情链接的添加和管理