<div class="Box-sc-g0xbh4-0 bJMeLZ js-snippet-clipboard-copy-unpositioned" data-hpc="true"><article class="markdown-body entry-content container-lg" itemprop="text"><div class="markdown-heading" dir="auto"><h1 tabindex="-1" class="heading-element" dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">软件开发的通信代理</font></font></h1><a id="user-content-communicative-agents-for-software-development" class="anchor" aria-label="永久链接：软件开发的通信代理" href="#communicative-agents-for-software-development"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a></div>
<p align="center" dir="auto">
  <a target="_blank" rel="noopener noreferrer" href="/OpenBMB/ChatDev/blob/main/misc/logo1.png"><img src="/OpenBMB/ChatDev/raw/main/misc/logo1.png" width="550" style="max-width: 100%;"></a>
</p>
<p align="center" dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">
    【中文 |</font></font><a href="/OpenBMB/ChatDev/blob/main/readme/README-Chinese.md"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">中文</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">|</font></font><a href="/OpenBMB/ChatDev/blob/main/readme/README-Japanese.md"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">日语</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">|</font></font><a href="/OpenBMB/ChatDev/blob/main/readme/README-Korean.md"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">韩语</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">|</font></font><a href="/OpenBMB/ChatDev/blob/main/readme/README-Filipino.md"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">菲律宾语</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">|</font></font><a href="/OpenBMB/ChatDev/blob/main/readme/README-French.md"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">法语</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">|</font></font><a href="/OpenBMB/ChatDev/blob/main/readme/README-Slovak.md"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">斯洛伐克语</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">|</font></font><a href="/OpenBMB/ChatDev/blob/main/readme/README-Portuguese.md"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">葡萄牙语</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">|</font></font><a href="/OpenBMB/ChatDev/blob/main/readme/README-Spanish.md"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">西班牙语</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">|</font></font><a href="/OpenBMB/ChatDev/blob/main/readme/README-Dutch.md"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">荷兰语</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">|</font></font><a href="/OpenBMB/ChatDev/blob/main/readme/README-Turkish.md"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">土耳其语</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">|</font></font><a href="/OpenBMB/ChatDev/blob/main/readme/README-Hindi.md"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">没有</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">|</font></font><a href="/OpenBMB/ChatDev/blob/main/readme/README-Bahasa-Indonesia.md"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">印尼语</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">】
</font></font></p>
<p align="center" dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">
    【📚</font></font><a href="/OpenBMB/ChatDev/blob/main/wiki.md"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">维基</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">| 🚀</font></font><a href="/OpenBMB/ChatDev/blob/main/wiki.md#visualizer"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">展示台</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">| 👥</font></font><a href="/OpenBMB/ChatDev/blob/main/Contribution.md"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">社区构建的软件</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">| 🔧</font></font><a href="/OpenBMB/ChatDev/blob/main/wiki.md#customization"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">定制</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">| 👾</font></font><a href="https://discord.gg/bn4t2Jy6TT" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">不和谐</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">】
</font></font></p>
<div class="markdown-heading" dir="auto"><h2 tabindex="-1" class="heading-element" dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">📖 概述</font></font></h2><a id="user-content--overview" class="anchor" aria-label="永久链接：📖 概述" href="#-overview"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a></div>
<ul dir="auto">
<li><strong><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">ChatDev</font></font></strong><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">是一家</font></font><strong><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">虚拟软件公司</font></font></strong><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">，通过担任不同角色的各种</font></font><strong><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">智能代理</font></font></strong><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">进行运营，包括首席执行官</font></font><a target="_blank" rel="noopener noreferrer" href="/OpenBMB/ChatDev/blob/main/visualizer/static/figures/ceo.png"><img src="/OpenBMB/ChatDev/raw/main/visualizer/static/figures/ceo.png" height="20" style="max-width: 100%;"></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">、首席产品官</font></font><a target="_blank" rel="noopener noreferrer" href="/OpenBMB/ChatDev/blob/main/visualizer/static/figures/cpo.png"><img src="/OpenBMB/ChatDev/raw/main/visualizer/static/figures/cpo.png" height="20" style="max-width: 100%;"></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">、首席技术官</font></font><a target="_blank" rel="noopener noreferrer" href="/OpenBMB/ChatDev/blob/main/visualizer/static/figures/cto.png"><img src="/OpenBMB/ChatDev/raw/main/visualizer/static/figures/cto.png" height="20" style="max-width: 100%;"></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">、程序员</font></font><a target="_blank" rel="noopener noreferrer" href="/OpenBMB/ChatDev/blob/main/visualizer/static/figures/programmer.png"><img src="/OpenBMB/ChatDev/raw/main/visualizer/static/figures/programmer.png" height="20" style="max-width: 100%;"></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">、审阅员</font></font><a target="_blank" rel="noopener noreferrer" href="/OpenBMB/ChatDev/blob/main/visualizer/static/figures/reviewer.png"><img src="/OpenBMB/ChatDev/raw/main/visualizer/static/figures/reviewer.png" height="20" style="max-width: 100%;"></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">、测试员</font></font><a target="_blank" rel="noopener noreferrer" href="/OpenBMB/ChatDev/blob/main/visualizer/static/figures/tester.png"><img src="/OpenBMB/ChatDev/raw/main/visualizer/static/figures/tester.png" height="20" style="max-width: 100%;"></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">、美术设计师</font></font><a target="_blank" rel="noopener noreferrer" href="/OpenBMB/ChatDev/blob/main/visualizer/static/figures/designer.png"><img src="/OpenBMB/ChatDev/raw/main/visualizer/static/figures/designer.png" height="20" style="max-width: 100%;"></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">。这些代理形成了一个多代理组织结构，并因“通过编程彻底改变数字世界”的使命而团结在一起。 ChatDev 中的代理通过参加专门的功能研讨会</font></font><strong><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">进行协作</font></font></strong><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">，包括设计、编码、测试和记录等任务。</font></font></li>
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">ChatDev 的主要目标是提供一个</font></font><strong><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">易于使用</font></font></strong><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">、</font></font><strong><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">高度可定制</font></font></strong><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">和</font></font><strong><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">可扩展的</font></font></strong><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">框架，该框架基于大型语言模型 (LLM)，并作为研究集体智慧的理想场景。</font></font></li>
</ul>
<p align="center" dir="auto">
  <a target="_blank" rel="noopener noreferrer" href="/OpenBMB/ChatDev/blob/main/misc/company.png"><img src="/OpenBMB/ChatDev/raw/main/misc/company.png" width="600" style="max-width: 100%;"></a>
</p>
<div class="markdown-heading" dir="auto"><h2 tabindex="-1" class="heading-element" dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">🎉新闻</font></font></h2><a id="user-content--news" class="anchor" aria-label="永久链接：🎉新闻" href="#-news"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a></div>
<ul dir="auto">
<li>
<p dir="auto"><strong><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">2024 年 5 月 7 日，我们引入了“迭代体验细化”（IER），这是一种新颖的方法，指导员和助理代理可以增强以捷径为导向的体验，以有效地适应新任务。这种方法涵盖了一系列任务中的经验获取、利用、传播和消除。我们的预印本论文可在</font></font><a href="https://arxiv.org/abs/2405.04219" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">https://arxiv.org/abs/2405.04219</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">获取，这项技术很快就会被纳入 ChatDev 中。</font></font></strong></p>
<p align="center" dir="auto">
<a target="_blank" rel="noopener noreferrer" href="/OpenBMB/ChatDev/blob/main/misc/ier.png"><img src="/OpenBMB/ChatDev/raw/main/misc/ier.png" width="220" style="max-width: 100%;"></a>
</p>
</li>
<li>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">2024 年 1 月 25 日：我们已将体验式共同学习模块集成到 ChatDev 中。请参阅</font></font><a href="/OpenBMB/ChatDev/blob/main/wiki.md#co-tracking"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">体验式共同学习指南</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">。</font></font></p>
</li>
<li>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">2023 年 12 月 28 日：我们推出体验式共同学习，这是一种创新方法，指导员和助理代理可以积累捷径导向的经验，以有效解决新任务，减少重复错误并提高效率。请查看我们的预印本论文：</font></font><a href="https://arxiv.org/abs/2312.17025" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">https://arxiv.org/abs/2312.17025</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">，该技术将很快集成到 ChatDev 中。</font></font></p>
<p align="center" dir="auto">
<a target="_blank" rel="noopener noreferrer" href="/OpenBMB/ChatDev/blob/main/misc/ecl.png"><img src="/OpenBMB/ChatDev/raw/main/misc/ecl.png" width="860" style="max-width: 100%;"></a>
</p>
</li>
<li>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">2023 年 11 月 15 日：我们推出了 ChatDev 作为 SaaS 平台，使软件开发人员和创新企业家能够以极低的成本和进入门槛高效地构建软件。尝试一下</font></font><a href="https://chatdev.modelbest.cn/" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">https://chatdev.modelbest.cn/</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">。</font></font></p>
<p align="center" dir="auto">
<a target="_blank" rel="noopener noreferrer" href="/OpenBMB/ChatDev/blob/main/misc/saas.png"><img src="/OpenBMB/ChatDev/raw/main/misc/saas.png" width="560" style="max-width: 100%;"></a>
</p>
</li>
<li>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">2023 年 11 月 2 日：ChatDev 现在支持一项新功能：增量开发，允许代理在现有代码上进行开发。尝试</font></font><code>--config "incremental" --path "[source_code_directory_path]"</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">启动它。</font></font></p>
<p align="center" dir="auto">
<a target="_blank" rel="noopener noreferrer" href="/OpenBMB/ChatDev/blob/main/misc/increment.png"><img src="/OpenBMB/ChatDev/raw/main/misc/increment.png" width="700" style="max-width: 100%;"></a>
</p>
</li>
<li>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">2023 年 10 月 26 日：ChatDev 现已支持 Docker 安全执行（感谢</font></font><a href="https://github.com/ManindraDeMel"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">ManindraDeMel</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">的贡献）。请参阅</font></font><a href="/OpenBMB/ChatDev/blob/main/wiki.md#docker-start"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Docker 入门指南</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">。</font></font></p>
<p align="center" dir="auto">
<a target="_blank" rel="noopener noreferrer" href="/OpenBMB/ChatDev/blob/main/misc/docker.png"><img src="/OpenBMB/ChatDev/raw/main/misc/docker.png" width="400" style="max-width: 100%;"></a>
</p>
</li>
</ul>
<ul dir="auto">
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">2023年9月25日：</font></font><strong><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Git</font></font></strong><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">模式现已上线，程序员</font></font><a target="_blank" rel="noopener noreferrer" href="/OpenBMB/ChatDev/blob/main/visualizer/static/figures/programmer.png"><img src="/OpenBMB/ChatDev/raw/main/visualizer/static/figures/programmer.png" height="20" style="max-width: 100%;"></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">可以利用Git进行版本控制。要启用此功能，只需将其设置</font></font><code>"git_management"</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">为</font></font><code>"True"</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">in </font></font><code>ChatChainConfig.json</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">。请参阅</font></font><a href="/OpenBMB/ChatDev/blob/main/wiki.md#git-mode"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">指南</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">。
</font></font><p align="center" dir="auto">
<a target="_blank" rel="noopener noreferrer" href="/OpenBMB/ChatDev/blob/main/misc/github.png"><img src="/OpenBMB/ChatDev/raw/main/misc/github.png" width="600" style="max-width: 100%;"></a>
</p>
</li>
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">2023 年 9 月 20 日：</font></font><strong><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">人类代理交互</font></font></strong><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">模式现已推出！您可以通过扮演审稿人的角色参与ChatDev团队</font></font><a target="_blank" rel="noopener noreferrer" href="/OpenBMB/ChatDev/blob/main/visualizer/static/figures/reviewer.png"><img src="/OpenBMB/ChatDev/raw/main/visualizer/static/figures/reviewer.png" height="20" style="max-width: 100%;"></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">，并向程序员提出建议</font></font><a target="_blank" rel="noopener noreferrer" href="/OpenBMB/ChatDev/blob/main/visualizer/static/figures/programmer.png"><img src="/OpenBMB/ChatDev/raw/main/visualizer/static/figures/programmer.png" height="20" style="max-width: 100%;"></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">；尝试</font></font><code>python3 run.py --task [description_of_your_idea] --config "Human"</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">。请参阅</font></font><a href="/OpenBMB/ChatDev/blob/main/wiki.md#human-agent-interaction"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">指南</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">和</font></font><a href="/OpenBMB/ChatDev/blob/main/WareHouse/Gomoku_HumanAgentInteraction_20230920135038"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">示例</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">。
</font></font><p align="center" dir="auto">
<a target="_blank" rel="noopener noreferrer" href="/OpenBMB/ChatDev/blob/main/misc/Human_intro.png"><img src="/OpenBMB/ChatDev/raw/main/misc/Human_intro.png" width="600" style="max-width: 100%;"></a>
</p>
</li>
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">2023 年 9 月 1 日：</font></font><strong><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">艺术</font></font></strong><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">模式现已推出！您可以激活设计器代理</font></font><a target="_blank" rel="noopener noreferrer" href="/OpenBMB/ChatDev/blob/main/visualizer/static/figures/designer.png"><img src="/OpenBMB/ChatDev/raw/main/visualizer/static/figures/designer.png" height="20" style="max-width: 100%;"></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">来生成软件中使用的图像；尝试</font></font><code>python3 run.py --task [description_of_your_idea] --config "Art"</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">。请参阅</font></font><a href="/OpenBMB/ChatDev/blob/main/wiki.md#art"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">指南</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">和</font></font><a href="/OpenBMB/ChatDev/blob/main/WareHouse/gomokugameArtExample_THUNLP_20230831122822"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">示例</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">。</font></font></li>
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">2023年8月28日：系统公开。</font></font></li>
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">2023年8月17日：v1.0.0版本已准备好发布。</font></font></li>
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">2023年7月30日：用户可以自定义ChatChain、阶段和角色设置。此外，现在还支持在线日志模式和回放模式。</font></font></li>
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">2023年7月16日：与该项目相关的</font></font><a href="https://arxiv.org/abs/2307.07924" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">预印本论文</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">发表。</font></font></li>
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">2023 年 6 月 30 日：ChatDev 存储库的初始版本发布。</font></font></li>
</ul>
<div class="markdown-heading" dir="auto"><h2 tabindex="-1" class="heading-element" dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">❓ ChatDev 可以做什么？</font></font></h2><a id="user-content--what-can-chatdev-do" class="anchor" aria-label="永久链接：❓ ChatDev 可以做什么？" href="#-what-can-chatdev-do"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a></div>
<p dir="auto"><a target="_blank" rel="noopener noreferrer" href="/OpenBMB/ChatDev/blob/main/misc/intro.png"><img src="/OpenBMB/ChatDev/raw/main/misc/intro.png" alt="介绍" style="max-width: 100%;"></a></p>
<details open="" class="details-reset border rounded-2">
  <summary class="px-3 py-2">
    <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-device-camera-video">
    <path d="M16 3.75v8.5a.75.75 0 0 1-1.136.643L11 10.575v.675A1.75 1.75 0 0 1 9.25 13h-7.5A1.75 1.75 0 0 1 0 11.25v-6.5C0 3.784.784 3 1.75 3h7.5c.966 0 1.75.784 1.75 1.75v.675l3.864-2.318A.75.75 0 0 1 16 3.75Zm-6.5 1a.25.25 0 0 0-.25-.25h-7.5a.25.25 0 0 0-.25.25v6.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-6.5ZM11 8.825l3.5 2.1v-5.85l-3.5 2.1Z"></path>
</svg>
    <span aria-label="视频说明demo.mp4" class="m-1"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">演示.mp4</font></font></span>
    <span class="dropdown-caret"></span>
  </summary>

  <video src="https://private-user-images.githubusercontent.com/11889052/263643733-80d01d2f-677b-4399-ad8b-f7af9bb62b72.mp4?jwt=eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9.eyJpc3MiOiJnaXRodWIuY29tIiwiYXVkIjoicmF3LmdpdGh1YnVzZXJjb250ZW50LmNvbSIsImtleSI6ImtleTUiLCJleHAiOjE3MTU2NzIwNTQsIm5iZiI6MTcxNTY3MTc1NCwicGF0aCI6Ii8xMTg4OTA1Mi8yNjM2NDM3MzMtODBkMDFkMmYtNjc3Yi00Mzk5LWFkOGItZjdhZjliYjYyYjcyLm1wND9YLUFtei1BbGdvcml0aG09QVdTNC1ITUFDLVNIQTI1NiZYLUFtei1DcmVkZW50aWFsPUFLSUFWQ09EWUxTQTUzUFFLNFpBJTJGMjAyNDA1MTQlMkZ1cy1lYXN0LTElMkZzMyUyRmF3czRfcmVxdWVzdCZYLUFtei1EYXRlPTIwMjQwNTE0VDA3MjkxNFomWC1BbXotRXhwaXJlcz0zMDAmWC1BbXotU2lnbmF0dXJlPTlmODRjN2JhMWJlNzQ3OWJiYmY4ZmMwMTQ5ZDdkYmVkZThmODhkOWM0ZGE3MTdhMDNhMTJkNmEwMzgwMThiZTcmWC1BbXotU2lnbmVkSGVhZGVycz1ob3N0JmFjdG9yX2lkPTAma2V5X2lkPTAmcmVwb19pZD0wIn0.reaWBvNyfFpj_DjE4Y9hLY_2sNY5OCeGKPNdbslpmJE" data-canonical-src="https://private-user-images.githubusercontent.com/11889052/263643733-80d01d2f-677b-4399-ad8b-f7af9bb62b72.mp4?jwt=eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9.eyJpc3MiOiJnaXRodWIuY29tIiwiYXVkIjoicmF3LmdpdGh1YnVzZXJjb250ZW50LmNvbSIsImtleSI6ImtleTUiLCJleHAiOjE3MTU2NzIwNTQsIm5iZiI6MTcxNTY3MTc1NCwicGF0aCI6Ii8xMTg4OTA1Mi8yNjM2NDM3MzMtODBkMDFkMmYtNjc3Yi00Mzk5LWFkOGItZjdhZjliYjYyYjcyLm1wND9YLUFtei1BbGdvcml0aG09QVdTNC1ITUFDLVNIQTI1NiZYLUFtei1DcmVkZW50aWFsPUFLSUFWQ09EWUxTQTUzUFFLNFpBJTJGMjAyNDA1MTQlMkZ1cy1lYXN0LTElMkZzMyUyRmF3czRfcmVxdWVzdCZYLUFtei1EYXRlPTIwMjQwNTE0VDA3MjkxNFomWC1BbXotRXhwaXJlcz0zMDAmWC1BbXotU2lnbmF0dXJlPTlmODRjN2JhMWJlNzQ3OWJiYmY4ZmMwMTQ5ZDdkYmVkZThmODhkOWM0ZGE3MTdhMDNhMTJkNmEwMzgwMThiZTcmWC1BbXotU2lnbmVkSGVhZGVycz1ob3N0JmFjdG9yX2lkPTAma2V5X2lkPTAmcmVwb19pZD0wIn0.reaWBvNyfFpj_DjE4Y9hLY_2sNY5OCeGKPNdbslpmJE" controls="controls" muted="muted" class="d-block rounded-bottom-2 border-top width-fit" style="max-height:640px; min-height: 200px">

  </video>
</details>

<div class="markdown-heading" dir="auto"><h2 tabindex="-1" class="heading-element" dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">⚡️ 快速入门</font></font></h2><a id="user-content-️-quickstart" class="anchor" aria-label="永久链接：⚡️ 快速入门" href="#️-quickstart"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a></div>
<div class="markdown-heading" dir="auto"><h3 tabindex="-1" class="heading-element" dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">💻️ Web 快速入门</font></font></h3><a id="user-content-️-quickstart-with-web" class="anchor" aria-label="永久链接：💻️ 网络快速入门" href="#️-quickstart-with-web"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a></div>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">访问网页进行可视化和配置使用：</font></font><a href="https://chatdev.modelbest.cn/" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">https://chatdev.modelbest.cn/</font></font></a></p>
<div class="markdown-heading" dir="auto"><h3 tabindex="-1" class="heading-element" dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">🖥️ 使用终端快速入门</font></font></h3><a id="user-content-️-quickstart-with-terminal" class="anchor" aria-label="永久链接：🖥️ 使用终端快速入门" href="#️-quickstart-with-terminal"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a></div>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">首先，请按照下列步骤操作：</font></font></p>
<ol dir="auto">
<li>
<p dir="auto"><strong><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">克隆 GitHub 存储库：</font></font></strong><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">首先使用以下命令克隆存储库：</font></font></p>
<div class="snippet-clipboard-content notranslate position-relative overflow-auto"><pre class="notranslate"><code>git clone https://github.com/OpenBMB/ChatDev.git
</code></pre><div class="zeroclipboard-container">
    <clipboard-copy aria-label="Copy" class="ClipboardButton btn btn-invisible js-clipboard-copy m-2 p-0 tooltipped-no-delay d-flex flex-justify-center flex-items-center" data-copy-feedback="Copied!" data-tooltip-direction="w" value="git clone https://github.com/OpenBMB/ChatDev.git" tabindex="0" role="button">
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-copy js-clipboard-copy-icon">
    <path d="M0 6.75C0 5.784.784 5 1.75 5h1.5a.75.75 0 0 1 0 1.5h-1.5a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-1.5a.75.75 0 0 1 1.5 0v1.5A1.75 1.75 0 0 1 9.25 16h-7.5A1.75 1.75 0 0 1 0 14.25Z"></path><path d="M5 1.75C5 .784 5.784 0 6.75 0h7.5C15.216 0 16 .784 16 1.75v7.5A1.75 1.75 0 0 1 14.25 11h-7.5A1.75 1.75 0 0 1 5 9.25Zm1.75-.25a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-7.5a.25.25 0 0 0-.25-.25Z"></path>
</svg>
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-check js-clipboard-check-icon color-fg-success d-none">
    <path d="M13.78 4.22a.75.75 0 0 1 0 1.06l-7.25 7.25a.75.75 0 0 1-1.06 0L2.22 9.28a.751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018L6 10.94l6.72-6.72a.75.75 0 0 1 1.06 0Z"></path>
</svg>
    </clipboard-copy>
  </div></div>
</li>
<li>
<p dir="auto"><strong><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">设置 Python 环境：</font></font></strong><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">确保您拥有 3.9 或更高版本的 Python 环境。您可以使用以下命令创建并激活此环境，并替换</font></font><code>ChatDev_conda_env</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">为您首选的环境名称：</font></font></p>
<div class="snippet-clipboard-content notranslate position-relative overflow-auto"><pre class="notranslate"><code>conda create -n ChatDev_conda_env python=3.9 -y
conda activate ChatDev_conda_env
</code></pre><div class="zeroclipboard-container">
    <clipboard-copy aria-label="Copy" class="ClipboardButton btn btn-invisible js-clipboard-copy m-2 p-0 tooltipped-no-delay d-flex flex-justify-center flex-items-center" data-copy-feedback="Copied!" data-tooltip-direction="w" value="conda create -n ChatDev_conda_env python=3.9 -y
conda activate ChatDev_conda_env" tabindex="0" role="button">
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-copy js-clipboard-copy-icon">
    <path d="M0 6.75C0 5.784.784 5 1.75 5h1.5a.75.75 0 0 1 0 1.5h-1.5a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-1.5a.75.75 0 0 1 1.5 0v1.5A1.75 1.75 0 0 1 9.25 16h-7.5A1.75 1.75 0 0 1 0 14.25Z"></path><path d="M5 1.75C5 .784 5.784 0 6.75 0h7.5C15.216 0 16 .784 16 1.75v7.5A1.75 1.75 0 0 1 14.25 11h-7.5A1.75 1.75 0 0 1 5 9.25Zm1.75-.25a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-7.5a.25.25 0 0 0-.25-.25Z"></path>
</svg>
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-check js-clipboard-check-icon color-fg-success d-none">
    <path d="M13.78 4.22a.75.75 0 0 1 0 1.06l-7.25 7.25a.75.75 0 0 1-1.06 0L2.22 9.28a.751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018L6 10.94l6.72-6.72a.75.75 0 0 1 1.06 0Z"></path>
</svg>
    </clipboard-copy>
  </div></div>
</li>
<li>
<p dir="auto"><strong><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">安装依赖项：</font></font></strong><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">进入</font></font><code>ChatDev</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">目录并通过运行以下命令安装必要的依赖项：</font></font></p>
<div class="snippet-clipboard-content notranslate position-relative overflow-auto"><pre class="notranslate"><code>cd ChatDev
pip3 install -r requirements.txt
</code></pre><div class="zeroclipboard-container">
    <clipboard-copy aria-label="Copy" class="ClipboardButton btn btn-invisible js-clipboard-copy m-2 p-0 tooltipped-no-delay d-flex flex-justify-center flex-items-center" data-copy-feedback="Copied!" data-tooltip-direction="w" value="cd ChatDev
pip3 install -r requirements.txt" tabindex="0" role="button">
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-copy js-clipboard-copy-icon">
    <path d="M0 6.75C0 5.784.784 5 1.75 5h1.5a.75.75 0 0 1 0 1.5h-1.5a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-1.5a.75.75 0 0 1 1.5 0v1.5A1.75 1.75 0 0 1 9.25 16h-7.5A1.75 1.75 0 0 1 0 14.25Z"></path><path d="M5 1.75C5 .784 5.784 0 6.75 0h7.5C15.216 0 16 .784 16 1.75v7.5A1.75 1.75 0 0 1 14.25 11h-7.5A1.75 1.75 0 0 1 5 9.25Zm1.75-.25a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-7.5a.25.25 0 0 0-.25-.25Z"></path>
</svg>
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-check js-clipboard-check-icon color-fg-success d-none">
    <path d="M13.78 4.22a.75.75 0 0 1 0 1.06l-7.25 7.25a.75.75 0 0 1-1.06 0L2.22 9.28a.751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018L6 10.94l6.72-6.72a.75.75 0 0 1 1.06 0Z"></path>
</svg>
    </clipboard-copy>
  </div></div>
</li>
<li>
<p dir="auto"><strong><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">设置 OpenAI API 密钥：</font></font></strong><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">将 OpenAI API 密钥导出为环境变量。替换</font></font><code>"your_OpenAI_API_key"</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">为您的实际 API 密钥。请记住，此环境变量是特定于会话的，因此如果打开新的终端会话，则需要再次设置它。在 Unix/Linux 上：</font></font></p>
<div class="snippet-clipboard-content notranslate position-relative overflow-auto"><pre class="notranslate"><code>export OPENAI_API_KEY="your_OpenAI_API_key"
</code></pre><div class="zeroclipboard-container">
    <clipboard-copy aria-label="Copy" class="ClipboardButton btn btn-invisible js-clipboard-copy m-2 p-0 tooltipped-no-delay d-flex flex-justify-center flex-items-center" data-copy-feedback="Copied!" data-tooltip-direction="w" value="export OPENAI_API_KEY=&quot;your_OpenAI_API_key&quot;" tabindex="0" role="button">
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-copy js-clipboard-copy-icon">
    <path d="M0 6.75C0 5.784.784 5 1.75 5h1.5a.75.75 0 0 1 0 1.5h-1.5a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-1.5a.75.75 0 0 1 1.5 0v1.5A1.75 1.75 0 0 1 9.25 16h-7.5A1.75 1.75 0 0 1 0 14.25Z"></path><path d="M5 1.75C5 .784 5.784 0 6.75 0h7.5C15.216 0 16 .784 16 1.75v7.5A1.75 1.75 0 0 1 14.25 11h-7.5A1.75 1.75 0 0 1 5 9.25Zm1.75-.25a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-7.5a.25.25 0 0 0-.25-.25Z"></path>
</svg>
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-check js-clipboard-check-icon color-fg-success d-none">
    <path d="M13.78 4.22a.75.75 0 0 1 0 1.06l-7.25 7.25a.75.75 0 0 1-1.06 0L2.22 9.28a.751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018L6 10.94l6.72-6.72a.75.75 0 0 1 1.06 0Z"></path>
</svg>
    </clipboard-copy>
  </div></div>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">在 Windows 上：</font></font></p>
<div class="snippet-clipboard-content notranslate position-relative overflow-auto"><pre class="notranslate"><code>$env:OPENAI_API_KEY="your_OpenAI_API_key"
</code></pre><div class="zeroclipboard-container">
    <clipboard-copy aria-label="Copy" class="ClipboardButton btn btn-invisible js-clipboard-copy m-2 p-0 tooltipped-no-delay d-flex flex-justify-center flex-items-center" data-copy-feedback="Copied!" data-tooltip-direction="w" value="$env:OPENAI_API_KEY=&quot;your_OpenAI_API_key&quot;" tabindex="0" role="button">
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-copy js-clipboard-copy-icon">
    <path d="M0 6.75C0 5.784.784 5 1.75 5h1.5a.75.75 0 0 1 0 1.5h-1.5a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-1.5a.75.75 0 0 1 1.5 0v1.5A1.75 1.75 0 0 1 9.25 16h-7.5A1.75 1.75 0 0 1 0 14.25Z"></path><path d="M5 1.75C5 .784 5.784 0 6.75 0h7.5C15.216 0 16 .784 16 1.75v7.5A1.75 1.75 0 0 1 14.25 11h-7.5A1.75 1.75 0 0 1 5 9.25Zm1.75-.25a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-7.5a.25.25 0 0 0-.25-.25Z"></path>
</svg>
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-check js-clipboard-check-icon color-fg-success d-none">
    <path d="M13.78 4.22a.75.75 0 0 1 0 1.06l-7.25 7.25a.75.75 0 0 1-1.06 0L2.22 9.28a.751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018L6 10.94l6.72-6.72a.75.75 0 0 1 1.06 0Z"></path>
</svg>
    </clipboard-copy>
  </div></div>
</li>
<li>
<p dir="auto"><strong><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">构建您的软件：</font></font></strong><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">使用以下命令启动软件的构建，替换</font></font><code>[description_of_your_idea]</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">为您的想法描述和</font></font><code>[project_name]</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">所需的项目名称：在 Unix/Linux 上：</font></font></p>
<div class="snippet-clipboard-content notranslate position-relative overflow-auto"><pre class="notranslate"><code>python3 run.py --task "[description_of_your_idea]" --name "[project_name]"
</code></pre><div class="zeroclipboard-container">
    <clipboard-copy aria-label="Copy" class="ClipboardButton btn btn-invisible js-clipboard-copy m-2 p-0 tooltipped-no-delay d-flex flex-justify-center flex-items-center" data-copy-feedback="Copied!" data-tooltip-direction="w" value="python3 run.py --task &quot;[description_of_your_idea]&quot; --name &quot;[project_name]&quot;" tabindex="0" role="button">
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-copy js-clipboard-copy-icon">
    <path d="M0 6.75C0 5.784.784 5 1.75 5h1.5a.75.75 0 0 1 0 1.5h-1.5a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-1.5a.75.75 0 0 1 1.5 0v1.5A1.75 1.75 0 0 1 9.25 16h-7.5A1.75 1.75 0 0 1 0 14.25Z"></path><path d="M5 1.75C5 .784 5.784 0 6.75 0h7.5C15.216 0 16 .784 16 1.75v7.5A1.75 1.75 0 0 1 14.25 11h-7.5A1.75 1.75 0 0 1 5 9.25Zm1.75-.25a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-7.5a.25.25 0 0 0-.25-.25Z"></path>
</svg>
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-check js-clipboard-check-icon color-fg-success d-none">
    <path d="M13.78 4.22a.75.75 0 0 1 0 1.06l-7.25 7.25a.75.75 0 0 1-1.06 0L2.22 9.28a.751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018L6 10.94l6.72-6.72a.75.75 0 0 1 1.06 0Z"></path>
</svg>
    </clipboard-copy>
  </div></div>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">在 Windows 上：</font></font></p>
<div class="snippet-clipboard-content notranslate position-relative overflow-auto"><pre class="notranslate"><code>python run.py --task "[description_of_your_idea]" --name "[project_name]"
</code></pre><div class="zeroclipboard-container">
    <clipboard-copy aria-label="Copy" class="ClipboardButton btn btn-invisible js-clipboard-copy m-2 p-0 tooltipped-no-delay d-flex flex-justify-center flex-items-center" data-copy-feedback="Copied!" data-tooltip-direction="w" value="python run.py --task &quot;[description_of_your_idea]&quot; --name &quot;[project_name]&quot;" tabindex="0" role="button">
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-copy js-clipboard-copy-icon">
    <path d="M0 6.75C0 5.784.784 5 1.75 5h1.5a.75.75 0 0 1 0 1.5h-1.5a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-1.5a.75.75 0 0 1 1.5 0v1.5A1.75 1.75 0 0 1 9.25 16h-7.5A1.75 1.75 0 0 1 0 14.25Z"></path><path d="M5 1.75C5 .784 5.784 0 6.75 0h7.5C15.216 0 16 .784 16 1.75v7.5A1.75 1.75 0 0 1 14.25 11h-7.5A1.75 1.75 0 0 1 5 9.25Zm1.75-.25a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-7.5a.25.25 0 0 0-.25-.25Z"></path>
</svg>
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-check js-clipboard-check-icon color-fg-success d-none">
    <path d="M13.78 4.22a.75.75 0 0 1 0 1.06l-7.25 7.25a.75.75 0 0 1-1.06 0L2.22 9.28a.751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018L6 10.94l6.72-6.72a.75.75 0 0 1 1.06 0Z"></path>
</svg>
    </clipboard-copy>
  </div></div>
</li>
<li>
<p dir="auto"><strong><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">运行您的软件：</font></font></strong><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">生成后，您可以在</font></font><code>WareHouse</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">特定项目文件夹下的目录中找到您的软件，例如</font></font><code>project_name_DefaultOrganization_timestamp</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">.在该目录中使用以下命令运行您的软件： 在 Unix/Linux 上：</font></font></p>
<div class="snippet-clipboard-content notranslate position-relative overflow-auto"><pre class="notranslate"><code>cd WareHouse/project_name_DefaultOrganization_timestamp
python3 main.py
</code></pre><div class="zeroclipboard-container">
    <clipboard-copy aria-label="Copy" class="ClipboardButton btn btn-invisible js-clipboard-copy m-2 p-0 tooltipped-no-delay d-flex flex-justify-center flex-items-center" data-copy-feedback="Copied!" data-tooltip-direction="w" value="cd WareHouse/project_name_DefaultOrganization_timestamp
python3 main.py" tabindex="0" role="button">
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-copy js-clipboard-copy-icon">
    <path d="M0 6.75C0 5.784.784 5 1.75 5h1.5a.75.75 0 0 1 0 1.5h-1.5a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-1.5a.75.75 0 0 1 1.5 0v1.5A1.75 1.75 0 0 1 9.25 16h-7.5A1.75 1.75 0 0 1 0 14.25Z"></path><path d="M5 1.75C5 .784 5.784 0 6.75 0h7.5C15.216 0 16 .784 16 1.75v7.5A1.75 1.75 0 0 1 14.25 11h-7.5A1.75 1.75 0 0 1 5 9.25Zm1.75-.25a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-7.5a.25.25 0 0 0-.25-.25Z"></path>
</svg>
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-check js-clipboard-check-icon color-fg-success d-none">
    <path d="M13.78 4.22a.75.75 0 0 1 0 1.06l-7.25 7.25a.75.75 0 0 1-1.06 0L2.22 9.28a.751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018L6 10.94l6.72-6.72a.75.75 0 0 1 1.06 0Z"></path>
</svg>
    </clipboard-copy>
  </div></div>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">在 Windows 上：</font></font></p>
<div class="snippet-clipboard-content notranslate position-relative overflow-auto"><pre class="notranslate"><code>cd WareHouse/project_name_DefaultOrganization_timestamp
python main.py
</code></pre><div class="zeroclipboard-container">
    <clipboard-copy aria-label="Copy" class="ClipboardButton btn btn-invisible js-clipboard-copy m-2 p-0 tooltipped-no-delay d-flex flex-justify-center flex-items-center" data-copy-feedback="Copied!" data-tooltip-direction="w" value="cd WareHouse/project_name_DefaultOrganization_timestamp
python main.py" tabindex="0" role="button">
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-copy js-clipboard-copy-icon">
    <path d="M0 6.75C0 5.784.784 5 1.75 5h1.5a.75.75 0 0 1 0 1.5h-1.5a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-1.5a.75.75 0 0 1 1.5 0v1.5A1.75 1.75 0 0 1 9.25 16h-7.5A1.75 1.75 0 0 1 0 14.25Z"></path><path d="M5 1.75C5 .784 5.784 0 6.75 0h7.5C15.216 0 16 .784 16 1.75v7.5A1.75 1.75 0 0 1 14.25 11h-7.5A1.75 1.75 0 0 1 5 9.25Zm1.75-.25a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-7.5a.25.25 0 0 0-.25-.25Z"></path>
</svg>
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-check js-clipboard-check-icon color-fg-success d-none">
    <path d="M13.78 4.22a.75.75 0 0 1 0 1.06l-7.25 7.25a.75.75 0 0 1-1.06 0L2.22 9.28a.751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018L6 10.94l6.72-6.72a.75.75 0 0 1 1.06 0Z"></path>
</svg>
    </clipboard-copy>
  </div></div>
</li>
</ol>
<div class="markdown-heading" dir="auto"><h3 tabindex="-1" class="heading-element" dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">🐳 Docker 快速入门</font></font></h3><a id="user-content--quickstart-with-docker" class="anchor" aria-label="永久链接：🐳 Docker 快速入门" href="#-quickstart-with-docker"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a></div>
<ul dir="auto">
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">我们感谢</font></font><a href="https://github.com/ManindraDeMel"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">ManindraDeMel</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">提供 Docker 支持。请参阅</font></font><a href="/OpenBMB/ChatDev/blob/main/wiki.md#docker-start"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Docker 入门指南</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">。</font></font></li>
</ul>
<div class="markdown-heading" dir="auto"><h2 tabindex="-1" class="heading-element" dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">✨️高级技能</font></font></h2><a id="user-content-️-advanced-skills" class="anchor" aria-label="永久链接：✨️高级技能" href="#️-advanced-skills"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a></div>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">有关更多详细信息，请参阅我们的</font></font><a href="/OpenBMB/ChatDev/blob/main/wiki.md"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Wiki</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">，您可以在其中找到：</font></font></p>
<ul dir="auto">
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">所有命令运行参数的介绍。</font></font></li>
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">设置本地 Web 可视化演示的简单指南，可以可视化实时日志、重播日志和 ChatChain。</font></font></li>
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">ChatDev 框架概述。</font></font></li>
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">全面介绍ChainChain配置中的所有高级参数。</font></font></li>
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">自定义 ChatDev 的指南，包括：
</font></font><ul dir="auto">
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">ChatChain：设计您自己的软件开发流程（或任何其他流程），例如</font></font><code>DemandAnalysis -&gt; Coding -&gt; Testing -&gt; Manual</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">。</font></font></li>
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">阶段：在 ChatChain 中设计您自己的阶段，例如</font></font><code>DemandAnalysis</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">.</font></font></li>
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">角色：定义公司中的各种代理，例如</font></font><code>Chief Executive Officer</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">.</font></font></li>
</ul>
</li>
</ul>
<div class="markdown-heading" dir="auto"><h2 tabindex="-1" class="heading-element" dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">🤗 分享您的软件</font></font></h2><a id="user-content--share-your-software" class="anchor" aria-label="永久链接：🤗 分享您的软件" href="#-share-your-software"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a></div>
<p dir="auto"><strong><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">代码</font></font></strong><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">：我们热忱欢迎您有兴趣参与我们的开源项目。如果您遇到任何问题，请随时报告。如果您有任何疑问或准备与我们分享您的工作，请随时创建拉取请求！您的贡献受到高度重视。如果您还有其他需要帮助的地方，请告诉我！</font></font></p>
<p dir="auto"><strong><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">公司</font></font></strong><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">：创建您自己的定制“ChatDev 公司”轻而易举。这种个性化设置涉及三个简单的配置 JSON 文件。查看</font></font><code>CompanyConfig/Default</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">目录中提供的示例。有关自定义的详细说明，请参阅我们的</font></font><a href="/OpenBMB/ChatDev/blob/main/wiki.md"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Wiki</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">。</font></font></p>
<p dir="auto"><strong><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">软件</font></font></strong><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">：每当您使用 ChatDev 开发软件时，都会生成一个包含所有基本信息的相应文件夹。与我们分享您的工作就像提出拉取请求一样简单。这是一个示例：执行命令</font></font><code>python3 run.py --task "design a 2048 game" --name "2048"  --org "THUNLP" --config "Default"</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">。这将创建一个软件包并生成一个名为 的文件夹</font></font><code>/WareHouse/2048_THUNLP_timestamp</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">。在里面，你会发现：</font></font></p>
<ul dir="auto">
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">与2048游戏软件相关的所有文件和文档</font></font></li>
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">负责该软件的公司的配置文件，包括来自</font></font><code>CompanyConfig/Default</code></li>
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">详细说明可用于重放的软件构建过程的综合日志 ( </font></font><code>timestamp.log</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">)</font></font></li>
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">用于创建此软件的初始提示 ( </font></font><code>2048.prompt</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">)</font></font></li>
</ul>
<p dir="auto"><strong><font style="vertical-align: inherit;"></font><a href="/OpenBMB/ChatDev/blob/main/Contribution.md"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">在这里</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">查看社区贡献的软件</font><font style="vertical-align: inherit;">！</font></font></strong></p>
<div class="markdown-heading" dir="auto"><h2 tabindex="-1" class="heading-element" dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">👨&zwj;💻&zwj; 贡献者</font></font></h2><a id="user-content--contributors" class="anchor" aria-label="永久链接：👨&zwj;💻&zwj; 贡献者" href="#-contributors"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a></div>
<a href="https://github.com/OpenBMB/ChatDev/graphs/contributors">
  <img src="https://camo.githubusercontent.com/6b86212e05a0010d2990e896298cc86dbff35e911802ac2482c097f907c50d30/68747470733a2f2f636f6e747269622e726f636b732f696d6167653f7265706f3d4f70656e424d422f43686174446576" data-canonical-src="https://contrib.rocks/image?repo=OpenBMB/ChatDev" style="max-width: 100%;">
</a>
<p dir="auto"><font style="vertical-align: inherit;"></font><a href="https://contrib.rocks" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">用contrib.rocks</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">制作</font><font style="vertical-align: inherit;">。</font></font></p>
<div class="markdown-heading" dir="auto"><h2 tabindex="-1" class="heading-element" dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">🔎 引文</font></font></h2><a id="user-content--citation" class="anchor" aria-label="永久链接：🔎引文" href="#-citation"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a></div>
<div class="snippet-clipboard-content notranslate position-relative overflow-auto"><pre class="notranslate"><code>@misc{qian2023communicative,
      title={Communicative Agents for Software Development},
      author={Chen Qian and Xin Cong and Wei Liu and Cheng Yang and Weize Chen and Yusheng Su and Yufan Dang and Jiahao Li and Juyuan Xu and Dahai Li and Zhiyuan Liu and Maosong Sun},
      year={2023},
      eprint={2307.07924},
      archivePrefix={arXiv},
      primaryClass={cs.SE}
}

@misc{qian2023experiential,
      title={Experiential Co-Learning of Software-Developing Agents}, 
      author={Chen Qian and Yufan Dang and Jiahao Li and Wei Liu and Weize Chen and Cheng Yang and Zhiyuan Liu and Maosong Sun},
      year={2023},
      eprint={2312.17025},
      archivePrefix={arXiv},
      primaryClass={cs.CL}
}

@misc{qian2024iterative,
      title={Iterative Experience Refinement of Software-Developing Agents}, 
      author={Chen Qian, Jiahao Li, Yufan Dang, Wei Liu, YiFei Wang, Zihao Xie, Weize Chen, Cheng Yang, Yingli Zhang, Zhiyuan Liu, Maosong Sun},
      year={2024},
      eprint={2405.04219},
      archivePrefix={arXiv},
      primaryClass={cs.CL}
}
</code></pre><div class="zeroclipboard-container">
    <clipboard-copy aria-label="Copy" class="ClipboardButton btn btn-invisible js-clipboard-copy m-2 p-0 tooltipped-no-delay d-flex flex-justify-center flex-items-center" data-copy-feedback="Copied!" data-tooltip-direction="w" value="@misc{qian2023communicative,
      title={Communicative Agents for Software Development},
      author={Chen Qian and Xin Cong and Wei Liu and Cheng Yang and Weize Chen and Yusheng Su and Yufan Dang and Jiahao Li and Juyuan Xu and Dahai Li and Zhiyuan Liu and Maosong Sun},
      year={2023},
      eprint={2307.07924},
      archivePrefix={arXiv},
      primaryClass={cs.SE}
}

@misc{qian2023experiential,
      title={Experiential Co-Learning of Software-Developing Agents}, 
      author={Chen Qian and Yufan Dang and Jiahao Li and Wei Liu and Weize Chen and Cheng Yang and Zhiyuan Liu and Maosong Sun},
      year={2023},
      eprint={2312.17025},
      archivePrefix={arXiv},
      primaryClass={cs.CL}
}

@misc{qian2024iterative,
      title={Iterative Experience Refinement of Software-Developing Agents}, 
      author={Chen Qian, Jiahao Li, Yufan Dang, Wei Liu, YiFei Wang, Zihao Xie, Weize Chen, Cheng Yang, Yingli Zhang, Zhiyuan Liu, Maosong Sun},
      year={2024},
      eprint={2405.04219},
      archivePrefix={arXiv},
      primaryClass={cs.CL}
}" tabindex="0" role="button">
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-copy js-clipboard-copy-icon">
    <path d="M0 6.75C0 5.784.784 5 1.75 5h1.5a.75.75 0 0 1 0 1.5h-1.5a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-1.5a.75.75 0 0 1 1.5 0v1.5A1.75 1.75 0 0 1 9.25 16h-7.5A1.75 1.75 0 0 1 0 14.25Z"></path><path d="M5 1.75C5 .784 5.784 0 6.75 0h7.5C15.216 0 16 .784 16 1.75v7.5A1.75 1.75 0 0 1 14.25 11h-7.5A1.75 1.75 0 0 1 5 9.25Zm1.75-.25a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-7.5a.25.25 0 0 0-.25-.25Z"></path>
</svg>
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-check js-clipboard-check-icon color-fg-success d-none">
    <path d="M13.78 4.22a.75.75 0 0 1 0 1.06l-7.25 7.25a.75.75 0 0 1-1.06 0L2.22 9.28a.751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018L6 10.94l6.72-6.72a.75.75 0 0 1 1.06 0Z"></path>
</svg>
    </clipboard-copy>
  </div></div>
<div class="markdown-heading" dir="auto"><h2 tabindex="-1" class="heading-element" dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">⚖️ 许可证</font></font></h2><a id="user-content-️-license" class="anchor" aria-label="永久链接：⚖️ 许可证" href="#️-license"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a></div>
<ul dir="auto">
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">源代码许可：我们项目的源代码已根据 Apache 2.0 许可证获得许可。该许可证允许使用、修改和分发代码，但须遵守 Apache 2.0 许可证中概述的某些条件。</font></font></li>
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">数据许可：我们项目中使用的相关数据已根据 CC BY-NC 4.0 进行许可。该许可证明确允许数据的非商业用途。我们想强调的是，使用这些数据集训练的任何模型都应严格遵守非商业使用限制，并且应仅用于研究目的。</font></font></li>
</ul>
<div class="markdown-heading" dir="auto"><h2 tabindex="-1" class="heading-element" dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">🤝致谢</font></font></h2><a id="user-content--acknowledgments" class="anchor" aria-label="永久链接：🤝致谢" href="#-acknowledgments"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a></div>
<p dir="auto"><a href="http://nlp.csai.tsinghua.edu.cn/" rel="nofollow"><img src="/OpenBMB/ChatDev/raw/main/misc/thunlp.png" height="50pt" style="max-width: 100%;"></a>&nbsp;&nbsp;
<a href="https://modelbest.cn/" rel="nofollow"><img src="/OpenBMB/ChatDev/raw/main/misc/modelbest.png" height="50pt" style="max-width: 100%;"></a>&nbsp;&nbsp;
<a href="https://github.com/OpenBMB/AgentVerse/"><img src="/OpenBMB/ChatDev/raw/main/misc/agentverse.png" height="50pt" style="max-width: 100%;"></a>&nbsp;&nbsp;
<a href="https://github.com/OpenBMB/RepoAgent"><img src="/OpenBMB/ChatDev/raw/main/misc/repoagent.png" height="50pt" style="max-width: 100%;"></a>
<a href="https://aibrb.com/introducing-herbie-your-super-employee-for-streamlined-productivity/" rel="nofollow"><img src="https://camo.githubusercontent.com/3087d789b30d7a43638d869c1519dd50e37815f5e1b683723c12c0b1f5f4cb01/68747470733a2f2f61696272622e636f6d2f77702d636f6e74656e742f75706c6f6164732f323032332f30392f46656174757265642d6f6e2d41494252422e636f6d2d77686974652d312e706e67" height="50pt" data-canonical-src="https://aibrb.com/wp-content/uploads/2023/09/Featured-on-AIBRB.com-white-1.png" style="max-width: 100%;"></a></p>
<div class="markdown-heading" dir="auto"><h2 tabindex="-1" class="heading-element" dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">📬 联系方式</font></font></h2><a id="user-content--contact" class="anchor" aria-label="永久链接：📬 联系方式" href="#-contact"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a></div>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">如果您有任何问题、反馈或想要联系，请随时通过电子邮件与我们联系：</font></font><a href="mailto:chatdev.openbmb@outlook.com"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">chatdev.openbmb@outlook.com</font></font></a></p>
</article></div>
