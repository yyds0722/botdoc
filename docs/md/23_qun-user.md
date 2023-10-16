# 群成员

#### 🚫获取用户群内身份

暂不对外开放

 

#### 🚫获取群内成员列表

[暂不对外开放] 

获取群成员 openid 列表

l **请求**

| 基本         |                                   |
| ------------ | --------------------------------- |
| HTTP URL     | /v2/groups/{group_openid}/members |
| HTTP Method  | POST                              |
| 接口频率限制 |                                   |

l **路径参数**

| **属性**     | **类型** | **必填** | **说明**      |
| ------------ | -------- | -------- | ------------- |
| group_openid | string   | 是       | 群聊的 openid |

l **请求参数**

| **属性**    | **类型** | **必填** | **说明**                                 |
| ----------- | -------- | -------- | ---------------------------------------- |
| limit       | int      | 否       | 每页限制数量 1-500                       |
| start_index | int      | 否       | 首页输入0，后续填入返回参数的 next_index |

l **返回参数**

| **属性**   | **类型** | **说明**                                          |
| ---------- | -------- | ------------------------------------------------- |
| members    | object[] | openid列表  {member_openid:'',join_timestamp:  0} |
| next_index | int      | 下一页的拉取标记位                                |

l **错误码**

| **错误码** | **错误码取值** | **解决方案** |
| ---------- | -------------- | ------------ |
| 0          | ok             |              |

 

#### 事件

##### 🚫用户加入群聊

暂不对外开放

 

##### 🚫用户退出群聊

暂不对外开放

 