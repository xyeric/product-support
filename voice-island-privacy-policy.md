# Voice Island Privacy Policy

Bundle ID: studio.eric.voiceisland

## 本机保存

声屿由 YongJun Zhang 提供。草稿、提供商配置、音色、录音样本和配音历史保存在设备的 SwiftData 数据库；API Key 单独存入仅限此设备的钥匙串。声屿没有开发者服务器、账户系统、广告、分析 SDK 或应用内云同步。系统备份、导出到 iCloud Drive 或其他应用的副本受相应服务的规则管理。

## 模型服务

只有你主动生成或创建音色时，声屿才会直接调用所选提供商。配音会发送文案、模型、Voice ID、声音参数和 API Key；克隆会发送所选录音、Voice ID 和 API Key。服务商还能接收到网络连接所需的 IP 地址等信息，并可能将请求关联至你的平台账户。首次生成前会显示接收方并征求授权；每次克隆需单独勾选授权。

## 接收对象

内置提供商为 MiniMax（api.minimaxi.com）和阿里云百炼（dashscope.aliyuncs.com）。阿里云克隆会使用其 OSS 临时上传地址。自定义提供商的接收方由你填写的 Base URL 决定。平台的保留期限、模型使用和删除方式请以所选平台的隐私政策及账户配置为准；声屿无法代替平台承诺不保留或不用于训练。

## 声音授权

麦克风仅在你选择录音并允许系统权限后使用。文件仅在你主动选择后读取。请仅使用本人或已经获得明确授权的声音，不得冒充他人、欺骗或侵犯他人权益。录音本身可能包含个人信息，请在上传前核对内容。

## 撤回删除

在设置中选择“撤回模型数据授权”，可撤回今后的配音授权。你也可清空提供商 API Key 并保存，以停止通过该配置调用。历史记录可逐条删除；自定义音色可长按移除。删除 App 会清除应用容器中的本地资料，钥匙串项目可能保留，请先清空密钥。上述操作不会删除服务商或导出目的地的副本；平台音色、录音和请求记录需要通过相应平台管理或联系平台删除。

## 分享反馈

导出仅在你使用系统分享菜单后发生，文件会交给你选择的应用或位置。支持页面由 GitHub 提供；你主动联系支持时，邮件服务会处理你发送的信息。请勿发送 API Key 或无关私人内容。隐私问题可联系 hixyeric@gmail.com。

## 政策更新

生效日期：2026 年 10 月 24 日。数据用途或接收方式变化时，我们会更新本政策，并在需要时重新征求授权。

[Alibaba Cloud privacy notice](https://help.aliyun.com/zh/model-studio/privacy-notice) | [MiniMax terms](https://platform.minimaxi.com/zh/protocol/user-agreement) | [Support](voice-island-support.md)
