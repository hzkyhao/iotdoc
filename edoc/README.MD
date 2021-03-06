# 

数蛙物联网平台API接口, 高并发全连接物联网平台,支持私有云部署的全开放的IoT产品全生命周期管理平台

JavaScript client for iot-api reference

This SDK is automatically generated by the Swagger Codegen project:

* API version: 1.4.1
* Package version: 

## Installation

### For [Node.js](https://nodejs.org/)

#### npm

To publish the library as a [npm](https://www.npmjs.com/),
please follow the procedure in ["Publishing npm packages"](https://docs.npmjs.com/getting-started/publishing-npm-packages).

Then install it via:

```shell
npm install jobsy_api_references --save
```

#### git

If the library is hosted at a git repository, e.g.
https://github.com/GIT_USER_ID/GIT_REPO_ID
then install it via:

```shell
npm install GIT_USER_ID/GIT_REPO_ID --save
```

### For browser

The library also works in the browser environment via npm and [browserify](http://browserify.org/). After following
the above steps with Node.js and installing browserify with `npm install -g browserify`,
perform the following (assuming *main.js* is your entry file):

```shell
browserify main.js > bundle.js
```

Then include *bundle.js* in the HTML pages.

### Webpack Configuration

Using Webpack you may encounter the following error: "Module not found: Error:
Cannot resolve module", most certainly you should disable AMD loader. Add/merge
the following section to your webpack config:

```javascript
module: {
    rules: [
        {
            parser: {
                amd: false
            }
        }
    ]
}
```

## Getting Started

Please follow the [installation](#installation) instruction and execute the following JS code:
```javascript
const api = require('iot-api')

let requestParams = {}

// Example request
let res = await api.exampleRequest(requestParams)
if (res) {
    // Response
} else {
    // Error
}
```

## Documentation for API Endpoints


## Product Requests
| Class | Method | Http Request | Description |
| ----- | ------ | ------------ | ----------- |
| API | [API.get_classes_product](api/get_classes_product.md) | GET /classes/Product | 查询产品 |
| API | [API.post_classes_product](api/post_classes_product.md) | POST /classes/Product | 新增产品 |
| API | [API.put_level_product](api/put_level_product.md) | PUT /level/Product | 设置产品表级别 |
| API | [API.delete_classes_product_id](api/delete_classes_product_id.md) | DELETE /classes/Product/{id} | 删除产品 |
| API | [API.get_classes_product_id](api/get_classes_product_id.md) | GET /classes/Product/{id} | 获取产品详情 |
| API | [API.put_classes_product_id](api/put_classes_product_id.md) | PUT /classes/Product/{id} | 更新产品 |
| API | [API.get_schema_product](api/get_schema_product.md) | GET /schema/Product | 获取产品表的权限级别和结构 |
| API | [API.get_trigger_product](api/get_trigger_product.md) | GET /trigger/Product | 获取产品表触发器 |
| API | [API.post_trigger_product](api/post_trigger_product.md) | POST /trigger/Product | 创建产品表触发器 |
| API | [API.put_trigger_product](api/put_trigger_product.md) | PUT /trigger/Product | 删除/编辑产品表触发器 |

## _User Requests
| Class | Method | Http Request | Description |
| ----- | ------ | ------------ | ----------- |
| API | [API.get_classes_user](api/get_classes_user.md) | GET /classes/_User | 查询_User |
| API | [API.post_classes_user](api/post_classes_user.md) | POST /classes/_User | 新增_User |
| API | [API.get_trigger_user](api/get_trigger_user.md) | GET /trigger/_User | 获取_User表触发器 |
| API | [API.post_trigger_user](api/post_trigger_user.md) | POST /trigger/_User | 创建_User表触发器 |
| API | [API.put_trigger_user](api/put_trigger_user.md) | PUT /trigger/_User | 删除/编辑_User表触发器 |
| API | [API.delete_classes_user_id](api/delete_classes_user_id.md) | DELETE /classes/_User/{id} | 删除_User |
| API | [API.get_classes_user_id](api/get_classes_user_id.md) | GET /classes/_User/{id} | 获取_User详情 |
| API | [API.put_classes_user_id](api/put_classes_user_id.md) | PUT /classes/_User/{id} | 更新_User |
| API | [API.put_level_user](api/put_level_user.md) | PUT /level/_User | 设置_User表级别 |
| API | [API.get_schema_user](api/get_schema_user.md) | GET /schema/_User | 获取_User表的权限级别和结构 |

## SuKe Requests
| Class | Method | Http Request | Description |
| ----- | ------ | ------------ | ----------- |
| API | [API.get_suke_query_devtype_info](api/get_suke_query_devtype_info.md) | GET /suke/query_devtype_info | 查询设备类型信息 |
| API | [API.post_suke_add_customernode](api/post_suke_add_customernode.md) | POST /suke/add_customernode | 增加客户节点 |
| API | [API.get_suke_query_info](api/get_suke_query_info.md) | GET /suke/query_info | 查询信息 |
| API | [API.put_suke_edit_zl](api/put_suke_edit_zl.md) | PUT /suke/edit_zl | 编辑指令 |
| API | [API.get_suke_query_suke_dev](api/get_suke_query_suke_dev.md) | GET /suke/query_suke_dev | 查询设备 |
| API | [API.get_server_send](api/get_server_send.md) | GET /server/send | 指令控制 |
| API | [API.put_suke_edit_devtype](api/put_suke_edit_devtype.md) | PUT /suke/edit_devtype | 编辑设备类型 |
| API | [API.post_suke_add_yys](api/post_suke_add_yys.md) | POST /suke/add_yys | 增加运营商 |
| API | [API.post_suke_add_zl](api/post_suke_add_zl.md) | POST /suke/add_zl | 增加指令 |
| API | [API.post_suke_add_devtype](api/post_suke_add_devtype.md) | POST /suke/add_devtype | 增加设备类型 |
| API | [API.put_suke_edit_yys](api/put_suke_edit_yys.md) | PUT /suke/edit_yys | 编辑应用商 |
| API | [API.post_suke_query_hardware_online](api/post_suke_query_hardware_online.md) | POST /suke/query_hardware_online | 查询设备在线状态 |
| API | [API.get_suke_query_yys_info](api/get_suke_query_yys_info.md) | GET /suke/query_yys_info | 查询应用商 |
| API | [API.get_suke_query_zl_info](api/get_suke_query_zl_info.md) | GET /suke/query_zl_info | 查询设备类型信息 |

## Rule Requests
| Class | Method | Http Request | Description |
| ----- | ------ | ------------ | ----------- |
| API | [API.get_resource_types](api/get_resource_types.md) | GET /resource_types | 获取资源类型列表 |
| API | [API.delete_rule_resource_id](api/delete_rule_resource_id.md) | DELETE /rule_resource/{id} | 根据资源ID删除资源 |
| API | [API.get_rule_resource_id](api/get_rule_resource_id.md) | GET /rule_resource/{id} | 根据资源ID获取资源 |
| API | [API.delete_rule_id](api/delete_rule_id.md) | DELETE /rule/{id} | 删除规则引擎 |
| API | [API.get_rule_id](api/get_rule_id.md) | GET /rule/{id} | 获取规则引擎 |
| API | [API.get_rule_resource](api/get_rule_resource.md) | GET /rule_resource | 获取资源列表 |
| API | [API.post_rule_resource](api/post_rule_resource.md) | POST /rule_resource | 创建资源 |
| API | [API.post_rule_test](api/post_rule_test.md) | POST /rule_test | 测试规则引擎 |
| API | [API.get_rule_actions](api/get_rule_actions.md) | GET /rule_actions | 获取动作列表 |
| API | [API.get_rules](api/get_rules.md) | GET /rules | 获取规则引擎列表 |
| API | [API.post_rules](api/post_rules.md) | POST /rules | 创建规则引擎 |

## _Role Requests
| Class | Method | Http Request | Description |
| ----- | ------ | ------------ | ----------- |
| API | [API.delete_classes_role_id](api/delete_classes_role_id.md) | DELETE /classes/_Role/{id} | 删除角色 |
| API | [API.get_classes_role_id](api/get_classes_role_id.md) | GET /classes/_Role/{id} | 获取角色详情 |
| API | [API.put_classes_role_id](api/put_classes_role_id.md) | PUT /classes/_Role/{id} | 更新角色 |
| API | [API.get_trigger_role](api/get_trigger_role.md) | GET /trigger/_Role | 获取角色表触发器 |
| API | [API.post_trigger_role](api/post_trigger_role.md) | POST /trigger/_Role | 创建角色表触发器 |
| API | [API.put_trigger_role](api/put_trigger_role.md) | PUT /trigger/_Role | 删除/编辑角色表触发器 |
| API | [API.put_level_role](api/put_level_role.md) | PUT /level/_Role | 设置角色表级别 |
| API | [API.get_schema_role](api/get_schema_role.md) | GET /schema/_Role | 获取角色表的权限级别和结构 |
| API | [API.get_classes_role](api/get_classes_role.md) | GET /classes/_Role | 查询角色 |
| API | [API.post_classes_role](api/post_classes_role.md) | POST /classes/_Role | 新增角色 |

## License Requests
| Class | Method | Http Request | Description |
| ----- | ------ | ------------ | ----------- |
| API | [API.get_health](api/get_health.md) | GET /health | health |
| API | [API.get_hardinfo](api/get_hardinfo.md) | GET /hardinfo | 获取硬件key |
| API | [API.get_licsetup](api/get_licsetup.md) | GET /licsetup | licsetup |
| API | [API.get_signdata](api/get_signdata.md) | GET /signdata | sign Data |
| API | [API.get_license](api/get_license.md) | GET /license | 获取license |
| API | [API.get_iotapp](api/get_iotapp.md) | GET /iotapp | deploy iot database |
| API | [API.get_trigger_license](api/get_trigger_license.md) | GET /trigger/License | 获取License表触发器 |
| API | [API.post_trigger_license](api/post_trigger_license.md) | POST /trigger/License | 创建License表触发器 |
| API | [API.put_trigger_license](api/put_trigger_license.md) | PUT /trigger/License | 删除/编辑License表触发器 |
| API | [API.get_iothub](api/get_iothub.md) | GET /iothub | start iot hub |
| API | [API.get_lictool](api/get_lictool.md) | GET /lictool | lictool |
| API | [API.get_setup_result](api/get_setup_result.md) | GET /setup_result | setup_result |
| API | [API.get_schema_license](api/get_schema_license.md) | GET /schema/License | 获取License表的权限级别和结构 |
| API | [API.get_classes_license](api/get_classes_license.md) | GET /classes/License | 查询License |
| API | [API.post_classes_license](api/post_classes_license.md) | POST /classes/License | 新增License |
| API | [API.get_ukey](api/get_ukey.md) | GET /ukey | get ukey |
| API | [API.delete_classes_license_id](api/delete_classes_license_id.md) | DELETE /classes/License/{id} | 删除License |
| API | [API.get_classes_license_id](api/get_classes_license_id.md) | GET /classes/License/{id} | 获取License详情 |
| API | [API.put_classes_license_id](api/put_classes_license_id.md) | PUT /classes/License/{id} | 更新License |
| API | [API.put_level_license](api/put_level_license.md) | PUT /level/License | 设置License表级别 |
| API | [API.get_verifysigndata](api/get_verifysigndata.md) | GET /verifysigndata | verify SignData |

## SukeLog Requests
| Class | Method | Http Request | Description |
| ----- | ------ | ------------ | ----------- |
| API | [API.get_schema_sukelog](api/get_schema_sukelog.md) | GET /schema/SukeLog | 获取SukeLog表的权限级别和结构 |
| API | [API.delete_classes_sukelog_id](api/delete_classes_sukelog_id.md) | DELETE /classes/SukeLog/{id} | 删除SukeLog |
| API | [API.get_classes_sukelog_id](api/get_classes_sukelog_id.md) | GET /classes/SukeLog/{id} | 获取SukeLog详情 |
| API | [API.put_classes_sukelog_id](api/put_classes_sukelog_id.md) | PUT /classes/SukeLog/{id} | 更新SukeLog |
| API | [API.put_level_sukelog](api/put_level_sukelog.md) | PUT /level/SukeLog | 设置SukeLog表级别 |
| API | [API.get_classes_sukelog](api/get_classes_sukelog.md) | GET /classes/SukeLog | 查询SukeLog |
| API | [API.post_classes_sukelog](api/post_classes_sukelog.md) | POST /classes/SukeLog | 新增SukeLog |
| API | [API.get_trigger_sukelog](api/get_trigger_sukelog.md) | GET /trigger/SukeLog | 获取SukeLog表触发器 |
| API | [API.post_trigger_sukelog](api/post_trigger_sukelog.md) | POST /trigger/SukeLog | 创建SukeLog表触发器 |
| API | [API.put_trigger_sukelog](api/put_trigger_sukelog.md) | PUT /trigger/SukeLog | 删除/编辑SukeLog表触发器 |

## Datas Requests
| Class | Method | Http Request | Description |
| ----- | ------ | ------------ | ----------- |
| API | [API.get_schema_datas](api/get_schema_datas.md) | GET /schema/Datas | 获取数据字典表的权限级别和结构 |
| API | [API.get_trigger_datas](api/get_trigger_datas.md) | GET /trigger/Datas | 获取数据字典表触发器 |
| API | [API.post_trigger_datas](api/post_trigger_datas.md) | POST /trigger/Datas | 创建数据字典表触发器 |
| API | [API.put_trigger_datas](api/put_trigger_datas.md) | PUT /trigger/Datas | 删除/编辑数据字典表触发器 |
| API | [API.put_level_datas](api/put_level_datas.md) | PUT /level/Datas | 设置数据字典表级别 |
| API | [API.delete_classes_datas_id](api/delete_classes_datas_id.md) | DELETE /classes/Datas/{id} | 删除数据字典 |
| API | [API.get_classes_datas_id](api/get_classes_datas_id.md) | GET /classes/Datas/{id} | 获取数据字典详情 |
| API | [API.put_classes_datas_id](api/put_classes_datas_id.md) | PUT /classes/Datas/{id} | 更新数据字典 |
| API | [API.get_classes_datas](api/get_classes_datas.md) | GET /classes/Datas | 查询数据字典 |
| API | [API.post_classes_datas](api/post_classes_datas.md) | POST /classes/Datas | 新增数据字典 |

## Crond Requests
| Class | Method | Http Request | Description |
| ----- | ------ | ------------ | ----------- |
| API | [API.get_classes_crond](api/get_classes_crond.md) | GET /classes/Crond | 查询Crond |
| API | [API.post_classes_crond](api/post_classes_crond.md) | POST /classes/Crond | 新增Crond |
| API | [API.put_level_crond](api/put_level_crond.md) | PUT /level/Crond | 设置Crond表级别 |
| API | [API.get_schema_crond](api/get_schema_crond.md) | GET /schema/Crond | 获取Crond表的权限级别和结构 |
| API | [API.delete_classes_crond_id](api/delete_classes_crond_id.md) | DELETE /classes/Crond/{id} | 删除Crond |
| API | [API.get_classes_crond_id](api/get_classes_crond_id.md) | GET /classes/Crond/{id} | 获取Crond详情 |
| API | [API.put_classes_crond_id](api/put_classes_crond_id.md) | PUT /classes/Crond/{id} | 更新Crond |
| API | [API.get_trigger_crond](api/get_trigger_crond.md) | GET /trigger/Crond | 获取Crond表触发器 |
| API | [API.post_trigger_crond](api/post_trigger_crond.md) | POST /trigger/Crond | 创建Crond表触发器 |
| API | [API.put_trigger_crond](api/put_trigger_crond.md) | PUT /trigger/Crond | 删除/编辑Crond表触发器 |

## Channel Requests
| Class | Method | Http Request | Description |
| ----- | ------ | ------------ | ----------- |
| API | [API.get_schema_channel](api/get_schema_channel.md) | GET /schema/Channel | 获取通道表的权限级别和结构 |
| API | [API.get_classes_channel](api/get_classes_channel.md) | GET /classes/Channel | 查询通道 |
| API | [API.post_classes_channel](api/post_classes_channel.md) | POST /classes/Channel | 新增通道 |
| API | [API.get_trigger_channel](api/get_trigger_channel.md) | GET /trigger/Channel | 获取通道表触发器 |
| API | [API.post_trigger_channel](api/post_trigger_channel.md) | POST /trigger/Channel | 创建通道表触发器 |
| API | [API.put_trigger_channel](api/put_trigger_channel.md) | PUT /trigger/Channel | 删除/编辑通道表触发器 |
| API | [API.delete_classes_channel_id](api/delete_classes_channel_id.md) | DELETE /classes/Channel/{id} | 删除通道 |
| API | [API.get_classes_channel_id](api/get_classes_channel_id.md) | GET /classes/Channel/{id} | 获取通道详情 |
| API | [API.put_classes_channel_id](api/put_classes_channel_id.md) | PUT /classes/Channel/{id} | 更新通道 |
| API | [API.put_level_channel](api/put_level_channel.md) | PUT /level/Channel | 设置通道表级别 |
| API | [API.post_control_channel](api/post_control_channel.md) | POST /control/channel | 更新通道 |

## Department Requests
| Class | Method | Http Request | Description |
| ----- | ------ | ------------ | ----------- |
| API | [API.put_level_department](api/put_level_department.md) | PUT /level/Department | 设置部门表级别 |
| API | [API.delete_classes_department_id](api/delete_classes_department_id.md) | DELETE /classes/Department/{id} | 删除部门 |
| API | [API.get_classes_department_id](api/get_classes_department_id.md) | GET /classes/Department/{id} | 获取部门详情 |
| API | [API.put_classes_department_id](api/put_classes_department_id.md) | PUT /classes/Department/{id} | 更新部门 |
| API | [API.get_trigger_department](api/get_trigger_department.md) | GET /trigger/Department | 获取部门表触发器 |
| API | [API.post_trigger_department](api/post_trigger_department.md) | POST /trigger/Department | 创建部门表触发器 |
| API | [API.put_trigger_department](api/put_trigger_department.md) | PUT /trigger/Department | 删除/编辑部门表触发器 |
| API | [API.get_classes_department](api/get_classes_department.md) | GET /classes/Department | 查询部门 |
| API | [API.post_classes_department](api/post_classes_department.md) | POST /classes/Department | 新增部门 |
| API | [API.get_schema_department](api/get_schema_department.md) | GET /schema/Department | 获取部门表的权限级别和结构 |

## Project Requests
| Class | Method | Http Request | Description |
| ----- | ------ | ------------ | ----------- |
| API | [API.get_trigger_project](api/get_trigger_project.md) | GET /trigger/Project | 获取Project表触发器 |
| API | [API.post_trigger_project](api/post_trigger_project.md) | POST /trigger/Project | 创建Project表触发器 |
| API | [API.put_trigger_project](api/put_trigger_project.md) | PUT /trigger/Project | 删除/编辑Project表触发器 |
| API | [API.get_classes_site_id](api/get_classes_site_id.md) | GET /classes/Site/{Id} | 获取应用信息 |
| API | [API.get_schema_project](api/get_schema_project.md) | GET /schema/Project | 获取Project表的权限级别和结构 |
| API | [API.delete_classes_project_id](api/delete_classes_project_id.md) | DELETE /classes/Project/{id} | 删除Project |
| API | [API.get_classes_project_id](api/get_classes_project_id.md) | GET /classes/Project/{id} | 获取Project详情 |
| API | [API.put_classes_project_id](api/put_classes_project_id.md) | PUT /classes/Project/{id} | 更新Project |
| API | [API.put_level_project](api/put_level_project.md) | PUT /level/Project | 设置Project表级别 |
| API | [API.get_classes_project](api/get_classes_project.md) | GET /classes/Project | 查询Project |
| API | [API.post_classes_project](api/post_classes_project.md) | POST /classes/Project | 新增Project |

## App Requests
| Class | Method | Http Request | Description |
| ----- | ------ | ------------ | ----------- |
| API | [API.get_schema_app](api/get_schema_app.md) | GET /schema/App | 获取应用表的权限级别和结构 |
| API | [API.get_classes_app](api/get_classes_app.md) | GET /classes/App | 查询应用 |
| API | [API.post_classes_app](api/post_classes_app.md) | POST /classes/App | 新增应用 |
| API | [API.put_level_app](api/put_level_app.md) | PUT /level/App | 设置应用表级别 |
| API | [API.get_trigger_app](api/get_trigger_app.md) | GET /trigger/App | 获取应用表触发器 |
| API | [API.post_trigger_app](api/post_trigger_app.md) | POST /trigger/App | 创建应用表触发器 |
| API | [API.put_trigger_app](api/put_trigger_app.md) | PUT /trigger/App | 删除/编辑应用表触发器 |
| API | [API.delete_classes_app_id](api/delete_classes_app_id.md) | DELETE /classes/App/{id} | 删除应用 |
| API | [API.get_classes_app_id](api/get_classes_app_id.md) | GET /classes/App/{id} | 获取应用详情 |
| API | [API.put_classes_app_id](api/put_classes_app_id.md) | PUT /classes/App/{id} | 更新应用 |

## System Requests
| Class | Method | Http Request | Description |
| ----- | ------ | ------------ | ----------- |
| API | [API.get_log_level](api/get_log_level.md) | GET /log/level | 获取日志配置 |
| API | [API.put_log_level](api/put_log_level.md) | PUT /log/level | 更新日志配置 |
| API | [API.post_compile](api/post_compile.md) | POST /compile | 编译代码 |
| API | [API.generate_api](api/generate_api.md) | POST /generate_api/{type} | 根据swagger产生API代码 |
| API | [API.post_cluster](api/post_cluster.md) | POST /cluster | 集群操作 |
| API | [API.get_chart_version](api/get_chart_version.md) | GET /chart/{version} | 统计获取 |
| API | [API.post_verify_code_action](api/post_verify_code_action.md) | POST /verify_code/{Action} | 验证手机号/邮箱是否通过 |
| API | [API.get_nodes](api/get_nodes.md) | GET /nodes | 获取节点 |
| API | [API.post_sendsms](api/post_sendsms.md) | POST /sendsms | 发送短信验证码 |
| API | [API.post_plugin_app](api/post_plugin_app.md) | POST /plugin/{App} | 对插件启动/停止/热更新/获取 |
| API | [API.post_upload](api/post_upload.md) | POST /upload | 服务器文件上传 |
| API | [API.get_file_signature](api/get_file_signature.md) | GET /file/signature | 获得文件操作权限 |
| API | [API.get_plugin](api/get_plugin.md) | GET /plugin | 获取插件 |
| API | [API.post_upload_token](api/post_upload_token.md) | POST /upload_token | 获取上传文件Token |

## Devices Requests
| Class | Method | Http Request | Description |
| ----- | ------ | ------------ | ----------- |
| API | [API.get_dev_addr](api/get_dev_addr.md) | GET /dev/{addr} | 获取设备当前状态 |
| API | [API.get_trigger_devices](api/get_trigger_devices.md) | GET /trigger/Devices | 获取设备管理表触发器 |
| API | [API.post_trigger_devices](api/post_trigger_devices.md) | POST /trigger/Devices | 创建设备管理表触发器 |
| API | [API.put_trigger_devices](api/put_trigger_devices.md) | PUT /trigger/Devices | 删除/编辑设备管理表触发器 |
| API | [API.put_level_devices](api/put_level_devices.md) | PUT /level/Devices | 设置设备管理表级别 |
| API | [API.get_schema_devices](api/get_schema_devices.md) | GET /schema/Devices | 获取设备管理表的权限级别和结构 |
| API | [API.get_classes_devices](api/get_classes_devices.md) | GET /classes/Devices | 查询设备管理 |
| API | [API.post_classes_devices](api/post_classes_devices.md) | POST /classes/Devices | 新增设备管理 |
| API | [API.get_devs](api/get_devs.md) | GET /devs | 查询设备列表 |
| API | [API.get_devs_vcon](api/get_devs_vcon.md) | GET /devs/{vcon} | 查询设备列表 |
| API | [API.delete_classes_devices_id](api/delete_classes_devices_id.md) | DELETE /classes/Devices/{id} | 删除设备管理 |
| API | [API.get_classes_devices_id](api/get_classes_devices_id.md) | GET /classes/Devices/{id} | 获取设备管理详情 |
| API | [API.put_classes_devices_id](api/put_classes_devices_id.md) | PUT /classes/Devices/{id} | 更新设备管理 |

## Notification Requests
| Class | Method | Http Request | Description |
| ----- | ------ | ------------ | ----------- |
| API | [API.put_level_notification](api/put_level_notification.md) | PUT /level/Notification | 设置通知表级别 |
| API | [API.get_trigger_notification](api/get_trigger_notification.md) | GET /trigger/Notification | 获取通知表触发器 |
| API | [API.post_trigger_notification](api/post_trigger_notification.md) | POST /trigger/Notification | 创建通知表触发器 |
| API | [API.put_trigger_notification](api/put_trigger_notification.md) | PUT /trigger/Notification | 删除/编辑通知表触发器 |
| API | [API.delete_classes_notification_id](api/delete_classes_notification_id.md) | DELETE /classes/Notification/{id} | 删除通知 |
| API | [API.get_classes_notification_id](api/get_classes_notification_id.md) | GET /classes/Notification/{id} | 获取通知详情 |
| API | [API.put_classes_notification_id](api/put_classes_notification_id.md) | PUT /classes/Notification/{id} | 更新通知 |
| API | [API.get_classes_notification](api/get_classes_notification.md) | GET /classes/Notification | 查询通知 |
| API | [API.post_classes_notification](api/post_classes_notification.md) | POST /classes/Notification | 新增通知 |
| API | [API.get_schema_notification](api/get_schema_notification.md) | GET /schema/Notification | 获取通知表的权限级别和结构 |

## DB Requests
| Class | Method | Http Request | Description |
| ----- | ------ | ------------ | ----------- |
| API | [API.get_config](api/get_config.md) | GET /config | 获取配置 |
| API | [API.put_config](api/put_config.md) | PUT /config | 更新配置 |
| API | [API.post_files_filename](api/post_files_filename.md) | POST /files/{filename} | 数据库文件上传 |
| API | [API.post_graphql](api/post_graphql.md) | POST /graphql | graphql |
| API | [API.post_functions_func](api/post_functions_func.md) | POST /functions/{func} | 云函数 |
| API | [API.post_batch](api/post_batch.md) | POST /batch | 数据批处理 |
| API | [API.post_import_data](api/post_import_data.md) | POST /import_data | 导库 |

## Dashboard Requests
| Class | Method | Http Request | Description |
| ----- | ------ | ------------ | ----------- |
| API | [API.get_classes_dashboard](api/get_classes_dashboard.md) | GET /classes/Dashboard | 查询Dashboard |
| API | [API.post_classes_dashboard](api/post_classes_dashboard.md) | POST /classes/Dashboard | 新增Dashboard |
| API | [API.put_level_dashboard](api/put_level_dashboard.md) | PUT /level/Dashboard | 设置Dashboard表级别 |
| API | [API.delete_classes_dashboard_id](api/delete_classes_dashboard_id.md) | DELETE /classes/Dashboard/{id} | 删除Dashboard |
| API | [API.get_classes_dashboard_id](api/get_classes_dashboard_id.md) | GET /classes/Dashboard/{id} | 获取Dashboard详情 |
| API | [API.put_classes_dashboard_id](api/put_classes_dashboard_id.md) | PUT /classes/Dashboard/{id} | 更新Dashboard |
| API | [API.get_trigger_dashboard](api/get_trigger_dashboard.md) | GET /trigger/Dashboard | 获取Dashboard表触发器 |
| API | [API.post_trigger_dashboard](api/post_trigger_dashboard.md) | POST /trigger/Dashboard | 创建Dashboard表触发器 |
| API | [API.put_trigger_dashboard](api/put_trigger_dashboard.md) | PUT /trigger/Dashboard | 删除/编辑Dashboard表触发器 |
| API | [API.get_schema_dashboard](api/get_schema_dashboard.md) | GET /schema/Dashboard | 获取Dashboard表的权限级别和结构 |

## _Session Requests
| Class | Method | Http Request | Description |
| ----- | ------ | ------------ | ----------- |
| API | [API.delete_classes_session_id](api/delete_classes_session_id.md) | DELETE /classes/_Session/{id} | 删除会话 |
| API | [API.get_classes_session_id](api/get_classes_session_id.md) | GET /classes/_Session/{id} | 获取会话详情 |
| API | [API.put_classes_session_id](api/put_classes_session_id.md) | PUT /classes/_Session/{id} | 更新会话 |
| API | [API.get_trigger_session](api/get_trigger_session.md) | GET /trigger/_Session | 获取会话表触发器 |
| API | [API.post_trigger_session](api/post_trigger_session.md) | POST /trigger/_Session | 创建会话表触发器 |
| API | [API.put_trigger_session](api/put_trigger_session.md) | PUT /trigger/_Session | 删除/编辑会话表触发器 |
| API | [API.get_classes_session](api/get_classes_session.md) | GET /classes/_Session | 查询会话 |
| API | [API.post_classes_session](api/post_classes_session.md) | POST /classes/_Session | 新增会话 |
| API | [API.put_level_session](api/put_level_session.md) | PUT /level/_Session | 设置会话表级别 |
| API | [API.get_schema_session](api/get_schema_session.md) | GET /schema/_Session | 获取会话表的权限级别和结构 |

## Permission Requests
| Class | Method | Http Request | Description |
| ----- | ------ | ------------ | ----------- |
| API | [API.put_add_permission](api/put_add_permission.md) | PUT /add_permission | 分配权限 |
| API | [API.delete_classes_permission_id](api/delete_classes_permission_id.md) | DELETE /classes/Permission/{id} | 删除权限 |
| API | [API.get_classes_permission_id](api/get_classes_permission_id.md) | GET /classes/Permission/{id} | 获取权限详情 |
| API | [API.put_classes_permission_id](api/put_classes_permission_id.md) | PUT /classes/Permission/{id} | 更新权限 |
| API | [API.get_classes_permission](api/get_classes_permission.md) | GET /classes/Permission | 查询权限 |
| API | [API.post_classes_permission](api/post_classes_permission.md) | POST /classes/Permission | 新增权限 |
| API | [API.get_schema_permission](api/get_schema_permission.md) | GET /schema/Permission | 获取权限表的权限级别和结构 |
| API | [API.get_trigger_permission](api/get_trigger_permission.md) | GET /trigger/Permission | 获取权限表触发器 |
| API | [API.post_trigger_permission](api/post_trigger_permission.md) | POST /trigger/Permission | 创建权限表触发器 |
| API | [API.put_trigger_permission](api/put_trigger_permission.md) | PUT /trigger/Permission | 删除/编辑权限表触发器 |
| API | [API.put_level_permission](api/put_level_permission.md) | PUT /level/Permission | 设置权限表级别 |

## Menu Requests
| Class | Method | Http Request | Description |
| ----- | ------ | ------------ | ----------- |
| API | [API.delete_classes_menu_id](api/delete_classes_menu_id.md) | DELETE /classes/Menu/{id} | 删除菜单 |
| API | [API.get_classes_menu_id](api/get_classes_menu_id.md) | GET /classes/Menu/{id} | 获取菜单详情 |
| API | [API.put_classes_menu_id](api/put_classes_menu_id.md) | PUT /classes/Menu/{id} | 更新菜单 |
| API | [API.put_level_menu](api/put_level_menu.md) | PUT /level/Menu | 设置菜单表级别 |
| API | [API.get_trigger_menu](api/get_trigger_menu.md) | GET /trigger/Menu | 获取菜单表触发器 |
| API | [API.post_trigger_menu](api/post_trigger_menu.md) | POST /trigger/Menu | 创建菜单表触发器 |
| API | [API.put_trigger_menu](api/put_trigger_menu.md) | PUT /trigger/Menu | 删除/编辑菜单表触发器 |
| API | [API.get_classes_menu](api/get_classes_menu.md) | GET /classes/Menu | 查询菜单 |
| API | [API.post_classes_menu](api/post_classes_menu.md) | POST /classes/Menu | 新增菜单 |
| API | [API.put_add_menu](api/put_add_menu.md) | PUT /add_menu | 分配菜单 |
| API | [API.get_classes_navigation](api/get_classes_navigation.md) | GET /classes/Navigation | 获取顶部导航 |
| API | [API.get_schema_menu](api/get_schema_menu.md) | GET /schema/Menu | 获取菜单表的权限级别和结构 |

## User Requests
| Class | Method | Http Request | Description |
| ----- | ------ | ------------ | ----------- |
| API | [API.get_login](api/get_login.md) | GET /login | 用户登录 |
| API | [API.get_users_id](api/get_users_id.md) | GET /users/{id} | 获取用户信息 |
| API | [API.get_token](api/get_token.md) | GET /get_token | 获取调用API凭证 |
| API | [API.post_requestpasswordreset](api/post_requestpasswordreset.md) | POST /requestPasswordReset | 重置密码 |
| API | [API.get_users_me](api/get_users_me.md) | GET /users/me | 检查会话是否有效 |
| API | [API.post_users](api/post_users.md) | POST /users | 用户注册 |
| API | [API.post_logout](api/post_logout.md) | POST /logout | 退出登录 |

## SukeDev Requests
| Class | Method | Http Request | Description |
| ----- | ------ | ------------ | ----------- |
| API | [API.get_classes_sukedev](api/get_classes_sukedev.md) | GET /classes/SukeDev | 查询SukeDev |
| API | [API.post_classes_sukedev](api/post_classes_sukedev.md) | POST /classes/SukeDev | 新增SukeDev |
| API | [API.get_schema_sukedev](api/get_schema_sukedev.md) | GET /schema/SukeDev | 获取SukeDev表的权限级别和结构 |
| API | [API.get_trigger_sukedev](api/get_trigger_sukedev.md) | GET /trigger/SukeDev | 获取SukeDev表触发器 |
| API | [API.post_trigger_sukedev](api/post_trigger_sukedev.md) | POST /trigger/SukeDev | 创建SukeDev表触发器 |
| API | [API.put_trigger_sukedev](api/put_trigger_sukedev.md) | PUT /trigger/SukeDev | 删除/编辑SukeDev表触发器 |
| API | [API.put_level_sukedev](api/put_level_sukedev.md) | PUT /level/SukeDev | 设置SukeDev表级别 |
| API | [API.delete_classes_sukedev_id](api/delete_classes_sukedev_id.md) | DELETE /classes/SukeDev/{id} | 删除SukeDev |
| API | [API.get_classes_sukedev_id](api/get_classes_sukedev_id.md) | GET /classes/SukeDev/{id} | 获取SukeDev详情 |
| API | [API.put_classes_sukedev_id](api/put_classes_sukedev_id.md) | PUT /classes/SukeDev/{id} | 更新SukeDev |

## [Action Model](models/Action.md)

## [App Model](models/App.md)

## [Channel Model](models/Channel.md)

## [ClassLevel Model](models/ClassLevel.md)

## [Crond Model](models/Crond.md)

## [Dashboard Model](models/Dashboard.md)

## [Datas Model](models/Datas.md)

## [Department Model](models/Department.md)

## [Devices Model](models/Devices.md)

## [License Model](models/License.md)

## [Menu Model](models/Menu.md)

## [Notification Model](models/Notification.md)

## [Permission Model](models/Permission.md)

## [Product Model](models/Product.md)

## [Project Model](models/Project.md)

## [Resource Model](models/Resource.md)

## [Rule Model](models/Rule.md)

## [SukeDev Model](models/SukeDev.md)

## [SukeLog Model](models/SukeLog.md)

## [Swagger Model](models/Swagger.md)

## [_Role Model](models/_Role.md)

## [_Session Model](models/_Session.md)

## [_User Model](models/_User.md)

## [error Model](models/error.md)


## Documentation for authorization

### APIKeyHeader
* Type: apiKey
* API key parameter name: sessionToken
* Location: Header
### APIKeyQueryParam
* Type: apiKey
* API key parameter name: sessionToken
* Location: URL query string
### BasicAuth
* Type: basic
### CookieAuth
* Type: apiKey
* API key parameter name: sessionToken
* Location: Header
