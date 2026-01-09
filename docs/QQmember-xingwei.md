1.**文明交流**：群成员应保持良好的交流氛围，使用文明用语，尊重他人意见和观点。

2.**积极分享**：鼓励群成员分享 Fold Craft Launcher 游戏相关的经验、技巧、资源等，共同提升游戏水平。

3.**问题解决**：群成员在遇到问题或纠纷时，应首先尝试通过友好沟通解决，避免矛盾升级。如无法自行解决，可寻求管理员或群主的帮助。

4.**维护群誉**：群成员应自觉维护群的声誉，不得在外散播对本群不利的言论或信息。如发现有人恶意诋毁本群，应及时向管理员或群主报告。

5.**尊重原创**：尊重他人的原创内容，如需转载或引用，应注明出处和作者，并获得相应授权。

6.**学习交流**：鼓励群成员积极参与群内组织的学习交流活动，互相学习，共同进步。

7.**新成员引导**：新成员入群时，老成员应主动上前打招呼，介绍群内规则和文化，帮助新成员尽快融入群聊。

8.**隐私保护**：群成员应自觉保护自己和他人的隐私，不在群内随意透露敏感信息，如个人身份证明、银行账户等。

9.**讨论组织**：在群内讨论问题时，应尽量保持话题的集中性和逻辑性，避免跑题和混乱，确保讨论的有效性和成果性。

10.**资源分享**：分享资源时，应确保资源的合法性和安全性，不得分享含有病毒、木马等恶意软件的资源链接。

11.**反馈建议**：对群内管理、活动组织等方面有建议或意见时，应通过合理渠道向管理员或群主反馈，共同促进群的发展和完善。

12.**行为示范**：群内的管理员和老成员应以身作则，遵守群规，为新成员树立良好的榜样，引导群内形成良好的风气。

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

  /* 标题过长换行，超出部分隐藏（移动端重要） */
  .title-text {
    white-space: normal;
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
  <a href="/details/" class="prev-section">
    <span class="cat-text">上一页</span>
    <span class="title-text">群规详情</span>
  </a>

  <!-- 中间分隔线（可选，如果不需要可以删掉<div class="divider-line"></div>这一行） -->
  <div class="divider-line"></div>

  <!-- 右侧：下一章 -->
  <a href="/download/" class="next-section">
    <span class="cat-text">下一页</span>
    <span class="title-text">FCL与MC链接跳转</span>
  </a>
</div>
