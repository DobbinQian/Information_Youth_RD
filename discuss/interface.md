# 接口文档讨论

| 编号 | 版块名称 | 大致内容                      | 提出建议                                                                    | 提出时间   | 讨论时间   | 讨论结果                                                   |
| ---- | -------- | ----------------------------- | --------------------------------------------------------------------------- | ---------- | ---------- | ---------------------------------------------------------- |
| 1    | 公共     | /getPS                        | 建议删除，直接获取版块信息和用户信息                                        | 2019-10-31 | 2019-11-05 | ---                                                        |
| 2    | 首页     | /getNewsList                  | 建议删除，之前说新闻列表公用一个组件，可通过一个接口请求比如/getNewsByClass | 2019-10-31 | 2019-11-05 | ---                                                        |
| 3    | 登录     | /login                        | 登录后，返回需用户基本数据，储存到前端状态管理组件中                        | 2019-10-31 | 2019-11-05 | 用户基本信息                                               |
| 4    | 更多     | /user/editFollowPlate         | 不太懂 queen                                                                | 2019-10-31 | 2019-11-05 | 改变保存形式为直接保存前台的 json 数据，项目最后再实现修改 |
| 5    | 详情     | 详情页的/getArticle           | 没有正文参数                                                                | 2019-10-31 | 2019-11-05 | 增加 content 参数                                          |
| 6    | 公共     | 当前页数、一页的容量          | 不太懂区别                                                                  | 2019-10-31 | 2019-11-05 | 已理解                                                     |
| 7    | 公共     | /user/getActionList           | 动态的 image 参数没有，是否需要发布人 ID                                    | 2019-10-31 | 2019-11-05 | 需增加                                                     |
| 8    | 注册     | /register                     | 是否需要注册图片验证码                                                      | 2019-10-31 | 2019-11-05 | 前端组件实现验证码                                         |
| 9    | 新闻     | /getNewsByClass               | 获取新闻的图片地址链接                                                      | 2019-10-31 | 2019-11-05 | 需增加                                                     |
| 10   | 综合     | /getNewsByClass               | classID                                                                     | 2019-11-01 | 2019-11-05 | 需增加                                                     |
| 11   | 详情     | /getCommentsList              | 文章 ID 是否需,判断被提问                                                   | 2019-11-04 | 2019-11-05 | 需，待定                                                   |
| 12   | 详情     | /getCommentsList 等           | date 的精确提问                                                             | 2019-11-04 | 2019-11-05 | 项目完成后决定待讨论                                       |
| 13   | 后台     | 待添加                        | /logout                                                                     | 2019-11-06 | 2019-11-14 | 待添加                                                     |
|      |
| 14   | 搜索     | 待添加                        | 搜索 API 找不到                                                             | 2019-11-07 | 2019-11-14 | 待添加                                                     |
| 15   | 综合     | /getNewsByClass               | 10 中讨论类别与板块分开添加                                                 | 2019-11-07 | 2019-11-14 | 已解决                                                     |
| 16   | 综合     | /getNewsByClass、/getNewsList | 列表是否合并                                                                | 2019-11-07 | 2019-11-14 | 已合并                                                     |
| 17   | 详情     | /getArticle                   | 板块类别                                                                    | 2019-11-07 | 2019-11-14 | 已解决                                                     |
| 18   | 后台     | ---                           | 具体形式分类                                                                | 2019-11-07 | 2019-11-14 | 添加密码正则                                               |
| 19   | login    | ---                           | session 测试                                                                | 2019-11-13 | 2019-11-14 | 待测试                                                     |

# 已经完成前端接入的接口

- /getTopLineHome
  - 11.01 已增加
- /getPlateAndClass
  - 11.01 已增加
- /user/getFollowPlate
  - 11.01 已增加
- /user/getActionList
  - 11.01 已增加
  - 11.07 已修改
- /getNewsByClass
  - 11.01 已增加
- /getList
  - 11.01 已增加
- /getRecommendList
  - 11.01 已增加
- /getCommentsList
  - 11.01 已增加
