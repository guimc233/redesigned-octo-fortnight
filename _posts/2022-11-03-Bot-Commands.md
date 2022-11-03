---
layout: post
title: 机器人命令~
---

> 此处为一些常用功能 部分质量可能没有覆盖到
{: .prompt-tip }

> 本篇博客图片较多 流量党情注意流量消耗
{: .prompt-warning }

<details>
<summary>网络查询 (限制权限)</summary>
<pre>
<code>
- /tracert &lt;目标名称&gt;	# 路由追踪
- /ping &lt;目标名称&gt; [ping次数] [超时时间(毫秒)]	# Ping连接测试
- /dns &lt;记录名称&gt; [记录类型] [自定义DNS]	# dns查询
- /web &lt;URL链接&gt; [编码]	# 网页测试
- /nmap &lt;目标名称&gt;	# 端口扫描
- /nmap &lt;目标名称&gt; &lt;起始端口&gt; &lt;结束端口&gt;	# 端口扫描
- /nmap &lt;目标名称&gt; &lt;端口&gt;	# 端口扫描
- /doh &lt;域名&gt; [类型]	# HTTPS加密DNS查询
- /gc &lt;目标名称&gt;	# 查墙
</code>
</pre>
</details>
1. 音乐
    - /music 点歌 \<name\>	# 点首歌听吧~
    - /music 转换 \<name\>	# 转换音乐分享

2. 图片获取
    - /acg	 # 动漫图片!
    - /httpcat \<code\>	# Funny Cat Pictures

3. 方块人 (由 [McMotd](https://github.com/Under-estimate/McMotd) 插件提供)
    - /mcp \<target\>	# 获取指定MC服务器的信息
    - /mcp	 # 获取指定MC服务器的信息
    - /mcadd \<name\> \<address\>	# 为当前群聊绑定MC服务器
    - /mcdel \<name\>	# 删除当前群聊绑定的服务器

4. 娱乐
    1. 由 [MuteGames](https://github.com/EvolvedGhost/MuteGames) 插件提供
        - (/)banMe	 # 自裁指令
        
        - (/)banMe \<seconds\>	# 自裁指令
        
	    - (/)duel	 # 决斗指令
        
        - (/)roulette	 # 俄罗斯轮盘指令
        
    2. 由 [AutoGroup](https://github.com/LaoLittle/AutoGroup) 插件提供
    
5. 图片生成

    1. 由 (PatPat)[https://github.com/LaoLittle/PatPat] 插件提供

       -  摸 + @目标  生成摸头Gif
    
    2. 由 [DrawMeme](https://github.com/LaoLittle/DrawMeme) 插件提供
       - #ph: Pxxnhub生成器
           - #ph + 文字    (会自动截取一半)
              ![1643769094640-1bcf3ad8-6e0e-40ba-9379-d6827c6eb539-uh1-05-neyj38c-y68e-87a.webp](https://repo.guimc.ltd/posts/2022/11/03/1643769094640-1bcf3ad8-6e0e-40ba-9379-d6827c6eb539-uh1-05-neyj38c-y68e-87a.webp)
           - #ph + 文字 + 文字
              ![1643769063079-aa4083d8-5cc1-4ee9-ba76-558ec305bf2f-image.webp](https://repo.guimc.ltd/posts/2022/11/03/1643769063079-aa4083d8-5cc1-4ee9-ba76-558ec305bf2f-image.webp)
       - #bw: 灰白照生成器  #bw + 文字 + 图片（若没有图片则要求获取）
             ![1643899604099-22.webp](https://repo.guimc.ltd/posts/2022/11/03/1643899604099-22.webp)
         - #5000兆 | #5k兆
            - #5k兆 + 文字        (分词效果和Pxxnhub生成器一致)
            - #5k兆 + 文字 + 文字
              ![1645006169912-49.webp](https://repo.guimc.ltd/posts/2022/11/03/1645006169912-49.webp)
       - emoji 合成 
        - 发送任意两个emoji（不支持的emoji不会发送）
          ![1645006235365-23.webp](https://repo.guimc.ltd/posts/2022/11/03/1645006235365-23.webp)
       - 0%生成器  使用#0即可
            ![1646562551927-5b9d8355-1401-4b3c-8991-6259b196ea20-image.webp](https://repo.guimc.ltd/posts/2022/11/03/1646562551927-5b9d8355-1401-4b3c-8991-6259b196ea20-image.webp)
       - osu生成  #osu + 文字
            ![1656989917119-1654271660710-37cb6493-438a-4cb5-8be8-c07528d5b0d3-image.png.webp](https://repo.guimc.ltd/posts/2022/11/03/1656989917119-1654271660710-37cb6493-438a-4cb5-8be8-c07528d5b0d3-image.png.webp)
       - marble大理石滤镜  #marble + 图片
            ![1656989996727-1653992153458-421c7dc2-c4ba-435b-9ab0-1be3f0acad82-image.png.webp](https://repo.guimc.ltd/posts/2022/11/03/1656989996727-1653992153458-421c7dc2-c4ba-435b-9ab0-1be3f0acad82-image.png.webp)
       - flash假闪照  #flash + 图片
            ![1656990024061-1653992169077-65bbfd9d-6c01-4549-aa12-619a2c8e6e20-image.png.webp](https://repo.guimc.ltd/posts/2022/11/03/1656990024061-1653992169077-65bbfd9d-6c01-4549-aa12-619a2c8e6e20-image.png.webp)
       - erode图像腐蚀
            - #erode + 图片
            - #erode + 数字 + 数字 + 数字 + 图片
              ![1656990106823-1653230905666-2db8fbf7-5464-4f06-abf9-8ade13c8b380-image.png.webp](https://repo.guimc.ltd/posts/2022/11/03/1656990106823-1653230905666-2db8fbf7-5464-4f06-abf9-8ade13c8b380-image.png.webp)

              ![1656990112471-1653231014640-deb017db-f555-4121-a528-0a4c65ba4e75-image.png.webp](https://repo.guimc.ltd/posts/2022/11/03/1656990112471-1653231014640-deb017db-f555-4121-a528-0a4c65ba4e75-image.png.webp)

              ![1656990156809-1653230862323-397f0daf-0367-44cb-b0ca-81bf49c91970-image.png.webp](https://repo.guimc.ltd/posts/2022/11/03/1656990156809-1653230862323-397f0daf-0367-44cb-b0ca-81bf49c91970-image.png.webp)
    
              ![1656990270705-1653230869837-5cfe7f6d-46ab-41d0-8643-25aec1bf0cd9-image.png.webp](https://repo.guimc.ltd/posts/2022/11/03/1656990270705-1653230869837-5cfe7f6d-46ab-41d0-8643-25aec1bf0cd9-image.png.webp)
