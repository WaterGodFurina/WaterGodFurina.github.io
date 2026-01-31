你们也看到了，本群有个叫＂可爱的棉花＂的QQ机器人
  
以下是针对此机器人写的使用与限制文档
  
## 可以使用的指令
以下指令经过测试，可以正常使用
  
**//mc.ver** - 查询 Minecraft 最新版本
![mc.ver](assets/img/mc.ver.jpg)
  
**//mc.status** - 查询 Minecraft 官方服务状态
![mc.status](assets/img/mc.status.jpg)
  
**//mc.info [server]** - 查询 Java 版服务器信息
![mc.info](assets/img/mcinfo.jpg)
  
**//mc.info.be [server]** - 查询基岩版服务器信息
![mc.info.be](assets/img/mc.info.be.jpg)
  
**//mc.player <username>** - 查询玩家信息
![mc.player](assets/img/mc.player.png)
  
**//mc.modrinth <keyword>** - 查询 Modrinth 资源
![mc.modrinth](assets/img/mc.modrinth.jpg)
![mc.modrinth1](assets/img/mc.modrinth1.jpg)
  
- -t <type:string>: 资源类型 (例如: mod, modpack, resourcepack, shader)
  
![mc.modrinth2](assets/img/mc.modrinth2.jpg)
  
- -v <version:string>: 支持版本
  
- -l <loader:string>: 加载器 (例如: fabric, forge, quilt)
  
- -f <facets:string>: 高级过滤 (JSON 字符串或逗号分隔的 key:value 对)
  
- -k <count:number>: 跳过结果数
  
- -sort <sort:string>: 排序方式 (例如: relevance, downloads, follows, new, updated)
  
- -dep: 显示依赖关系
   
**//mc.curseforge <keyword>** - 查询 CurseForge 资源
![mc.curseforge](assets/img/mc.curseforge.jpg)
![mc.curseforge1](assets/img/mc.curseforge1.jpg)
  
- -t <type:string>: 资源类型 (例如: mod, modpack, resourcepack, shader等)
  
- -v <version:string>: 支持版本
  
- -l <loader:string>: 加载器 (例如: forge, fabric, quilt, neoforge等)
  
- -k <count:number>: 跳过结果数
  

**//mcmod <keyword>** - 查询MC百科上资源
![mc.mcmod](assets/img/mcmod.jpg)
![mc.mcmod1](assets/img/mcmod1.jpg)
  
- //mcmod sodium <number>：跳转到指定页数
  
**//mcwiki <keyword>** - 查询mcwiki内容（调用的是ai总结，可能不准）
![mc.wiki](assets/img/mcwiki.jpg)
![mc.wiki1](assets/img/mcwiki1.jpg)
  
## QQbot限制

- 不允许在1群里面频繁调用机器人，导致影响群友正常聊天
- 在1群里面戳一戳bot和@bot，会被禁言2个小时（不信邪的可以试试）
- 如果有人被禁言后还恶意戳bot，有概率会被踢出群聊

<style>
  /* 移动端优化的导航卡片 */
  .mobile-pagination-card {
    background: #ffffff;
    border: 1px solid #e0e0e0;
    border-radius: 12px;
    padding: 1.2rem;
    margin: 1.5rem 0;
    display: flex;
    justify-content: space-between;
    align-items: center;
    box-shadow: 0 4px 12px rgba(0,0,0,0.08);
  }

  /* 左侧“上一章”区域 */
  .prev-section {
    flex: 1;
    display: flex;
    flex-direction: column;
    align-items: flex-start;
    text-align: left;
    padding-right: 1rem;
  }

  /* 右侧“下一章”区域 */
  .next-section {
    flex: 2; /* 右边占更多空间，因为标题通常更长 */
    display: flex;
    flex-direction: column;
    align-items: flex-end;
    text-align: right;
    padding-left: 1rem;
  }

  /* 类目小字（上一章/下一页） */
  .cat-text {
    font-size: 0.55rem;
    color: #888;
    margin-bottom: 0.25rem;
    font-weight: normal;
  }

  /* 标题大字 */
  .title-text {
    font-size: 1rem; /* 手机上稍微大一点，便于点击 */
    color: #2196F3; /* 蓝色表示链接 */
    font-weight: 600;
    text-decoration: none;
    display: block;
  }

  /* 防止标题过长换行，超出部分隐藏（移动端重要） */
  .title-text {
    white-space: nowrap;
    overflow: hidden;
    text-overflow: ellipsis;
    max-width: 100%; /* 防止溢出 */
  }

  /* Hover效果（虽然手机没有hover，但为了平板或电脑浏览保留） */
  .title-text:hover {
    color: #1976D2;
  }

  /* 分隔线（可选，增加区分度） */
  .divider-line {
    width: 1px;
    height: 24px;
    background-color: #eee;
    margin: 0 1rem;
  }

  @media (max-width: 480px) {
    /* 更小的屏幕下调整内边距 */
    .mobile-pagination-card {
      padding: 1rem;
    }
    .title-text {
      font-size: 0.75rem;
    }
  }
</style>

<!-- HTML 结构 -->
<div class="mobile-pagination-card">
  <!-- 左侧：上一章 -->
  <a href="/others/" class="prev-section">
    <span class="cat-text">上一章</span>
    <span class="title-text">额外补充</span>
  </a>

  <!-- 中间分隔线（可选，如果不需要可以删掉<div class="divider-line"></div>这一行） -->
  <div class="divider-line"></div>

  <!-- 右侧：下一章 -->
  <a href="/" class="next-section">
    <span class="cat-text">没有下一页力</span>
    <span class="title-text">返回首页</span>
  </a>
</div>
