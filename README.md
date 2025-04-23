# TRTC Chat UIKit

This template is designed to help users quickly deploy and experience high-quality online chat. In actual application scenarios, whether it is a friendly chat between friends thousands of miles apart, or private communication between business partners, using this template, you can easily initiate a video chat with others and enjoy a clear and smooth communication experience like face-to-face communication.

In addition, by reading this document, you will learn how to quickly run the TUIChatKit sample project and perform secondary development. It only takes 5 minutes to successfully run the Demo and quickly build your own innovative applications such as stranger chat.

## Quick Deployment

Using the EdgeOne page, you can achieve zero-code audio and video conference system setup through rapid template deployment.

<a href="https://edgeone.ai/pages/new?from=github&amp;template=https://github.com/q153877011/trtc-chat&amp;output-directory=build&amp;install-command=npm%20install&amp;build-command=npm%20run%20build&amp;from=github" rel="nofollow"><img src="https://camo.githubusercontent.com/6a94a67f6a020d5810ef905549fc5255bf99ccd09f17881b6855b332b579a364/68747470733a2f2f63646e7374617469632e74656e63656e7463732e636f6d2f656467656f6e652f70616765732f6465706c6f792e737667" alt="Deploy with EdgeOne Pages" style="max-width: 100%;"></a>

You can click the "View Demo" button on the left to experience the online demonstration.

Please note that the deployment template is based on secondary development of the original repository code, mainly for experiencing quick deployment features and online Demo. If you need to develop more extensive features, we recommend using the original repository code for in-depth development. Original development repository address: [https://github.com/TencentCloud/chat-uikit-react](https://github.com/TencentCloud/chat-uikit-react)

The following tutorial will provide detailed guidance on how to quickly run and experience the Demo.

## About Tencent Cloud Chat

[Tencent Cloud Chat](https://trtc.io/document/50061?platform=web&product=chat&menulabel=uikit) provides globally interconnected chat APIs, multi-platform SDKs, and UIKit components to help you quickly bring messaging capabilities such as one-to-one chat, group chat, chat rooms, and system notifications to your applications and websites.
## Global Compliance Certifications
<table>
<tr>
<td> <img src="https://staticintl.cloudcachetci.com/cms/backend-cms/Vk2L735_1SOC.png" width=90 height=80 /> </td>
<td> <img src="https://staticintl.cloudcachetci.com/cms/backend-cms/Mp5i133_2ISO%209001.png" width=88 height=90 /> </td>
<td> <img src="https://staticintl.cloudcachetci.com/cms/backend-cms/AfnR546_4ISO%2027001.png" width=90 height=87 /> </td>
<td> <img src="https://staticintl.cloudcachetci.com/cms/backend-cms/WQjf098_5ISO%2027017.png" width=90 height=87 /> </td>
<td> <img src="https://staticintl.cloudcachetci.com/cms/backend-cms/aNQJ919_6ISO%2027018.png" width=90 height=86 /> </td>
</tr>
<tr>
<td> <img src="https://staticintl.cloudcachetci.com/cms/backend-cms/Rj5T795_7CSASTAR.png" width=90 height=90 /> </td>
<td> <img src="https://staticintl.cloudcachetci.com/cms/backend-cms/BXNX111_8NIST%20CSF.png" width=90 height=84 /> </td>
<td> <img src="https://staticintl.cloudcachetci.com/cms/backend-cms/dHEg621_9ISO%2027701.png" width=90 height=86 /> </td>
<td> <img src="https://staticintl.cloudcachetci.com/cms/backend-cms/BLQI655_10ISO%2029151.png" width=90 height=86 /> </td>
<td> <img src="https://staticintl.cloudcachetci.com/cms/backend-cms/dHDE860_11BS10012.png" width=90 height=42 /> </td>
</tr>
</table>

## Integrating chat-uikit-react
This tutorial shows how you can build a chat application in just 10 minutes by integrating chat-uikit-react
[<img src="https://web.sdk.qcloud.com/im/assets/images/build_react_chat.png" width="800"/>](https://www.youtube.com/watch?v=o0PcxpGl66Y)

## Core Capabilities

- 1 Billion+ Monthly active users
- 550 Billion+ Daily peak messages
- 100,000+ Customers worldwid
- 99.99% Message success rate

## Low-Code UIKit and Free Demo

![](https://cloudcache.intl.tencent-cloud.com/cms/backend-cms/712468b756a111ee974d5254005f490f.png)
![](https://cloudcache.intl.tencent-cloud.com/cms/backend-cms/80785e9c56a111ee974d5254005f490f.png)


## Get Started

> In respect for the copyright of emoji designs, the Chat Demo/TUIKit project does not include large emoji element cutouts. Please replace them with your own designed or copyrighted emoji packs before the official commercial launch. The default QQ emojis are copyrighted by Tencent and do not support authorization. We ask for your understanding and to be aware of this.

### Step 1. Create an app

1. Log in to the [Chat console](https://console.trtc.io/).
2. Click `Create Application`, enter your app name, and click `Create`.
![](https://github.com/user-attachments/assets/1ce0bdc2-2770-4006-b480-8c0e7d89271f)
3. After creation, you can see the status, service version, SDKAppID, creation time, tag, and expiration time of the new app on the overview page of the console.

### Step 2. Obtain the SDKAppID and SECRETKEY
1. Click the target app card to go to the basic configuration page of the app.
2. In the Basic info area, click `Display key`, and then copy and save the key information, which is SECRETKEY.
![](https://github.com/user-attachments/assets/26c1f583-cc2a-4f19-b952-6ca7ebccf27f)

### Step 3. Download the source code and install dependencies
```
# Please run the following code in the terminal.
$ git clone https://github.com/TencentCloud/chat-uikit-react
# Go to the project  
$ cd chat-uikit-react/examples/sample-chat
# Install dependencies of the demo and build chat-uikit-react
$ npm install
```
### Step 4. Configure
1. Open the `examples/sample-chat` project and locate the `GenerateTestUserSig.js` file in `./examples/sample-chat/src/debug/GenerateTestUserSig.js`.
2. Set the `SDKAppID` and `SECRETKEY` obtained at Step 2.
![](https://github.com/user-attachments/assets/57858e6d-6dad-4c99-bb69-b32b5f78f813)

### Step 5. Run the demo
```
$ npm run start
```

