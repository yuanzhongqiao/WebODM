<div class="Box-sc-g0xbh4-0 bJMeLZ js-snippet-clipboard-copy-unpositioned" data-hpc="true"><article class="markdown-body entry-content container-lg" itemprop="text"><p dir="auto"><a target="_blank" rel="noopener noreferrer nofollow" href="https://user-images.githubusercontent.com/1951843/34074943-8f057c3c-e287-11e7-924d-3ccafa60c43a.png"><img alt="网络ODM" src="https://user-images.githubusercontent.com/1951843/34074943-8f057c3c-e287-11e7-924d-3ccafa60c43a.png" width="180" style="max-width: 100%;"></a></p>
<p dir="auto"><a target="_blank" rel="noopener noreferrer nofollow" href="https://camo.githubusercontent.com/03e8d90c4bd6c997af22fd18918b9af660628c6d12afcf1d17b6f001ef1ea0d6/68747470733a2f2f696d672e736869656c64732e696f2f6769746875622f616374696f6e732f776f726b666c6f772f7374617475732f4f70656e44726f6e654d61702f5765624f444d2f6275696c642d616e642d7075626c6973682e796d6c3f6272616e63683d6d6173746572"><img src="https://camo.githubusercontent.com/03e8d90c4bd6c997af22fd18918b9af660628c6d12afcf1d17b6f001ef1ea0d6/68747470733a2f2f696d672e736869656c64732e696f2f6769746875622f616374696f6e732f776f726b666c6f772f7374617475732f4f70656e44726f6e654d61702f5765624f444d2f6275696c642d616e642d7075626c6973682e796d6c3f6272616e63683d6d6173746572" alt="构建状态" data-canonical-src="https://img.shields.io/github/actions/workflow/status/OpenDroneMap/WebODM/build-and-publish.yml?branch=master" style="max-width: 100%;"></a> <a target="_blank" rel="noopener noreferrer nofollow" href="https://camo.githubusercontent.com/cde2d8431778376bc89ad8573a4c62cef63dea87ff277af3bd9972c29f722c7b/68747470733a2f2f696d672e736869656c64732e696f2f6769746875622f762f72656c656173652f4f70656e44726f6e654d61702f5765624f444d"><img src="https://camo.githubusercontent.com/cde2d8431778376bc89ad8573a4c62cef63dea87ff277af3bd9972c29f722c7b/68747470733a2f2f696d672e736869656c64732e696f2f6769746875622f762f72656c656173652f4f70656e44726f6e654d61702f5765624f444d" alt="版本" data-canonical-src="https://img.shields.io/github/v/release/OpenDroneMap/WebODM" style="max-width: 100%;"></a> <a href="https://hosted.weblate.org/engage/webodm/" rel="nofollow"><img src="https://camo.githubusercontent.com/c9d755ec5c22f3bfbc07148663f54bcbb969badde44d670b75a5a9023062dcaa/68747470733a2f2f686f737465642e7765626c6174652e6f72672f776964676574732f7765626f646d2f2d2f7376672d62616467652e737667" alt="已翻译" data-canonical-src="https://hosted.weblate.org/widgets/webodm/-/svg-badge.svg" style="max-width: 100%;"></a></p>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">用于无人机图像处理的用户友好型商业级软件。从航空图像生成地理参考地图、点云、高程模型和纹理 3D 模型。它支持多种引擎进行处理，目前是</font></font><a href="https://github.com/OpenDroneMap/ODM"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">ODM</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">和</font></font><a href="https://github.com/OpenDroneMap/NodeMICMAC/"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">MicMac</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">。</font></font></p>
<p dir="auto"><a target="_blank" rel="noopener noreferrer nofollow" href="https://user-images.githubusercontent.com/1951843/174504753-6869e56e-7b65-4775-bb23-6c1dc256575c.png"><img src="https://user-images.githubusercontent.com/1951843/174504753-6869e56e-7b65-4775-bb23-6c1dc256575c.png" alt="图像" style="max-width: 100%;"></a></p>
<ul dir="auto">
<li><a href="#getting-started"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">入门</font></font></a>
<ul dir="auto">
<li><a href="#manage-processing-nodes"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">管理处理节点</font></font></a></li>
<li><a href="#enable-micmac"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">启用麦克风</font></font></a></li>
<li><a href="#enable-ssl"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">启用 SSL</font></font></a></li>
<li><a href="#where-are-my-files-stored"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">我的文件存储在哪里？</font></font></a></li>
<li><a href="#common-troubleshooting"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">常见故障排除</font></font></a></li>
<li><a href="#backup-and-restore"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">备份还原</font></font></a></li>
<li><a href="#reset-password"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">重设密码</font></font></a></li>
<li><a href="#manage-plugins"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">管理插件</font></font></a></li>
<li><a href="#update"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">更新</font></font></a></li>
</ul>
</li>
<li><a href="#recommended-machine-specs"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">推荐机器规格</font></font></a></li>
<li><a href="#customizing-and-extending"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">定制和扩展</font></font></a></li>
<li><a href="#api-docs"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">API文档</font></font></a></li>
<li><a href="#roadmap"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">路线图</font></font></a></li>
<li><a href="#getting-help"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">寻求帮助</font></font></a></li>
<li><a href="#support-the-project"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">支持项目</font></font></a></li>
<li><a href="#translations"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">翻译</font></font></a></li>
<li><a href="#become-a-contributor"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">成为贡献者</font></font></a></li>
<li><a href="#architecture-overview"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">架构概述</font></font></a></li>
<li><a href="#run-the-docker-version-as-a-linux-service"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">将 docker 版本作为 Linux 服务运行</font></font></a></li>
<li><a href="#run-it-natively"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">本地运行</font></font></a></li>
<li><a href="#run-it-on-the-cloud-google-compute-amazon-aws"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">在云上运行（Google Compute、Amazon AWS）</font></font></a></li>
<li><a href="#license"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">执照</font></font></a></li>
</ul>
<p dir="auto"><a target="_blank" rel="noopener noreferrer nofollow" href="https://user-images.githubusercontent.com/1951843/174504771-b0bcfd29-3960-41f7-8d44-103b63050bd5.png"><img src="https://user-images.githubusercontent.com/1951843/174504771-b0bcfd29-3960-41f7-8d44-103b63050bd5.png" alt="图像" style="max-width: 100%;"></a></p>
<p dir="auto"><a target="_blank" rel="noopener noreferrer nofollow" href="https://user-images.githubusercontent.com/1951843/174504773-f8d8febb-7a45-4d9c-89b6-7d2404c5b8fd.png"><img src="https://user-images.githubusercontent.com/1951843/174504773-f8d8febb-7a45-4d9c-89b6-7d2404c5b8fd.png" alt="图像" style="max-width: 100%;"></a></p>
<div class="markdown-heading" dir="auto"><h2 tabindex="-1" class="heading-element" dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">入门</font></font></h2><a id="user-content-getting-started" class="anchor" aria-label="永久链接：开始使用" href="#getting-started"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a></div>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Windows 和 macOS 用户可以购买自动</font></font><a href="https://www.opendronemap.org/webodm/download#installer" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">安装程序</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">，这使得安装过程更加容易。</font></font></p>
<p dir="auto"><font style="vertical-align: inherit;"></font><a href="https://webodm.net" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">webodm.net</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">还提供了 WebODM 的云托管版本</font><font style="vertical-align: inherit;">。</font></font></p>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">要在您的计算机上手动安装 WebODM：</font></font></p>
<ul dir="auto">
<li>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">安装以下应用程序：</font></font></p>
<ul dir="auto">
<li><a href="https://git-scm.com/downloads" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">git</font></font></a></li>
<li><a href="https://www.docker.com/" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">码头工人</font></font></a></li>
<li><a href="https://docs.docker.com/compose/install/" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Docker-compose</font></font></a></li>
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Python</font></font></li>
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">点</font></font></li>
</ul>
</li>
<li>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Windows 用户应该安装</font></font><a href="https://hub.docker.com/editions/community/docker-ce-desktop-windows" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Docker Desktop</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">，并且 1) 确保启用 Linux 容器（切换到 Linux 容器...），2) 为 Docker 提供足够的 CPU（默认 2）和 RAM（&gt;4Gb，16Gb 更好，但为 Windows 留一些）转至“设置”--“高级”，然后 3) 选择虚拟硬盘驱动器在硬盘上的驻留位置（“设置”--“高级”--“图像和卷”）。</font></font></p>
</li>
<li>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">从 Docker 快速入门终端或 Git Bash (Windows)，或从命令行 (Mac/Linux)，键入：</font></font></p>
</li>
</ul>
<div class="highlight highlight-source-shell notranslate position-relative overflow-auto" dir="auto"><pre>git clone https://github.com/OpenDroneMap/WebODM --config core.autocrlf=input --depth 1
<span class="pl-c1">cd</span> WebODM
./webodm.sh start </pre><div class="zeroclipboard-container">
    <clipboard-copy aria-label="Copy" class="ClipboardButton btn btn-invisible js-clipboard-copy m-2 p-0 tooltipped-no-delay d-flex flex-justify-center flex-items-center" data-copy-feedback="Copied!" data-tooltip-direction="w" value="git clone https://github.com/OpenDroneMap/WebODM --config core.autocrlf=input --depth 1
cd WebODM
./webodm.sh start " tabindex="0" role="button">
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-copy js-clipboard-copy-icon">
    <path d="M0 6.75C0 5.784.784 5 1.75 5h1.5a.75.75 0 0 1 0 1.5h-1.5a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-1.5a.75.75 0 0 1 1.5 0v1.5A1.75 1.75 0 0 1 9.25 16h-7.5A1.75 1.75 0 0 1 0 14.25Z"></path><path d="M5 1.75C5 .784 5.784 0 6.75 0h7.5C15.216 0 16 .784 16 1.75v7.5A1.75 1.75 0 0 1 14.25 11h-7.5A1.75 1.75 0 0 1 5 9.25Zm1.75-.25a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-7.5a.25.25 0 0 0-.25-.25Z"></path>
</svg>
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-check js-clipboard-check-icon color-fg-success d-none">
    <path d="M13.78 4.22a.75.75 0 0 1 0 1.06l-7.25 7.25a.75.75 0 0 1-1.06 0L2.22 9.28a.751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018L6 10.94l6.72-6.72a.75.75 0 0 1 1.06 0Z"></path>
</svg>
    </clipboard-copy>
  </div></div>
<ul dir="auto">
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">如果您在 Linux 上的最后一步遇到任何问题，请确保您的用户是 docker 组的一部分：</font></font></li>
</ul>
<div class="highlight highlight-source-shell notranslate position-relative overflow-auto" dir="auto"><pre>sudo usermod -aG docker <span class="pl-smi">$USER</span>
<span class="pl-c1">exit</span>
(restart shell by logging out and <span class="pl-k">then</span> back-in)
./webodm.sh start</pre><div class="zeroclipboard-container">
    <clipboard-copy aria-label="Copy" class="ClipboardButton btn btn-invisible js-clipboard-copy m-2 p-0 tooltipped-no-delay d-flex flex-justify-center flex-items-center" data-copy-feedback="Copied!" data-tooltip-direction="w" value="sudo usermod -aG docker $USER
exit
(restart shell by logging out and then back-in)
./webodm.sh start" tabindex="0" role="button">
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-copy js-clipboard-copy-icon">
    <path d="M0 6.75C0 5.784.784 5 1.75 5h1.5a.75.75 0 0 1 0 1.5h-1.5a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-1.5a.75.75 0 0 1 1.5 0v1.5A1.75 1.75 0 0 1 9.25 16h-7.5A1.75 1.75 0 0 1 0 14.25Z"></path><path d="M5 1.75C5 .784 5.784 0 6.75 0h7.5C15.216 0 16 .784 16 1.75v7.5A1.75 1.75 0 0 1 14.25 11h-7.5A1.75 1.75 0 0 1 5 9.25Zm1.75-.25a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-7.5a.25.25 0 0 0-.25-.25Z"></path>
</svg>
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-check js-clipboard-check-icon color-fg-success d-none">
    <path d="M13.78 4.22a.75.75 0 0 1 0 1.06l-7.25 7.25a.75.75 0 0 1-1.06 0L2.22 9.28a.751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018L6 10.94l6.72-6.72a.75.75 0 0 1 1.06 0Z"></path>
</svg>
    </clipboard-copy>
  </div></div>
<ul dir="auto">
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">打开 Web 浏览器</font></font><code>http://localhost:8000</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">（除非您在 Windows 上使用 Docker Toolbox，请参见下文）</font></font></li>
</ul>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Docker Toolbox 用户需要通过从 Docker 快速启动终端运行以下命令来查找其 docker 计算机的 IP：</font></font></p>
<div class="highlight highlight-source-shell notranslate position-relative overflow-auto" dir="auto"><pre>docker-machine ip
192.168.1.100 (your output will be different)</pre><div class="zeroclipboard-container">
    <clipboard-copy aria-label="Copy" class="ClipboardButton btn btn-invisible js-clipboard-copy m-2 p-0 tooltipped-no-delay d-flex flex-justify-center flex-items-center" data-copy-feedback="Copied!" data-tooltip-direction="w" value="docker-machine ip
192.168.1.100 (your output will be different)" tabindex="0" role="button">
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-copy js-clipboard-copy-icon">
    <path d="M0 6.75C0 5.784.784 5 1.75 5h1.5a.75.75 0 0 1 0 1.5h-1.5a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-1.5a.75.75 0 0 1 1.5 0v1.5A1.75 1.75 0 0 1 9.25 16h-7.5A1.75 1.75 0 0 1 0 14.25Z"></path><path d="M5 1.75C5 .784 5.784 0 6.75 0h7.5C15.216 0 16 .784 16 1.75v7.5A1.75 1.75 0 0 1 14.25 11h-7.5A1.75 1.75 0 0 1 5 9.25Zm1.75-.25a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-7.5a.25.25 0 0 0-.25-.25Z"></path>
</svg>
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-check js-clipboard-check-icon color-fg-success d-none">
    <path d="M13.78 4.22a.75.75 0 0 1 0 1.06l-7.25 7.25a.75.75 0 0 1-1.06 0L2.22 9.28a.751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018L6 10.94l6.72-6.72a.75.75 0 0 1 1.06 0Z"></path>
</svg>
    </clipboard-copy>
  </div></div>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">连接的地址将是：</font></font><code>http://192.168.1.100:8000</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">。</font></font></p>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">要停止 WebODM，请按 CTRL+C 或运行：</font></font></p>
<div class="snippet-clipboard-content notranslate position-relative overflow-auto"><pre class="notranslate"><code>./webodm.sh stop
</code></pre><div class="zeroclipboard-container">
    <clipboard-copy aria-label="Copy" class="ClipboardButton btn btn-invisible js-clipboard-copy m-2 p-0 tooltipped-no-delay d-flex flex-justify-center flex-items-center" data-copy-feedback="Copied!" data-tooltip-direction="w" value="./webodm.sh stop" tabindex="0" role="button">
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-copy js-clipboard-copy-icon">
    <path d="M0 6.75C0 5.784.784 5 1.75 5h1.5a.75.75 0 0 1 0 1.5h-1.5a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-1.5a.75.75 0 0 1 1.5 0v1.5A1.75 1.75 0 0 1 9.25 16h-7.5A1.75 1.75 0 0 1 0 14.25Z"></path><path d="M5 1.75C5 .784 5.784 0 6.75 0h7.5C15.216 0 16 .784 16 1.75v7.5A1.75 1.75 0 0 1 14.25 11h-7.5A1.75 1.75 0 0 1 5 9.25Zm1.75-.25a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-7.5a.25.25 0 0 0-.25-.25Z"></path>
</svg>
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-check js-clipboard-check-icon color-fg-success d-none">
    <path d="M13.78 4.22a.75.75 0 0 1 0 1.06l-7.25 7.25a.75.75 0 0 1-1.06 0L2.22 9.28a.751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018L6 10.94l6.72-6.72a.75.75 0 0 1 1.06 0Z"></path>
</svg>
    </clipboard-copy>
  </div></div>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">要将 WebODM 更新到最新版本，请使用：</font></font></p>
<div class="highlight highlight-source-shell notranslate position-relative overflow-auto" dir="auto"><pre>./webodm.sh update</pre><div class="zeroclipboard-container">
    <clipboard-copy aria-label="Copy" class="ClipboardButton btn btn-invisible js-clipboard-copy m-2 p-0 tooltipped-no-delay d-flex flex-justify-center flex-items-center" data-copy-feedback="Copied!" data-tooltip-direction="w" value="./webodm.sh update" tabindex="0" role="button">
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-copy js-clipboard-copy-icon">
    <path d="M0 6.75C0 5.784.784 5 1.75 5h1.5a.75.75 0 0 1 0 1.5h-1.5a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-1.5a.75.75 0 0 1 1.5 0v1.5A1.75 1.75 0 0 1 9.25 16h-7.5A1.75 1.75 0 0 1 0 14.25Z"></path><path d="M5 1.75C5 .784 5.784 0 6.75 0h7.5C15.216 0 16 .784 16 1.75v7.5A1.75 1.75 0 0 1 14.25 11h-7.5A1.75 1.75 0 0 1 5 9.25Zm1.75-.25a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-7.5a.25.25 0 0 0-.25-.25Z"></path>
</svg>
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-check js-clipboard-check-icon color-fg-success d-none">
    <path d="M13.78 4.22a.75.75 0 0 1 0 1.06l-7.25 7.25a.75.75 0 0 1-1.06 0L2.22 9.28a.751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018L6 10.94l6.72-6.72a.75.75 0 0 1 1.06 0Z"></path>
</svg>
    </clipboard-copy>
  </div></div>
<div class="markdown-heading" dir="auto"><h3 tabindex="-1" class="heading-element" dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">管理处理节点</font></font></h3><a id="user-content-manage-processing-nodes" class="anchor" aria-label="永久链接：管理处理节点" href="#manage-processing-nodes"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a></div>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">WebODM 可以链接到一个或多个使用</font></font><a href="https://github.com/OpenDroneMap/NodeODM/blob/master/docs/index.adoc"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">NodeODM API</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">的处理节点，例如</font></font><a href="https://github.com/OpenDroneMap/NodeODM"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">NodeODM</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">、</font></font><a href="https://github.com/OpenDroneMap/NodeMICMAC/"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">NodeMICMAC</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">或</font></font><a href="https://github.com/OpenDroneMap/ClusterODM"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">ClusterODM</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">。默认配置包括一个“node-odm-1”处理节点，它与 WebODM 在同一台计算机上运行，&ZeroWidthSpace;&ZeroWidthSpace;只是为了帮助您入门。随着您对 WebODM 越来越熟悉，您可能希望在单独的计算机上安装处理节点。</font></font></p>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">添加更多处理节点将允许您并行运行多个作业。</font></font></p>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">您还可以设置</font></font><a href="https://github.com/OpenDroneMap/ClusterODM"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">ClusterODM</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">节点，通过</font></font><a href="https://docs.opendronemap.org/large/?highlight=distributed#getting-started-with-distributed-split-merge" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">分布式拆分合并</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">在多台计算机上运行单个任务，并以更少的内存更快地处理数十万个图像。</font></font></p>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">如果您不需要默认的“node-odm-1”节点，只需</font></font><code>--default-nodes 0</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">在启动 WebODM 时传递标志即可：</font></font></p>
<p dir="auto"><code>./webodm.sh restart --default-nodes 0</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">。</font></font></p>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">然后从 Web 界面中手动删除“node-odm-1”节点即可。</font></font></p>
<div class="markdown-heading" dir="auto"><h3 tabindex="-1" class="heading-element" dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">启用麦克风</font></font></h3><a id="user-content-enable-micmac" class="anchor" aria-label="永久链接：启用 MicMac" href="#enable-micmac"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a></div>
<p dir="auto"><font style="vertical-align: inherit;"><a href="https://github.com/OpenDroneMap/NodeMICMAC/"><font style="vertical-align: inherit;">WebODM 可以通过NodeMICMAC</font></a><font style="vertical-align: inherit;">使用</font></font><a href="https://github.com/OpenDroneMap/micmac"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">MicMac</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">作为处理引擎</font><font style="vertical-align: inherit;">。要添加 MicMac，只需运行：</font></font><a href="https://github.com/OpenDroneMap/NodeMICMAC/"><font style="vertical-align: inherit;"></font></a><font style="vertical-align: inherit;"></font></p>
<p dir="auto"><code>./webodm.sh restart --with-micmac</code></p>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">这将在运行 WebODM 的同一台计算机上创建一个“node-micmac-1”处理节点。请注意，NodeMICMAC 正在积极开发中，目前处于实验阶段。如果您发现问题，请</font><font style="vertical-align: inherit;">在 NodeMICMAC 存储库上</font></font><a href="https://github.com/OpenDroneMap/NodeMICMAC/issues"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">报告。</font></font></a><font style="vertical-align: inherit;"></font></p>
<div class="markdown-heading" dir="auto"><h3 tabindex="-1" class="heading-element" dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">启用 SSL</font></font></h3><a id="user-content-enable-ssl" class="anchor" aria-label="永久链接：启用 SSL" href="#enable-ssl"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a></div>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">WebODM 能够通过</font></font><a href="https://letsencrypt.org/" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Let's Encrypt</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">自动请求和安装 SSL 证书，或者您也可以手动指定您自己的密钥/证书对。</font></font></p>
<ul dir="auto">
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">设置您的 DNS 记录（webodm.myorg.com --&gt; 服务器 IP）。</font></font></li>
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">确保端口 80 和 443 已打开。</font></font></li>
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">运行以下命令：</font></font></li>
</ul>
<div class="highlight highlight-source-shell notranslate position-relative overflow-auto" dir="auto"><pre>./webodm.sh restart --ssl --hostname webodm.myorg.com</pre><div class="zeroclipboard-container">
    <clipboard-copy aria-label="Copy" class="ClipboardButton btn btn-invisible js-clipboard-copy m-2 p-0 tooltipped-no-delay d-flex flex-justify-center flex-items-center" data-copy-feedback="Copied!" data-tooltip-direction="w" value="./webodm.sh restart --ssl --hostname webodm.myorg.com" tabindex="0" role="button">
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-copy js-clipboard-copy-icon">
    <path d="M0 6.75C0 5.784.784 5 1.75 5h1.5a.75.75 0 0 1 0 1.5h-1.5a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-1.5a.75.75 0 0 1 1.5 0v1.5A1.75 1.75 0 0 1 9.25 16h-7.5A1.75 1.75 0 0 1 0 14.25Z"></path><path d="M5 1.75C5 .784 5.784 0 6.75 0h7.5C15.216 0 16 .784 16 1.75v7.5A1.75 1.75 0 0 1 14.25 11h-7.5A1.75 1.75 0 0 1 5 9.25Zm1.75-.25a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-7.5a.25.25 0 0 0-.25-.25Z"></path>
</svg>
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-check js-clipboard-check-icon color-fg-success d-none">
    <path d="M13.78 4.22a.75.75 0 0 1 0 1.06l-7.25 7.25a.75.75 0 0 1-1.06 0L2.22 9.28a.751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018L6 10.94l6.72-6.72a.75.75 0 0 1 1.06 0Z"></path>
</svg>
    </clipboard-copy>
  </div></div>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">就是这样！证书将在需要时自动更新。</font></font></p>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">如果您想指定自己的密钥/证书对，只需将</font></font><code>--ssl-key</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">和</font></font><code>--ssl-cert</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">选项传递给</font></font><code>./webodm.sh</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">.请参阅</font></font><code>./webodm.sh --help</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">获取更多信息。</font></font></p>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">笔记！您不能将 IP 地址传递给主机名参数！您需要 DNS 记录设置。</font></font></p>
<div class="markdown-heading" dir="auto"><h3 tabindex="-1" class="heading-element" dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">我的文件存储在哪里？</font></font></h3><a id="user-content-where-are-my-files-stored" class="anchor" aria-label="永久链接：我的文件存储在哪里？" href="#where-are-my-files-stored"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a></div>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">使用 Docker 时，所有处理结果都存储在 docker 卷中，并且在主机文件系统上不可用。有两个特定的 docker 卷值得关注：</font></font></p>
<ol dir="auto">
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">媒体（称为 webodm_appmedia）：这是存储与项目和任务相关的所有文件的位置。</font></font></li>
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Postgres DB（称为 webodm_dbdata）：这是 Postgres 数据库用来存储其数据的内容。</font></font></li>
</ol>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">有关如何使用这两个卷以及在哪些容器中使用的更多信息，请参阅</font></font><a href="/OpenDroneMap/WebODM/blob/master/docker-compose.yml"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">docker-compose.yml</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">文件。</font></font></p>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">出于各种原因（例如易于备份/恢复），如果您想将文件存储在主机文件系统而不是 docker 卷上，则需要通过 和</font></font><code>--media-dir</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">/或</font></font><code>--db-dir</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">选项传递路径：</font></font></p>
<div class="highlight highlight-source-shell notranslate position-relative overflow-auto" dir="auto"><pre>./webodm.sh restart --media-dir /home/user/webodm_data --db-dir /home/user/webodm_db</pre><div class="zeroclipboard-container">
    <clipboard-copy aria-label="Copy" class="ClipboardButton btn btn-invisible js-clipboard-copy m-2 p-0 tooltipped-no-delay d-flex flex-justify-center flex-items-center" data-copy-feedback="Copied!" data-tooltip-direction="w" value="./webodm.sh restart --media-dir /home/user/webodm_data --db-dir /home/user/webodm_db" tabindex="0" role="button">
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-copy js-clipboard-copy-icon">
    <path d="M0 6.75C0 5.784.784 5 1.75 5h1.5a.75.75 0 0 1 0 1.5h-1.5a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-1.5a.75.75 0 0 1 1.5 0v1.5A1.75 1.75 0 0 1 9.25 16h-7.5A1.75 1.75 0 0 1 0 14.25Z"></path><path d="M5 1.75C5 .784 5.784 0 6.75 0h7.5C15.216 0 16 .784 16 1.75v7.5A1.75 1.75 0 0 1 14.25 11h-7.5A1.75 1.75 0 0 1 5 9.25Zm1.75-.25a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-7.5a.25.25 0 0 0-.25-.25Z"></path>
</svg>
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-check js-clipboard-check-icon color-fg-success d-none">
    <path d="M13.78 4.22a.75.75 0 0 1 0 1.06l-7.25 7.25a.75.75 0 0 1-1.06 0L2.22 9.28a.751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018L6 10.94l6.72-6.72a.75.75 0 0 1 1.06 0Z"></path>
</svg>
    </clipboard-copy>
  </div></div>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">请注意，更改后现有任务结果将不可用。有关迁移现有任务结果的信息</font><font style="vertical-align: inherit;">，请参阅</font><font style="vertical-align: inherit;">Docker 文档的</font></font><a href="https://docs.docker.com/engine/tutorials/dockervolumes/#backup-restore-or-migrate-data-volumes" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">迁移数据卷部分。</font></font></a><font style="vertical-align: inherit;"></font></p>
<div class="markdown-heading" dir="auto"><h3 tabindex="-1" class="heading-element" dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">常见故障排除</font></font></h3><a id="user-content-common-troubleshooting" class="anchor" aria-label="永久链接：常见故障排除" href="#common-troubleshooting"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a></div>
<table>
<thead>
<tr>
<th><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">症状</font></font></th>
<th><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">可能的解决方案</font></font></th>
</tr>
</thead>
<tbody>
<tr>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">内存不足</font></font></td>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">确保您的 Docker 环境分配了足够的 RAM：</font></font><a href="http://stackoverflow.com/a/39720010" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">MacOS 说明</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">、</font></font><a href="https://docs.docker.com/docker-for-windows/#advanced" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Windows 说明</font></font></a></td>
</tr>
<tr>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">启动 WebODM 时，您将获得：</font></font><code>'WaitNamedPipe','The system cannot find the file specified.'</code></td>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">1. 确保您已在 BIOS 中启用 VT-x 虚拟化。</font></font><br><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">2.尝试将Python版本降级到2.7</font></font></td>
</tr>
<tr>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">在 Windows 上，docker-compose 失败并显示</font></font><code>Failed to execute the script docker-compose</code></td>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">确保您已在 BIOS 中启用 VT-x 虚拟化</font></font></td>
</tr>
<tr>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">无法在 Windows 10 上使用 Microsoft Edge 访问 WebODM</font></font></td>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">尝试根据</font></font><a href="http://www.hanselman.com/blog/FixedMicrosoftEdgeCantSeeOrOpenVirtualBoxhostedLocalWebSites.aspx" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">这些说明调整您的互联网属性</font></font></a></td>
</tr>
<tr>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">出现</font></font><code>No space left on device</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">错误，但硬盘有足够的剩余空间</font></font></td>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">默认情况下，Windows 上的 Docker 只会为默认 docker-machine 分配 20GB 的空间。您需要增加该金额。请参阅</font></font><a href="http://support.divio.com/local-development/docker/managing-disk-space-in-your-docker-vm" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">此链接</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">和</font></font><a href="https://www.howtogeek.com/124622/how-to-enlarge-a-virtual-machines-disk-in-virtualbox-or-vmware/" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">此链接</font></font></a></td>
</tr>
<tr>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">无法通过 启动 WebODM </font></font><code>./webodm.sh start</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">，每次重试时错误消息都不同</font></font></td>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">您可能内存不足。确保您有足够的可用内存。推荐的最低容量应为 2GB，除非您知道自己在做什么</font></font></td>
</tr>
<tr>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">使用 Docker Toolbox (VirtualBox) 运行 WebODM 时，您无法从同一网络中的另一台计算机访问 WebODM。</font></font></td>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">以管理员身份运行，</font></font><code>cmd.exe</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">然后键入</font></font><code>"C:\Program Files\Oracle\VirtualBox\VBoxManage.exe" controlvm "default" natpf1 "rule-name,tcp,,8000,,8000"</code></td>
</tr>
<tr>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">在Windows上，WebODM诊断页面上显示的存储空间与Docker设置中实际设置的不一样。</font></font></td>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">在 Hyper-V 管理器中，右键单击“DockerDesktopVM”，转到“编辑磁盘”，然后选择扩展磁盘并将最大大小与 Docker 设置中指定的设置相匹配。进行更改后，重新启动 docker。</font></font></td>
</tr>
</tbody>
</table>
<div class="markdown-heading" dir="auto"><h4 tabindex="-1" class="heading-element" dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">闪电资产中缺少图像</font></font></h4><a id="user-content-images-missing-from-lightning-assets" class="anchor" aria-label="永久链接：闪电资产中缺少图像" href="#images-missing-from-lightning-assets"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a></div>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">当您使用 Lightning 处理任务时，您需要将所有资产下载到 WebODM 的本地实例。所有资产 zip</font></font><em><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">不</font></font></em><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">包含用于创建正射马赛克的图像。这意味着，尽管您可以在本地 WebODM 中可视化相机层，但当您单击特定相机图标时，将不会显示图像。</font></font></p>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">如果您将 WebODM 与 Docker 一起使用，则修复如下（说明适用于 MacOS 主机）：</font></font></p>
<ol dir="auto">
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">确保您有一个包含任务的所有图像且仅包含图像的目录；</font></font></li>
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">打开 Docker Desktop 并导航到容器。识别您的 WebODM 实例并导航到名为 的容器</font></font><code>worker</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">。您将需要容器 ID。这是容器名称下列出的哈希值。单击以使用旁边的复制图标复制容器 ID。</font></font></li>
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">打开终端并输入</font></font><code>docker cp &lt;sourcedirectory&gt;/. &lt;dockercontainerID&gt;:/webodm/app/media/project/&lt;projectID&gt;/task/&lt;taskID&gt;</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">.粘贴容器 ID 以替换标题为 的位置</font></font><code>&lt;dockercontainerID&gt;</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">。输入要替换的图像的完整目录路径</font></font><code>&lt;sourcedirectory&gt;</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">；</font></font></li>
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">返回 Docker Desktop 并导航到侧栏中的 Volumes。单击名为 的卷</font></font><code>webodm_appmedia</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">，单击</font></font><code>project</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">，确定正确的项目并单击它，单击</font></font><code>task</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">并确定正确的任务。</font></font></li>
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">从 Docker Desktop 将正确的</font></font><code>&lt;projectID&gt;</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">和替换</font></font><code>&lt;taskID&gt;</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">为终端中的命令；</font></font></li>
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">在终端中执行新编辑的命令。您将看到一系列进度消息，并且您的映像将被复制到 Docker；</font></font></li>
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">导航到本地 WebODM 实例中的项目；</font></font></li>
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">打开地图并打开相机层（左上角）；</font></font></li>
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">单击相机图标，将显示相关图像</font></font></li>
</ol>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">您还有其他问题吗？请</font></font><a href="https://github.com/OpenDroneMap/WebODM/issues/new"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">报告它们</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">，以便我们将它们包含在本文档中。</font></font></p>
<div class="markdown-heading" dir="auto"><h3 tabindex="-1" class="heading-element" dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">备份还原</font></font></h3><a id="user-content-backup-and-restore" class="anchor" aria-label="永久链接：备份和恢复" href="#backup-and-restore"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a></div>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">如果您想将 WebODM 移动到另一个系统，您只需传输 docker 卷（除非您将文件存储在文件系统上）。</font></font></p>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">在旧系统上：</font></font></p>
<div class="highlight highlight-source-shell notranslate position-relative overflow-auto" dir="auto"><pre>mkdir -v backup
docker run --rm --volume webodm_dbdata:/temp --volume <span class="pl-s"><span class="pl-pds">`</span>pwd<span class="pl-pds">`</span></span>/backup:/backup ubuntu tar cvf /backup/dbdata.tar /temp
docker run --rm --volume webodm_appmedia:/temp --volume <span class="pl-s"><span class="pl-pds">`</span>pwd<span class="pl-pds">`</span></span>/backup:/backup ubuntu tar cvf /backup/appmedia.tar /temp</pre><div class="zeroclipboard-container">
    <clipboard-copy aria-label="Copy" class="ClipboardButton btn btn-invisible js-clipboard-copy m-2 p-0 tooltipped-no-delay d-flex flex-justify-center flex-items-center" data-copy-feedback="Copied!" data-tooltip-direction="w" value="mkdir -v backup
docker run --rm --volume webodm_dbdata:/temp --volume `pwd`/backup:/backup ubuntu tar cvf /backup/dbdata.tar /temp
docker run --rm --volume webodm_appmedia:/temp --volume `pwd`/backup:/backup ubuntu tar cvf /backup/appmedia.tar /temp" tabindex="0" role="button">
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-copy js-clipboard-copy-icon">
    <path d="M0 6.75C0 5.784.784 5 1.75 5h1.5a.75.75 0 0 1 0 1.5h-1.5a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-1.5a.75.75 0 0 1 1.5 0v1.5A1.75 1.75 0 0 1 9.25 16h-7.5A1.75 1.75 0 0 1 0 14.25Z"></path><path d="M5 1.75C5 .784 5.784 0 6.75 0h7.5C15.216 0 16 .784 16 1.75v7.5A1.75 1.75 0 0 1 14.25 11h-7.5A1.75 1.75 0 0 1 5 9.25Zm1.75-.25a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-7.5a.25.25 0 0 0-.25-.25Z"></path>
</svg>
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-check js-clipboard-check-icon color-fg-success d-none">
    <path d="M13.78 4.22a.75.75 0 0 1 0 1.06l-7.25 7.25a.75.75 0 0 1-1.06 0L2.22 9.28a.751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018L6 10.94l6.72-6.72a.75.75 0 0 1 1.06 0Z"></path>
</svg>
    </clipboard-copy>
  </div></div>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">您的备份文件将存储在新创建的</font></font><code>backup</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">目录中。将目录</font><font style="vertical-align: inherit;">转移</font></font><code>backup</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">到新系统，然后在新系统上：</font></font></p>
<div class="highlight highlight-source-shell notranslate position-relative overflow-auto" dir="auto"><pre>ls backup <span class="pl-c"><span class="pl-c">#</span> --&gt; appmedia.tar  dbdata.tar</span>
./webodm.sh down <span class="pl-c"><span class="pl-c">#</span> Make sure WebODM is down</span>
docker run --rm --volume webodm_dbdata:/temp --volume <span class="pl-s"><span class="pl-pds">`</span>pwd<span class="pl-pds">`</span></span>/backup:/backup ubuntu bash -c <span class="pl-s"><span class="pl-pds">"</span>rm -fr /temp/* &amp;&amp; tar xvf /backup/dbdata.tar<span class="pl-pds">"</span></span>
docker run --rm --volume webodm_appmedia:/temp --volume <span class="pl-s"><span class="pl-pds">`</span>pwd<span class="pl-pds">`</span></span>/backup:/backup ubuntu bash -c <span class="pl-s"><span class="pl-pds">"</span>rm -fr /temp/* &amp;&amp; tar xvf /backup/appmedia.tar<span class="pl-pds">"</span></span>
./webodm.sh start</pre><div class="zeroclipboard-container">
    <clipboard-copy aria-label="Copy" class="ClipboardButton btn btn-invisible js-clipboard-copy m-2 p-0 tooltipped-no-delay d-flex flex-justify-center flex-items-center" data-copy-feedback="Copied!" data-tooltip-direction="w" value="ls backup # --> appmedia.tar  dbdata.tar
./webodm.sh down # Make sure WebODM is down
docker run --rm --volume webodm_dbdata:/temp --volume `pwd`/backup:/backup ubuntu bash -c &quot;rm -fr /temp/* &amp;&amp; tar xvf /backup/dbdata.tar&quot;
docker run --rm --volume webodm_appmedia:/temp --volume `pwd`/backup:/backup ubuntu bash -c &quot;rm -fr /temp/* &amp;&amp; tar xvf /backup/appmedia.tar&quot;
./webodm.sh start" tabindex="0" role="button">
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-copy js-clipboard-copy-icon">
    <path d="M0 6.75C0 5.784.784 5 1.75 5h1.5a.75.75 0 0 1 0 1.5h-1.5a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-1.5a.75.75 0 0 1 1.5 0v1.5A1.75 1.75 0 0 1 9.25 16h-7.5A1.75 1.75 0 0 1 0 14.25Z"></path><path d="M5 1.75C5 .784 5.784 0 6.75 0h7.5C15.216 0 16 .784 16 1.75v7.5A1.75 1.75 0 0 1 14.25 11h-7.5A1.75 1.75 0 0 1 5 9.25Zm1.75-.25a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-7.5a.25.25 0 0 0-.25-.25Z"></path>
</svg>
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-check js-clipboard-check-icon color-fg-success d-none">
    <path d="M13.78 4.22a.75.75 0 0 1 0 1.06l-7.25 7.25a.75.75 0 0 1-1.06 0L2.22 9.28a.751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018L6 10.94l6.72-6.72a.75.75 0 0 1 1.06 0Z"></path>
</svg>
    </clipboard-copy>
  </div></div>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">如果恢复 .tar 丢失或损坏，您可以进行</font></font><a href="/OpenDroneMap/WebODM/blob/master/contrib/Hard_Recovery_Guide.md"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">硬恢复</font></font></a></p>
<div class="markdown-heading" dir="auto"><h3 tabindex="-1" class="heading-element" dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">重设密码</font></font></h3><a id="user-content-reset-password" class="anchor" aria-label="永久链接：重置密码" href="#reset-password"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a></div>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">如果您忘记了首次登录 WebODM 时选择的密码，只需键入以下命令即可重置密码：</font></font></p>
<div class="highlight highlight-source-shell notranslate position-relative overflow-auto" dir="auto"><pre>./webodm.sh start <span class="pl-k">&amp;&amp;</span> ./webodm.sh resetadminpassword newpass</pre><div class="zeroclipboard-container">
    <clipboard-copy aria-label="Copy" class="ClipboardButton btn btn-invisible js-clipboard-copy m-2 p-0 tooltipped-no-delay d-flex flex-justify-center flex-items-center" data-copy-feedback="Copied!" data-tooltip-direction="w" value="./webodm.sh start &amp;&amp; ./webodm.sh resetadminpassword newpass" tabindex="0" role="button">
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-copy js-clipboard-copy-icon">
    <path d="M0 6.75C0 5.784.784 5 1.75 5h1.5a.75.75 0 0 1 0 1.5h-1.5a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-1.5a.75.75 0 0 1 1.5 0v1.5A1.75 1.75 0 0 1 9.25 16h-7.5A1.75 1.75 0 0 1 0 14.25Z"></path><path d="M5 1.75C5 .784 5.784 0 6.75 0h7.5C15.216 0 16 .784 16 1.75v7.5A1.75 1.75 0 0 1 14.25 11h-7.5A1.75 1.75 0 0 1 5 9.25Zm1.75-.25a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-7.5a.25.25 0 0 0-.25-.25Z"></path>
</svg>
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-check js-clipboard-check-icon color-fg-success d-none">
    <path d="M13.78 4.22a.75.75 0 0 1 0 1.06l-7.25 7.25a.75.75 0 0 1-1.06 0L2.22 9.28a.751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018L6 10.94l6.72-6.72a.75.75 0 0 1 1.06 0Z"></path>
</svg>
    </clipboard-copy>
  </div></div>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">密码将重置为</font></font><code>newpass</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">。该命令还会告诉您选择的用户名。</font></font></p>
<div class="markdown-heading" dir="auto"><h3 tabindex="-1" class="heading-element" dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">管理插件</font></font></h3><a id="user-content-manage-plugins" class="anchor" aria-label="永久链接：管理插件" href="#manage-plugins"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a></div>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">可以从用户界面启用和禁用插件。只需转到“管理”-“插件”。</font></font></p>
<div class="markdown-heading" dir="auto"><h3 tabindex="-1" class="heading-element" dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">更新</font></font></h3><a id="user-content-update" class="anchor" aria-label="永久链接：更新" href="#update"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a></div>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">如果您使用 docker，更新就像运行一样简单：</font></font></p>
<div class="highlight highlight-source-shell notranslate position-relative overflow-auto" dir="auto"><pre>./webodm.sh update</pre><div class="zeroclipboard-container">
    <clipboard-copy aria-label="Copy" class="ClipboardButton btn btn-invisible js-clipboard-copy m-2 p-0 tooltipped-no-delay d-flex flex-justify-center flex-items-center" data-copy-feedback="Copied!" data-tooltip-direction="w" value="./webodm.sh update" tabindex="0" role="button">
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-copy js-clipboard-copy-icon">
    <path d="M0 6.75C0 5.784.784 5 1.75 5h1.5a.75.75 0 0 1 0 1.5h-1.5a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-1.5a.75.75 0 0 1 1.5 0v1.5A1.75 1.75 0 0 1 9.25 16h-7.5A1.75 1.75 0 0 1 0 14.25Z"></path><path d="M5 1.75C5 .784 5.784 0 6.75 0h7.5C15.216 0 16 .784 16 1.75v7.5A1.75 1.75 0 0 1 14.25 11h-7.5A1.75 1.75 0 0 1 5 9.25Zm1.75-.25a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-7.5a.25.25 0 0 0-.25-.25Z"></path>
</svg>
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-check js-clipboard-check-icon color-fg-success d-none">
    <path d="M13.78 4.22a.75.75 0 0 1 0 1.06l-7.25 7.25a.75.75 0 0 1-1.06 0L2.22 9.28a.751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018L6 10.94l6.72-6.72a.75.75 0 0 1 1.06 0Z"></path>
</svg>
    </clipboard-copy>
  </div></div>
<p dir="auto"><font style="vertical-align: inherit;"></font><a href="#run-it-natively"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">如果您本地</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">运行 WebODM </font><font style="vertical-align: inherit;">，这些命令应该可以做到这一点：</font></font></p>
<div class="highlight highlight-source-shell notranslate position-relative overflow-auto" dir="auto"><pre><span class="pl-c1">cd</span> /webodm
sudo su odm <span class="pl-c"><span class="pl-c">#</span> Only in case you are running WebODM with a different user</span>
git pull origin master
<span class="pl-c1">source</span> python3-venv/bin/activate <span class="pl-c"><span class="pl-c">#</span> If you are running a virtualenv</span>
npm install
pip install -r requirements.txt
webpack --mode production
python manage.py collectstatic --noinput
python manage.py migrate</pre><div class="zeroclipboard-container">
    <clipboard-copy aria-label="Copy" class="ClipboardButton btn btn-invisible js-clipboard-copy m-2 p-0 tooltipped-no-delay d-flex flex-justify-center flex-items-center" data-copy-feedback="Copied!" data-tooltip-direction="w" value="cd /webodm
sudo su odm # Only in case you are running WebODM with a different user
git pull origin master
source python3-venv/bin/activate # If you are running a virtualenv
npm install
pip install -r requirements.txt
webpack --mode production
python manage.py collectstatic --noinput
python manage.py migrate" tabindex="0" role="button">
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-copy js-clipboard-copy-icon">
    <path d="M0 6.75C0 5.784.784 5 1.75 5h1.5a.75.75 0 0 1 0 1.5h-1.5a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-1.5a.75.75 0 0 1 1.5 0v1.5A1.75 1.75 0 0 1 9.25 16h-7.5A1.75 1.75 0 0 1 0 14.25Z"></path><path d="M5 1.75C5 .784 5.784 0 6.75 0h7.5C15.216 0 16 .784 16 1.75v7.5A1.75 1.75 0 0 1 14.25 11h-7.5A1.75 1.75 0 0 1 5 9.25Zm1.75-.25a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-7.5a.25.25 0 0 0-.25-.25Z"></path>
</svg>
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-check js-clipboard-check-icon color-fg-success d-none">
    <path d="M13.78 4.22a.75.75 0 0 1 0 1.06l-7.25 7.25a.75.75 0 0 1-1.06 0L2.22 9.28a.751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018L6 10.94l6.72-6.72a.75.75 0 0 1 1.06 0Z"></path>
</svg>
    </clipboard-copy>
  </div></div>
<div class="markdown-heading" dir="auto"><h2 tabindex="-1" class="heading-element" dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">推荐机器规格</font></font></h2><a id="user-content-recommended-machine-specs" class="anchor" aria-label="永久链接：推荐机器规格" href="#recommended-machine-specs"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a></div>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">要运行 WebODM（用户界面）的独立安装，包括处理组件 (NodeODM)，我们建议至少：</font></font></p>
<ul dir="auto">
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">100 GB 可用磁盘空间</font></font></li>
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">16 GB 内存</font></font></li>
</ul>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">不要期望使用这些规格处理超过数百个图像。要处理更大的数据集，请根据要处理的图像数量线性添加更多 RAM。具有更多内核的 CPU 将加快处理速度，但会增加内存使用量。还支持 GPU 加速。要使用兼容 CUDA 的显卡，请确保</font></font><code>--gpu</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">在启动 WebODM 时通过。在这种情况下，您需要安装 nvidia-docker，请参阅</font></font><a href="https://github.com/NVIDIA/nvidia-docker"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">https://github.com/NVIDIA/nvidia-docker</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">和</font></font><a href="https://docs.nvidia.com/datacenter/cloud-native/container-toolkit/install-guide.html#docker" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">https://docs.nvidia.com/datacenter/cloud-native/container-toolkit/install-guide。 html#docker</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">了解有关 docker/NVIDIA 设置的信息。</font></font></p>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">WebODM 在 Linux 上运行最佳，但在 Windows 和 Mac 上也能正常运行。如果您有技术倾向，您可以让 WebODM 在所有三个平台上本机运行。</font></font></p>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">WebODM 本身只是一个用户界面（见</font></font><a href="#odm-nodeodm-webodm-what"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">下文</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">），不需要很多资源。 WebODM 可以加载到只有 1 或 2 GB RAM 的机器上，并且无需 NodeODM 即可正常工作。然后，您可以使用处理服务（例如</font></font><a href="https://webodm.net" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">闪电网络）</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">或在单独的、功能更强大的机器上运行 NodeODM。</font></font></p>
<div class="markdown-heading" dir="auto"><h2 tabindex="-1" class="heading-element" dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">定制和扩展</font></font></h2><a id="user-content-customizing-and-extending" class="anchor" aria-label="永久链接：定制和扩展" href="#customizing-and-extending"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a></div>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">更改应用程序颜色、名称、徽标或添加自定义 CSS/HTML/Javascript 等小型自定义操作可以直接从 WebODM 中的自定义 -- 品牌/主题面板执行。无需分叉或更改代码。</font></font></p>
<p dir="auto"><font style="vertical-align: inherit;"></font><a href="https://github.com/OpenDroneMap/WebODM/tree/master/coreplugins"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">更高级的定制可以通过编写插件</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">来实现</font><font style="vertical-align: inherit;">。这是向 WebODM 添加新功能的首选方法，因为它比维护单独的分支需要更少的工作。该插件系统具有</font><font style="vertical-align: inherit;">可用于通知各种事件的</font><font style="vertical-align: inherit;">服务器端</font></font><a href="https://github.com/OpenDroneMap/WebODM/blob/master/app/plugins/signals.py"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">信号、ES6/React 构建系统、用于向 UI 添加元素的动态</font></font></a><font style="vertical-align: inherit;"></font><a href="https://github.com/OpenDroneMap/WebODM/tree/master/app/static/app/js/classes/plugins"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">客户端 API</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">、内置数据存储、异步任务运行程序，一个 GRASS 引擎，可以添加菜单项和功能来快速注入 CSS、Javascript 和 Django 视图。</font></font></p>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">对于插件，目前最好的文档来源是查看现&ZeroWidthSpace;&ZeroWidthSpace;有</font></font><a href="https://github.com/OpenDroneMap/WebODM/tree/master/coreplugins"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">代码</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">。如果您的插件的特定挂钩/入口点尚不存在，</font></font><a href="https://github.com/OpenDroneMap/WebODM/issues"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">请请求它</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">。我们正在添加挂钩和入口点。</font></font></p>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">要创建插件，只需将</font></font><code>plugins/test</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">插件复制到新目录（例如，</font></font><code>plugins/myplugin</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">），然后修改</font></font><code>manifest.json</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">，</font></font><code>plugin.py</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">并发出</font></font><code>./webodm.sh restart</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">.</font></font></p>
<div class="markdown-heading" dir="auto"><h2 tabindex="-1" class="heading-element" dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">API文档</font></font></h2><a id="user-content-api-docs" class="anchor" aria-label="永久链接：API 文档" href="#api-docs"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a></div>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">请参阅</font></font><a href="http://docs.webodm.org" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">API 文档页面</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">。</font></font></p>
<div class="markdown-heading" dir="auto"><h2 tabindex="-1" class="heading-element" dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">路线图</font></font></h2><a id="user-content-roadmap" class="anchor" aria-label="永久链接：路线图" href="#roadmap"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a></div>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">我们遵循自下而上的方法来决定向 WebODM 添加哪些新功能。用户反馈指导我们的决策过程，我们通过</font></font><a href="https://github.com/OpenDroneMap/WebODM/issues?q=is%3Aopen+is%3Aissue+label%3Aimprovements"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">改进请求</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">收集此类反馈。</font></font></p>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">没有看到您想要的功能？</font></font><a href="https://github.com/OpenDroneMap/WebODM/issues"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">提出功能请求</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">或</font></font><a href="/OpenDroneMap/WebODM/blob/master/CONTRIBUTING.md"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">帮助我们构建它</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">。</font></font></p>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">有时我们也会优先考虑已获得财政支持的工作。如果您的组织有能力在经济上支持特定功能的开发，</font></font><a href="https://community.opendronemap.org" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">请与我们联系</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">，我们将帮助您实现这一目标。</font></font></p>
<div class="markdown-heading" dir="auto"><h2 tabindex="-1" class="heading-element" dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">寻求帮助</font></font></h2><a id="user-content-getting-help" class="anchor" aria-label="永久链接：获取帮助" href="#getting-help"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a></div>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">我们有多种沟通渠道供人们提出问题并参与社区：</font></font></p>
<ul dir="auto">
<li><a href="http://community.opendronemap.org/c/webodm" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">OpenDroneMap 社区论坛</font></font></a></li>
<li><a href="https://github.com/OpenDroneMap/WebODM/issues"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">报告问题</font></font></a></li>
</ul>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">我们还有</font></font><a href="https://gitter.im/OpenDroneMap/web-development" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Gitter Chat</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">，但首选的沟通方式是通过</font></font><a href="http://community.opendronemap.org/c/webodm" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">OpenDroneMap 社区论坛</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">。</font></font></p>
<div class="markdown-heading" dir="auto"><h2 tabindex="-1" class="heading-element" dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">支持项目</font></font></h2><a id="user-content-support-the-project" class="anchor" aria-label="永久链接：支持该项目" href="#support-the-project"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a></div>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">有多种方式可以为项目做出贡献：</font></font></p>
<ul dir="auto">
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">帮助我们测试新功能和现有功能并报告</font></font><a href="https://www.github.com/OpenDroneMap/WebODM/issues"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">错误</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">和</font></font><a href="http://community.opendronemap.org/c/webodm" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">反馈</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">。</font></font></li>
<li><a href="http://community.opendronemap.org/c/datasets" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">分享</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">您的航空数据集。</font></font></li>
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">帮助回答社区</font></font><a href="http://community.opendronemap.org/c/webodm" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">论坛</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">和</font></font><a href="https://gitter.im/OpenDroneMap/web-development" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">聊天</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">中的问题。</font></font></li>
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">⭐️ 我们在 GitHub 上。</font></font></li>
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">帮助我们将 WebODM</font></font><a href="#translations"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">翻译</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">成您的语言。</font></font></li>
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">帮助我们对</font></font><a href="https://github.com/OpenDroneMap/ODMSemantic3D"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">点云数据集</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">进行分类。</font></font></li>
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">在社交媒体上传播有关 WebODM 和 OpenDroneMap 的信息。</font></font></li>
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">虽然我们不接受捐赠，但您可以购买</font></font><a href="https://webodm.org/download#installer" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">安装程序</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">、</font></font><a href="https://odmbook.com/" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">书籍</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">或</font></font><a href="https://github.com/users/pierotofy/sponsorship"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">赞助商套餐</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">。</font></font></li>
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">您可以</font></font><a href="https://fund.webodm.org" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">承诺提供资金</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">来构建新功能和修复错误。</font></font></li>
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">成为贡献者🤘</font></font></li>
</ul>
<div class="markdown-heading" dir="auto"><h2 tabindex="-1" class="heading-element" dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">翻译</font></font></h2><a id="user-content-translations" class="anchor" aria-label="永久链接：翻译" href="#translations"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a></div>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">将 WebODM 翻译成不同的语言非常容易！</font></font></p>
<ul dir="auto">
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">访问</font></font><a href="https://hosted.weblate.org/engage/webodm/" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">https://hosted.weblate.org/engage/webodm/</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">并注册一个帐户（免费）</font></font></li>
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">选择要翻译的语言，或</font></font><a href="https://hosted.weblate.org/new-lang/webodm/webodm/" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">开始新的翻译</font></font></a></li>
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">开始翻译！就是这么简单。</font></font></li>
</ul>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">如果您想预览翻译工作，请在开发者模式下启动 WebODM：</font></font></p>
<div class="snippet-clipboard-content notranslate position-relative overflow-auto"><pre class="notranslate"><code>./webodm.sh restart --dev
</code></pre><div class="zeroclipboard-container">
    <clipboard-copy aria-label="Copy" class="ClipboardButton btn btn-invisible js-clipboard-copy m-2 p-0 tooltipped-no-delay d-flex flex-justify-center flex-items-center" data-copy-feedback="Copied!" data-tooltip-direction="w" value="./webodm.sh restart --dev" tabindex="0" role="button">
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-copy js-clipboard-copy-icon">
    <path d="M0 6.75C0 5.784.784 5 1.75 5h1.5a.75.75 0 0 1 0 1.5h-1.5a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-1.5a.75.75 0 0 1 1.5 0v1.5A1.75 1.75 0 0 1 9.25 16h-7.5A1.75 1.75 0 0 1 0 14.25Z"></path><path d="M5 1.75C5 .784 5.784 0 6.75 0h7.5C15.216 0 16 .784 16 1.75v7.5A1.75 1.75 0 0 1 14.25 11h-7.5A1.75 1.75 0 0 1 5 9.25Zm1.75-.25a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-7.5a.25.25 0 0 0-.25-.25Z"></path>
</svg>
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-check js-clipboard-check-icon color-fg-success d-none">
    <path d="M13.78 4.22a.75.75 0 0 1 0 1.06l-7.25 7.25a.75.75 0 0 1-1.06 0L2.22 9.28a.751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018L6 10.94l6.72-6.72a.75.75 0 0 1 1.06 0Z"></path>
</svg>
    </clipboard-copy>
  </div></div>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">然后编辑</font></font><a href="https://github.com/OpenDroneMap/WebODM/blob/master/LOCALES"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">LOCALES</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">文件以包含您的翻译区域设置代码。最后，</font></font><code>Developer Tools</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">从 WebODM 的仪表板</font><font style="vertical-align: inherit;">访问面板并按下</font></font><code>Download and Replace Translation Files</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">按钮：</font></font></p>
<p dir="auto"><a target="_blank" rel="noopener noreferrer nofollow" href="https://user-images.githubusercontent.com/1951843/102927263-a294a100-4464-11eb-956e-888b73dc5b94.png"><img src="https://user-images.githubusercontent.com/1951843/102927263-a294a100-4464-11eb-956e-888b73dc5b94.png" alt="图像" style="max-width: 100%;"></a></p>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">将下载 weblate.org 上的最新翻译文件并将其应用于 WebODM 的安装。</font></font></p>
<div class="markdown-heading" dir="auto"><h2 tabindex="-1" class="heading-element" dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">成为贡献者</font></font></h2><a id="user-content-become-a-contributor" class="anchor" aria-label="永久链接：成为贡献者" href="#become-a-contributor"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a></div>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">最简单的开始方法是查看我们的</font></font><a href="https://github.com/OpenDroneMap/WebODM/labels/help%20wanted"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">未决问题</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">列表并选择一个。您还可以根据您使用 WebODM 的经验修复/改进一些全新的东西。所有想法都会得到考虑，欢迎各种技能水平的人做出贡献。</font></font></p>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">您不一定需要成为开发人员才能成为贡献者。我们可以利用您的帮助来编写更好的文档并改进用户界面文本和视觉效果。</font></font></p>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">如果您知道如何编码，我们主要使用 Python (Django)、Javascript (React)、HTML 和 SCSS。</font><font style="vertical-align: inherit;">有关更多信息，</font><font style="vertical-align: inherit;">请参阅</font></font><a href="http://docs.webodm.org/#development-quickstart" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">开发快速入门</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">和</font></font><a href="/OpenDroneMap/WebODM/blob/master/CONTRIBUTING.md"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">贡献文档。</font></font></a><font style="vertical-align: inherit;"></font></p>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">要做出贡献，您需要打开拉取请求（</font></font><a href="https://github.com/Roshanjossey/first-contributions#fork-this-repository"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">以下是操作方法</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">）。要对 WebODM 进行更改，请克隆存储库并运行</font></font><code>./webodm.sh start --dev</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">.</font></font></p>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">如果您有疑问，请访问我们的论坛</font></font><a href="http://community.opendronemap.org/c/webodm" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">，</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">我们将很乐意帮助您完成首次贡献。</font></font></p>
<div class="markdown-heading" dir="auto"><h2 tabindex="-1" class="heading-element" dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">架构概述</font></font></h2><a id="user-content-architecture-overview" class="anchor" aria-label="永久链接：架构概述" href="#architecture-overview"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a></div>
<p dir="auto"><font style="vertical-align: inherit;"></font><a href="https://github.com/OpenDroneMap/"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">OpenDroneMap 项目</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">由</font><font style="vertical-align: inherit;">多个组件组成。</font></font></p>
<ul dir="auto">
<li><a href="https://github.com/OpenDroneMap/ODM"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">ODM</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">是一个处理航拍图像的命令行工具包。熟悉命令行的用户可能可以单独使用此组件。</font></font></li>
<li><a href="https://github.com/OpenDroneMap/NodeODM"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">NodeODM是直接构建在</font></font></a><font style="vertical-align: inherit;"></font><a href="https://github.com/OpenDroneMap/ODM"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">ODM</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">之上的轻量级接口和API（应用程序接口）</font><font style="vertical-align: inherit;">。不熟悉命令行的用户可以使用此界面来处理航拍图像，开发人员可以使用 API 来构建应用程序。不提供用户认证、地图显示等功能。</font></font></li>
<li><a href="https://github.com/OpenDroneMap/WebODM"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">WebODM</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">添加了更多功能，例如用户身份验证、地图显示、3D 显示、更高级别的 API 以及编排多个处理节点（并行运行作业）的能力。处理节点只是运行</font></font><a href="https://github.com/OpenDroneMap/NodeODM"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">NodeODM 的</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">服务器。</font></font></li>
</ul>
<p dir="auto"><a target="_blank" rel="noopener noreferrer nofollow" href="https://cloud.githubusercontent.com/assets/1951843/25567386/5aeec7aa-2dba-11e7-9169-aca97b70db79.png"><img src="https://cloud.githubusercontent.com/assets/1951843/25567386/5aeec7aa-2dba-11e7-9169-aca97b70db79.png" alt="网络博德姆" style="max-width: 100%;"></a></p>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">WebODM 在构建时考虑了可扩展性和性能。虽然默认设置将所有数据库和应用程序放置在同一台计算机上，但用户可以分离其组件以提高性能（例如，将 Celery 工作程序放置在单独的计算机上以运行后台任务）。</font></font></p>
<p dir="auto"><a target="_blank" rel="noopener noreferrer nofollow" href="https://user-images.githubusercontent.com/1951843/36916884-3a269a7a-1e23-11e8-997a-a57cd6ca7950.png"><img src="https://user-images.githubusercontent.com/1951843/36916884-3a269a7a-1e23-11e8-997a-a57cd6ca7950.png" alt="建筑学" style="max-width: 100%;"></a></p>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">有几点需要注意：</font></font></p>
<ul dir="auto">
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">我们使用 Celery 工作线程执行后台任务，例如调整图像大小和处理任务结果，但我们使用临时调度机制与 NodeODM（处理正射影像、3D 模型等）进行通信。选择使用两个独立的系统进行任务调度是因为临时机制为我们提供了某些操作的灵活性（捕获任务输出、持久数据和中途重新启动任务的能力、通过 REST 调用进行通信等） 。</font></font></li>
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">如果加载在多台机器上，Celery 工作人员都应该</font></font><code>app/media</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">与 Django 应用程序共享其目录（通过网络共享）。您可以通过以下方式管理员工</font></font><code>./worker.sh</code></li>
</ul>
<div class="markdown-heading" dir="auto"><h2 tabindex="-1" class="heading-element" dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">将 docker 版本作为 Linux 服务运行</font></font></h2><a id="user-content-run-the-docker-version-as-a-linux-service" class="anchor" aria-label="永久链接：将 docker 版本作为 Linux 服务运行" href="#run-the-docker-version-as-a-linux-service"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a></div>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">如果您希望运行具有自动启动/监控/停止等功能的 docker 版本，作为 systemd 风格的 Linux 服务，则系统d 单元文件包含在存储库的服务文件夹中。</font></font></p>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">这应该适用于任何能够运行 WebODM 并使用基于 SystemD 的服务守护进程的 Linux 操作系统（例如 Ubuntu 16.04 服务器）。</font></font></p>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">仅在 Ubuntu 16.04 服务器和 Red Hat Enterprise Linux 9 上进行了测试。</font></font></p>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">需要满足以下先决条件：</font></font></p>
<ul dir="auto">
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">需要 odm 用户</font></font></li>
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">需要通过系统安装 docker (ubuntu: </font></font><code>sudo apt-get install docker.io</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">)</font></font></li>
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">需要安装“屏幕”包</font></font></li>
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">需要 docker 组的 odm 用户成员</font></font></li>
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">所需的 WebODM 目录签出/克隆到 /opt/WebODM</font></font></li>
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">要求 /opt/WebODM 由 odm:odm 递归拥有</font></font></li>
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">需要在 /opt/WebODM/python3-venv 处使用 Python 3 环境</font></font></li>
</ul>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">如果满足所有先决条件，并且存储库已检出/克隆到 /opt/WebODM 文件夹，则您可以使用以下步骤来启用和管理服务：</font></font></p>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">首先，安装服务，并让服务从现在开始开机运行：</font></font></p>
<div class="highlight highlight-source-shell notranslate position-relative overflow-auto" dir="auto"><pre>sudo systemctl <span class="pl-c1">enable</span> /opt/WebODM/service/webodm-docker.service</pre><div class="zeroclipboard-container">
    <clipboard-copy aria-label="Copy" class="ClipboardButton btn btn-invisible js-clipboard-copy m-2 p-0 tooltipped-no-delay d-flex flex-justify-center flex-items-center" data-copy-feedback="Copied!" data-tooltip-direction="w" value="sudo systemctl enable /opt/WebODM/service/webodm-docker.service" tabindex="0" role="button">
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-copy js-clipboard-copy-icon">
    <path d="M0 6.75C0 5.784.784 5 1.75 5h1.5a.75.75 0 0 1 0 1.5h-1.5a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-1.5a.75.75 0 0 1 1.5 0v1.5A1.75 1.75 0 0 1 9.25 16h-7.5A1.75 1.75 0 0 1 0 14.25Z"></path><path d="M5 1.75C5 .784 5.784 0 6.75 0h7.5C15.216 0 16 .784 16 1.75v7.5A1.75 1.75 0 0 1 14.25 11h-7.5A1.75 1.75 0 0 1 5 9.25Zm1.75-.25a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-7.5a.25.25 0 0 0-.25-.25Z"></path>
</svg>
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-check js-clipboard-check-icon color-fg-success d-none">
    <path d="M13.78 4.22a.75.75 0 0 1 0 1.06l-7.25 7.25a.75.75 0 0 1-1.06 0L2.22 9.28a.751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018L6 10.94l6.72-6.72a.75.75 0 0 1 1.06 0Z"></path>
</svg>
    </clipboard-copy>
  </div></div>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">手动启动/停止服务：</font></font></p>
<div class="highlight highlight-source-shell notranslate position-relative overflow-auto" dir="auto"><pre>sudo systemctl stop webodm-docker
sudo systemctl start webodm-docker</pre><div class="zeroclipboard-container">
    <clipboard-copy aria-label="Copy" class="ClipboardButton btn btn-invisible js-clipboard-copy m-2 p-0 tooltipped-no-delay d-flex flex-justify-center flex-items-center" data-copy-feedback="Copied!" data-tooltip-direction="w" value="sudo systemctl stop webodm-docker
sudo systemctl start webodm-docker" tabindex="0" role="button">
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-copy js-clipboard-copy-icon">
    <path d="M0 6.75C0 5.784.784 5 1.75 5h1.5a.75.75 0 0 1 0 1.5h-1.5a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-1.5a.75.75 0 0 1 1.5 0v1.5A1.75 1.75 0 0 1 9.25 16h-7.5A1.75 1.75 0 0 1 0 14.25Z"></path><path d="M5 1.75C5 .784 5.784 0 6.75 0h7.5C15.216 0 16 .784 16 1.75v7.5A1.75 1.75 0 0 1 14.25 11h-7.5A1.75 1.75 0 0 1 5 9.25Zm1.75-.25a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-7.5a.25.25 0 0 0-.25-.25Z"></path>
</svg>
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-check js-clipboard-check-icon color-fg-success d-none">
    <path d="M13.78 4.22a.75.75 0 0 1 0 1.06l-7.25 7.25a.75.75 0 0 1-1.06 0L2.22 9.28a.751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018L6 10.94l6.72-6.72a.75.75 0 0 1 1.06 0Z"></path>
</svg>
    </clipboard-copy>
  </div></div>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">手动检查服务状态：</font></font></p>
<div class="highlight highlight-source-shell notranslate position-relative overflow-auto" dir="auto"><pre>sudo systemctl status webodm-docker</pre><div class="zeroclipboard-container">
    <clipboard-copy aria-label="Copy" class="ClipboardButton btn btn-invisible js-clipboard-copy m-2 p-0 tooltipped-no-delay d-flex flex-justify-center flex-items-center" data-copy-feedback="Copied!" data-tooltip-direction="w" value="sudo systemctl status webodm-docker" tabindex="0" role="button">
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-copy js-clipboard-copy-icon">
    <path d="M0 6.75C0 5.784.784 5 1.75 5h1.5a.75.75 0 0 1 0 1.5h-1.5a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-1.5a.75.75 0 0 1 1.5 0v1.5A1.75 1.75 0 0 1 9.25 16h-7.5A1.75 1.75 0 0 1 0 14.25Z"></path><path d="M5 1.75C5 .784 5.784 0 6.75 0h7.5C15.216 0 16 .784 16 1.75v7.5A1.75 1.75 0 0 1 14.25 11h-7.5A1.75 1.75 0 0 1 5 9.25Zm1.75-.25a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-7.5a.25.25 0 0 0-.25-.25Z"></path>
</svg>
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-check js-clipboard-check-icon color-fg-success d-none">
    <path d="M13.78 4.22a.75.75 0 0 1 0 1.06l-7.25 7.25a.75.75 0 0 1-1.06 0L2.22 9.28a.751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018L6 10.94l6.72-6.72a.75.75 0 0 1 1.06 0Z"></path>
</svg>
    </clipboard-copy>
  </div></div>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">对于喜欢冒险的人来说，可以将存储库放在您喜欢的任何位置，方法是在启用反映存储库位置的服务之前编辑 ./WebODM/service/webodm-docker.service 文件，并将 systemctl enable 命令修改为该目录。</font></font></p>
<div class="markdown-heading" dir="auto"><h2 tabindex="-1" class="heading-element" dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">本地运行</font></font></h2><a id="user-content-run-it-natively" class="anchor" aria-label="永久链接：本地运行" href="#run-it-natively"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a></div>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">WebODM 可以在 Windows、MacOS 和 Linux 上本机运行。我们不建议原生运行 WebODM（使用 docker 更容易），但这是可能的。</font></font></p>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Ubuntu 16.04 LTS 用户可以参考</font></font><a href="/OpenDroneMap/WebODM/blob/master/contrib/ubuntu_1604_install.sh"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">此社区脚本</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">在新机器上原生安装 WebODM。</font></font></p>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">要运行 WebODM，您需要安装：</font></font></p>
<ul dir="auto">
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">PostgreSQL (&gt;= 9.5)</font></font></li>
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">后地理信息系统2.3</font></font></li>
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Python 3.6</font></font></li>
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">GDAL (&gt;= 3)</font></font></li>
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Node.js (&gt;= 6.0)</font></font></li>
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Nginx (Linux/MacOS) - 或 - Apache + mod_wsgi 或 Waitress (Windows)</font></font></li>
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">雷迪斯 (&gt;= 2.6)</font></font></li>
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">草地 GIS (&gt;= 7.8)</font></font></li>
</ul>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">在 Linux 上，请确保您拥有：</font></font></p>
<div class="highlight highlight-source-shell notranslate position-relative overflow-auto" dir="auto"><pre>apt-get install binutils libproj-dev gdal-bin nginx</pre><div class="zeroclipboard-container">
    <clipboard-copy aria-label="Copy" class="ClipboardButton btn btn-invisible js-clipboard-copy m-2 p-0 tooltipped-no-delay d-flex flex-justify-center flex-items-center" data-copy-feedback="Copied!" data-tooltip-direction="w" value="apt-get install binutils libproj-dev gdal-bin nginx" tabindex="0" role="button">
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-copy js-clipboard-copy-icon">
    <path d="M0 6.75C0 5.784.784 5 1.75 5h1.5a.75.75 0 0 1 0 1.5h-1.5a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-1.5a.75.75 0 0 1 1.5 0v1.5A1.75 1.75 0 0 1 9.25 16h-7.5A1.75 1.75 0 0 1 0 14.25Z"></path><path d="M5 1.75C5 .784 5.784 0 6.75 0h7.5C15.216 0 16 .784 16 1.75v7.5A1.75 1.75 0 0 1 14.25 11h-7.5A1.75 1.75 0 0 1 5 9.25Zm1.75-.25a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-7.5a.25.25 0 0 0-.25-.25Z"></path>
</svg>
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-check js-clipboard-check-icon color-fg-success d-none">
    <path d="M13.78 4.22a.75.75 0 0 1 0 1.06l-7.25 7.25a.75.75 0 0 1-1.06 0L2.22 9.28a.751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018L6 10.94l6.72-6.72a.75.75 0 0 1 1.06 0Z"></path>
</svg>
    </clipboard-copy>
  </div></div>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">在 Windows 上，使用</font></font><a href="https://trac.osgeo.org/osgeo4w/" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">OSGeo4W</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">安装程序来安装 GDAL。 MacOS 用户可以使用：</font></font></p>
<div class="snippet-clipboard-content notranslate position-relative overflow-auto"><pre class="notranslate"><code>brew install postgres postgis
</code></pre><div class="zeroclipboard-container">
    <clipboard-copy aria-label="Copy" class="ClipboardButton btn btn-invisible js-clipboard-copy m-2 p-0 tooltipped-no-delay d-flex flex-justify-center flex-items-center" data-copy-feedback="Copied!" data-tooltip-direction="w" value="brew install postgres postgis" tabindex="0" role="button">
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-copy js-clipboard-copy-icon">
    <path d="M0 6.75C0 5.784.784 5 1.75 5h1.5a.75.75 0 0 1 0 1.5h-1.5a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-1.5a.75.75 0 0 1 1.5 0v1.5A1.75 1.75 0 0 1 9.25 16h-7.5A1.75 1.75 0 0 1 0 14.25Z"></path><path d="M5 1.75C5 .784 5.784 0 6.75 0h7.5C15.216 0 16 .784 16 1.75v7.5A1.75 1.75 0 0 1 14.25 11h-7.5A1.75 1.75 0 0 1 5 9.25Zm1.75-.25a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-7.5a.25.25 0 0 0-.25-.25Z"></path>
</svg>
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-check js-clipboard-check-icon color-fg-success d-none">
    <path d="M13.78 4.22a.75.75 0 0 1 0 1.06l-7.25 7.25a.75.75 0 0 1-1.06 0L2.22 9.28a.751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018L6 10.94l6.72-6.72a.75.75 0 0 1 1.06 0Z"></path>
</svg>
    </clipboard-copy>
  </div></div>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">那么这些步骤应该足以让您启动并运行：</font></font></p>
<div class="highlight highlight-source-shell notranslate position-relative overflow-auto" dir="auto"><pre>git clone --depth 1 https://github.com/OpenDroneMap/WebODM</pre><div class="zeroclipboard-container">
    <clipboard-copy aria-label="Copy" class="ClipboardButton btn btn-invisible js-clipboard-copy m-2 p-0 tooltipped-no-delay d-flex flex-justify-center flex-items-center" data-copy-feedback="Copied!" data-tooltip-direction="w" value="git clone --depth 1 https://github.com/OpenDroneMap/WebODM" tabindex="0" role="button">
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-copy js-clipboard-copy-icon">
    <path d="M0 6.75C0 5.784.784 5 1.75 5h1.5a.75.75 0 0 1 0 1.5h-1.5a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-1.5a.75.75 0 0 1 1.5 0v1.5A1.75 1.75 0 0 1 9.25 16h-7.5A1.75 1.75 0 0 1 0 14.25Z"></path><path d="M5 1.75C5 .784 5.784 0 6.75 0h7.5C15.216 0 16 .784 16 1.75v7.5A1.75 1.75 0 0 1 14.25 11h-7.5A1.75 1.75 0 0 1 5 9.25Zm1.75-.25a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-7.5a.25.25 0 0 0-.25-.25Z"></path>
</svg>
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-check js-clipboard-check-icon color-fg-success d-none">
    <path d="M13.78 4.22a.75.75 0 0 1 0 1.06l-7.25 7.25a.75.75 0 0 1-1.06 0L2.22 9.28a.751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018L6 10.94l6.72-6.72a.75.75 0 0 1 1.06 0Z"></path>
</svg>
    </clipboard-copy>
  </div></div>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">创建一个</font></font><code>WebODM/webodm/local_settings.py</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">包含数据库设置的文件：</font></font></p>
<div class="highlight highlight-source-python notranslate position-relative overflow-auto" dir="auto"><pre><span class="pl-v">DATABASES</span> <span class="pl-c1">=</span> {
    <span class="pl-s">'default'</span>: {
        <span class="pl-s">'ENGINE'</span>: <span class="pl-s">'django.contrib.gis.db.backends.postgis'</span>,
        <span class="pl-s">'NAME'</span>: <span class="pl-s">'webodm_dev'</span>,
        <span class="pl-s">'USER'</span>: <span class="pl-s">'postgres'</span>,
        <span class="pl-s">'PASSWORD'</span>: <span class="pl-s">'postgres'</span>,
        <span class="pl-s">'HOST'</span>: <span class="pl-s">'localhost'</span>,
        <span class="pl-s">'PORT'</span>: <span class="pl-s">'5432'</span>,
    }
}</pre><div class="zeroclipboard-container">
    <clipboard-copy aria-label="Copy" class="ClipboardButton btn btn-invisible js-clipboard-copy m-2 p-0 tooltipped-no-delay d-flex flex-justify-center flex-items-center" data-copy-feedback="Copied!" data-tooltip-direction="w" value="DATABASES = {
    'default': {
        'ENGINE': 'django.contrib.gis.db.backends.postgis',
        'NAME': 'webodm_dev',
        'USER': 'postgres',
        'PASSWORD': 'postgres',
        'HOST': 'localhost',
        'PORT': '5432',
    }
}" tabindex="0" role="button">
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-copy js-clipboard-copy-icon">
    <path d="M0 6.75C0 5.784.784 5 1.75 5h1.5a.75.75 0 0 1 0 1.5h-1.5a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-1.5a.75.75 0 0 1 1.5 0v1.5A1.75 1.75 0 0 1 9.25 16h-7.5A1.75 1.75 0 0 1 0 14.25Z"></path><path d="M5 1.75C5 .784 5.784 0 6.75 0h7.5C15.216 0 16 .784 16 1.75v7.5A1.75 1.75 0 0 1 14.25 11h-7.5A1.75 1.75 0 0 1 5 9.25Zm1.75-.25a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-7.5a.25.25 0 0 0-.25-.25Z"></path>
</svg>
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-check js-clipboard-check-icon color-fg-success d-none">
    <path d="M13.78 4.22a.75.75 0 0 1 0 1.06l-7.25 7.25a.75.75 0 0 1-1.06 0L2.22 9.28a.751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018L6 10.94l6.72-6.72a.75.75 0 0 1 1.06 0Z"></path>
</svg>
    </clipboard-copy>
  </div></div>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">从 psql 或</font></font><a href="https://www.pgadmin.org" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">pgadmin</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">，连接到 PostgreSQL，创建一个新数据库（将其命名</font></font><code>webodm_dev</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">），连接到它并设置</font></font><a href="http://postgis.net/docs/manual-2.2/postgis_enable_outdb_rasters.html" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">postgis.enable_outdb_rasters</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">和</font></font><a href="http://postgis.net/docs/postgis_gdal_enabled_drivers.html" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">postgis.gdal_enabled_drivers</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">设置：</font></font></p>
<div class="highlight highlight-source-sql notranslate position-relative overflow-auto" dir="auto"><pre>ALTER SYSTEM <span class="pl-k">SET</span> <span class="pl-c1">postgis</span>.<span class="pl-c1">enable_outdb_rasters</span> TO True;
ALTER SYSTEM <span class="pl-k">SET</span> <span class="pl-c1">postgis</span>.<span class="pl-c1">gdal_enabled_drivers</span> TO <span class="pl-s"><span class="pl-pds">'</span>GTiff<span class="pl-pds">'</span></span>;</pre><div class="zeroclipboard-container">
    <clipboard-copy aria-label="Copy" class="ClipboardButton btn btn-invisible js-clipboard-copy m-2 p-0 tooltipped-no-delay d-flex flex-justify-center flex-items-center" data-copy-feedback="Copied!" data-tooltip-direction="w" value="ALTER SYSTEM SET postgis.enable_outdb_rasters TO True;
ALTER SYSTEM SET postgis.gdal_enabled_drivers TO 'GTiff';" tabindex="0" role="button">
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-copy js-clipboard-copy-icon">
    <path d="M0 6.75C0 5.784.784 5 1.75 5h1.5a.75.75 0 0 1 0 1.5h-1.5a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-1.5a.75.75 0 0 1 1.5 0v1.5A1.75 1.75 0 0 1 9.25 16h-7.5A1.75 1.75 0 0 1 0 14.25Z"></path><path d="M5 1.75C5 .784 5.784 0 6.75 0h7.5C15.216 0 16 .784 16 1.75v7.5A1.75 1.75 0 0 1 14.25 11h-7.5A1.75 1.75 0 0 1 5 9.25Zm1.75-.25a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-7.5a.25.25 0 0 0-.25-.25Z"></path>
</svg>
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-check js-clipboard-check-icon color-fg-success d-none">
    <path d="M13.78 4.22a.75.75 0 0 1 0 1.06l-7.25 7.25a.75.75 0 0 1-1.06 0L2.22 9.28a.751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018L6 10.94l6.72-6.72a.75.75 0 0 1 1.06 0Z"></path>
</svg>
    </clipboard-copy>
  </div></div>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">启动 Redis 代理：</font></font></p>
<div class="highlight highlight-source-shell notranslate position-relative overflow-auto" dir="auto"><pre>redis-server</pre><div class="zeroclipboard-container">
    <clipboard-copy aria-label="Copy" class="ClipboardButton btn btn-invisible js-clipboard-copy m-2 p-0 tooltipped-no-delay d-flex flex-justify-center flex-items-center" data-copy-feedback="Copied!" data-tooltip-direction="w" value="redis-server" tabindex="0" role="button">
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-copy js-clipboard-copy-icon">
    <path d="M0 6.75C0 5.784.784 5 1.75 5h1.5a.75.75 0 0 1 0 1.5h-1.5a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-1.5a.75.75 0 0 1 1.5 0v1.5A1.75 1.75 0 0 1 9.25 16h-7.5A1.75 1.75 0 0 1 0 14.25Z"></path><path d="M5 1.75C5 .784 5.784 0 6.75 0h7.5C15.216 0 16 .784 16 1.75v7.5A1.75 1.75 0 0 1 14.25 11h-7.5A1.75 1.75 0 0 1 5 9.25Zm1.75-.25a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-7.5a.25.25 0 0 0-.25-.25Z"></path>
</svg>
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-check js-clipboard-check-icon color-fg-success d-none">
    <path d="M13.78 4.22a.75.75 0 0 1 0 1.06l-7.25 7.25a.75.75 0 0 1-1.06 0L2.22 9.28a.751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018L6 10.94l6.72-6.72a.75.75 0 0 1 1.06 0Z"></path>
</svg>
    </clipboard-copy>
  </div></div>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">然后：</font></font></p>
<div class="highlight highlight-source-shell notranslate position-relative overflow-auto" dir="auto"><pre>pip install -r requirements.txt
sudo npm install -g webpack
sudo npm install -g webpack-cli
npm install
webpack --mode production
python manage.py collectstatic --noinput
chmod +x start.sh <span class="pl-k">&amp;&amp;</span> ./start.sh --no-gunicorn</pre><div class="zeroclipboard-container">
    <clipboard-copy aria-label="Copy" class="ClipboardButton btn btn-invisible js-clipboard-copy m-2 p-0 tooltipped-no-delay d-flex flex-justify-center flex-items-center" data-copy-feedback="Copied!" data-tooltip-direction="w" value="pip install -r requirements.txt
sudo npm install -g webpack
sudo npm install -g webpack-cli
npm install
webpack --mode production
python manage.py collectstatic --noinput
chmod +x start.sh &amp;&amp; ./start.sh --no-gunicorn" tabindex="0" role="button">
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-copy js-clipboard-copy-icon">
    <path d="M0 6.75C0 5.784.784 5 1.75 5h1.5a.75.75 0 0 1 0 1.5h-1.5a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-1.5a.75.75 0 0 1 1.5 0v1.5A1.75 1.75 0 0 1 9.25 16h-7.5A1.75 1.75 0 0 1 0 14.25Z"></path><path d="M5 1.75C5 .784 5.784 0 6.75 0h7.5C15.216 0 16 .784 16 1.75v7.5A1.75 1.75 0 0 1 14.25 11h-7.5A1.75 1.75 0 0 1 5 9.25Zm1.75-.25a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-7.5a.25.25 0 0 0-.25-.25Z"></path>
</svg>
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-check js-clipboard-check-icon color-fg-success d-none">
    <path d="M13.78 4.22a.75.75 0 0 1 0 1.06l-7.25 7.25a.75.75 0 0 1-1.06 0L2.22 9.28a.751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018L6 10.94l6.72-6.72a.75.75 0 0 1 1.06 0Z"></path>
</svg>
    </clipboard-copy>
  </div></div>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">最后，启动至少一个 celery worker：</font></font></p>
<div class="highlight highlight-source-shell notranslate position-relative overflow-auto" dir="auto"><pre>./worker.sh start</pre><div class="zeroclipboard-container">
    <clipboard-copy aria-label="Copy" class="ClipboardButton btn btn-invisible js-clipboard-copy m-2 p-0 tooltipped-no-delay d-flex flex-justify-center flex-items-center" data-copy-feedback="Copied!" data-tooltip-direction="w" value="./worker.sh start" tabindex="0" role="button">
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-copy js-clipboard-copy-icon">
    <path d="M0 6.75C0 5.784.784 5 1.75 5h1.5a.75.75 0 0 1 0 1.5h-1.5a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-1.5a.75.75 0 0 1 1.5 0v1.5A1.75 1.75 0 0 1 9.25 16h-7.5A1.75 1.75 0 0 1 0 14.25Z"></path><path d="M5 1.75C5 .784 5.784 0 6.75 0h7.5C15.216 0 16 .784 16 1.75v7.5A1.75 1.75 0 0 1 14.25 11h-7.5A1.75 1.75 0 0 1 5 9.25Zm1.75-.25a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-7.5a.25.25 0 0 0-.25-.25Z"></path>
</svg>
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-check js-clipboard-check-icon color-fg-success d-none">
    <path d="M13.78 4.22a.75.75 0 0 1 0 1.06l-7.25 7.25a.75.75 0 0 1-1.06 0L2.22 9.28a.751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018L6 10.94l6.72-6.72a.75.75 0 0 1 1.06 0Z"></path>
</svg>
    </clipboard-copy>
  </div></div>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">如果传递参数，脚本</font></font><code>start.sh</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">将使用 Django 的内置服务器</font></font><code>--no-gunicorn</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">。这有利于测试，但不利于生产。</font></font></p>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">在生产中，如果安装了 nginx，请修改配置文件</font></font><code>nginx/nginx.conf</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">以匹配您的系统配置，然后</font></font><code>start.sh</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">不带参数运行。</font></font></p>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Windows 用户应参考</font></font><a href="https://docs.djangoproject.com/en/1.11/howto/deployment/wsgi/modwsgi/" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">本指南</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">来安装 Apache + mod_wsgi 并运行 Gunicorn：</font></font></p>
<div class="highlight highlight-source-shell notranslate position-relative overflow-auto" dir="auto"><pre>gunicorn webodm.wsgi --bind 0.0.0.0:8000 --preload</pre><div class="zeroclipboard-container">
    <clipboard-copy aria-label="Copy" class="ClipboardButton btn btn-invisible js-clipboard-copy m-2 p-0 tooltipped-no-delay d-flex flex-justify-center flex-items-center" data-copy-feedback="Copied!" data-tooltip-direction="w" value="gunicorn webodm.wsgi --bind 0.0.0.0:8000 --preload" tabindex="0" role="button">
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-copy js-clipboard-copy-icon">
    <path d="M0 6.75C0 5.784.784 5 1.75 5h1.5a.75.75 0 0 1 0 1.5h-1.5a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-1.5a.75.75 0 0 1 1.5 0v1.5A1.75 1.75 0 0 1 9.25 16h-7.5A1.75 1.75 0 0 1 0 14.25Z"></path><path d="M5 1.75C5 .784 5.784 0 6.75 0h7.5C15.216 0 16 .784 16 1.75v7.5A1.75 1.75 0 0 1 14.25 11h-7.5A1.75 1.75 0 0 1 5 9.25Zm1.75-.25a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-7.5a.25.25 0 0 0-.25-.25Z"></path>
</svg>
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-check js-clipboard-check-icon color-fg-success d-none">
    <path d="M13.78 4.22a.75.75 0 0 1 0 1.06l-7.25 7.25a.75.75 0 0 1-1.06 0L2.22 9.28a.751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018L6 10.94l6.72-6.72a.75.75 0 0 1 1.06 0Z"></path>
</svg>
    </clipboard-copy>
  </div></div>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">如果您获得的是</font></font><code>rt_raster_gdal_warp: Could not create GDAL transformation object for output dataset creation</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">，请确保您的 PostGIS 安装具有 PROJ 支持：</font></font></p>
<div class="highlight highlight-source-sql notranslate position-relative overflow-auto" dir="auto"><pre><span class="pl-k">SELECT</span> PostGIS_Full_Version();</pre><div class="zeroclipboard-container">
    <clipboard-copy aria-label="Copy" class="ClipboardButton btn btn-invisible js-clipboard-copy m-2 p-0 tooltipped-no-delay d-flex flex-justify-center flex-items-center" data-copy-feedback="Copied!" data-tooltip-direction="w" value="SELECT PostGIS_Full_Version();" tabindex="0" role="button">
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-copy js-clipboard-copy-icon">
    <path d="M0 6.75C0 5.784.784 5 1.75 5h1.5a.75.75 0 0 1 0 1.5h-1.5a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-1.5a.75.75 0 0 1 1.5 0v1.5A1.75 1.75 0 0 1 9.25 16h-7.5A1.75 1.75 0 0 1 0 14.25Z"></path><path d="M5 1.75C5 .784 5.784 0 6.75 0h7.5C15.216 0 16 .784 16 1.75v7.5A1.75 1.75 0 0 1 14.25 11h-7.5A1.75 1.75 0 0 1 5 9.25Zm1.75-.25a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-7.5a.25.25 0 0 0-.25-.25Z"></path>
</svg>
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-check js-clipboard-check-icon color-fg-success d-none">
    <path d="M13.78 4.22a.75.75 0 0 1 0 1.06l-7.25 7.25a.75.75 0 0 1-1.06 0L2.22 9.28a.751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018L6 10.94l6.72-6.72a.75.75 0 0 1 1.06 0Z"></path>
</svg>
    </clipboard-copy>
  </div></div>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">您可能还需要将环境变量 PROJSO 设置为 PostGIS 正在使用的 .so 或 .dll 投影库。只需要文件名即可。例如，在 Windows 上，您可以在控制面板 -&gt; 系统 -&gt; 环境变量中添加一个名为 PROJSO 的系统变量并将其设置为 libproj.dll（如果您使用的是 proj 4.6.1）。进行此更改后，您必须重新启动 PostgreSQL 服务/守护程序。</font></font><a href="http://postgis.net/docs/manual-2.0/RT_ST_Transform.html" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">http://postgis.net/docs/manual-2.0/RT_ST_Transform.html</font></font></a></p>
<p dir="auto"><font style="vertical-align: inherit;"></font><code>pip install -r requirements.txt</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">如果您使用的是 Windows，并且由于 zlib 和 Pillow 相关的错误而</font><font style="vertical-align: inherit;">无法执行该命令，请手动编辑该</font></font><code>requirements.txt</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">文件，删除 Pillow 要求并运行：</font></font></p>
<div class="highlight highlight-source-shell notranslate position-relative overflow-auto" dir="auto"><pre>easy_install pillow
pip install -r requirements.txt</pre><div class="zeroclipboard-container">
    <clipboard-copy aria-label="Copy" class="ClipboardButton btn btn-invisible js-clipboard-copy m-2 p-0 tooltipped-no-delay d-flex flex-justify-center flex-items-center" data-copy-feedback="Copied!" data-tooltip-direction="w" value="easy_install pillow
pip install -r requirements.txt" tabindex="0" role="button">
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-copy js-clipboard-copy-icon">
    <path d="M0 6.75C0 5.784.784 5 1.75 5h1.5a.75.75 0 0 1 0 1.5h-1.5a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-1.5a.75.75 0 0 1 1.5 0v1.5A1.75 1.75 0 0 1 9.25 16h-7.5A1.75 1.75 0 0 1 0 14.25Z"></path><path d="M5 1.75C5 .784 5.784 0 6.75 0h7.5C15.216 0 16 .784 16 1.75v7.5A1.75 1.75 0 0 1 14.25 11h-7.5A1.75 1.75 0 0 1 5 9.25Zm1.75-.25a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-7.5a.25.25 0 0 0-.25-.25Z"></path>
</svg>
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-check js-clipboard-check-icon color-fg-success d-none">
    <path d="M13.78 4.22a.75.75 0 0 1 0 1.06l-7.25 7.25a.75.75 0 0 1-1.06 0L2.22 9.28a.751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018L6 10.94l6.72-6.72a.75.75 0 0 1 1.06 0Z"></path>
</svg>
    </clipboard-copy>
  </div></div>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">在 Windows 上，确保所有 PATH 环境变量均已正确设置。这些命令：</font></font></p>
<div class="highlight highlight-source-shell notranslate position-relative overflow-auto" dir="auto"><pre>python --version
pip --version
npm --version
gdalinfo --version
redis-server --version</pre><div class="zeroclipboard-container">
    <clipboard-copy aria-label="Copy" class="ClipboardButton btn btn-invisible js-clipboard-copy m-2 p-0 tooltipped-no-delay d-flex flex-justify-center flex-items-center" data-copy-feedback="Copied!" data-tooltip-direction="w" value="python --version
pip --version
npm --version
gdalinfo --version
redis-server --version" tabindex="0" role="button">
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-copy js-clipboard-copy-icon">
    <path d="M0 6.75C0 5.784.784 5 1.75 5h1.5a.75.75 0 0 1 0 1.5h-1.5a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-1.5a.75.75 0 0 1 1.5 0v1.5A1.75 1.75 0 0 1 9.25 16h-7.5A1.75 1.75 0 0 1 0 14.25Z"></path><path d="M5 1.75C5 .784 5.784 0 6.75 0h7.5C15.216 0 16 .784 16 1.75v7.5A1.75 1.75 0 0 1 14.25 11h-7.5A1.75 1.75 0 0 1 5 9.25Zm1.75-.25a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-7.5a.25.25 0 0 0-.25-.25Z"></path>
</svg>
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-check js-clipboard-check-icon color-fg-success d-none">
    <path d="M13.78 4.22a.75.75 0 0 1 0 1.06l-7.25 7.25a.75.75 0 0 1-1.06 0L2.22 9.28a.751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018L6 10.94l6.72-6.72a.75.75 0 0 1 1.06 0Z"></path>
</svg>
    </clipboard-copy>
  </div></div>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">应该一切正常，没有错误。</font></font></p>
<div class="markdown-heading" dir="auto"><h2 tabindex="-1" class="heading-element" dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">在云上运行（Google Compute、Amazon AWS）</font></font></h2><a id="user-content-run-it-on-the-cloud-google-compute-amazon-aws" class="anchor" aria-label="永久链接：在云上运行（Google Compute、Amazon AWS）" href="#run-it-on-the-cloud-google-compute-amazon-aws"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a></div>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">12 个步骤，让 WebODM 在云实例上运行。</font></font></p>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">这些步骤适用于 Google Cloud，但也可用于 Amazon AWS 和其他云平台，只需进行少量修改：</font></font></p>
<ol dir="auto">
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">启动 Ubuntu 18.0 LTS 的 Google Cloud 实例。</font></font></li>
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">打开 SSH 终端 - Google 通过网站提供 SSH。</font></font></li>
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">运行 sudo apt-get update</font></font></li>
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">运行 sudo apt-get 升级</font></font></li>
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">运行 sudo apt-get install docker-compose</font></font></li>
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">运行 sudo apt-get install python-pip</font></font></li>
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">运行 git clone </font></font><a href="https://github.com/OpenDroneMap/WebODM"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">https://github.com/OpenDroneMap/WebODM</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;"> --config core.autocrlf=input --深度 1</font></font></li>
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">cd WebODM（Linux 区分大小写）</font></font></li>
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">sudo ./webodm.sh 启动</font></font></li>
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">您现在可以通过 google 实例的公共 IP 地址访问 webodm。请记住默认端口 8000。</font></font></li>
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">检查您实例的防火墙是否允许端口 8000 上的入站 TCP 连接！如果您忘记此步骤，您将无法连接到 WebODM。</font></font></li>
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">打开</font></font><a href="http://GooglepublicIPaddressforyourinstance:8000" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">http://GooglepublicIPaddressforyourinstance:8000</font></font></a></li>
</ol>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">要在 Google Cloud 上设置防火墙，请打开实例，在实例设置页面的中间找到 NIC0。打开它，然后在防火墙上添加 TCP 端口 8000 作为入口和出口。</font></font></p>
<div class="markdown-heading" dir="auto"><h2 tabindex="-1" class="heading-element" dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">执照</font></font></h2><a id="user-content-license" class="anchor" aria-label="永久链接：许可证" href="#license"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a></div>
<p dir="auto"><font style="vertical-align: inherit;"></font><a href="https://github.com/OpenDroneMap/WebODM/blob/master/LICENSE.md"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">WebODM 根据GNU Affero 通用公共许可证 v3.0</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">的条款获得许可</font><font style="vertical-align: inherit;">。</font></font></p>
<div class="markdown-heading" dir="auto"><h2 tabindex="-1" class="heading-element" dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">商标</font></font></h2><a id="user-content-trademark" class="anchor" aria-label="永久链接： 商标" href="#trademark"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a></div>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">请参阅</font></font><a href="https://github.com/OpenDroneMap/documents/blob/master/TRADEMARK.md"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">商标指南</font></font></a></p>
</article></div>
