<div class="Box-sc-g0xbh4-0 bJMeLZ js-snippet-clipboard-copy-unpositioned" data-hpc="true"><article class="markdown-body entry-content container-lg" itemprop="text"><div align="center" dir="auto">
  <a href="https://github.com/reviewdog/reviewdog">
    <img alt="评论狗" src="https://raw.githubusercontent.com/haya14busa/i/d598ed7dc49fefb0018e422e4c43e5ab8f207a6b/reviewdog/reviewdog.logo.png" style="max-width: 100%;">
  </a>
</div>
<h2 align="center" tabindex="-1" dir="auto"><a id="user-content---reviewdog---a-code-review-dog-who-keeps-your-codebase-healthy" class="anchor" aria-hidden="true" tabindex="-1" href="#--reviewdog---a-code-review-dog-who-keeps-your-codebase-healthy"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">
  reviewdog - 保持代码库健康的代码审查狗。
</font></font></h2>
<div align="center" dir="auto">
  <a href="/reviewdog/reviewdog/blob/master/LICENSE">
    <img alt="执照" src="https://camo.githubusercontent.com/475cc24ac7cb3cbc4110bef1535d505145715f5a6d467b0e123cec3eda47eacd/68747470733a2f2f696d672e736869656c64732e696f2f62616467652f6c6963656e73652d4d49542d626c75652e7376673f6d61784167653d3433323030" data-canonical-src="https://img.shields.io/badge/license-MIT-blue.svg?maxAge=43200" style="max-width: 100%;">
  </a>
  <a href="https://godoc.org/github.com/reviewdog/reviewdog" rel="nofollow">
    <img alt="戈多克" src="https://camo.githubusercontent.com/4fe00ff84fb6f0b9bf9d631c76e2e4ff3b3499c6edd0e9ec247b86df6e2b6076/68747470733a2f2f696d672e736869656c64732e696f2f62616467652f676f646f632d7265666572656e63652d3446373342332e7376673f6c6162656c3d676f646f632e6f7267266d61784167653d3433323030266c6f676f3d676f" data-canonical-src="https://img.shields.io/badge/godoc-reference-4F73B3.svg?label=godoc.org&amp;maxAge=43200&amp;logo=go" style="max-width: 100%;">
  </a>
  <a href="/reviewdog/reviewdog/blob/master/CHANGELOG.md">
    <img alt="发布" src="https://camo.githubusercontent.com/ff56896bdde803bb977c7af485a02e6846cda5916fe9d03d352bd6d2261d6a1c/68747470733a2f2f696d672e736869656c64732e696f2f6769746875622f72656c656173652f726576696577646f672f726576696577646f672e7376673f6c6f676f3d676974687562" data-canonical-src="https://img.shields.io/github/release/reviewdog/reviewdog.svg?logo=github" style="max-width: 100%;">
  </a>
  <a href="https://github.com/reviewdog/nightly">
    <img alt="每晚发布" src="https://camo.githubusercontent.com/06b529cc7cc28ac170f022403d736b14abcc5bc4c364872f549c661fb93af4a8/68747470733a2f2f696d672e736869656c64732e696f2f6769746875622f762f72656c656173652f726576696577646f672f6e696768746c792e7376673f6c6f676f3d676974687562" data-canonical-src="https://img.shields.io/github/v/release/reviewdog/nightly.svg?logo=github" style="max-width: 100%;">
  </a>
</div>
<div align="center" dir="auto">
  <a href="https://github.com/reviewdog/reviewdog/actions?query=workflow%3AGo+event%3Apush+branch%3Amaster">
    <img alt="GitHub 操作" src="https://github.com/reviewdog/reviewdog/workflows/Go/badge.svg" style="max-width: 100%;">
  </a>
  <a href="https://github.com/reviewdog/reviewdog/actions?query=workflow%3Areviewdog+event%3Apush+branch%3Amaster">
    <img alt="评论狗" src="https://github.com/reviewdog/reviewdog/workflows/reviewdog/badge.svg?branch=master&amp;event=push" style="max-width: 100%;">
  </a>
  <a href="https://github.com/reviewdog/reviewdog/actions?query=workflow%3Arelease">
    <img alt="发布" src="https://github.com/reviewdog/reviewdog/workflows/release/badge.svg" style="max-width: 100%;">
  </a>
  <a href="https://travis-ci.org/reviewdog/reviewdog" rel="nofollow"><img alt="特拉维斯状态" src="https://camo.githubusercontent.com/1a027597f129504e71606e34332ab3911076da1001ca75f137271eb90a1d3621/68747470733a2f2f696d672e736869656c64732e696f2f7472617669732f726576696577646f672f726576696577646f672f6d61737465722e7376673f6c6162656c3d547261766973266c6f676f3d747261766973" data-canonical-src="https://img.shields.io/travis/reviewdog/reviewdog/master.svg?label=Travis&amp;logo=travis" style="max-width: 100%;"></a>
  <a href="https://circleci.com/gh/reviewdog/reviewdog" rel="nofollow"><img alt="CircleCI 状态" src="https://camo.githubusercontent.com/48467001f4d1ab2c0b341a91d65e9de7314ac7887c7c37111e0e99598097fe9b/687474703a2f2f696d672e736869656c64732e696f2f636972636c6563692f6275696c642f6769746875622f726576696577646f672f726576696577646f672f6d61737465722e7376673f6c6162656c3d436972636c654349266c6f676f3d636972636c656369" data-canonical-src="http://img.shields.io/circleci/build/github/reviewdog/reviewdog/master.svg?label=CircleCI&amp;logo=circleci" style="max-width: 100%;"></a>
  <a href="https://codecov.io/github/reviewdog/reviewdog" rel="nofollow"><img alt="覆盖状态" src="https://camo.githubusercontent.com/fe975b0a86174abc875e2060337dbfe7d5c82b3da2547983a4b33c1c7697000b/68747470733a2f2f696d672e736869656c64732e696f2f636f6465636f762f632f6769746875622f726576696577646f672f726576696577646f672f6d61737465722e7376673f6c6f676f3d636f6465636f76" data-canonical-src="https://img.shields.io/codecov/c/github/reviewdog/reviewdog/master.svg?logo=codecov" style="max-width: 100%;"></a>
</div>
<div align="center" dir="auto">
  <a href="https://gitlab.com/reviewdog/reviewdog/pipelines" rel="nofollow">
    <img alt="亚搏体育appGitLab支持" src="https://camo.githubusercontent.com/ccf7b1db7c3b396ad3c18c9516ecbadc5e6675e0a8554a11bb56b971571bdb5b/68747470733a2f2f696d672e736869656c64732e696f2f62616467652f4769744c61622532302d537570706f727465642d6663366432363f6c6f676f3d6769746c6162" data-canonical-src="https://img.shields.io/badge/GitLab%20-Supported-fc6d26?logo=gitlab" style="max-width: 100%;">
  </a>
  <a href="https://github.com/haya14busa/action-bumpr">
    <img alt="支持动作碰撞" src="https://camo.githubusercontent.com/9ad9919146466aef4edf9fb3c80edb41ee732837177307d7eca8f14f31820bf7/68747470733a2f2f696d672e736869656c64732e696f2f62616467652f62756d70722d737570706f727465642d6666363962343f6c6f676f3d676974687562266c696e6b3d68747470733a2f2f6769746875622e636f6d2f686179613134627573612f616374696f6e2d62756d7072" data-canonical-src="https://img.shields.io/badge/bumpr-supported-ff69b4?logo=github&amp;link=https://github.com/haya14busa/action-bumpr" style="max-width: 100%;">
  </a>
  <a href="https://github.com/reviewdog/.github/blob/master/CODE_OF_CONDUCT.md">
    <img alt="贡献者契约" src="https://camo.githubusercontent.com/20fe195dfecc3508e105ec04e6a1acea97bd409201ac6ca09c07942c8a8e4ad2/68747470733a2f2f696d672e736869656c64732e696f2f62616467652f436f6e7472696275746f72253230436f76656e616e742d76322e3025323061646f707465642d6666363962342e737667" data-canonical-src="https://img.shields.io/badge/Contributor%20Covenant-v2.0%20adopted-ff69b4.svg" style="max-width: 100%;">
  </a>
  <a href="https://somsubhra.github.io/github-release-stats/?username=reviewdog&amp;repository=reviewdog&amp;per_page=30" rel="nofollow">
    <img alt="GitHub 发布统计数据" src="https://camo.githubusercontent.com/c2691f6650303895120532cbafd1af6cd3652a9c7c027f7a2d1eb6ac82cba25c/68747470733a2f2f696d672e736869656c64732e696f2f6769746875622f646f776e6c6f6164732f726576696577646f672f726576696577646f672f746f74616c2e7376673f6c6f676f3d676974687562" data-canonical-src="https://img.shields.io/github/downloads/reviewdog/reviewdog/total.svg?logo=github" style="max-width: 100%;">
  </a>
  <a href="https://starchart.cc/reviewdog/reviewdog" rel="nofollow"><img alt="星星" src="https://camo.githubusercontent.com/49ab0bc1f2d748bf150814b27a6ee139670b453b820b95f20b4e802cce132b92/68747470733a2f2f696d672e736869656c64732e696f2f6769746875622f73746172732f726576696577646f672f726576696577646f672e7376673f7374796c653d736f6369616c" data-canonical-src="https://img.shields.io/github/stars/reviewdog/reviewdog.svg?style=social" style="max-width: 100%;"></a>
</div>
<br>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">reviewdog 提供了一种通过轻松与任何 linter 工具集成来自动将审阅评论发布到代码托管服务（例如 GitHub）的方法。</font><font style="vertical-align: inherit;">它使用 lint 工具的输出，并将其作为评论发布（如果发现的结果位于要审查的补丁的差异中）。</font></font></p>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">reviewdog还支持在本地环境中运行，通过diff过滤lint工具的输出。</font></font></p>
<p dir="auto"><a href="https://docs.google.com/document/d/1mGOX19SSqRowWGbXieBfGPtLnM0BdTkIc9JelTiu6wA/edit?usp=sharing" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">设计文档</font></font></a></p>
<h2 tabindex="-1" dir="auto"><a id="user-content-table-of-contents" class="anchor" aria-hidden="true" tabindex="-1" href="#table-of-contents"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">目录</font></font></h2>
<ul dir="auto">
<li><a href="#installation"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">安装</font></font></a></li>
<li><a href="#input-format"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">输入格式</font></font></a>
<ul dir="auto">
<li><a href="#errorformat"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">'错误格式'</font></font></a></li>
<li><a href="#available-pre-defined-errorformat"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">可用的预定义“错误格式”</font></font></a></li>
<li><a href="#reviewdog-diagnostic-format-rdformat"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Reviewdog 诊断格式 (RDFormat)</font></font></a></li>
<li><a href="#diff"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">差异</font></font></a></li>
<li><a href="#checkstyle-format"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">检查式格式</font></font></a></li>
<li><a href="#sarif-format"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">SARIF 格式</font></font></a></li>
</ul>
</li>
<li><a href="#code-suggestions"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">代码建议</font></font></a></li>
<li><a href="#reviewdog-config-file"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">审查狗配置文件</font></font></a></li>
<li><a href="#reporters"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">记者</font></font></a>
<ul dir="auto">
<li><a href="#reporter-local--reporterlocal-default"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">记者：本地（-reporter=local）[默认]</font></font></a></li>
<li><a href="#reporter-github-checks--reportergithub-pr-check"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">记者：GitHub 检查 (-reporter=github-pr-check)</font></font></a></li>
<li><a href="#reporter-github-checks--reportergithub-check"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">记者：GitHub 检查 (-reporter=github-check)</font></font></a></li>
<li><a href="#reporter-github-pullrequest-review-comment--reportergithub-pr-review"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">记者：GitHub PullRequest 审核评论 (-reporter=github-pr-review)</font></font></a></li>
<li><a href="#reporter-gitlab-mergerequest-discussions--reportergitlab-mr-discussion"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">记者：GitLab MergeRequest 讨论 (-reporter=gitlab-mr-discussion)</font></font></a></li>
<li><a href="#reporter-gitlab-mergerequest-commit--reportergitlab-mr-commit"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">报告者：GitLab MergeRequest 提交 (-reporter=gitlab-mr-commit)</font></font></a></li>
<li><a href="#reporter-bitbucket-code-insights-reports--reporterbitbucket-code-report"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">记者：Bitbucket 代码洞察报告 (-reporter=bitbucket-code-report)</font></font></a></li>
</ul>
</li>
<li><a href="#supported-ci-services"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">支持的 CI 服务</font></font></a>
<ul dir="auto">
<li><a href="#github-actions"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">GitHub 操作</font></font></a></li>
<li><a href="#travis-ci"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">特拉维斯·西尔</font></font></a></li>
<li><a href="#circle-ci"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">圆CI</font></font></a></li>
<li><a href="#gitlab-ci"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">亚搏体育appGitLab持续集成</font></font></a></li>
<li><a href="#bitbucket-pipelines"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">位桶管道</font></font></a></li>
<li><a href="#common-jenkins-local-etc"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">常见（詹金斯、本地等...）</font></font></a>
<ul dir="auto">
<li><a href="#jenkins-with-github-pull-request-builder-plugin"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">带有 GitHub 拉取请求构建器插件的 Jenkins</font></font></a></li>
</ul>
</li>
</ul>
</li>
<li><a href="#exit-codes"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">退出代码</font></font></a></li>
<li><a href="#filter-mode"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">过滤模式</font></font></a></li>
<li><a href="#articles"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">文章</font></font></a></li>
</ul>
<p dir="auto"><a href="https://github.com/reviewdog/reviewdog/pull/131/checks"><img src="https://user-images.githubusercontent.com/3797062/40884858-6efd82a0-6756-11e8-9f1a-c6af4f920fb0.png" alt="github-pr-检查示例" style="max-width: 100%;"></a>
<a target="_blank" rel="noopener noreferrer nofollow" href="https://user-images.githubusercontent.com/3797062/40941822-1d775064-6887-11e8-98e9-4775d37d47f8.png"><img src="https://user-images.githubusercontent.com/3797062/40941822-1d775064-6887-11e8-98e9-4775d37d47f8.png" alt="在拉取请求中发表评论" style="max-width: 100%;"></a>
<a target="_blank" rel="noopener noreferrer nofollow" href="https://user-images.githubusercontent.com/3797062/40941738-d62acb0a-6886-11e8-858d-7b97aded2a42.png"><img src="https://user-images.githubusercontent.com/3797062/40941738-d62acb0a-6886-11e8-858d-7b97aded2a42.png" alt="提交状态" style="max-width: 100%;"></a>
<a href="https://github.com/reviewdog/reviewdog/pull/24#discussion_r84599728" data-hovercard-type="pull_request" data-hovercard-url="/reviewdog/reviewdog/pull/24/hovercard"><img src="https://raw.githubusercontent.com/haya14busa/i/dc0ccb1e110515ea407c146d99b749018db05c45/reviewdog/sample-comment.png" alt="样本评论.png" style="max-width: 100%;"></a>
<animated-image data-catalyst=""><a target="_blank" rel="noopener noreferrer nofollow" href="https://raw.githubusercontent.com/haya14busa/i/dc0ccb1e110515ea407c146d99b749018db05c45/reviewdog/reviewdog-local-demo.gif" data-target="animated-image.originalLink"><img src="https://raw.githubusercontent.com/haya14busa/i/dc0ccb1e110515ea407c146d99b749018db05c45/reviewdog/reviewdog-local-demo.gif" alt="评论dog-local-demo.gif" style="max-width: 100%; display: inline-block;" data-target="animated-image.originalImage"></a>
      <span class="AnimatedImagePlayer" data-target="animated-image.player" hidden="">
        <a data-target="animated-image.replacedLink" class="AnimatedImagePlayer-images" href="https://raw.githubusercontent.com/haya14busa/i/dc0ccb1e110515ea407c146d99b749018db05c45/reviewdog/reviewdog-local-demo.gif" target="_blank">
          
 
<h2 tabindex="-1" dir="auto"><a id="user-content-installation" class="anchor" aria-hidden="true" tabindex="-1" href="#installation"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">安装</font></font></h2>
<div class="highlight highlight-source-shell notranslate position-relative overflow-auto" dir="auto"><pre><span class="pl-c"><span class="pl-c">#</span> Install the latest version. (Install it into ./bin/ by default).</span>
$ curl -sfL https://raw.githubusercontent.com/reviewdog/reviewdog/master/install.sh <span class="pl-k">|</span> sh -s

<span class="pl-c"><span class="pl-c">#</span> Specify installation directory ($(go env GOPATH)/bin/) and version.</span>
$ curl -sfL https://raw.githubusercontent.com/reviewdog/reviewdog/master/install.sh <span class="pl-k">|</span> sh -s -- -b <span class="pl-s"><span class="pl-pds">$(</span>go env GOPATH<span class="pl-pds">)</span></span>/bin [vX.Y.Z]

<span class="pl-c"><span class="pl-c">#</span> In alpine linux (as it does not come with curl by default)</span>
$ wget -O - -q https://raw.githubusercontent.com/reviewdog/reviewdog/master/install.sh <span class="pl-k">|</span> sh -s [vX.Y.Z]</pre><div class="zeroclipboard-container">
    <clipboard-copy aria-label="Copy" class="ClipboardButton btn btn-invisible js-clipboard-copy m-2 p-0 tooltipped-no-delay d-flex flex-justify-center flex-items-center" data-copy-feedback="Copied!" data-tooltip-direction="w" value="# Install the latest version. (Install it into ./bin/ by default).
$ curl -sfL https://raw.githubusercontent.com/reviewdog/reviewdog/master/install.sh | sh -s

# Specify installation directory ($(go env GOPATH)/bin/) and version.
$ curl -sfL https://raw.githubusercontent.com/reviewdog/reviewdog/master/install.sh | sh -s -- -b $(go env GOPATH)/bin [vX.Y.Z]

# In alpine linux (as it does not come with curl by default)
$ wget -O - -q https://raw.githubusercontent.com/reviewdog/reviewdog/master/install.sh | sh -s [vX.Y.Z]" tabindex="0" role="button">

      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-copy js-clipboard-copy-icon">
    <path d="M0 6.75C0 5.784.784 5 1.75 5h1.5a.75.75 0 0 1 0 1.5h-1.5a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-1.5a.75.75 0 0 1 1.5 0v1.5A1.75 1.75 0 0 1 9.25 16h-7.5A1.75 1.75 0 0 1 0 14.25Z"></path><path d="M5 1.75C5 .784 5.784 0 6.75 0h7.5C15.216 0 16 .784 16 1.75v7.5A1.75 1.75 0 0 1 14.25 11h-7.5A1.75 1.75 0 0 1 5 9.25Zm1.75-.25a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-7.5a.25.25 0 0 0-.25-.25Z"></path>
</svg>
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-check js-clipboard-check-icon color-fg-success d-none">
    <path d="M13.78 4.22a.75.75 0 0 1 0 1.06l-7.25 7.25a.75.75 0 0 1-1.06 0L2.22 9.28a.751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018L6 10.94l6.72-6.72a.75.75 0 0 1 1.06 0Z"></path>
</svg>
    </clipboard-copy>
  </div></div>
<h3 tabindex="-1" dir="auto"><a id="user-content-nightly-releases" class="anchor" aria-hidden="true" tabindex="-1" href="#nightly-releases"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">每晚发布</font></font></h3>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">您还可以使用</font></font><a href="https://github.com/reviewdog/nightly"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">夜间 reviewdog 发布</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">
来每天尝试最新的 reviewdog 改进！</font></font></p>
<div class="highlight highlight-source-shell notranslate position-relative overflow-auto" dir="auto"><pre>$ curl -sfL https://raw.githubusercontent.com/reviewdog/nightly/master/install.sh <span class="pl-k">|</span> sh -s -- -b <span class="pl-s"><span class="pl-pds">$(</span>go env GOPATH<span class="pl-pds">)</span></span>/bin</pre><div class="zeroclipboard-container">
    <clipboard-copy aria-label="Copy" class="ClipboardButton btn btn-invisible js-clipboard-copy m-2 p-0 tooltipped-no-delay d-flex flex-justify-center flex-items-center" data-copy-feedback="Copied!" data-tooltip-direction="w" value="$ curl -sfL https://raw.githubusercontent.com/reviewdog/nightly/master/install.sh | sh -s -- -b $(go env GOPATH)/bin" tabindex="0" role="button">
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-copy js-clipboard-copy-icon">
    <path d="M0 6.75C0 5.784.784 5 1.75 5h1.5a.75.75 0 0 1 0 1.5h-1.5a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-1.5a.75.75 0 0 1 1.5 0v1.5A1.75 1.75 0 0 1 9.25 16h-7.5A1.75 1.75 0 0 1 0 14.25Z"></path><path d="M5 1.75C5 .784 5.784 0 6.75 0h7.5C15.216 0 16 .784 16 1.75v7.5A1.75 1.75 0 0 1 14.25 11h-7.5A1.75 1.75 0 0 1 5 9.25Zm1.75-.25a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-7.5a.25.25 0 0 0-.25-.25Z"></path>
</svg>
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-check js-clipboard-check-icon color-fg-success d-none">
    <path d="M13.78 4.22a.75.75 0 0 1 0 1.06l-7.25 7.25a.75.75 0 0 1-1.06 0L2.22 9.28a.751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018L6 10.94l6.72-6.72a.75.75 0 0 1 1.06 0Z"></path>
</svg>
    </clipboard-copy>
  </div></div>
<h3 tabindex="-1" dir="auto"><a id="user-content-github-action-reviewdogaction-setup" class="anchor" aria-hidden="true" tabindex="-1" href="#github-action-reviewdogaction-setup"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">GitHub Action：</font></font><a href="https://github.com/reviewdog/action-setup"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">reviewdog/action-setup</font></font></a></h3>
<div class="highlight highlight-source-yaml notranslate position-relative overflow-auto" dir="auto"><pre><span class="pl-ent">steps</span>:
- <span class="pl-ent">uses</span>: <span class="pl-s">reviewdog/action-setup@v1</span>
  <span class="pl-ent">with</span>:
    <span class="pl-ent">reviewdog_version</span>: <span class="pl-s">latest </span><span class="pl-c"><span class="pl-c">#</span> Optional. [latest,nightly,v.X.Y.Z]</span></pre><div class="zeroclipboard-container">
    <clipboard-copy aria-label="Copy" class="ClipboardButton btn btn-invisible js-clipboard-copy m-2 p-0 tooltipped-no-delay d-flex flex-justify-center flex-items-center" data-copy-feedback="Copied!" data-tooltip-direction="w" value="steps:
- uses: reviewdog/action-setup@v1
  with:
    reviewdog_version: latest # Optional. [latest,nightly,v.X.Y.Z]" tabindex="0" role="button">
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-copy js-clipboard-copy-icon">
    <path d="M0 6.75C0 5.784.784 5 1.75 5h1.5a.75.75 0 0 1 0 1.5h-1.5a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-1.5a.75.75 0 0 1 1.5 0v1.5A1.75 1.75 0 0 1 9.25 16h-7.5A1.75 1.75 0 0 1 0 14.25Z"></path><path d="M5 1.75C5 .784 5.784 0 6.75 0h7.5C15.216 0 16 .784 16 1.75v7.5A1.75 1.75 0 0 1 14.25 11h-7.5A1.75 1.75 0 0 1 5 9.25Zm1.75-.25a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-7.5a.25.25 0 0 0-.25-.25Z"></path>
</svg>
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-check js-clipboard-check-icon color-fg-success d-none">
    <path d="M13.78 4.22a.75.75 0 0 1 0 1.06l-7.25 7.25a.75.75 0 0 1-1.06 0L2.22 9.28a.751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018L6 10.94l6.72-6.72a.75.75 0 0 1 1.06 0Z"></path>
</svg>
    </clipboard-copy>
  </div></div>
<h3 tabindex="-1" dir="auto"><a id="user-content-homebrew--linuxbrew" class="anchor" aria-hidden="true" tabindex="-1" href="#homebrew--linuxbrew"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">自制软件 / linuxbrew</font></font></h3>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">您还可以使用brew安装reviewdog：</font></font></p>
<div class="highlight highlight-source-shell notranslate position-relative overflow-auto" dir="auto"><pre>$ brew install reviewdog/tap/reviewdog
$ brew upgrade reviewdog/tap/reviewdog</pre><div class="zeroclipboard-container">
    <clipboard-copy aria-label="Copy" class="ClipboardButton btn btn-invisible js-clipboard-copy m-2 p-0 tooltipped-no-delay d-flex flex-justify-center flex-items-center" data-copy-feedback="Copied!" data-tooltip-direction="w" value="$ brew install reviewdog/tap/reviewdog
$ brew upgrade reviewdog/tap/reviewdog" tabindex="0" role="button">
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-copy js-clipboard-copy-icon">
    <path d="M0 6.75C0 5.784.784 5 1.75 5h1.5a.75.75 0 0 1 0 1.5h-1.5a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-1.5a.75.75 0 0 1 1.5 0v1.5A1.75 1.75 0 0 1 9.25 16h-7.5A1.75 1.75 0 0 1 0 14.25Z"></path><path d="M5 1.75C5 .784 5.784 0 6.75 0h7.5C15.216 0 16 .784 16 1.75v7.5A1.75 1.75 0 0 1 14.25 11h-7.5A1.75 1.75 0 0 1 5 9.25Zm1.75-.25a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-7.5a.25.25 0 0 0-.25-.25Z"></path>
</svg>
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-check js-clipboard-check-icon color-fg-success d-none">
    <path d="M13.78 4.22a.75.75 0 0 1 0 1.06l-7.25 7.25a.75.75 0 0 1-1.06 0L2.22 9.28a.751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018L6 10.94l6.72-6.72a.75.75 0 0 1 1.06 0Z"></path>
</svg>
    </clipboard-copy>
  </div></div>
<h3 tabindex="-1" dir="auto"><a id="user-content-scoop-on-windows" class="anchor" aria-hidden="true" tabindex="-1" href="#scoop-on-windows"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a><a href="https://scoop.sh/" rel="nofollow"><font style="vertical-align: inherit;"></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Windows 上的</font><a href="https://scoop.sh/" rel="nofollow"><font style="vertical-align: inherit;">独家新闻</font></a></font></h3>
<div class="snippet-clipboard-content notranslate position-relative overflow-auto"><pre class="notranslate"><code>&gt; scoop install reviewdog
</code></pre><div class="zeroclipboard-container">
    <clipboard-copy aria-label="Copy" class="ClipboardButton btn btn-invisible js-clipboard-copy m-2 p-0 tooltipped-no-delay d-flex flex-justify-center flex-items-center" data-copy-feedback="Copied!" data-tooltip-direction="w" value="> scoop install reviewdog" tabindex="0" role="button">
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-copy js-clipboard-copy-icon">
    <path d="M0 6.75C0 5.784.784 5 1.75 5h1.5a.75.75 0 0 1 0 1.5h-1.5a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-1.5a.75.75 0 0 1 1.5 0v1.5A1.75 1.75 0 0 1 9.25 16h-7.5A1.75 1.75 0 0 1 0 14.25Z"></path><path d="M5 1.75C5 .784 5.784 0 6.75 0h7.5C15.216 0 16 .784 16 1.75v7.5A1.75 1.75 0 0 1 14.25 11h-7.5A1.75 1.75 0 0 1 5 9.25Zm1.75-.25a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-7.5a.25.25 0 0 0-.25-.25Z"></path>
</svg>
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-check js-clipboard-check-icon color-fg-success d-none">
    <path d="M13.78 4.22a.75.75 0 0 1 0 1.06l-7.25 7.25a.75.75 0 0 1-1.06 0L2.22 9.28a.751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018L6 10.94l6.72-6.72a.75.75 0 0 1 1.06 0Z"></path>
</svg>
    </clipboard-copy>
  </div></div>
<h3 tabindex="-1" dir="auto"><a id="user-content-build-with-go-install" class="anchor" aria-hidden="true" tabindex="-1" href="#build-with-go-install"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">使用 go install 构建</font></font></h3>
<div class="highlight highlight-source-shell notranslate position-relative overflow-auto" dir="auto"><pre>$ go install github.com/reviewdog/reviewdog/cmd/reviewdog@latest</pre><div class="zeroclipboard-container">
    <clipboard-copy aria-label="Copy" class="ClipboardButton btn btn-invisible js-clipboard-copy m-2 p-0 tooltipped-no-delay d-flex flex-justify-center flex-items-center" data-copy-feedback="Copied!" data-tooltip-direction="w" value="$ go install github.com/reviewdog/reviewdog/cmd/reviewdog@latest" tabindex="0" role="button">
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-copy js-clipboard-copy-icon">
    <path d="M0 6.75C0 5.784.784 5 1.75 5h1.5a.75.75 0 0 1 0 1.5h-1.5a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-1.5a.75.75 0 0 1 1.5 0v1.5A1.75 1.75 0 0 1 9.25 16h-7.5A1.75 1.75 0 0 1 0 14.25Z"></path><path d="M5 1.75C5 .784 5.784 0 6.75 0h7.5C15.216 0 16 .784 16 1.75v7.5A1.75 1.75 0 0 1 14.25 11h-7.5A1.75 1.75 0 0 1 5 9.25Zm1.75-.25a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-7.5a.25.25 0 0 0-.25-.25Z"></path>
</svg>
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-check js-clipboard-check-icon color-fg-success d-none">
    <path d="M13.78 4.22a.75.75 0 0 1 0 1.06l-7.25 7.25a.75.75 0 0 1-1.06 0L2.22 9.28a.751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018L6 10.94l6.72-6.72a.75.75 0 0 1 1.06 0Z"></path>
</svg>
    </clipboard-copy>
  </div></div>
<h2 tabindex="-1" dir="auto"><a id="user-content-input-format" class="anchor" aria-hidden="true" tabindex="-1" href="#input-format"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">输入格式</font></font></h2>
<h3 tabindex="-1" dir="auto"><a id="user-content-errorformat" class="anchor" aria-hidden="true" tabindex="-1" href="#errorformat"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">'错误格式'</font></font></h3>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">reviewdog 接受来自 stdin 的任何编译器或 linter 结果，并使用 scan-f 解析它，如</font></font><a href="https://github.com/reviewdog/errorformat"><strong><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">'errorformat'</font></font></strong></a><font style="vertical-align: inherit;"></font><a href="https://vim-jp.org/vimdoc-en/quickfix.html#error-file-format" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;"> ，这是 Vim 的errorformat</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">功能的端口</font><font style="vertical-align: inherit;">
。</font></font></p>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">例如，如果结果格式为</font></font><code>{file}:{line number}:{column number}: {message}</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">，则错误格式应为</font></font><code>%f:%l:%c: %m</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">，并且您可以将其作为</font></font><code>-efm</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">参数传递。</font></font></p>
<div class="highlight highlight-source-shell notranslate position-relative overflow-auto" dir="auto"><pre>$ golint ./...
comment_iowriter.go:11:6: exported <span class="pl-c1">type</span> CommentWriter should have comment or be unexported
$ golint ./... <span class="pl-k">|</span> reviewdog -efm=<span class="pl-s"><span class="pl-pds">"</span>%f:%l:%c: %m<span class="pl-pds">"</span></span> -diff=<span class="pl-s"><span class="pl-pds">"</span>git diff FETCH_HEAD<span class="pl-pds">"</span></span></pre><div class="zeroclipboard-container">
    <clipboard-copy aria-label="Copy" class="ClipboardButton btn btn-invisible js-clipboard-copy m-2 p-0 tooltipped-no-delay d-flex flex-justify-center flex-items-center" data-copy-feedback="Copied!" data-tooltip-direction="w" value="$ golint ./...
comment_iowriter.go:11:6: exported type CommentWriter should have comment or be unexported
$ golint ./... | reviewdog -efm=&quot;%f:%l:%c: %m&quot; -diff=&quot;git diff FETCH_HEAD&quot;" tabindex="0" role="button">
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-copy js-clipboard-copy-icon">
    <path d="M0 6.75C0 5.784.784 5 1.75 5h1.5a.75.75 0 0 1 0 1.5h-1.5a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-1.5a.75.75 0 0 1 1.5 0v1.5A1.75 1.75 0 0 1 9.25 16h-7.5A1.75 1.75 0 0 1 0 14.25Z"></path><path d="M5 1.75C5 .784 5.784 0 6.75 0h7.5C15.216 0 16 .784 16 1.75v7.5A1.75 1.75 0 0 1 14.25 11h-7.5A1.75 1.75 0 0 1 5 9.25Zm1.75-.25a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-7.5a.25.25 0 0 0-.25-.25Z"></path>
</svg>
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-check js-clipboard-check-icon color-fg-success d-none">
    <path d="M13.78 4.22a.75.75 0 0 1 0 1.06l-7.25 7.25a.75.75 0 0 1-1.06 0L2.22 9.28a.751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018L6 10.94l6.72-6.72a.75.75 0 0 1 1.06 0Z"></path>
</svg>
    </clipboard-copy>
  </div></div>
<table>
<thead>
<tr>
<th><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">姓名</font></font></th>
<th><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">描述</font></font></th>
</tr>
</thead>
<tbody>
<tr>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">％F</font></font></td>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">文件名</font></font></td>
</tr>
<tr>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">%l</font></font></td>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">电话号码</font></font></td>
</tr>
<tr>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">％C</font></font></td>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">列号</font></font></td>
</tr>
<tr>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">%m</font></font></td>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">错误信息</font></font></td>
</tr>
<tr>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">%%</font></font></td>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">单个“%”字符</font></font></td>
</tr>
<tr>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">...</font></font></td>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">...</font></font></td>
</tr>
</tbody>
</table>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">
如果您想处理更复杂的输出，</font><font style="vertical-align: inherit;">请参阅</font></font><a href="https://github.com/reviewdog/errorformat"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">reviewdog/errorformat</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">
和</font></font><a href="https://vim-jp.org/vimdoc-en/quickfix.html#error-file-format" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">:h errorformat 。</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">'errorformat' 可以处理更复杂的输出，例如多行错误消息。</font></font></p>
<p dir="auto"><font style="vertical-align: inherit;"></font><a href="https://reviewdog.github.io/errorformat-playground/" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">您还可以在Playground</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">上尝试 errorformat </font><font style="vertical-align: inherit;">！</font></font></p>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">借助此“错误格式”功能，reviewdog 可以轻松支持任何工具输出。</font></font></p>
<h3 tabindex="-1" dir="auto"><a id="user-content-available-pre-defined-errorformat" class="anchor" aria-hidden="true" tabindex="-1" href="#available-pre-defined-errorformat"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">可用的预定义“错误格式”</font></font></h3>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">但是，在许多情况下您不必编写“errorformat”。</font><font style="vertical-align: inherit;">reviewdog 支持主要工具的预定义错误格式。</font></font></p>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">您可以通过 找到可用的错误格式名称，</font></font><code>reviewdog -list</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">并且可以将其与 一起使用</font></font><code>-f={name}</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">。</font></font></p>
<div class="highlight highlight-source-shell notranslate position-relative overflow-auto" dir="auto"><pre>$ reviewdog -list
golint          linter <span class="pl-k">for</span> Go <span class="pl-c1">source</span> code                                       - https://github.com/golang/lint
govet           Vet examines Go <span class="pl-c1">source</span> code and reports suspicious problems     - https://golang.org/cmd/vet/
sbt             the interactive build tool                                      - http://www.scala-sbt.org/
...</pre><div class="zeroclipboard-container">
    <clipboard-copy aria-label="Copy" class="ClipboardButton btn btn-invisible js-clipboard-copy m-2 p-0 tooltipped-no-delay d-flex flex-justify-center flex-items-center" data-copy-feedback="Copied!" data-tooltip-direction="w" value="$ reviewdog -list
golint          linter for Go source code                                       - https://github.com/golang/lint
govet           Vet examines Go source code and reports suspicious problems     - https://golang.org/cmd/vet/
sbt             the interactive build tool                                      - http://www.scala-sbt.org/
..." tabindex="0" role="button">
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-copy js-clipboard-copy-icon">
    <path d="M0 6.75C0 5.784.784 5 1.75 5h1.5a.75.75 0 0 1 0 1.5h-1.5a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-1.5a.75.75 0 0 1 1.5 0v1.5A1.75 1.75 0 0 1 9.25 16h-7.5A1.75 1.75 0 0 1 0 14.25Z"></path><path d="M5 1.75C5 .784 5.784 0 6.75 0h7.5C15.216 0 16 .784 16 1.75v7.5A1.75 1.75 0 0 1 14.25 11h-7.5A1.75 1.75 0 0 1 5 9.25Zm1.75-.25a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-7.5a.25.25 0 0 0-.25-.25Z"></path>
</svg>
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-check js-clipboard-check-icon color-fg-success d-none">
    <path d="M13.78 4.22a.75.75 0 0 1 0 1.06l-7.25 7.25a.75.75 0 0 1-1.06 0L2.22 9.28a.751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018L6 10.94l6.72-6.72a.75.75 0 0 1 1.06 0Z"></path>
</svg>
    </clipboard-copy>
  </div></div>
<div class="highlight highlight-source-shell notranslate position-relative overflow-auto" dir="auto"><pre>$ golint ./... <span class="pl-k">|</span> reviewdog -f=golint -diff=<span class="pl-s"><span class="pl-pds">"</span>git diff FETCH_HEAD<span class="pl-pds">"</span></span></pre><div class="zeroclipboard-container">
    <clipboard-copy aria-label="Copy" class="ClipboardButton btn btn-invisible js-clipboard-copy m-2 p-0 tooltipped-no-delay d-flex flex-justify-center flex-items-center" data-copy-feedback="Copied!" data-tooltip-direction="w" value="$ golint ./... | reviewdog -f=golint -diff=&quot;git diff FETCH_HEAD&quot;" tabindex="0" role="button">
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-copy js-clipboard-copy-icon">
    <path d="M0 6.75C0 5.784.784 5 1.75 5h1.5a.75.75 0 0 1 0 1.5h-1.5a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-1.5a.75.75 0 0 1 1.5 0v1.5A1.75 1.75 0 0 1 9.25 16h-7.5A1.75 1.75 0 0 1 0 14.25Z"></path><path d="M5 1.75C5 .784 5.784 0 6.75 0h7.5C15.216 0 16 .784 16 1.75v7.5A1.75 1.75 0 0 1 14.25 11h-7.5A1.75 1.75 0 0 1 5 9.25Zm1.75-.25a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-7.5a.25.25 0 0 0-.25-.25Z"></path>
</svg>
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-check js-clipboard-check-icon color-fg-success d-none">
    <path d="M13.78 4.22a.75.75 0 0 1 0 1.06l-7.25 7.25a.75.75 0 0 1-1.06 0L2.22 9.28a.751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018L6 10.94l6.72-6.72a.75.75 0 0 1 1.06 0Z"></path>
</svg>
    </clipboard-copy>
  </div></div>
<p dir="auto"><font style="vertical-align: inherit;"><a href="https://github.com/reviewdog/errorformat"><font style="vertical-align: inherit;">您可以通过向reviewdog/errorformat</font></a><font style="vertical-align: inherit;">做出贡献来添加受支持的预定义“errorformat”</font></font><a href="https://github.com/reviewdog/errorformat"><font style="vertical-align: inherit;"></font></a></p>
<h3 tabindex="-1" dir="auto"><a id="user-content-reviewdog-diagnostic-format-rdformat" class="anchor" aria-hidden="true" tabindex="-1" href="#reviewdog-diagnostic-format-rdformat"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Reviewdog 诊断格式 (RDFormat)</font></font></h3>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">reviewdog 支持</font></font><a href="/reviewdog/reviewdog/blob/master/proto/rdf"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Reviewdog 诊断格式 (RDFormat)</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">作为通用诊断格式，并且支持</font></font><a href="/reviewdog/reviewdog/blob/master/proto/rdf/#rdjson"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">rdjson</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">和
</font></font><a href="/reviewdog/reviewdog/blob/master/proto/rdf/#rdjsonl"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">rdjsonl</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">格式。</font></font></p>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">此 rdformat 支持丰富的功能，例如多行范围注释、严重性、带有 URL 的规则代码和</font></font><a href="#code-suggestions"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">代码建议</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">。</font></font></p>
<div class="highlight highlight-source-shell notranslate position-relative overflow-auto" dir="auto"><pre>$ <span class="pl-k">&lt;</span>linter<span class="pl-k">&gt;</span> <span class="pl-k">|</span> <span class="pl-k">&lt;</span>convert-to-rdjson<span class="pl-k">&gt;</span> <span class="pl-k">|</span> reviewdog -f=rdjson -reporter=github-pr-review
<span class="pl-c"><span class="pl-c">#</span> or</span>
$ <span class="pl-k">&lt;</span>linter<span class="pl-k">&gt;</span> <span class="pl-k">|</span> <span class="pl-k">&lt;</span>convert-to-rdjsonl<span class="pl-k">&gt;</span> <span class="pl-k">|</span> reviewdog -f=rdjsonl -reporter=github-pr-review</pre><div class="zeroclipboard-container">
    <clipboard-copy aria-label="Copy" class="ClipboardButton btn btn-invisible js-clipboard-copy m-2 p-0 tooltipped-no-delay d-flex flex-justify-center flex-items-center" data-copy-feedback="Copied!" data-tooltip-direction="w" value="$ <linter> | <convert-to-rdjson> | reviewdog -f=rdjson -reporter=github-pr-review
# or
$ <linter> | <convert-to-rdjsonl> | reviewdog -f=rdjsonl -reporter=github-pr-review" tabindex="0" role="button">
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-copy js-clipboard-copy-icon">
    <path d="M0 6.75C0 5.784.784 5 1.75 5h1.5a.75.75 0 0 1 0 1.5h-1.5a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-1.5a.75.75 0 0 1 1.5 0v1.5A1.75 1.75 0 0 1 9.25 16h-7.5A1.75 1.75 0 0 1 0 14.25Z"></path><path d="M5 1.75C5 .784 5.784 0 6.75 0h7.5C15.216 0 16 .784 16 1.75v7.5A1.75 1.75 0 0 1 14.25 11h-7.5A1.75 1.75 0 0 1 5 9.25Zm1.75-.25a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-7.5a.25.25 0 0 0-.25-.25Z"></path>
</svg>
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-check js-clipboard-check-icon color-fg-success d-none">
    <path d="M13.78 4.22a.75.75 0 0 1 0 1.06l-7.25 7.25a.75.75 0 0 1-1.06 0L2.22 9.28a.751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018L6 10.94l6.72-6.72a.75.75 0 0 1 1.06 0Z"></path>
</svg>
    </clipboard-copy>
  </div></div>
<h4 tabindex="-1" dir="auto"><a id="user-content-example-eslint-with-rdformat" class="anchor" aria-hidden="true" tabindex="-1" href="#example-eslint-with-rdformat"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">示例：带有 RDFormat 的 ESLint</font></font></h4>
<p dir="auto"><a target="_blank" rel="noopener noreferrer nofollow" href="https://user-images.githubusercontent.com/3797062/97085944-87233a80-165b-11eb-94a8-0a47d5e24905.png"><img src="https://user-images.githubusercontent.com/3797062/97085944-87233a80-165b-11eb-94a8-0a47d5e24905.png" alt="eslint reviewdog rdjson 演示" style="max-width: 100%;"></a></p>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">您可以使用</font></font><a href="https://www.npmjs.com/package/eslint-formatter-rdjson" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">eslint-formatter-rdjson</font></font></a><font style="vertical-align: inherit;"></font><code>rdjson</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">以 eslint 输出格式</font><font style="vertical-align: inherit;">
输出。</font></font></p>
<div class="highlight highlight-source-shell notranslate position-relative overflow-auto" dir="auto"><pre>$ npm install --save-dev eslint-formatter-rdjson
$ eslint -f rdjson <span class="pl-c1">.</span> <span class="pl-k">|</span> reviewdog -f=rdjson -reporter=github-pr-review</pre><div class="zeroclipboard-container">
    <clipboard-copy aria-label="Copy" class="ClipboardButton btn btn-invisible js-clipboard-copy m-2 p-0 tooltipped-no-delay d-flex flex-justify-center flex-items-center" data-copy-feedback="Copied!" data-tooltip-direction="w" value="$ npm install --save-dev eslint-formatter-rdjson
$ eslint -f rdjson . | reviewdog -f=rdjson -reporter=github-pr-review" tabindex="0" role="button">
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-copy js-clipboard-copy-icon">
    <path d="M0 6.75C0 5.784.784 5 1.75 5h1.5a.75.75 0 0 1 0 1.5h-1.5a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-1.5a.75.75 0 0 1 1.5 0v1.5A1.75 1.75 0 0 1 9.25 16h-7.5A1.75 1.75 0 0 1 0 14.25Z"></path><path d="M5 1.75C5 .784 5.784 0 6.75 0h7.5C15.216 0 16 .784 16 1.75v7.5A1.75 1.75 0 0 1 14.25 11h-7.5A1.75 1.75 0 0 1 5 9.25Zm1.75-.25a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-7.5a.25.25 0 0 0-.25-.25Z"></path>
</svg>
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-check js-clipboard-check-icon color-fg-success d-none">
    <path d="M13.78 4.22a.75.75 0 0 1 0 1.06l-7.25 7.25a.75.75 0 0 1-1.06 0L2.22 9.28a.751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018L6 10.94l6.72-6.72a.75.75 0 0 1 1.06 0Z"></path>
</svg>
    </clipboard-copy>
  </div></div>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">或者您也可以使用</font></font><a href="https://github.com/reviewdog/action-eslint"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">reviewdog/action-eslint</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">进行 GitHub Actions。</font></font></p>
<h3 tabindex="-1" dir="auto"><a id="user-content-diff" class="anchor" aria-hidden="true" tabindex="-1" href="#diff"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">差异</font></font></h3>
<p dir="auto"><a target="_blank" rel="noopener noreferrer nofollow" href="https://user-images.githubusercontent.com/3797062/89168305-a3ad5a80-d5b7-11ea-8939-be7ac1976d30.png"><img src="https://user-images.githubusercontent.com/3797062/89168305-a3ad5a80-d5b7-11ea-8939-be7ac1976d30.png" alt="以 gofmt 为例进行 reviewdog" style="max-width: 100%;"></a></p>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">reviewdog 支持 diff（统一格式）作为输入格式，对于</font></font><a href="#code-suggestions"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">代码建议</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">特别有用。</font><font style="vertical-align: inherit;">reviewdog 可以与任何代码建议工具或格式化程序集成以报告建议。</font></font></p>
<p dir="auto"><code>-f.diff.strip</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">：选项</font></font><code>-f=diff</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">：从 diff 文件名中删除 NUM 个前导组件（相当于“patch -p”）（对于 git diff 默认为 1）（默认为 1）</font></font></p>
<div class="highlight highlight-source-shell notranslate position-relative overflow-auto" dir="auto"><pre>$ <span class="pl-k">&lt;</span>any-code-fixer/formatter<span class="pl-k">&gt;</span> <span class="pl-c"><span class="pl-c">#</span> e.g. eslint --fix, gofmt</span>
$ TMPFILE=<span class="pl-s"><span class="pl-pds">$(</span>mktemp<span class="pl-pds">)</span></span>
$ git diff <span class="pl-k">&gt;</span><span class="pl-s"><span class="pl-pds">"</span><span class="pl-smi">${TMPFILE}</span><span class="pl-pds">"</span></span>
$ git stash -u <span class="pl-k">&amp;&amp;</span> git stash drop
$ reviewdog -f=diff -f.diff.strip=1 -reporter=github-pr-review <span class="pl-k">&lt;</span> <span class="pl-s"><span class="pl-pds">"</span><span class="pl-smi">${TMPFILE}</span><span class="pl-pds">"</span></span></pre><div class="zeroclipboard-container">
    <clipboard-copy aria-label="Copy" class="ClipboardButton btn btn-invisible js-clipboard-copy m-2 p-0 tooltipped-no-delay d-flex flex-justify-center flex-items-center" data-copy-feedback="Copied!" data-tooltip-direction="w" value="$ <any-code-fixer/formatter> # e.g. eslint --fix, gofmt
$ TMPFILE=$(mktemp)
$ git diff >&quot;${TMPFILE}&quot;
$ git stash -u &amp;&amp; git stash drop
$ reviewdog -f=diff -f.diff.strip=1 -reporter=github-pr-review < &quot;${TMPFILE}&quot;" tabindex="0" role="button">
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-copy js-clipboard-copy-icon">
    <path d="M0 6.75C0 5.784.784 5 1.75 5h1.5a.75.75 0 0 1 0 1.5h-1.5a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-1.5a.75.75 0 0 1 1.5 0v1.5A1.75 1.75 0 0 1 9.25 16h-7.5A1.75 1.75 0 0 1 0 14.25Z"></path><path d="M5 1.75C5 .784 5.784 0 6.75 0h7.5C15.216 0 16 .784 16 1.75v7.5A1.75 1.75 0 0 1 14.25 11h-7.5A1.75 1.75 0 0 1 5 9.25Zm1.75-.25a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-7.5a.25.25 0 0 0-.25-.25Z"></path>
</svg>
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-check js-clipboard-check-icon color-fg-success d-none">
    <path d="M13.78 4.22a.75.75 0 0 1 0 1.06l-7.25 7.25a.75.75 0 0 1-1.06 0L2.22 9.28a.751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018L6 10.94l6.72-6.72a.75.75 0 0 1 1.06 0Z"></path>
</svg>
    </clipboard-copy>
  </div></div>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">或者，您也可以使用</font></font><a href="https://github.com/reviewdog/action-suggester"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">reviewdog/action-suggester</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">进行 GitHub Actions。</font></font></p>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">如果诊断工具支持 diff 输出格式，您可以直接通过管道传输 diff。</font></font></p>
<div class="highlight highlight-source-shell notranslate position-relative overflow-auto" dir="auto"><pre>$ gofmt -s -d <span class="pl-c1">.</span> <span class="pl-k">|</span> reviewdog -name=<span class="pl-s"><span class="pl-pds">"</span>gofmt<span class="pl-pds">"</span></span> -f=diff -f.diff.strip=0 -reporter=github-pr-review
$ shellcheck -f diff <span class="pl-s"><span class="pl-pds">$(</span>shfmt -f .<span class="pl-pds">)</span></span> <span class="pl-k">|</span> reviewdog -f=diff</pre><div class="zeroclipboard-container">
    <clipboard-copy aria-label="Copy" class="ClipboardButton btn btn-invisible js-clipboard-copy m-2 p-0 tooltipped-no-delay d-flex flex-justify-center flex-items-center" data-copy-feedback="Copied!" data-tooltip-direction="w" value="$ gofmt -s -d . | reviewdog -name=&quot;gofmt&quot; -f=diff -f.diff.strip=0 -reporter=github-pr-review
$ shellcheck -f diff $(shfmt -f .) | reviewdog -f=diff" tabindex="0" role="button">
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-copy js-clipboard-copy-icon">
    <path d="M0 6.75C0 5.784.784 5 1.75 5h1.5a.75.75 0 0 1 0 1.5h-1.5a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-1.5a.75.75 0 0 1 1.5 0v1.5A1.75 1.75 0 0 1 9.25 16h-7.5A1.75 1.75 0 0 1 0 14.25Z"></path><path d="M5 1.75C5 .784 5.784 0 6.75 0h7.5C15.216 0 16 .784 16 1.75v7.5A1.75 1.75 0 0 1 14.25 11h-7.5A1.75 1.75 0 0 1 5 9.25Zm1.75-.25a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-7.5a.25.25 0 0 0-.25-.25Z"></path>
</svg>
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-check js-clipboard-check-icon color-fg-success d-none">
    <path d="M13.78 4.22a.75.75 0 0 1 0 1.06l-7.25 7.25a.75.75 0 0 1-1.06 0L2.22 9.28a.751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018L6 10.94l6.72-6.72a.75.75 0 0 1 1.06 0Z"></path>
</svg>
    </clipboard-copy>
  </div></div>
<h3 tabindex="-1" dir="auto"><a id="user-content-checkstyle-format" class="anchor" aria-hidden="true" tabindex="-1" href="#checkstyle-format"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">检查式格式</font></font></h3>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">reviewdog 还接受</font></font><a href="http://checkstyle.sourceforge.net/" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">checkstyle XML 格式</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">。</font><font style="vertical-align: inherit;">如果 linter 支持 checkstyle 格式作为报告格式，则可以使用 -f=checkstyle 而不是使用 'errorformat'。</font></font></p>
<div class="highlight highlight-source-shell notranslate position-relative overflow-auto" dir="auto"><pre><span class="pl-c"><span class="pl-c">#</span> Local</span>
$ eslint -f checkstyle <span class="pl-c1">.</span> <span class="pl-k">|</span> reviewdog -f=checkstyle -diff=<span class="pl-s"><span class="pl-pds">"</span>git diff<span class="pl-pds">"</span></span>

<span class="pl-c"><span class="pl-c">#</span> CI (overwrite tool name which is shown in review comment by -name arg)</span>
$ eslint -f checkstyle <span class="pl-c1">.</span> <span class="pl-k">|</span> reviewdog -f=checkstyle -name=<span class="pl-s"><span class="pl-pds">"</span>eslint<span class="pl-pds">"</span></span> -reporter=github-check</pre><div class="zeroclipboard-container">
    <clipboard-copy aria-label="Copy" class="ClipboardButton btn btn-invisible js-clipboard-copy m-2 p-0 tooltipped-no-delay d-flex flex-justify-center flex-items-center" data-copy-feedback="Copied!" data-tooltip-direction="w" value="# Local
$ eslint -f checkstyle . | reviewdog -f=checkstyle -diff=&quot;git diff&quot;

# CI (overwrite tool name which is shown in review comment by -name arg)
$ eslint -f checkstyle . | reviewdog -f=checkstyle -name=&quot;eslint&quot; -reporter=github-check" tabindex="0" role="button">
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-copy js-clipboard-copy-icon">
    <path d="M0 6.75C0 5.784.784 5 1.75 5h1.5a.75.75 0 0 1 0 1.5h-1.5a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-1.5a.75.75 0 0 1 1.5 0v1.5A1.75 1.75 0 0 1 9.25 16h-7.5A1.75 1.75 0 0 1 0 14.25Z"></path><path d="M5 1.75C5 .784 5.784 0 6.75 0h7.5C15.216 0 16 .784 16 1.75v7.5A1.75 1.75 0 0 1 14.25 11h-7.5A1.75 1.75 0 0 1 5 9.25Zm1.75-.25a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-7.5a.25.25 0 0 0-.25-.25Z"></path>
</svg>
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-check js-clipboard-check-icon color-fg-success d-none">
    <path d="M13.78 4.22a.75.75 0 0 1 0 1.06l-7.25 7.25a.75.75 0 0 1-1.06 0L2.22 9.28a.751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018L6 10.94l6.72-6.72a.75.75 0 0 1 1.06 0Z"></path>
</svg>
    </clipboard-copy>
  </div></div>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">另外，如果您想将其他 Json/XML/etc... 格式传递给 reviewdog，您可以编写一个转换器。</font></font></p>
<div class="highlight highlight-source-shell notranslate position-relative overflow-auto" dir="auto"><pre>$ <span class="pl-k">&lt;</span>linter<span class="pl-k">&gt;</span> <span class="pl-k">|</span> <span class="pl-k">&lt;</span>convert-to-checkstyle<span class="pl-k">&gt;</span> <span class="pl-k">|</span> reviewdog -f=checkstyle -name=<span class="pl-s"><span class="pl-pds">"</span>&lt;linter&gt;<span class="pl-pds">"</span></span> -reporter=github-pr-check</pre><div class="zeroclipboard-container">
    <clipboard-copy aria-label="Copy" class="ClipboardButton btn btn-invisible js-clipboard-copy m-2 p-0 tooltipped-no-delay d-flex flex-justify-center flex-items-center" data-copy-feedback="Copied!" data-tooltip-direction="w" value="$ <linter> | <convert-to-checkstyle> | reviewdog -f=checkstyle -name=&quot;<linter>&quot; -reporter=github-pr-check" tabindex="0" role="button">
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-copy js-clipboard-copy-icon">
    <path d="M0 6.75C0 5.784.784 5 1.75 5h1.5a.75.75 0 0 1 0 1.5h-1.5a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-1.5a.75.75 0 0 1 1.5 0v1.5A1.75 1.75 0 0 1 9.25 16h-7.5A1.75 1.75 0 0 1 0 14.25Z"></path><path d="M5 1.75C5 .784 5.784 0 6.75 0h7.5C15.216 0 16 .784 16 1.75v7.5A1.75 1.75 0 0 1 14.25 11h-7.5A1.75 1.75 0 0 1 5 9.25Zm1.75-.25a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-7.5a.25.25 0 0 0-.25-.25Z"></path>
</svg>
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-check js-clipboard-check-icon color-fg-success d-none">
    <path d="M13.78 4.22a.75.75 0 0 1 0 1.06l-7.25 7.25a.75.75 0 0 1-1.06 0L2.22 9.28a.751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018L6 10.94l6.72-6.72a.75.75 0 0 1 1.06 0Z"></path>
</svg>
    </clipboard-copy>
  </div></div>
<h3 tabindex="-1" dir="auto"><a id="user-content-sarif-format" class="anchor" aria-hidden="true" tabindex="-1" href="#sarif-format"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">SARIF 格式</font></font></h3>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">reviewdog 支持</font></font><a href="https://sarifweb.azurewebsites.net/" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">SARIF 2.1.0 JSON 格式</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">。</font><font style="vertical-align: inherit;">您可以将 reviewdog 与 -f=sarif 选项一起使用。</font></font></p>
<div class="highlight highlight-source-shell notranslate position-relative overflow-auto" dir="auto"><pre><span class="pl-c"><span class="pl-c">#</span> Local</span>
$ eslint -f @microsoft/eslint-formatter-sarif <span class="pl-c1">.</span> <span class="pl-k">|</span> reviewdog -f=sarif -diff=<span class="pl-s"><span class="pl-pds">"</span>git diff<span class="pl-pds">"</span></span></pre><div class="zeroclipboard-container">
    <clipboard-copy aria-label="Copy" class="ClipboardButton btn btn-invisible js-clipboard-copy m-2 p-0 tooltipped-no-delay d-flex flex-justify-center flex-items-center" data-copy-feedback="Copied!" data-tooltip-direction="w" value="# Local
$ eslint -f @microsoft/eslint-formatter-sarif . | reviewdog -f=sarif -diff=&quot;git diff&quot;" tabindex="0" role="button">
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-copy js-clipboard-copy-icon">
    <path d="M0 6.75C0 5.784.784 5 1.75 5h1.5a.75.75 0 0 1 0 1.5h-1.5a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-1.5a.75.75 0 0 1 1.5 0v1.5A1.75 1.75 0 0 1 9.25 16h-7.5A1.75 1.75 0 0 1 0 14.25Z"></path><path d="M5 1.75C5 .784 5.784 0 6.75 0h7.5C15.216 0 16 .784 16 1.75v7.5A1.75 1.75 0 0 1 14.25 11h-7.5A1.75 1.75 0 0 1 5 9.25Zm1.75-.25a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-7.5a.25.25 0 0 0-.25-.25Z"></path>
</svg>
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-check js-clipboard-check-icon color-fg-success d-none">
    <path d="M13.78 4.22a.75.75 0 0 1 0 1.06l-7.25 7.25a.75.75 0 0 1-1.06 0L2.22 9.28a.751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018L6 10.94l6.72-6.72a.75.75 0 0 1 1.06 0Z"></path>
</svg>
    </clipboard-copy>
  </div></div>
<h2 tabindex="-1" dir="auto"><a id="user-content-code-suggestions" class="anchor" aria-hidden="true" tabindex="-1" href="#code-suggestions"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">代码建议</font></font></h2>
<p dir="auto"><a target="_blank" rel="noopener noreferrer nofollow" href="https://user-images.githubusercontent.com/3797062/97085944-87233a80-165b-11eb-94a8-0a47d5e24905.png"><img src="https://user-images.githubusercontent.com/3797062/97085944-87233a80-165b-11eb-94a8-0a47d5e24905.png" alt="eslint reviewdog 建议演示" style="max-width: 100%;"></a>
<a target="_blank" rel="noopener noreferrer nofollow" href="https://user-images.githubusercontent.com/3797062/89168305-a3ad5a80-d5b7-11ea-8939-be7ac1976d30.png"><img src="https://user-images.githubusercontent.com/3797062/89168305-a3ad5a80-d5b7-11ea-8939-be7ac1976d30.png" alt="以 gofmt 为例进行 reviewdog" style="max-width: 100%;"></a></p>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">reviewdog 支持带有</font><a href="#reviewdog-diagnostic-format-rdformat"><font style="vertical-align: inherit;">rdformat</font></a><font style="vertical-align: inherit;">或</font><a href="#diff"><font style="vertical-align: inherit;">diff输入的</font></a></font><em><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">代码建议</font></font></em><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">功能</font><font style="vertical-align: inherit;">。</font><font style="vertical-align: inherit;">您还可以使用</font><a href="https://github.com/reviewdog/action-suggester"><font style="vertical-align: inherit;">reviewdog/action-suggester</font></a><font style="vertical-align: inherit;">进行 GitHub Actions。</font></font><a href="#reviewdog-diagnostic-format-rdformat"><font style="vertical-align: inherit;"></font></a><font style="vertical-align: inherit;"></font><a href="#diff"><font style="vertical-align: inherit;"></font></a><font style="vertical-align: inherit;"></font><a href="https://github.com/reviewdog/action-suggester"><font style="vertical-align: inherit;"></font></a><font style="vertical-align: inherit;"></font></p>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">如果诊断工具支持代码建议数据，则 reviewdog 可以建议代码更改以及诊断结果。</font><font style="vertical-align: inherit;">您可以将 reviewdog 与任何代码修复工具以及任何具有</font></font><a href="#diff"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">diff</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">输入的代码格式化程序集成。</font></font></p>
<h3 tabindex="-1" dir="auto"><a id="user-content-code-suggestions-support-table" class="anchor" aria-hidden="true" tabindex="-1" href="#code-suggestions-support-table"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">代码建议支持表</font></font></h3>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">请注意，并非所有报告者都提供对代码建议的支持。</font></font></p>
<table>
<thead>
<tr>
<th><code>-reporter</code></th>
<th><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">建议支持</font></font></th>
</tr>
</thead>
<tbody>
<tr>
<td><strong><code>local</code></strong></td>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">否 [1]</font></font></td>
</tr>
<tr>
<td><strong><code>github-check</code></strong></td>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">否 [2]</font></font></td>
</tr>
<tr>
<td><strong><code>github-pr-check</code></strong></td>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">否 [2]</font></font></td>
</tr>
<tr>
<td><strong><code>github-pr-review</code></strong></td>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">好的</font></font></td>
</tr>
<tr>
<td><strong><code>gitlab-mr-discussion</code></strong></td>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">好的</font></font></td>
</tr>
<tr>
<td><strong><code>gitlab-mr-commit</code></strong></td>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">否 [2]</font></font></td>
</tr>
<tr>
<td><strong><code>gerrit-change-review</code></strong></td>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">否 [1]</font></font></td>
</tr>
<tr>
<td><strong><code>bitbucket-code-report</code></strong></td>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">否 [2]</font></font></td>
</tr>
<tr>
<td><strong><code>gitea-pr-review</code></strong></td>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">否 [2]</font></font></td>
</tr>
</tbody>
</table>
<ul dir="auto">
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">[1] Reporter服务支持代码建议功能，但reviewdog尚不支持。</font><font style="vertical-align: inherit;">有关状态，</font><font style="vertical-align: inherit;">请参阅</font></font><a href="https://github.com/reviewdog/reviewdog/issues/678" data-hovercard-type="issue" data-hovercard-url="/reviewdog/reviewdog/issues/678/hovercard"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">#678 。</font></font></a><font style="vertical-align: inherit;"></font></li>
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">[2] 报告服务本身不支持代码建议功能。</font></font></li>
</ul>
<h2 tabindex="-1" dir="auto"><a id="user-content-reviewdog-config-file" class="anchor" aria-hidden="true" tabindex="-1" href="#reviewdog-config-file"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">审查狗配置文件</font></font></h2>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">reviewdog 还可以通过 .reviewdog.yml 配置文件而不是“-f”或“-efm”参数进行控制。</font></font></p>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">使用 .reviewdog.yml，您可以为 CI 服务和本地环境运行相同的命令，包括轻松地进行编辑器集成。</font></font></p>
<h4 tabindex="-1" dir="auto"><a id="user-content-reviewdogyml" class="anchor" aria-hidden="true" tabindex="-1" href="#reviewdogyml"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">.reviewdog.yml</font></font></h4>
<div class="highlight highlight-source-yaml notranslate position-relative overflow-auto" dir="auto"><pre><span class="pl-ent">runner</span>:
  <span class="pl-ent">&lt;tool-name&gt;</span>:
    <span class="pl-ent">cmd</span>: <span class="pl-s">&lt;command&gt; </span><span class="pl-c"><span class="pl-c">#</span> (required)</span>
    <span class="pl-ent">errorformat</span>: <span class="pl-c"><span class="pl-c">#</span> (optional if you use `format`)</span>
      - <span class="pl-s">&lt;list of errorformat&gt;</span>
    <span class="pl-ent">format</span>: <span class="pl-s">&lt;format-name&gt; </span><span class="pl-c"><span class="pl-c">#</span> (optional if you use `errorformat`. e.g. golint,rdjson,rdjsonl)</span>
    <span class="pl-ent">name</span>: <span class="pl-s">&lt;tool-name&gt; </span><span class="pl-c"><span class="pl-c">#</span> (optional. you can overwrite &lt;tool-name&gt; defined by runner key)</span>
    <span class="pl-ent">level</span>: <span class="pl-s">&lt;level&gt; </span><span class="pl-c"><span class="pl-c">#</span> (optional. same as -level flag. [info,warning,error])</span>

  <span class="pl-c"><span class="pl-c">#</span> examples</span>
  <span class="pl-ent">golint</span>:
    <span class="pl-ent">cmd</span>: <span class="pl-s">golint ./...</span>
    <span class="pl-ent">errorformat</span>:
      - <span class="pl-s"><span class="pl-pds">"</span>%f:%l:%c: %m<span class="pl-pds">"</span></span>
    <span class="pl-ent">level</span>: <span class="pl-s">warning</span>
  <span class="pl-ent">govet</span>:
    <span class="pl-ent">cmd</span>: <span class="pl-s">go vet -all .</span>
    <span class="pl-ent">format</span>: <span class="pl-s">govet</span>
  <span class="pl-ent">your-awesome-linter</span>:
    <span class="pl-ent">cmd</span>: <span class="pl-s">awesome-linter run</span>
    <span class="pl-ent">format</span>: <span class="pl-s">rdjson</span>
    <span class="pl-ent">name</span>: <span class="pl-s">AwesomeLinter</span></pre><div class="zeroclipboard-container">
    <clipboard-copy aria-label="Copy" class="ClipboardButton btn btn-invisible js-clipboard-copy m-2 p-0 tooltipped-no-delay d-flex flex-justify-center flex-items-center" data-copy-feedback="Copied!" data-tooltip-direction="w" value="runner:
  <tool-name>:
    cmd: <command> # (required)
    errorformat: # (optional if you use `format`)
      - <list of errorformat>
    format: <format-name> # (optional if you use `errorformat`. e.g. golint,rdjson,rdjsonl)
    name: <tool-name> # (optional. you can overwrite <tool-name> defined by runner key)
    level: <level> # (optional. same as -level flag. [info,warning,error])

  # examples
  golint:
    cmd: golint ./...
    errorformat:
      - &quot;%f:%l:%c: %m&quot;
    level: warning
  govet:
    cmd: go vet -all .
    format: govet
  your-awesome-linter:
    cmd: awesome-linter run
    format: rdjson
    name: AwesomeLinter" tabindex="0" role="button">
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-copy js-clipboard-copy-icon">
    <path d="M0 6.75C0 5.784.784 5 1.75 5h1.5a.75.75 0 0 1 0 1.5h-1.5a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-1.5a.75.75 0 0 1 1.5 0v1.5A1.75 1.75 0 0 1 9.25 16h-7.5A1.75 1.75 0 0 1 0 14.25Z"></path><path d="M5 1.75C5 .784 5.784 0 6.75 0h7.5C15.216 0 16 .784 16 1.75v7.5A1.75 1.75 0 0 1 14.25 11h-7.5A1.75 1.75 0 0 1 5 9.25Zm1.75-.25a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-7.5a.25.25 0 0 0-.25-.25Z"></path>
</svg>
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-check js-clipboard-check-icon color-fg-success d-none">
    <path d="M13.78 4.22a.75.75 0 0 1 0 1.06l-7.25 7.25a.75.75 0 0 1-1.06 0L2.22 9.28a.751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018L6 10.94l6.72-6.72a.75.75 0 0 1 1.06 0Z"></path>
</svg>
    </clipboard-copy>
  </div></div>
<div class="highlight highlight-source-shell notranslate position-relative overflow-auto" dir="auto"><pre>$ reviewdog -diff=<span class="pl-s"><span class="pl-pds">"</span>git diff FETCH_HEAD<span class="pl-pds">"</span></span>
project/run_test.go:61:28: [golint] error strings should not end with punctuation
project/run.go:57:18: [errcheck]        defer os.Setenv(name, os.Getenv(name))
project/run.go:58:12: [errcheck]        os.Setenv(name, <span class="pl-s"><span class="pl-pds">"</span><span class="pl-pds">"</span></span>)
<span class="pl-c"><span class="pl-c">#</span> You can use -runners to run only specified runners.</span>
$ reviewdog -diff=<span class="pl-s"><span class="pl-pds">"</span>git diff FETCH_HEAD<span class="pl-pds">"</span></span> -runners=golint,govet
project/run_test.go:61:28: [golint] error strings should not end with punctuation
<span class="pl-c"><span class="pl-c">#</span> You can use -conf to specify config file path.</span>
$ reviewdog -conf=./.reviewdog.yml -reporter=github-pr-check</pre><div class="zeroclipboard-container">
    <clipboard-copy aria-label="Copy" class="ClipboardButton btn btn-invisible js-clipboard-copy m-2 p-0 tooltipped-no-delay d-flex flex-justify-center flex-items-center" data-copy-feedback="Copied!" data-tooltip-direction="w" value="$ reviewdog -diff=&quot;git diff FETCH_HEAD&quot;
project/run_test.go:61:28: [golint] error strings should not end with punctuation
project/run.go:57:18: [errcheck]        defer os.Setenv(name, os.Getenv(name))
project/run.go:58:12: [errcheck]        os.Setenv(name, &quot;&quot;)
# You can use -runners to run only specified runners.
$ reviewdog -diff=&quot;git diff FETCH_HEAD&quot; -runners=golint,govet
project/run_test.go:61:28: [golint] error strings should not end with punctuation
# You can use -conf to specify config file path.
$ reviewdog -conf=./.reviewdog.yml -reporter=github-pr-check" tabindex="0" role="button">
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-copy js-clipboard-copy-icon">
    <path d="M0 6.75C0 5.784.784 5 1.75 5h1.5a.75.75 0 0 1 0 1.5h-1.5a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-1.5a.75.75 0 0 1 1.5 0v1.5A1.75 1.75 0 0 1 9.25 16h-7.5A1.75 1.75 0 0 1 0 14.25Z"></path><path d="M5 1.75C5 .784 5.784 0 6.75 0h7.5C15.216 0 16 .784 16 1.75v7.5A1.75 1.75 0 0 1 14.25 11h-7.5A1.75 1.75 0 0 1 5 9.25Zm1.75-.25a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-7.5a.25.25 0 0 0-.25-.25Z"></path>
</svg>
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-check js-clipboard-check-icon color-fg-success d-none">
    <path d="M13.78 4.22a.75.75 0 0 1 0 1.06l-7.25 7.25a.75.75 0 0 1-1.06 0L2.22 9.28a.751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018L6 10.94l6.72-6.72a.75.75 0 0 1 1.06 0Z"></path>
</svg>
    </clipboard-copy>
  </div></div>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">基于项目配置的运行的输出格式是以下格式之一。</font></font></p>
<ul dir="auto">
<li><code>&lt;file&gt;: [&lt;tool name&gt;] &lt;message&gt;</code></li>
<li><code>&lt;file&gt;:&lt;lnum&gt;: [&lt;tool name&gt;] &lt;message&gt;</code></li>
<li><code>&lt;file&gt;:&lt;lnum&gt;:&lt;col&gt;: [&lt;tool name&gt;] &lt;message&gt;</code></li>
</ul>
<h2 tabindex="-1" dir="auto"><a id="user-content-reporters" class="anchor" aria-hidden="true" tabindex="-1" href="#reporters"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">记者</font></font></h2>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">reviewdog 可以在本地环境中报告结果，并将审查服务作为持续集成。</font></font></p>
<h3 tabindex="-1" dir="auto"><a id="user-content-reporter-local--reporterlocal-default" class="anchor" aria-hidden="true" tabindex="-1" href="#reporter-local--reporterlocal-default"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">记者：本地（-reporter=local）[默认]</font></font></h3>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">reviewdog 可以通过使用 diff 过滤 linter 结果来找到新引入的发现。</font><font style="vertical-align: inherit;">您可以将 diff 命令作为</font></font><code>-diff</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">arg 传递。</font></font></p>
<div class="highlight highlight-source-shell notranslate position-relative overflow-auto" dir="auto"><pre>$ golint ./... <span class="pl-k">|</span> reviewdog -f=golint -diff=<span class="pl-s"><span class="pl-pds">"</span>git diff FETCH_HEAD<span class="pl-pds">"</span></span></pre><div class="zeroclipboard-container">
    <clipboard-copy aria-label="Copy" class="ClipboardButton btn btn-invisible js-clipboard-copy m-2 p-0 tooltipped-no-delay d-flex flex-justify-center flex-items-center" data-copy-feedback="Copied!" data-tooltip-direction="w" value="$ golint ./... | reviewdog -f=golint -diff=&quot;git diff FETCH_HEAD&quot;" tabindex="0" role="button">
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-copy js-clipboard-copy-icon">
    <path d="M0 6.75C0 5.784.784 5 1.75 5h1.5a.75.75 0 0 1 0 1.5h-1.5a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-1.5a.75.75 0 0 1 1.5 0v1.5A1.75 1.75 0 0 1 9.25 16h-7.5A1.75 1.75 0 0 1 0 14.25Z"></path><path d="M5 1.75C5 .784 5.784 0 6.75 0h7.5C15.216 0 16 .784 16 1.75v7.5A1.75 1.75 0 0 1 14.25 11h-7.5A1.75 1.75 0 0 1 5 9.25Zm1.75-.25a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-7.5a.25.25 0 0 0-.25-.25Z"></path>
</svg>
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-check js-clipboard-check-icon color-fg-success d-none">
    <path d="M13.78 4.22a.75.75 0 0 1 0 1.06l-7.25 7.25a.75.75 0 0 1-1.06 0L2.22 9.28a.751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018L6 10.94l6.72-6.72a.75.75 0 0 1 1.06 0Z"></path>
</svg>
    </clipboard-copy>
  </div></div>
<h3 tabindex="-1" dir="auto"><a id="user-content-reporter-github-checks--reportergithub-pr-check" class="anchor" aria-hidden="true" tabindex="-1" href="#reporter-github-checks--reportergithub-pr-check"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">记者：GitHub 检查 (-reporter=github-pr-check)</font></font></h3>
<p dir="auto"><a href="https://github.com/reviewdog/reviewdog/pull/275/files#annotation_6177941961779419"><img src="https://user-images.githubusercontent.com/3797062/64875597-65016f80-d688-11e9-843f-4679fb666f0d.png" alt="github-pr-check 带有选项 1 的示例注释" style="max-width: 100%;"></a>
<a href="https://github.com/reviewdog/reviewdog/pull/131/checks"><img src="https://user-images.githubusercontent.com/3797062/40884858-6efd82a0-6756-11e8-9f1a-c6af4f920fb0.png" alt="github-pr-检查示例" style="max-width: 100%;"></a></p>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">github-pr-check 记者向</font></font><a href="https://docs.github.com/en/pull-requests/collaborating-with-pull-requests/collaborating-on-repositories-with-code-quality-features/about-status-checks"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">GitHub Checks</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">报告结果。</font></font></p>
<p dir="auto"><font style="vertical-align: inherit;"><a href="#reviewdog-config-file"><font style="vertical-align: inherit;">您可以通过配置文件</font></a><font style="vertical-align: inherit;">或标志</font></font><code>level</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">中的字段</font><font style="vertical-align: inherit;">更改此记者的报告级别</font><font style="vertical-align: inherit;">。</font><font style="vertical-align: inherit;">您可以使用此功能控制 GitHub 状态检查结果。</font><font style="vertical-align: inherit;">（默认值：错误）</font></font><a href="#reviewdog-config-file"><font style="vertical-align: inherit;"></font></a><font style="vertical-align: inherit;"></font><code>-level</code><font style="vertical-align: inherit;"></font></p>
<table>
<thead>
<tr>
<th><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">等级</font></font></th>
<th><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">GitHub 状态</font></font></th>
</tr>
</thead>
<tbody>
<tr>
<td><code>info</code></td>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">中性的</font></font></td>
</tr>
<tr>
<td><code>warning</code></td>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">中性的</font></font></td>
</tr>
<tr>
<td><code>error</code></td>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">失败</font></font></td>
</tr>
</tbody>
</table>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">使用此报告器有两种选择。</font></font></p>
<h4 tabindex="-1" dir="auto"><a id="user-content-option-1-run-reviewdog-from-github-actions-w-secretsgithub_token" class="anchor" aria-hidden="true" tabindex="-1" href="#option-1-run-reviewdog-from-github-actions-w-secretsgithub_token"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">选项 1) 从 GitHub Actions 运行 reviewdog w/secrets.GITHUB_TOKEN</font></font></h4>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">示例：</font></font><a href="/reviewdog/reviewdog/blob/master/.github/workflows/reviewdog.yml"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">.github/workflows/reviewdog.yml</font></font></a></p>
<div class="highlight highlight-source-yaml notranslate position-relative overflow-auto" dir="auto"><pre>- <span class="pl-ent">name</span>: <span class="pl-s">Run reviewdog</span>
  <span class="pl-ent">env</span>:
    <span class="pl-ent">REVIEWDOG_GITHUB_API_TOKEN</span>: <span class="pl-s">${{ secrets.GITHUB_TOKEN }}</span>
  <span class="pl-ent">run</span>: <span class="pl-s">|</span>
<span class="pl-s">    golint ./... | reviewdog -f=golint -reporter=github-pr-check</span></pre><div class="zeroclipboard-container">
    <clipboard-copy aria-label="Copy" class="ClipboardButton btn btn-invisible js-clipboard-copy m-2 p-0 tooltipped-no-delay d-flex flex-justify-center flex-items-center" data-copy-feedback="Copied!" data-tooltip-direction="w" value="- name: Run reviewdog
  env:
    REVIEWDOG_GITHUB_API_TOKEN: ${{ secrets.GITHUB_TOKEN }}
  run: |
    golint ./... | reviewdog -f=golint -reporter=github-pr-check" tabindex="0" role="button">
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-copy js-clipboard-copy-icon">
    <path d="M0 6.75C0 5.784.784 5 1.75 5h1.5a.75.75 0 0 1 0 1.5h-1.5a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-1.5a.75.75 0 0 1 1.5 0v1.5A1.75 1.75 0 0 1 9.25 16h-7.5A1.75 1.75 0 0 1 0 14.25Z"></path><path d="M5 1.75C5 .784 5.784 0 6.75 0h7.5C15.216 0 16 .784 16 1.75v7.5A1.75 1.75 0 0 1 14.25 11h-7.5A1.75 1.75 0 0 1 5 9.25Zm1.75-.25a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-7.5a.25.25 0 0 0-.25-.25Z"></path>
</svg>
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-check js-clipboard-check-icon color-fg-success d-none">
    <path d="M13.78 4.22a.75.75 0 0 1 0 1.06l-7.25 7.25a.75.75 0 0 1-1.06 0L2.22 9.28a.751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018L6 10.94l6.72-6.72a.75.75 0 0 1 1.06 0Z"></path>
</svg>
    </clipboard-copy>
  </div></div>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">另请参阅</font></font><a href="#github-actions"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">GitHub Actions</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">部分。</font><font style="vertical-align: inherit;">您还可以使用公共评审狗 GitHub Actions。</font></font></p>
<h4 tabindex="-1" dir="auto"><a id="user-content-option-2-install-reviewdog-github-apps" class="anchor" aria-hidden="true" tabindex="-1" href="#option-2-install-reviewdog-github-apps"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">选项 2) 安装 reviewdog GitHub 应用程序</font></font></h4>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">reviewdog CLI 向 reviewdog GitHub App 服务器发送请求，服务器将结果发布为 GitHub Checks，因为 Check API 仅支持 GitHub App 和 GitHub Actions。</font></font></p>
<ol dir="auto">
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">安装reviewdog应用程序。</font></font><a href="https://github.com/apps/reviewdog"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">https://github.com/apps/reviewdog</font></font></a></li>
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">在受信任的 CI 提供商中设置</font></font><code>REVIEWDOG_TOKEN</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">或运行 reviewdog CLI。</font></font></li>
</ol>
<ul dir="auto">
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">从 获取令牌</font></font><code>https://reviewdog.app/gh/{owner}/{repo-name}</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">。</font></font></li>
</ul>
<div class="highlight highlight-source-shell notranslate position-relative overflow-auto" dir="auto"><pre>$ <span class="pl-k">export</span> REVIEWDOG_TOKEN=<span class="pl-s"><span class="pl-pds">"</span>&lt;token&gt;<span class="pl-pds">"</span></span>
$ reviewdog -reporter=github-pr-check</pre><div class="zeroclipboard-container">
    <clipboard-copy aria-label="Copy" class="ClipboardButton btn btn-invisible js-clipboard-copy m-2 p-0 tooltipped-no-delay d-flex flex-justify-center flex-items-center" data-copy-feedback="Copied!" data-tooltip-direction="w" value="$ export REVIEWDOG_TOKEN=&quot;<token>&quot;
$ reviewdog -reporter=github-pr-check" tabindex="0" role="button">
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-copy js-clipboard-copy-icon">
    <path d="M0 6.75C0 5.784.784 5 1.75 5h1.5a.75.75 0 0 1 0 1.5h-1.5a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-1.5a.75.75 0 0 1 1.5 0v1.5A1.75 1.75 0 0 1 9.25 16h-7.5A1.75 1.75 0 0 1 0 14.25Z"></path><path d="M5 1.75C5 .784 5.784 0 6.75 0h7.5C15.216 0 16 .784 16 1.75v7.5A1.75 1.75 0 0 1 14.25 11h-7.5A1.75 1.75 0 0 1 5 9.25Zm1.75-.25a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-7.5a.25.25 0 0 0-.25-.25Z"></path>
</svg>
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-check js-clipboard-check-icon color-fg-success d-none">
    <path d="M13.78 4.22a.75.75 0 0 1 0 1.06l-7.25 7.25a.75.75 0 0 1-1.06 0L2.22 9.28a.751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018L6 10.94l6.72-6.72a.75.75 0 0 1 1.06 0Z"></path>
</svg>
    </clipboard-copy>
  </div></div>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">注意：如果您在 Travis 或 AppVeyor 中运行 reviewdog，则不需要令牌。</font></font></p>
<p dir="auto"><em><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">警告</font></font></em></p>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">如上所述，具有选项 2 的 github-pr-check 记者依赖于 reviewdog GitHub App 服务器。</font><font style="vertical-align: inherit;">服务器目前是用haya14busa的零用钱运行的，我可能会弄坏东西，所以我不能保证服务器365天24小时运行。</font></font></p>
<p dir="auto"><strong><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">更新：</font></font></strong><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">开始获得</font></font><a href="https://opencollective.com/reviewdog" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">opencollective</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">
和 GitHub 赞助商的支持。</font><font style="vertical-align: inherit;">请参阅</font></font><a href="#supporting-reviewdog"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">支持 reviewdog</font></font></a></p>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">如果您不想依赖 reviewdog 服务器，可以使用 github-pr-review reports 或使用 GitHub Actions 下的 run reviewdog。</font></font></p>
<h3 tabindex="-1" dir="auto"><a id="user-content-reporter-github-checks--reportergithub-check" class="anchor" aria-hidden="true" tabindex="-1" href="#reporter-github-checks--reportergithub-check"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">记者：GitHub 检查 (-reporter=github-check)</font></font></h3>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">它基本上是相同的，</font></font><code>-reporter=github-pr-check</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">只是它不仅适用于 Pull Request，还适用于提交。</font></font></p>
<p dir="auto"><a href="https://github.com/reviewdog/reviewdog/pull/364/files"><img src="https://user-images.githubusercontent.com/3797062/69917921-e0680580-14ae-11ea-9a56-de9e3cbac005.png" alt="diff 之外的示例注释" style="max-width: 100%;"></a></p>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">您可以</font><font style="vertical-align: inherit;">为此记者创建</font></font><a href="#reviewdog-badge-"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">评论狗徽章。</font></font></a><font style="vertical-align: inherit;"></font></p>
<h3 tabindex="-1" dir="auto"><a id="user-content-reporter-github-pullrequest-review-comment--reportergithub-pr-review" class="anchor" aria-hidden="true" tabindex="-1" href="#reporter-github-pullrequest-review-comment--reportergithub-pr-review"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">记者：GitHub PullRequest 审核评论 (-reporter=github-pr-review)</font></font></h3>
<p dir="auto"><a href="https://github.com/reviewdog/reviewdog/pull/24#discussion_r84599728" data-hovercard-type="pull_request" data-hovercard-url="/reviewdog/reviewdog/pull/24/hovercard"><img src="https://raw.githubusercontent.com/haya14busa/i/dc0ccb1e110515ea407c146d99b749018db05c45/reviewdog/sample-comment.png" alt="样本评论.png" style="max-width: 100%;"></a></p>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">github-pr-review 记者使用 GitHub 个人 API 访问令牌向 GitHub PullRequest 审核评论报告结果。
</font></font><a href="https://github.com/enterprise"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">GitHub Enterprise</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">也受支持。</font></font></p>
<ul dir="auto">
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">转到</font></font><a href="https://github.com/settings/tokens"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">https://github.com/settings/tokens</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">并生成新的 API 令牌。</font></font></li>
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">检查</font></font><code>repo</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">私有存储库或</font></font><code>public_repo</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">公共存储库。</font></font></li>
</ul>
<div class="highlight highlight-source-shell notranslate position-relative overflow-auto" dir="auto"><pre>$ <span class="pl-k">export</span> REVIEWDOG_GITHUB_API_TOKEN=<span class="pl-s"><span class="pl-pds">"</span>&lt;token&gt;<span class="pl-pds">"</span></span>
$ reviewdog -reporter=github-pr-review</pre><div class="zeroclipboard-container">
    <clipboard-copy aria-label="Copy" class="ClipboardButton btn btn-invisible js-clipboard-copy m-2 p-0 tooltipped-no-delay d-flex flex-justify-center flex-items-center" data-copy-feedback="Copied!" data-tooltip-direction="w" value="$ export REVIEWDOG_GITHUB_API_TOKEN=&quot;<token>&quot;
$ reviewdog -reporter=github-pr-review" tabindex="0" role="button">
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-copy js-clipboard-copy-icon">
    <path d="M0 6.75C0 5.784.784 5 1.75 5h1.5a.75.75 0 0 1 0 1.5h-1.5a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-1.5a.75.75 0 0 1 1.5 0v1.5A1.75 1.75 0 0 1 9.25 16h-7.5A1.75 1.75 0 0 1 0 14.25Z"></path><path d="M5 1.75C5 .784 5.784 0 6.75 0h7.5C15.216 0 16 .784 16 1.75v7.5A1.75 1.75 0 0 1 14.25 11h-7.5A1.75 1.75 0 0 1 5 9.25Zm1.75-.25a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-7.5a.25.25 0 0 0-.25-.25Z"></path>
</svg>
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-check js-clipboard-check-icon color-fg-success d-none">
    <path d="M13.78 4.22a.75.75 0 0 1 0 1.06l-7.25 7.25a.75.75 0 0 1-1.06 0L2.22 9.28a.751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018L6 10.94l6.72-6.72a.75.75 0 0 1 1.06 0Z"></path>
</svg>
    </clipboard-copy>
  </div></div>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">对于 GitHub Enterprise，通过环境变量设置 API 端点。</font></font></p>
<div class="highlight highlight-source-shell notranslate position-relative overflow-auto" dir="auto"><pre>$ <span class="pl-k">export</span> GITHUB_API=<span class="pl-s"><span class="pl-pds">"</span>https://example.githubenterprise.com/api/v3/<span class="pl-pds">"</span></span>
$ <span class="pl-k">export</span> REVIEWDOG_INSECURE_SKIP_VERIFY=true <span class="pl-c"><span class="pl-c">#</span> set this as you need to skip verifying SSL</span></pre><div class="zeroclipboard-container">
    <clipboard-copy aria-label="Copy" class="ClipboardButton btn btn-invisible js-clipboard-copy m-2 p-0 tooltipped-no-delay d-flex flex-justify-center flex-items-center" data-copy-feedback="Copied!" data-tooltip-direction="w" value="$ export GITHUB_API=&quot;https://example.githubenterprise.com/api/v3/&quot;
$ export REVIEWDOG_INSECURE_SKIP_VERIFY=true # set this as you need to skip verifying SSL" tabindex="0" role="button">
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-copy js-clipboard-copy-icon">
    <path d="M0 6.75C0 5.784.784 5 1.75 5h1.5a.75.75 0 0 1 0 1.5h-1.5a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-1.5a.75.75 0 0 1 1.5 0v1.5A1.75 1.75 0 0 1 9.25 16h-7.5A1.75 1.75 0 0 1 0 14.25Z"></path><path d="M5 1.75C5 .784 5.784 0 6.75 0h7.5C15.216 0 16 .784 16 1.75v7.5A1.75 1.75 0 0 1 14.25 11h-7.5A1.75 1.75 0 0 1 5 9.25Zm1.75-.25a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-7.5a.25.25 0 0 0-.25-.25Z"></path>
</svg>
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-check js-clipboard-check-icon color-fg-success d-none">
    <path d="M13.78 4.22a.75.75 0 0 1 0 1.06l-7.25 7.25a.75.75 0 0 1-1.06 0L2.22 9.28a.751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018L6 10.94l6.72-6.72a.75.75 0 0 1 1.06 0Z"></path>
</svg>
    </clipboard-copy>
  </div></div>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">如果您可以使用</font></font><a href="#github-actions"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">GitHub Actions，</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">也请参阅GitHub Actions 部分。</font><font style="vertical-align: inherit;">您还可以使用公共评审狗 GitHub Actions。</font></font></p>
<h3 tabindex="-1" dir="auto"><a id="user-content-reporter-github-pr-annotations--reportergithub-pr-annotations" class="anchor" aria-hidden="true" tabindex="-1" href="#reporter-github-pr-annotations--reportergithub-pr-annotations"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">记者：GitHub PR 注释 (-reporter=github-pr-annotations)</font></font></h3>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">github-pr-annotations 使用 GitHub Actions 注释格式将错误和警告输出到</font></font><code>stdout</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">例如</font></font></p>
<div class="snippet-clipboard-content notranslate position-relative overflow-auto"><pre class="notranslate"><code>::error line=11,col=41,file=app/index.md::[vale] reported by reviewdog 🐶%0A[demo.Spelling] Did you really mean 'boobarbaz'?%0A%0ARaw Output:%0A{"message": "[demo.Spelling] Did you really mean 'boobarbaz'?", "location": {"path": "app/index.md", "range": {"start": {"line": 11, "column": 41}}}, "severity": "ERROR"}
</code></pre><div class="zeroclipboard-container">
    <clipboard-copy aria-label="Copy" class="ClipboardButton btn btn-invisible js-clipboard-copy m-2 p-0 tooltipped-no-delay d-flex flex-justify-center flex-items-center" data-copy-feedback="Copied!" data-tooltip-direction="w" value="::error line=11,col=41,file=app/index.md::[vale] reported by reviewdog 🐶%0A[demo.Spelling] Did you really mean 'boobarbaz'?%0A%0ARaw Output:%0A{&quot;message&quot;: &quot;[demo.Spelling] Did you really mean 'boobarbaz'?&quot;, &quot;location&quot;: {&quot;path&quot;: &quot;app/index.md&quot;, &quot;range&quot;: {&quot;start&quot;: {&quot;line&quot;: 11, &quot;column&quot;: 41}}}, &quot;severity&quot;: &quot;ERROR&quot;}" tabindex="0" role="button">
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-copy js-clipboard-copy-icon">
    <path d="M0 6.75C0 5.784.784 5 1.75 5h1.5a.75.75 0 0 1 0 1.5h-1.5a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-1.5a.75.75 0 0 1 1.5 0v1.5A1.75 1.75 0 0 1 9.25 16h-7.5A1.75 1.75 0 0 1 0 14.25Z"></path><path d="M5 1.75C5 .784 5.784 0 6.75 0h7.5C15.216 0 16 .784 16 1.75v7.5A1.75 1.75 0 0 1 14.25 11h-7.5A1.75 1.75 0 0 1 5 9.25Zm1.75-.25a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-7.5a.25.25 0 0 0-.25-.25Z"></path>
</svg>
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-check js-clipboard-check-icon color-fg-success d-none">
    <path d="M13.78 4.22a.75.75 0 0 1 0 1.06l-7.25 7.25a.75.75 0 0 1-1.06 0L2.22 9.28a.751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018L6 10.94l6.72-6.72a.75.75 0 0 1 1.06 0Z"></path>
</svg>
    </clipboard-copy>
  </div></div>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">该报告者需要有效的 GitHub API 令牌来生成差异，但不会使用该令牌来报告错误。</font></font></p>
<h3 tabindex="-1" dir="auto"><a id="user-content-reporter-gitlab-mergerequest-discussions--reportergitlab-mr-discussion" class="anchor" aria-hidden="true" tabindex="-1" href="#reporter-gitlab-mergerequest-discussions--reportergitlab-mr-discussion"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">记者：GitLab MergeRequest 讨论 (-reporter=gitlab-mr-discussion)</font></font></h3>
<p dir="auto"><a href="https://gitlab.com/reviewdog/reviewdog/-/merge_requests/113#note_83411103" rel="nofollow"><img src="https://user-images.githubusercontent.com/3797062/41810718-f91bc540-773d-11e8-8598-fbc09ce9b1c7.png" alt="gitlab-mr-讨论样本" style="max-width: 100%;"></a></p>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">所需的 GitLab 版本：&gt;= v10.8.0</font></font></p>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">gitlab-mr-discussion 记者使用 GitLab 个人 API 访问令牌向 GitLab MergeRequest 讨论报告结果。</font></font><code>api</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">从</font></font><a href="https://gitlab.com/profile/personal_access_tokens" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">https://gitlab.com/profile/personal_access_tokens</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">获取具有范围的令牌</font><font style="vertical-align: inherit;">。</font></font></p>
<div class="highlight highlight-source-shell notranslate position-relative overflow-auto" dir="auto"><pre>$ <span class="pl-k">export</span> REVIEWDOG_GITLAB_API_TOKEN=<span class="pl-s"><span class="pl-pds">"</span>&lt;token&gt;<span class="pl-pds">"</span></span>
$ reviewdog -reporter=gitlab-mr-discussion</pre><div class="zeroclipboard-container">
    <clipboard-copy aria-label="Copy" class="ClipboardButton btn btn-invisible js-clipboard-copy m-2 p-0 tooltipped-no-delay d-flex flex-justify-center flex-items-center" data-copy-feedback="Copied!" data-tooltip-direction="w" value="$ export REVIEWDOG_GITLAB_API_TOKEN=&quot;<token>&quot;
$ reviewdog -reporter=gitlab-mr-discussion" tabindex="0" role="button">
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-copy js-clipboard-copy-icon">
    <path d="M0 6.75C0 5.784.784 5 1.75 5h1.5a.75.75 0 0 1 0 1.5h-1.5a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-1.5a.75.75 0 0 1 1.5 0v1.5A1.75 1.75 0 0 1 9.25 16h-7.5A1.75 1.75 0 0 1 0 14.25Z"></path><path d="M5 1.75C5 .784 5.784 0 6.75 0h7.5C15.216 0 16 .784 16 1.75v7.5A1.75 1.75 0 0 1 14.25 11h-7.5A1.75 1.75 0 0 1 5 9.25Zm1.75-.25a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-7.5a.25.25 0 0 0-.25-.25Z"></path>
</svg>
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-check js-clipboard-check-icon color-fg-success d-none">
    <path d="M13.78 4.22a.75.75 0 0 1 0 1.06l-7.25 7.25a.75.75 0 0 1-1.06 0L2.22 9.28a.751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018L6 10.94l6.72-6.72a.75.75 0 0 1 1.06 0Z"></path>
</svg>
    </clipboard-copy>
  </div></div>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">由 Gitlab CI（v11.7 及以上版本）自动定义的环境</font></font><code>CI_API_V4_URL</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">变量将用于查找 Gitlab API URL。</font></font></p>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">或者，</font></font><code>GITLAB_API</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">也可以定义，在这种情况下它将优先于</font></font><code>CI_API_V4_URL</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">。</font></font></p>
<div class="highlight highlight-source-shell notranslate position-relative overflow-auto" dir="auto"><pre>$ <span class="pl-k">export</span> GITLAB_API=<span class="pl-s"><span class="pl-pds">"</span>https://example.gitlab.com/api/v4<span class="pl-pds">"</span></span>
$ <span class="pl-k">export</span> REVIEWDOG_INSECURE_SKIP_VERIFY=true <span class="pl-c"><span class="pl-c">#</span> set this as you need to skip verifying SSL</span></pre><div class="zeroclipboard-container">
    <clipboard-copy aria-label="Copy" class="ClipboardButton btn btn-invisible js-clipboard-copy m-2 p-0 tooltipped-no-delay d-flex flex-justify-center flex-items-center" data-copy-feedback="Copied!" data-tooltip-direction="w" value="$ export GITLAB_API=&quot;https://example.gitlab.com/api/v4&quot;
$ export REVIEWDOG_INSECURE_SKIP_VERIFY=true # set this as you need to skip verifying SSL" tabindex="0" role="button">
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-copy js-clipboard-copy-icon">
    <path d="M0 6.75C0 5.784.784 5 1.75 5h1.5a.75.75 0 0 1 0 1.5h-1.5a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-1.5a.75.75 0 0 1 1.5 0v1.5A1.75 1.75 0 0 1 9.25 16h-7.5A1.75 1.75 0 0 1 0 14.25Z"></path><path d="M5 1.75C5 .784 5.784 0 6.75 0h7.5C15.216 0 16 .784 16 1.75v7.5A1.75 1.75 0 0 1 14.25 11h-7.5A1.75 1.75 0 0 1 5 9.25Zm1.75-.25a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-7.5a.25.25 0 0 0-.25-.25Z"></path>
</svg>
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-check js-clipboard-check-icon color-fg-success d-none">
    <path d="M13.78 4.22a.75.75 0 0 1 0 1.06l-7.25 7.25a.75.75 0 0 1-1.06 0L2.22 9.28a.751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018L6 10.94l6.72-6.72a.75.75 0 0 1 1.06 0Z"></path>
</svg>
    </clipboard-copy>
  </div></div>
<h3 tabindex="-1" dir="auto"><a id="user-content-reporter-gitlab-mergerequest-commit--reportergitlab-mr-commit" class="anchor" aria-hidden="true" tabindex="-1" href="#reporter-gitlab-mergerequest-commit--reportergitlab-mr-commit"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">报告者：GitLab MergeRequest 提交 (-reporter=gitlab-mr-commit)</font></font></h3>
<p dir="auto"><font style="vertical-align: inherit;"></font><a href="#reporter-gitlab-mergerequest-discussions--reportergitlab-mr-discussion"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">gitlab-mr-commit 与gitlab-mr-discussion</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;"> reports类似</font><font style="vertical-align: inherit;">，但向 GitLab MergeRequest 中的每个提交报告结果。</font></font></p>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">推荐使用 gitlab-mr-discussion，但如果您的 GitLab 版本低于 v10.8.0，则可以使用 gitlab-mr-commit reports。</font></font></p>
<div class="highlight highlight-source-shell notranslate position-relative overflow-auto" dir="auto"><pre>$ <span class="pl-k">export</span> REVIEWDOG_GITLAB_API_TOKEN=<span class="pl-s"><span class="pl-pds">"</span>&lt;token&gt;<span class="pl-pds">"</span></span>
$ reviewdog -reporter=gitlab-mr-commit</pre><div class="zeroclipboard-container">
    <clipboard-copy aria-label="Copy" class="ClipboardButton btn btn-invisible js-clipboard-copy m-2 p-0 tooltipped-no-delay d-flex flex-justify-center flex-items-center" data-copy-feedback="Copied!" data-tooltip-direction="w" value="$ export REVIEWDOG_GITLAB_API_TOKEN=&quot;<token>&quot;
$ reviewdog -reporter=gitlab-mr-commit" tabindex="0" role="button">
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-copy js-clipboard-copy-icon">
    <path d="M0 6.75C0 5.784.784 5 1.75 5h1.5a.75.75 0 0 1 0 1.5h-1.5a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-1.5a.75.75 0 0 1 1.5 0v1.5A1.75 1.75 0 0 1 9.25 16h-7.5A1.75 1.75 0 0 1 0 14.25Z"></path><path d="M5 1.75C5 .784 5.784 0 6.75 0h7.5C15.216 0 16 .784 16 1.75v7.5A1.75 1.75 0 0 1 14.25 11h-7.5A1.75 1.75 0 0 1 5 9.25Zm1.75-.25a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-7.5a.25.25 0 0 0-.25-.25Z"></path>
</svg>
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-check js-clipboard-check-icon color-fg-success d-none">
    <path d="M13.78 4.22a.75.75 0 0 1 0 1.06l-7.25 7.25a.75.75 0 0 1-1.06 0L2.22 9.28a.751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018L6 10.94l6.72-6.72a.75.75 0 0 1 1.06 0Z"></path>
</svg>
    </clipboard-copy>
  </div></div>
<h3 tabindex="-1" dir="auto"><a id="user-content-reporter-gerrit-change-review--reportergerrit-change-review" class="anchor" aria-hidden="true" tabindex="-1" href="#reporter-gerrit-change-review--reportergerrit-change-review"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">记者：Gerrit 变更审查 (-reporter=gerrit-change-review)</font></font></h3>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">gerrit-change-review 记者使用 Gerrit Rest API 向 Gerrit Change 报告结果。</font></font></p>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">报告器支持基本身份验证和基于 Git-cookie 的身份验证来报告结果。</font></font></p>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">设置</font><font style="vertical-align: inherit;">基本身份验证的环境变量，并设置</font><font style="vertical-align: inherit;">基于 git cookie 的身份验证</font></font><code>GERRIT_USERNAME</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">。</font></font><code>GERRIT_PASSWORD</code><font style="vertical-align: inherit;"></font><code>GIT_GITCOOKIE_PATH</code><font style="vertical-align: inherit;"></font></p>
<div class="highlight highlight-source-shell notranslate position-relative overflow-auto" dir="auto"><pre>$ <span class="pl-k">export</span> GERRIT_CHANGE_ID=changeID
$ <span class="pl-k">export</span> GERRIT_REVISION_ID=revisionID
$ <span class="pl-k">export</span> GERRIT_BRANCH=master
$ <span class="pl-k">export</span> GERRIT_ADDRESS=http://<span class="pl-k">&lt;</span>gerrit-host<span class="pl-k">&gt;</span>:<span class="pl-k">&lt;</span>gerrit-port<span class="pl-k">&gt;</span>
$ reviewdog -reporter=gerrit-change-review</pre><div class="zeroclipboard-container">
    <clipboard-copy aria-label="Copy" class="ClipboardButton btn btn-invisible js-clipboard-copy m-2 p-0 tooltipped-no-delay d-flex flex-justify-center flex-items-center" data-copy-feedback="Copied!" data-tooltip-direction="w" value="$ export GERRIT_CHANGE_ID=changeID
$ export GERRIT_REVISION_ID=revisionID
$ export GERRIT_BRANCH=master
$ export GERRIT_ADDRESS=http://<gerrit-host>:<gerrit-port>
$ reviewdog -reporter=gerrit-change-review" tabindex="0" role="button">
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-copy js-clipboard-copy-icon">
    <path d="M0 6.75C0 5.784.784 5 1.75 5h1.5a.75.75 0 0 1 0 1.5h-1.5a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-1.5a.75.75 0 0 1 1.5 0v1.5A1.75 1.75 0 0 1 9.25 16h-7.5A1.75 1.75 0 0 1 0 14.25Z"></path><path d="M5 1.75C5 .784 5.784 0 6.75 0h7.5C15.216 0 16 .784 16 1.75v7.5A1.75 1.75 0 0 1 14.25 11h-7.5A1.75 1.75 0 0 1 5 9.25Zm1.75-.25a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-7.5a.25.25 0 0 0-.25-.25Z"></path>
</svg>
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-check js-clipboard-check-icon color-fg-success d-none">
    <path d="M13.78 4.22a.75.75 0 0 1 0 1.06l-7.25 7.25a.75.75 0 0 1-1.06 0L2.22 9.28a.751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018L6 10.94l6.72-6.72a.75.75 0 0 1 1.06 0Z"></path>
</svg>
    </clipboard-copy>
  </div></div>
<h3 tabindex="-1" dir="auto"><a id="user-content-reporter-bitbucket-code-insights-reports--reporterbitbucket-code-report" class="anchor" aria-hidden="true" tabindex="-1" href="#reporter-bitbucket-code-insights-reports--reporterbitbucket-code-report"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">记者：Bitbucket 代码洞察报告 (-reporter=bitbucket-code-report)</font></font></h3>
<p dir="auto"><a href="https://bitbucket.org/Trane9991/reviewdog-example/pull-requests/1" rel="nofollow"><img src="https://user-images.githubusercontent.com/9948629/96770123-c138d600-13e8-11eb-8e46-250b4bb393bd.png" alt="位桶代码报告" style="max-width: 100%;"></a>
<a href="https://bitbucket.org/Trane9991/reviewdog-example/pull-requests/1" rel="nofollow"><img src="https://user-images.githubusercontent.com/9948629/97054896-5e813f00-158e-11eb-9ad7-f8d75489b8ba.png" alt="位桶代码注释" style="max-width: 100%;"></a></p>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">bitbucket-code-report 生成带注释的
</font></font><a href="https://support.atlassian.com/bitbucket-cloud/docs/code-insights/" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Bitbucket Code Insights</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">报告。</font></font></p>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">目前，仅</font></font><code>no-filter</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">支持该模式，因此每次运行时都会扫描整个项目。</font><font style="vertical-align: inherit;">报告按提交存储，并且可以从 Bitbucket Pipelines UI 或拉取请求中查看每次提交。</font><font style="vertical-align: inherit;">在拉取请求 UI 中，受影响的代码行将在差异中进行注释，并且您将能够按此</font></font><strong><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">拉取请求</font></font></strong><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">或</font></font><strong><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">全部</font></font></strong><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">过滤注释。</font></font></p>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">如果从</font></font><a href="#bitbucket-pipelines"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Bitbucket Pipelines</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">运行，则不需要额外的配置（甚至不需要凭据）。</font><font style="vertical-align: inherit;">如果在本地运行或从其他 CI 系统运行，您需要提供 Bitbucket API 凭据：</font></font></p>
<ul dir="auto">
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">对于基本身份验证，您需要设置以下环境变量：
</font></font><code>BITBUCKET_USER</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">和</font></font><code>BITBUCKET_PASSWORD</code></li>
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">对于 AccessToken Auth，您需要设置</font></font><code>BITBUCKET_ACCESS_TOKEN</code></li>
</ul>
<div class="highlight highlight-source-shell notranslate position-relative overflow-auto" dir="auto"><pre>$ <span class="pl-k">export</span> BITBUCKET_USER=<span class="pl-s"><span class="pl-pds">"</span>my_user<span class="pl-pds">"</span></span>
$ <span class="pl-k">export</span> BITBUCKET_PASSWORD=<span class="pl-s"><span class="pl-pds">"</span>my_password<span class="pl-pds">"</span></span>
$ reviewdog -reporter=bitbucket-code-report</pre><div class="zeroclipboard-container">
    <clipboard-copy aria-label="Copy" class="ClipboardButton btn btn-invisible js-clipboard-copy m-2 p-0 tooltipped-no-delay d-flex flex-justify-center flex-items-center" data-copy-feedback="Copied!" data-tooltip-direction="w" value="$ export BITBUCKET_USER=&quot;my_user&quot;
$ export BITBUCKET_PASSWORD=&quot;my_password&quot;
$ reviewdog -reporter=bitbucket-code-report" tabindex="0" role="button">
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-copy js-clipboard-copy-icon">
    <path d="M0 6.75C0 5.784.784 5 1.75 5h1.5a.75.75 0 0 1 0 1.5h-1.5a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-1.5a.75.75 0 0 1 1.5 0v1.5A1.75 1.75 0 0 1 9.25 16h-7.5A1.75 1.75 0 0 1 0 14.25Z"></path><path d="M5 1.75C5 .784 5.784 0 6.75 0h7.5C15.216 0 16 .784 16 1.75v7.5A1.75 1.75 0 0 1 14.25 11h-7.5A1.75 1.75 0 0 1 5 9.25Zm1.75-.25a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-7.5a.25.25 0 0 0-.25-.25Z"></path>
</svg>
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-check js-clipboard-check-icon color-fg-success d-none">
    <path d="M13.78 4.22a.75.75 0 0 1 0 1.06l-7.25 7.25a.75.75 0 0 1-1.06 0L2.22 9.28a.751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018L6 10.94l6.72-6.72a.75.75 0 0 1 1.06 0Z"></path>
</svg>
    </clipboard-copy>
  </div></div>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">要将报告发布到 Bitbucket 服务器，请使用</font></font><code>BITBUCKET_SERVER_URL</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">变量：</font></font></p>
<div class="highlight highlight-source-shell notranslate position-relative overflow-auto" dir="auto"><pre>$ <span class="pl-k">export</span> BITBUCKET_USER=<span class="pl-s"><span class="pl-pds">"</span>my_user<span class="pl-pds">"</span></span>
$ <span class="pl-k">export</span> BITBUCKET_PASSWORD=<span class="pl-s"><span class="pl-pds">"</span>my_password<span class="pl-pds">"</span></span>
$ <span class="pl-k">export</span> BITBUCKET_SERVER_URL=<span class="pl-s"><span class="pl-pds">"</span>https://bitbucket.my-company.com<span class="pl-pds">"</span></span>
$ reviewdog -reporter=bitbucket-code-report</pre><div class="zeroclipboard-container">
    <clipboard-copy aria-label="Copy" class="ClipboardButton btn btn-invisible js-clipboard-copy m-2 p-0 tooltipped-no-delay d-flex flex-justify-center flex-items-center" data-copy-feedback="Copied!" data-tooltip-direction="w" value="$ export BITBUCKET_USER=&quot;my_user&quot;
$ export BITBUCKET_PASSWORD=&quot;my_password&quot;
$ export BITBUCKET_SERVER_URL=&quot;https://bitbucket.my-company.com&quot;
$ reviewdog -reporter=bitbucket-code-report" tabindex="0" role="button">
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-copy js-clipboard-copy-icon">
    <path d="M0 6.75C0 5.784.784 5 1.75 5h1.5a.75.75 0 0 1 0 1.5h-1.5a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-1.5a.75.75 0 0 1 1.5 0v1.5A1.75 1.75 0 0 1 9.25 16h-7.5A1.75 1.75 0 0 1 0 14.25Z"></path><path d="M5 1.75C5 .784 5.784 0 6.75 0h7.5C15.216 0 16 .784 16 1.75v7.5A1.75 1.75 0 0 1 14.25 11h-7.5A1.75 1.75 0 0 1 5 9.25Zm1.75-.25a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-7.5a.25.25 0 0 0-.25-.25Z"></path>
</svg>
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-check js-clipboard-check-icon color-fg-success d-none">
    <path d="M13.78 4.22a.75.75 0 0 1 0 1.06l-7.25 7.25a.75.75 0 0 1-1.06 0L2.22 9.28a.751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018L6 10.94l6.72-6.72a.75.75 0 0 1 1.06 0Z"></path>
</svg>
    </clipboard-copy>
  </div></div>
<h2 tabindex="-1" dir="auto"><a id="user-content-supported-ci-services" class="anchor" aria-hidden="true" tabindex="-1" href="#supported-ci-services"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">支持的 CI 服务</font></font></h2>
<h3 tabindex="-1" dir="auto"><a id="user-content-github-actions" class="anchor" aria-hidden="true" tabindex="-1" href="#github-actions"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a><a href="https://github.com/features/actions"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">GitHub 操作</font></font></a></h3>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">示例：</font></font><a href="/reviewdog/reviewdog/blob/master/.github/workflows/reviewdog.yml"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">.github/workflows/reviewdog.yml</font></font></a></p>
<div class="highlight highlight-source-yaml notranslate position-relative overflow-auto" dir="auto"><pre><span class="pl-ent">name</span>: <span class="pl-s">reviewdog</span>
<span class="pl-ent">on</span>: <span class="pl-s">[pull_request]</span>
<span class="pl-ent">jobs</span>:
  <span class="pl-ent">reviewdog</span>:
    <span class="pl-ent">name</span>: <span class="pl-s">reviewdog</span>
    <span class="pl-ent">runs-on</span>: <span class="pl-s">ubuntu-latest</span>
    <span class="pl-ent">steps</span>:
      <span class="pl-c"><span class="pl-c">#</span> ...</span>
      - <span class="pl-ent">uses</span>: <span class="pl-s">reviewdog/action-setup@v1</span>
        <span class="pl-ent">with</span>:
          <span class="pl-ent">reviewdog_version</span>: <span class="pl-s">latest </span><span class="pl-c"><span class="pl-c">#</span> Optional. [latest,nightly,v.X.Y.Z]</span>
      - <span class="pl-ent">name</span>: <span class="pl-s">Run reviewdog</span>
        <span class="pl-ent">env</span>:
          <span class="pl-ent">REVIEWDOG_GITHUB_API_TOKEN</span>: <span class="pl-s">${{ secrets.GITHUB_TOKEN }}</span>
        <span class="pl-ent">run</span>: <span class="pl-s">|</span>
<span class="pl-s">          reviewdog -reporter=github-pr-check -runners=golint,govet</span>
<span class="pl-s">          <span class="pl-c"><span class="pl-c">#</span> or</span></span>
<span class="pl-s">          reviewdog -reporter=github-pr-review -runners=golint,govet</span></pre><div class="zeroclipboard-container">
    <clipboard-copy aria-label="Copy" class="ClipboardButton btn btn-invisible js-clipboard-copy m-2 p-0 tooltipped-no-delay d-flex flex-justify-center flex-items-center" data-copy-feedback="Copied!" data-tooltip-direction="w" value="name: reviewdog
on: [pull_request]
jobs:
  reviewdog:
    name: reviewdog
    runs-on: ubuntu-latest
    steps:
      # ...
      - uses: reviewdog/action-setup@v1
        with:
          reviewdog_version: latest # Optional. [latest,nightly,v.X.Y.Z]
      - name: Run reviewdog
        env:
          REVIEWDOG_GITHUB_API_TOKEN: ${{ secrets.GITHUB_TOKEN }}
        run: |
          reviewdog -reporter=github-pr-check -runners=golint,govet
          # or
          reviewdog -reporter=github-pr-review -runners=golint,govet" tabindex="0" role="button">
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-copy js-clipboard-copy-icon">
    <path d="M0 6.75C0 5.784.784 5 1.75 5h1.5a.75.75 0 0 1 0 1.5h-1.5a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-1.5a.75.75 0 0 1 1.5 0v1.5A1.75 1.75 0 0 1 9.25 16h-7.5A1.75 1.75 0 0 1 0 14.25Z"></path><path d="M5 1.75C5 .784 5.784 0 6.75 0h7.5C15.216 0 16 .784 16 1.75v7.5A1.75 1.75 0 0 1 14.25 11h-7.5A1.75 1.75 0 0 1 5 9.25Zm1.75-.25a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-7.5a.25.25 0 0 0-.25-.25Z"></path>
</svg>
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-check js-clipboard-check-icon color-fg-success d-none">
    <path d="M13.78 4.22a.75.75 0 0 1 0 1.06l-7.25 7.25a.75.75 0 0 1-1.06 0L2.22 9.28a.751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018L6 10.94l6.72-6.72a.75.75 0 0 1 1.06 0Z"></path>
</svg>
    </clipboard-copy>
  </div></div>
<details>
<summary><strong><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">示例（github-check 记者）：</font></font></strong></summary>
<p dir="auto"><a href="/reviewdog/reviewdog/blob/master/.github/workflows/reviewdog.yml">.github/workflows/reviewdog</a></p>
<p dir="auto">Only <code>github-check</code> reporter can run on the push event too.</p>
<div class="highlight highlight-source-yaml notranslate position-relative overflow-auto" dir="auto"><pre><span class="pl-ent">name</span>: <span class="pl-s">reviewdog (github-check)</span>
<span class="pl-ent">on</span>:
  <span class="pl-ent">push</span>:
    <span class="pl-ent">branches</span>:
      - <span class="pl-s">master</span>
  <span class="pl-ent">pull_request</span>:

<span class="pl-ent">jobs</span>:
  <span class="pl-ent">reviewdog</span>:
    <span class="pl-ent">name</span>: <span class="pl-s">reviewdog</span>
    <span class="pl-ent">runs-on</span>: <span class="pl-s">ubuntu-latest</span>
    <span class="pl-ent">steps</span>:
      <span class="pl-c"><span class="pl-c">#</span> ...</span>
      - <span class="pl-ent">name</span>: <span class="pl-s">Run reviewdog</span>
        <span class="pl-ent">env</span>:
          <span class="pl-ent">REVIEWDOG_GITHUB_API_TOKEN</span>: <span class="pl-s">${{ secrets.GITHUB_TOKEN }}</span>
        <span class="pl-ent">run</span>: <span class="pl-s">|</span>
<span class="pl-s">          reviewdog -reporter=github-check -runners=golint,govet</span></pre><div class="zeroclipboard-container">
    <clipboard-copy aria-label="Copy" class="ClipboardButton btn btn-invisible js-clipboard-copy m-2 p-0 tooltipped-no-delay d-flex flex-justify-center flex-items-center" data-copy-feedback="Copied!" data-tooltip-direction="w" value="name: reviewdog (github-check)
on:
  push:
    branches:
      - master
  pull_request:

jobs:
  reviewdog:
    name: reviewdog
    runs-on: ubuntu-latest
    steps:
      # ...
      - name: Run reviewdog
        env:
          REVIEWDOG_GITHUB_API_TOKEN: ${{ secrets.GITHUB_TOKEN }}
        run: |
          reviewdog -reporter=github-check -runners=golint,govet" tabindex="0" role="button">
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-copy js-clipboard-copy-icon">
    <path d="M0 6.75C0 5.784.784 5 1.75 5h1.5a.75.75 0 0 1 0 1.5h-1.5a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-1.5a.75.75 0 0 1 1.5 0v1.5A1.75 1.75 0 0 1 9.25 16h-7.5A1.75 1.75 0 0 1 0 14.25Z"></path><path d="M5 1.75C5 .784 5.784 0 6.75 0h7.5C15.216 0 16 .784 16 1.75v7.5A1.75 1.75 0 0 1 14.25 11h-7.5A1.75 1.75 0 0 1 5 9.25Zm1.75-.25a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-7.5a.25.25 0 0 0-.25-.25Z"></path>
</svg>
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-check js-clipboard-check-icon color-fg-success d-none">
    <path d="M13.78 4.22a.75.75 0 0 1 0 1.06l-7.25 7.25a.75.75 0 0 1-1.06 0L2.22 9.28a.751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018L6 10.94l6.72-6.72a.75.75 0 0 1 1.06 0Z"></path>
</svg>
    </clipboard-copy>
  </div></div>
</details>
<h4 tabindex="-1" dir="auto"><a id="user-content-public-reviewdog-github-actions" class="anchor" aria-hidden="true" tabindex="-1" href="#public-reviewdog-github-actions"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">公共评论狗 GitHub 操作</font></font></h4>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">您可以使用公共 GitHub Actions 轻松开始使用 reviewdog！</font><font style="vertical-align: inherit;">🎉</font></font><g-emoji class="g-emoji" alias="arrow_forward"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">▶️</font></font></g-emoji><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">🎉</font></font></p>
<ul dir="auto">
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">常见的
</font></font><ul dir="auto">
<li><a href="https://github.com/reviewdog/action-misspell"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">reviewdog/action-misspell</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;"> - 运行</font></font><a href="https://github.com/client9/misspell"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">misspell</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">。</font></font></li>
<li><a href="https://github.com/EPMatt/reviewdog-action-prettier"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">EPMatt/reviewdog-action-prettier</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;"> - 运行</font></font><a href="https://prettier.io/" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Prettier</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">。</font></font></li>
</ul>
</li>
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">文本
</font></font><ul dir="auto">
<li><a href="https://github.com/reviewdog/action-alex"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">reviewdog/action-alex</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;"> - 运行</font></font><a href="https://github.com/get-alex/alex"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">alex</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">来捕获不敏感、不体贴的写作。</font><font style="vertical-align: inherit;">（例如主/从）</font></font></li>
<li><a href="https://github.com/reviewdog/action-languagetool"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">reviewdog/action-languagetool</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;"> - 运行</font></font><a href="https://github.com/languagetool-org/languagetool"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">languagetool</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">。</font></font></li>
<li><a href="https://github.com/tsuyoshicho/action-textlint"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">tsuyoshicho/action-textlint</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;"> - 运行</font></font><a href="https://github.com/textlint/textlint"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">textlint</font></font></a></li>
<li><a href="https://github.com/tsuyoshicho/action-redpen"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">tsuyoshicho/action-redpen</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;"> - 运行</font></font><a href="https://github.com/redpen-cc/redpen"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">redpen</font></font></a></li>
</ul>
</li>
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">降价
</font></font><ul dir="auto">
<li><a href="https://github.com/reviewdog/action-markdownlint"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">reviewdog/action-markdownlint</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;"> - 运行</font></font><a href="https://github.com/DavidAnson/markdownlint"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">markdownlint</font></font></a></li>
</ul>
</li>
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">码头工人
</font></font><ul dir="auto">
<li><a href="https://github.com/reviewdog/action-hadolint"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">reviewdog/action-hadolint</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;"> - 运行</font></font><a href="https://github.com/hadolint/hadolint"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">hadolint</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">来 lint </font></font><code>Dockerfile</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">。</font></font></li>
</ul>
</li>
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">环境
</font></font><ul dir="auto">
<li><a href="https://github.com/dotenv-linter/action-dotenv-linter"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">dotenv-linter/action-dotenv-linter</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;"> - 运行</font></font><a href="https://github.com/dotenv-linter/dotenv-linter"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">dotenv-linter</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">以处理 lint</font></font><code>.env</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">文件。</font></font></li>
</ul>
</li>
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">外壳脚本
</font></font><ul dir="auto">
<li><a href="https://github.com/reviewdog/action-shellcheck"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">reviewdog/action-shellcheck</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;"> - 运行</font></font><a href="https://github.com/koalaman/shellcheck"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">shellcheck</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">。</font></font></li>
<li><a href="https://github.com/reviewdog/action-shfmt"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">reviewdog/action-shfmt</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;"> - 运行</font></font><a href="https://github.com/mvdan/sh"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">shfmt</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">。</font></font></li>
</ul>
</li>
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">去
</font></font><ul dir="auto">
<li><a href="https://github.com/reviewdog/action-staticcheck"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">reviewdog/action-staticcheck</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;"> - 运行</font></font><a href="https://staticcheck.io/" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">staticcheck</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">。</font></font></li>
<li><a href="https://github.com/reviewdog/action-golangci-lint"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">reviewdog/action-golangci-lint</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;"> - 通过 golangci-lint 单独运行</font></font><a href="https://github.com/golangci/golangci-lint"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">golangci-lint</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">和支持的 linter.</font></font></li>
</ul>
</li>
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">JavaScript
</font></font><ul dir="auto">
<li><a href="https://github.com/reviewdog/action-eslint"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">reviewdog/action-eslint</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;"> - 运行</font></font><a href="https://github.com/eslint/eslint"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">eslint</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">。</font></font></li>
<li><a href="https://github.com/mongolyy/reviewdog-action-biome"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">mongolyy/reviewdog-action-biome</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;"> - 运行</font></font><a href="https://biomejs.dev/" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">生物群落</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">。</font></font></li>
</ul>
</li>
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">打字稿
</font></font><ul dir="auto">
<li><a href="https://github.com/EPMatt/reviewdog-action-tsc"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">EPMatt/reviewdog-action-tsc</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;"> - 运行</font></font><a href="https://www.typescriptlang.org/docs/handbook/compiler-options.html" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">tsc</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">。</font></font></li>
</ul>
</li>
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">CSS
</font></font><ul dir="auto">
<li><a href="https://github.com/reviewdog/action-stylelint"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">reviewdog/action-stylelint</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;"> - 运行</font></font><a href="https://github.com/stylelint/stylelint"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">stylelint</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">。</font></font></li>
</ul>
</li>
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Vim 脚本
</font></font><ul dir="auto">
<li><a href="https://github.com/reviewdog/action-vint"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">reviewdog/action-vint</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;"> - 运行</font></font><a href="https://github.com/Vimjas/vint"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">vint</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">。</font></font></li>
<li><a href="https://github.com/tsuyoshicho/action-vimlint"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">tsuyoshicho/action-vimlint</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;"> - 运行</font></font><a href="https://github.com/syngan/vim-vimlint"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">vim-vimlint</font></font></a></li>
</ul>
</li>
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">地形
</font></font><ul dir="auto">
<li><a href="https://github.com/reviewdog/action-tflint"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">reviewdog/action-tflint</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;"> - 运行</font></font><a href="https://github.com/terraform-linters/tflint"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">tflint</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">。</font></font></li>
</ul>
</li>
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">YAML
</font></font><ul dir="auto">
<li><a href="https://github.com/reviewdog/action-yamllint"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">reviewdog/action-yamllint</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;"> - 运行</font></font><a href="https://github.com/adrienverge/yamllint"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">yamllint</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">。</font></font></li>
</ul>
</li>
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">红宝石
</font></font><ul dir="auto">
<li><a href="https://github.com/reviewdog/action-brakeman"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">reviewdog/action-brakeman</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;"> - 运行</font></font><a href="https://github.com/presidentbeef/brakeman"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">brakeman</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">。</font></font></li>
<li><a href="https://github.com/reviewdog/action-reek"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">reviewdog/action-reek</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;"> - 运行</font></font><a href="https://github.com/troessner/reek"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">reek</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">。</font></font></li>
<li><a href="https://github.com/reviewdog/action-rubocop"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">reviewdog/action-rubocop</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;"> - 运行</font></font><a href="https://github.com/rubocop/rubocop"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">rubocop</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">。</font></font></li>
<li><a href="https://github.com/vk26/action-fasterer"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">vk26/action-fasterer</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;"> - 跑得</font></font><a href="https://github.com/DamirSvrtan/fasterer"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">更快</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">。</font></font></li>
<li><a href="https://github.com/PrintReleaf/action-standardrb"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">PrintReleaf/action-standardrb</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;"> - 运行</font></font><a href="https://github.com/standardrb/standard"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">standardrb</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">。</font></font></li>
<li><a href="https://github.com/tk0miya/action-erblint"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">tk0miya/action-erblint</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;"> - 运行</font></font><a href="https://github.com/Shopify/erb-lint"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">erb-lint</font></font></a></li>
<li><a href="https://github.com/tk0miya/action-steep"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">tk0miya/action-steep</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;"> -</font></font><a href="https://github.com/soutaro/steep"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">陡峭运行</font></font></a></li>
<li><a href="https://github.com/blooper05/action-rails_best_practices"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">blooper05/action-rails_best_practices</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;"> - 运行</font></font><a href="https://github.com/flyerhzm/rails_best_practices"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">rails_best_practices</font></font></a></li>
<li><a href="https://github.com/tomferreira/action-bundler-audit"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">tomferreira/action-bundler-audit</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;"> - 运行</font></font><a href="https://github.com/rubysec/bundler-audit"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">bundler-audit</font></font></a></li>
</ul>
</li>
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Python
</font></font><ul dir="auto">
<li><a href="https://github.com/wemake-services/wemake-python-styleguide"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">wemake-python-styleguide</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;"> - 运行 wemake-python-styleguide</font></font></li>
<li><a href="https://github.com/tsuyoshicho/action-mypy"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">tsuyoshicho/action-mypy</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;"> - 运行</font></font><a href="https://pypi.org/project/mypy/" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">mypy</font></font></a></li>
<li><a href="https://github.com/jordemort/action-pyright"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">jordemort/action-pyright</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;"> - 运行</font></font><a href="https://github.com/Microsoft/pyright"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Pyright</font></font></a></li>
<li><a href="https://github.com/dciborow/action-pylint"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">dciborow/action-pylint</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;"> - 运行</font></font><a href="https://github.com/pylint-dev/pylint"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">pylint</font></font></a></li>
<li><a href="https://github.com/reviewdog/action-black"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">reviewdog/action-black</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;"> -</font></font><a href="https://github.com/psf/black"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">黑色奔跑</font></font></a></li>
</ul>
</li>
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">科特林
</font></font><ul dir="auto">
<li><a href="https://github.com/ScaCap/action-ktlint"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">ScaCap/action-ktlint</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;"> - 运行</font></font><a href="https://ktlint.github.io/" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">ktlint</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">。</font></font></li>
</ul>
</li>
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Android Lint
</font></font><ul dir="auto">
<li><a href="https://github.com/DVDAndroid/action-android-lint"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">dvdandroid/action-android-lint</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;"> - 运行</font></font><a href="https://developer.android.com/studio/write/lint" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Android Lint</font></font></a></li>
</ul>
</li>
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">安西布尔
</font></font><ul dir="auto">
<li><a href="https://github.com/reviewdog/action-ansiblelint"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">reviewdog/action-ansiblelint</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;"> - 运行</font></font><a href="https://github.com/ansible/ansible-lint"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">ansible-lint</font></font></a></li>
</ul>
</li>
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">GitHub 操作
</font></font><ul dir="auto">
<li><a href="https://github.com/reviewdog/action-actionlint"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">reviewdog/action-actionlint</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;"> - 运行</font></font><a href="https://github.com/rhysd/actionlint"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">actionlint</font></font></a></li>
</ul>
</li>
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">协议缓冲区
</font></font><ul dir="auto">
<li><a href="https://github.com/yoheimuta/action-protolint"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">yoheimuta/action-protolint</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;"> - 运行</font></font><a href="https://github.com/yoheimuta/protolint"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">protolint</font></font></a></li>
</ul>
</li>
</ul>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">...以及</font></font><a href="https://github.com/marketplace?utf8=%E2%9C%93&amp;type=actions&amp;query=reviewdog"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">GitHub Marketplace</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">上的更多内容。</font></font></p>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">缺少动作？</font><font style="vertical-align: inherit;">查看</font></font><a href="https://github.com/reviewdog/action-template"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">reviewdog/action-template</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">并创建一个新的 reviewdog 操作！</font></font></p>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">请打开拉取请求以在此处添加您创建的 reviewdog 操作 ✨。</font><font style="vertical-align: inherit;">我还可以将您的存储库置于 reviewdog 组织之下并共同维护操作。</font><font style="vertical-align: inherit;">示例：</font></font><a href="https://github.com/reviewdog/reviewdog/issues/322" data-hovercard-type="issue" data-hovercard-url="/reviewdog/reviewdog/issues/322/hovercard"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">action-tflint</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">。</font></font></p>
<h4 tabindex="-1" dir="auto"><a id="user-content-graceful-degradation-for-pull-requests-from-forked-repositories" class="anchor" aria-hidden="true" tabindex="-1" href="#graceful-degradation-for-pull-requests-from-forked-repositories"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">来自分叉存储库的拉取请求的优雅降级</font></font></h4>
<p dir="auto"><a target="_blank" rel="noopener noreferrer nofollow" href="https://user-images.githubusercontent.com/3797062/71781334-e2266b00-3010-11ea-8a38-dee6e30c8162.png"><img src="https://user-images.githubusercontent.com/3797062/71781334-e2266b00-3010-11ea-8a38-dee6e30c8162.png" alt="优雅降级示例" style="max-width: 100%;"></a></p>
<p dir="auto"><code>GITHUB_TOKEN</code><font style="vertical-align: inherit;"></font><a href="https://docs.github.com/en/actions/security-guides/automatic-token-authentication#permissions-for-the-github_token"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">由于GitHub Actions 限制</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">，来自分叉存储库的 Pull 请求没有对 Check API 和 Review API 的写入权限</font><font style="vertical-align: inherit;">。</font></font></p>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">相反，reviewdog 使用</font></font><a href="https://docs.github.com/en/actions/using-workflows/workflow-commands-for-github-actions#set-an-error-message-error"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">GitHub Actions 的 Logging 命令将结果作为</font></font></a><font style="vertical-align: inherit;"></font><a href="https://docs.github.com/en/rest/checks/runs#annotations-object"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">注释</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">
发布，
</font><font style="vertical-align: inherit;">
类似于</font></font><code>github-pr-check</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">记者。</font></font></p>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">请注意，通过日志记录命令创建的注释存在限制，例如</font></font><a href="https://github.com/reviewdog/reviewdog/issues/411#issuecomment-570893427" data-hovercard-type="issue" data-hovercard-url="/reviewdog/reviewdog/issues/411/hovercard"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">每次运行的最大注释数</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">。</font><font style="vertical-align: inherit;">在这种情况下，您可以检查 GitHub Actions 日志以查看完整结果。</font></font></p>
<h4 tabindex="-1" dir="auto"><a id="user-content-reviewdog-badge-" class="anchor" aria-hidden="true" tabindex="-1" href="#reviewdog-badge-"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">评论狗徽章</font></font><a href="https://github.com/reviewdog/reviewdog/actions?query=workflow%3Areviewdog+event%3Apush+branch%3Amaster"><img src="https://github.com/reviewdog/reviewdog/workflows/reviewdog/badge.svg?branch=master&amp;event=push" alt="评论狗" style="max-width: 100%;"></a></h4>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">由于</font></font><a href="#reporter-github-checks--reportergithub-pr-check"><code>github-check</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">记者</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">支持在提交上运行，我们可以创建 reviewdog
 </font></font><a href="https://docs.github.com/en/actions/using-workflows#adding-a-workflow-status-badge-to-your-repository"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">GitHub Action 徽章</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">
来检查主提交的结果。</font><font style="vertical-align: inherit;">🎉</font></font></p>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">例子：</font></font></p>
<div class="snippet-clipboard-content notranslate position-relative overflow-auto"><pre class="notranslate"><code>&lt;!-- Replace &lt;OWNER&gt; and &lt;REPOSITORY&gt;. It assumes workflow name is "reviewdog" --&gt;
[![reviewdog](https://github.com/&lt;OWNER&gt;/&lt;REPOSITORY&gt;/workflows/reviewdog/badge.svg?branch=master&amp;event=push)](https://github.com/&lt;OWNER&gt;/&lt;REPOSITORY&gt;/actions?query=workflow%3Areviewdog+event%3Apush+branch%3Amaster)
</code></pre><div class="zeroclipboard-container">
    <clipboard-copy aria-label="Copy" class="ClipboardButton btn btn-invisible js-clipboard-copy m-2 p-0 tooltipped-no-delay d-flex flex-justify-center flex-items-center" data-copy-feedback="Copied!" data-tooltip-direction="w" value="<!-- Replace <OWNER> and <REPOSITORY>. It assumes workflow name is &quot;reviewdog&quot; -->
[![reviewdog](https://github.com/<OWNER>/<REPOSITORY>/workflows/reviewdog/badge.svg?branch=master&amp;event=push)](https://github.com/<OWNER>/<REPOSITORY>/actions?query=workflow%3Areviewdog+event%3Apush+branch%3Amaster)" tabindex="0" role="button">
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-copy js-clipboard-copy-icon">
    <path d="M0 6.75C0 5.784.784 5 1.75 5h1.5a.75.75 0 0 1 0 1.5h-1.5a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-1.5a.75.75 0 0 1 1.5 0v1.5A1.75 1.75 0 0 1 9.25 16h-7.5A1.75 1.75 0 0 1 0 14.25Z"></path><path d="M5 1.75C5 .784 5.784 0 6.75 0h7.5C15.216 0 16 .784 16 1.75v7.5A1.75 1.75 0 0 1 14.25 11h-7.5A1.75 1.75 0 0 1 5 9.25Zm1.75-.25a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-7.5a.25.25 0 0 0-.25-.25Z"></path>
</svg>
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-check js-clipboard-check-icon color-fg-success d-none">
    <path d="M13.78 4.22a.75.75 0 0 1 0 1.06l-7.25 7.25a.75.75 0 0 1-1.06 0L2.22 9.28a.751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018L6 10.94l6.72-6.72a.75.75 0 0 1 1.06 0Z"></path>
</svg>
    </clipboard-copy>
  </div></div>
<h3 tabindex="-1" dir="auto"><a id="user-content-travis-ci" class="anchor" aria-hidden="true" tabindex="-1" href="#travis-ci"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">特拉维斯·西尔</font></font></h3>
<h4 tabindex="-1" dir="auto"><a id="user-content-travis-ci--reportergithub-pr-check" class="anchor" aria-hidden="true" tabindex="-1" href="#travis-ci--reportergithub-pr-check"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Travis CI (-reporter=github-pr-check)</font></font></h4>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">如果你在 Travis CI 中使用 -reporter=github-pr-check ，则不需要设置</font></font><code>REVIEWDOG_TOKEN</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">.</font></font></p>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">例子：</font></font></p>
<div class="highlight highlight-source-yaml notranslate position-relative overflow-auto" dir="auto"><pre><span class="pl-ent">install</span>:
  - <span class="pl-s">mkdir -p ~/bin/ &amp;&amp; export PATH="~/bin/:$PATH"</span>
  - <span class="pl-s">curl -sfL https://raw.githubusercontent.com/reviewdog/reviewdog/master/install.sh| sh -s -- -b ~/bin</span>

<span class="pl-ent">script</span>:
  - <span class="pl-s">reviewdog -conf=.reviewdog.yml -reporter=github-pr-check</span></pre><div class="zeroclipboard-container">
    <clipboard-copy aria-label="Copy" class="ClipboardButton btn btn-invisible js-clipboard-copy m-2 p-0 tooltipped-no-delay d-flex flex-justify-center flex-items-center" data-copy-feedback="Copied!" data-tooltip-direction="w" value="install:
  - mkdir -p ~/bin/ &amp;&amp; export PATH=&quot;~/bin/:$PATH&quot;
  - curl -sfL https://raw.githubusercontent.com/reviewdog/reviewdog/master/install.sh| sh -s -- -b ~/bin

script:
  - reviewdog -conf=.reviewdog.yml -reporter=github-pr-check" tabindex="0" role="button">
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-copy js-clipboard-copy-icon">
    <path d="M0 6.75C0 5.784.784 5 1.75 5h1.5a.75.75 0 0 1 0 1.5h-1.5a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-1.5a.75.75 0 0 1 1.5 0v1.5A1.75 1.75 0 0 1 9.25 16h-7.5A1.75 1.75 0 0 1 0 14.25Z"></path><path d="M5 1.75C5 .784 5.784 0 6.75 0h7.5C15.216 0 16 .784 16 1.75v7.5A1.75 1.75 0 0 1 14.25 11h-7.5A1.75 1.75 0 0 1 5 9.25Zm1.75-.25a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-7.5a.25.25 0 0 0-.25-.25Z"></path>
</svg>
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-check js-clipboard-check-icon color-fg-success d-none">
    <path d="M13.78 4.22a.75.75 0 0 1 0 1.06l-7.25 7.25a.75.75 0 0 1-1.06 0L2.22 9.28a.751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018L6 10.94l6.72-6.72a.75.75 0 0 1 1.06 0Z"></path>
</svg>
    </clipboard-copy>
  </div></div>
<h4 tabindex="-1" dir="auto"><a id="user-content-travis-ci--reportergithub-pr-review" class="anchor" aria-hidden="true" tabindex="-1" href="#travis-ci--reportergithub-pr-review"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Travis CI (-reporter=github-pr-review)</font></font></h4>
<p dir="auto"><font style="vertical-align: inherit;"></font><a href="https://docs.travis-ci.com/user/encryption-keys/" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">通过travis 加密密钥</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">存储 GitHub API 令牌</font><font style="vertical-align: inherit;">。</font></font></p>
<div class="highlight highlight-source-shell notranslate position-relative overflow-auto" dir="auto"><pre>$ gem install travis
$ travis encrypt REVIEWDOG_GITHUB_API_TOKEN=<span class="pl-k">&lt;</span>token<span class="pl-k">&gt;</span> --add env.global</pre><div class="zeroclipboard-container">
    <clipboard-copy aria-label="Copy" class="ClipboardButton btn btn-invisible js-clipboard-copy m-2 p-0 tooltipped-no-delay d-flex flex-justify-center flex-items-center" data-copy-feedback="Copied!" data-tooltip-direction="w" value="$ gem install travis
$ travis encrypt REVIEWDOG_GITHUB_API_TOKEN=<token> --add env.global" tabindex="0" role="button">
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-copy js-clipboard-copy-icon">
    <path d="M0 6.75C0 5.784.784 5 1.75 5h1.5a.75.75 0 0 1 0 1.5h-1.5a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-1.5a.75.75 0 0 1 1.5 0v1.5A1.75 1.75 0 0 1 9.25 16h-7.5A1.75 1.75 0 0 1 0 14.25Z"></path><path d="M5 1.75C5 .784 5.784 0 6.75 0h7.5C15.216 0 16 .784 16 1.75v7.5A1.75 1.75 0 0 1 14.25 11h-7.5A1.75 1.75 0 0 1 5 9.25Zm1.75-.25a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-7.5a.25.25 0 0 0-.25-.25Z"></path>
</svg>
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-check js-clipboard-check-icon color-fg-success d-none">
    <path d="M13.78 4.22a.75.75 0 0 1 0 1.06l-7.25 7.25a.75.75 0 0 1-1.06 0L2.22 9.28a.751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018L6 10.94l6.72-6.72a.75.75 0 0 1 1.06 0Z"></path>
</svg>
    </clipboard-copy>
  </div></div>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">例子：</font></font></p>
<div class="highlight highlight-source-yaml notranslate position-relative overflow-auto" dir="auto"><pre><span class="pl-ent">env</span>:
  <span class="pl-ent">global</span>:
    - <span class="pl-ent">secure</span>: <span class="pl-s">&lt;token&gt;</span>

<span class="pl-ent">install</span>:
  - <span class="pl-s">mkdir -p ~/bin/ &amp;&amp; export PATH="~/bin/:$PATH"</span>
  - <span class="pl-s">curl -sfL https://raw.githubusercontent.com/reviewdog/reviewdog/master/install.sh| sh -s -- -b ~/bin</span>

<span class="pl-ent">script</span>:
  - <span class="pl-s">&gt;-</span>
<span class="pl-s">    golint ./... | reviewdog -f=golint -reporter=github-pr-review</span></pre><div class="zeroclipboard-container">
    <clipboard-copy aria-label="Copy" class="ClipboardButton btn btn-invisible js-clipboard-copy m-2 p-0 tooltipped-no-delay d-flex flex-justify-center flex-items-center" data-copy-feedback="Copied!" data-tooltip-direction="w" value="env:
  global:
    - secure: <token>

install:
  - mkdir -p ~/bin/ &amp;&amp; export PATH=&quot;~/bin/:$PATH&quot;
  - curl -sfL https://raw.githubusercontent.com/reviewdog/reviewdog/master/install.sh| sh -s -- -b ~/bin

script:
  - >-
    golint ./... | reviewdog -f=golint -reporter=github-pr-review" tabindex="0" role="button">
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-copy js-clipboard-copy-icon">
    <path d="M0 6.75C0 5.784.784 5 1.75 5h1.5a.75.75 0 0 1 0 1.5h-1.5a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-1.5a.75.75 0 0 1 1.5 0v1.5A1.75 1.75 0 0 1 9.25 16h-7.5A1.75 1.75 0 0 1 0 14.25Z"></path><path d="M5 1.75C5 .784 5.784 0 6.75 0h7.5C15.216 0 16 .784 16 1.75v7.5A1.75 1.75 0 0 1 14.25 11h-7.5A1.75 1.75 0 0 1 5 9.25Zm1.75-.25a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-7.5a.25.25 0 0 0-.25-.25Z"></path>
</svg>
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-check js-clipboard-check-icon color-fg-success d-none">
    <path d="M13.78 4.22a.75.75 0 0 1 0 1.06l-7.25 7.25a.75.75 0 0 1-1.06 0L2.22 9.28a.751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018L6 10.94l6.72-6.72a.75.75 0 0 1 1.06 0Z"></path>
</svg>
    </clipboard-copy>
  </div></div>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">例子</font></font></p>
<ul dir="auto">
<li><a href="https://github.com/azu/textlint-reviewdog-example"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">https://github.com/azu/textlint-reviewdog-example</font></font></a></li>
</ul>
<h3 tabindex="-1" dir="auto"><a id="user-content-circle-ci" class="anchor" aria-hidden="true" tabindex="-1" href="#circle-ci"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">圆CI</font></font></h3>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">存储</font></font><code>REVIEWDOG_GITHUB_API_TOKEN</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">（或</font></font><code>REVIEWDOG_TOKEN</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">用于 github-pr-check）在
</font></font><a href="https://circleci.com/docs/environment-variables/#setting-environment-variables-for-all-commands-without-adding-them-to-git" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">环境变量中 - CircleCI</font></font></a></p>
<h4 tabindex="-1" dir="auto"><a id="user-content-circleciconfigyml-sample" class="anchor" aria-hidden="true" tabindex="-1" href="#circleciconfigyml-sample"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">.circleci/config.yml 示例</font></font></h4>
<div class="highlight highlight-source-yaml notranslate position-relative overflow-auto" dir="auto"><pre><span class="pl-ent">version</span>: <span class="pl-c1">2</span>
<span class="pl-ent">jobs</span>:
  <span class="pl-ent">build</span>:
    <span class="pl-ent">docker</span>:
      - <span class="pl-ent">image</span>: <span class="pl-s">golang:latest</span>
    <span class="pl-ent">steps</span>:
      - <span class="pl-s">checkout</span>
      - <span class="pl-ent">run</span>: <span class="pl-s">curl -sfL https://raw.githubusercontent.com/reviewdog/reviewdog/master/install.sh| sh -s -- -b ./bin</span>
      - <span class="pl-ent">run</span>: <span class="pl-s">go vet ./... 2&gt;&amp;1 | ./bin/reviewdog -f=govet -reporter=github-pr-review</span>

      <span class="pl-c"><span class="pl-c">#</span> Deprecated: prefer GitHub Actions to use github-pr-check reporter.</span>
      - <span class="pl-ent">run</span>: <span class="pl-s">go vet ./... 2&gt;&amp;1 | ./bin/reviewdog -f=govet -reporter=github-pr-check</span></pre><div class="zeroclipboard-container">
    <clipboard-copy aria-label="Copy" class="ClipboardButton btn btn-invisible js-clipboard-copy m-2 p-0 tooltipped-no-delay d-flex flex-justify-center flex-items-center" data-copy-feedback="Copied!" data-tooltip-direction="w" value="version: 2
jobs:
  build:
    docker:
      - image: golang:latest
    steps:
      - checkout
      - run: curl -sfL https://raw.githubusercontent.com/reviewdog/reviewdog/master/install.sh| sh -s -- -b ./bin
      - run: go vet ./... 2>&amp;1 | ./bin/reviewdog -f=govet -reporter=github-pr-review

      # Deprecated: prefer GitHub Actions to use github-pr-check reporter.
      - run: go vet ./... 2>&amp;1 | ./bin/reviewdog -f=govet -reporter=github-pr-check" tabindex="0" role="button">
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-copy js-clipboard-copy-icon">
    <path d="M0 6.75C0 5.784.784 5 1.75 5h1.5a.75.75 0 0 1 0 1.5h-1.5a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-1.5a.75.75 0 0 1 1.5 0v1.5A1.75 1.75 0 0 1 9.25 16h-7.5A1.75 1.75 0 0 1 0 14.25Z"></path><path d="M5 1.75C5 .784 5.784 0 6.75 0h7.5C15.216 0 16 .784 16 1.75v7.5A1.75 1.75 0 0 1 14.25 11h-7.5A1.75 1.75 0 0 1 5 9.25Zm1.75-.25a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-7.5a.25.25 0 0 0-.25-.25Z"></path>
</svg>
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-check js-clipboard-check-icon color-fg-success d-none">
    <path d="M13.78 4.22a.75.75 0 0 1 0 1.06l-7.25 7.25a.75.75 0 0 1-1.06 0L2.22 9.28a.751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018L6 10.94l6.72-6.72a.75.75 0 0 1 1.06 0Z"></path>
</svg>
    </clipboard-copy>
  </div></div>
<h3 tabindex="-1" dir="auto"><a id="user-content-gitlab-ci" class="anchor" aria-hidden="true" tabindex="-1" href="#gitlab-ci"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">亚搏体育appGitLab持续集成</font></font></h3>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">存储</font></font><code>REVIEWDOG_GITLAB_API_TOKEN</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">在</font></font><a href="https://docs.gitlab.com/ee/ci/variables/#variables" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">GitLab CI 变量</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">中。</font></font></p>
<h4 tabindex="-1" dir="auto"><a id="user-content-gitlab-ciyml-sample" class="anchor" aria-hidden="true" tabindex="-1" href="#gitlab-ciyml-sample"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">.gitlab-ci.yml 示例</font></font></h4>
<div class="highlight highlight-source-yaml notranslate position-relative overflow-auto" dir="auto"><pre><span class="pl-ent">reviewdog</span>:
  <span class="pl-ent">script</span>:
    - <span class="pl-s">reviewdog -reporter=gitlab-mr-discussion</span>
    <span class="pl-c"><span class="pl-c">#</span> Or</span>
    - <span class="pl-s">reviewdog -reporter=gitlab-mr-commit</span></pre><div class="zeroclipboard-container">
    <clipboard-copy aria-label="Copy" class="ClipboardButton btn btn-invisible js-clipboard-copy m-2 p-0 tooltipped-no-delay d-flex flex-justify-center flex-items-center" data-copy-feedback="Copied!" data-tooltip-direction="w" value="reviewdog:
  script:
    - reviewdog -reporter=gitlab-mr-discussion
    # Or
    - reviewdog -reporter=gitlab-mr-commit" tabindex="0" role="button">
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-copy js-clipboard-copy-icon">
    <path d="M0 6.75C0 5.784.784 5 1.75 5h1.5a.75.75 0 0 1 0 1.5h-1.5a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-1.5a.75.75 0 0 1 1.5 0v1.5A1.75 1.75 0 0 1 9.25 16h-7.5A1.75 1.75 0 0 1 0 14.25Z"></path><path d="M5 1.75C5 .784 5.784 0 6.75 0h7.5C15.216 0 16 .784 16 1.75v7.5A1.75 1.75 0 0 1 14.25 11h-7.5A1.75 1.75 0 0 1 5 9.25Zm1.75-.25a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-7.5a.25.25 0 0 0-.25-.25Z"></path>
</svg>
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-check js-clipboard-check-icon color-fg-success d-none">
    <path d="M13.78 4.22a.75.75 0 0 1 0 1.06l-7.25 7.25a.75.75 0 0 1-1.06 0L2.22 9.28a.751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018L6 10.94l6.72-6.72a.75.75 0 0 1 1.06 0Z"></path>
</svg>
    </clipboard-copy>
  </div></div>
<h3 tabindex="-1" dir="auto"><a id="user-content-bitbucket-pipelines" class="anchor" aria-hidden="true" tabindex="-1" href="#bitbucket-pipelines"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">位桶管道</font></font></h3>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">无需额外配置。</font></font></p>
<h4 tabindex="-1" dir="auto"><a id="user-content-bitbucket-pipelinesyml-sample" class="anchor" aria-hidden="true" tabindex="-1" href="#bitbucket-pipelinesyml-sample"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">bitbucket-pipelines.yml 示例</font></font></h4>
<div class="highlight highlight-source-yaml notranslate position-relative overflow-auto" dir="auto"><pre><span class="pl-ent">pipelines</span>:
  <span class="pl-ent">default</span>:
    - <span class="pl-ent">step</span>:
        <span class="pl-ent">name</span>: <span class="pl-s">Reviewdog</span>
        <span class="pl-ent">image</span>: <span class="pl-s">golangci/golangci-lint:v1.31-alpine</span>
        <span class="pl-ent">script</span>:
          - <span class="pl-s">wget -O - -q https://raw.githubusercontent.com/reviewdog/reviewdog/master/install.sh | </span>
              <span class="pl-s">sh -s -- -b $(go env GOPATH)/bin</span>
          - <span class="pl-s">golangci-lint run --out-format=line-number ./... | reviewdog -f=golangci-lint -reporter=bitbucket-code-report</span></pre><div class="zeroclipboard-container">
    <clipboard-copy aria-label="Copy" class="ClipboardButton btn btn-invisible js-clipboard-copy m-2 p-0 tooltipped-no-delay d-flex flex-justify-center flex-items-center" data-copy-feedback="Copied!" data-tooltip-direction="w" value="pipelines:
  default:
    - step:
        name: Reviewdog
        image: golangci/golangci-lint:v1.31-alpine
        script:
          - wget -O - -q https://raw.githubusercontent.com/reviewdog/reviewdog/master/install.sh | 
              sh -s -- -b $(go env GOPATH)/bin
          - golangci-lint run --out-format=line-number ./... | reviewdog -f=golangci-lint -reporter=bitbucket-code-report" tabindex="0" role="button">
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-copy js-clipboard-copy-icon">
    <path d="M0 6.75C0 5.784.784 5 1.75 5h1.5a.75.75 0 0 1 0 1.5h-1.5a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-1.5a.75.75 0 0 1 1.5 0v1.5A1.75 1.75 0 0 1 9.25 16h-7.5A1.75 1.75 0 0 1 0 14.25Z"></path><path d="M5 1.75C5 .784 5.784 0 6.75 0h7.5C15.216 0 16 .784 16 1.75v7.5A1.75 1.75 0 0 1 14.25 11h-7.5A1.75 1.75 0 0 1 5 9.25Zm1.75-.25a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-7.5a.25.25 0 0 0-.25-.25Z"></path>
</svg>
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-check js-clipboard-check-icon color-fg-success d-none">
    <path d="M13.78 4.22a.75.75 0 0 1 0 1.06l-7.25 7.25a.75.75 0 0 1-1.06 0L2.22 9.28a.751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018L6 10.94l6.72-6.72a.75.75 0 0 1 1.06 0Z"></path>
</svg>
    </clipboard-copy>
  </div></div>
<h3 tabindex="-1" dir="auto"><a id="user-content-common-jenkins-local-etc" class="anchor" aria-hidden="true" tabindex="-1" href="#common-jenkins-local-etc"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">常见（詹金斯、本地等...）</font></font></h3>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">您可以使用 reviewdog 从任何具有以下环境变量的地方发布评论评论。</font></font></p>
<table>
<thead>
<tr>
<th><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">姓名</font></font></th>
<th><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">描述</font></font></th>
</tr>
</thead>
<tbody>
<tr>
<td><code>CI_PULL_REQUEST</code></td>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">拉取请求编号（例如 14）</font></font></td>
</tr>
<tr>
<td><code>CI_COMMIT</code></td>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">当前版本的 SHA1</font></font></td>
</tr>
<tr>
<td><code>CI_REPO_OWNER</code></td>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">存储库所有者（例如</font></font><a href="https://github.com/reviewdog/errorformat"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">https://github.com/reviewdog/errorformat</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">的“reviewdog” ）</font></font></td>
</tr>
<tr>
<td><code>CI_REPO_NAME</code></td>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">存储库名称（例如</font></font><a href="https://github.com/reviewdog/errorformat"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">https://github.com/reviewdog/errorformat</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">的“errorformat” ）</font></font></td>
</tr>
<tr>
<td><code>CI_BRANCH</code></td>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">[可选] 提交的分支</font></font></td>
</tr>
</tbody>
</table>
<div class="highlight highlight-source-shell notranslate position-relative overflow-auto" dir="auto"><pre>$ <span class="pl-k">export</span> CI_PULL_REQUEST=14
$ <span class="pl-k">export</span> CI_REPO_OWNER=haya14busa
$ <span class="pl-k">export</span> CI_REPO_NAME=reviewdog
$ <span class="pl-k">export</span> CI_COMMIT=<span class="pl-s"><span class="pl-pds">$(</span>git rev-parse HEAD<span class="pl-pds">)</span></span></pre><div class="zeroclipboard-container">
    <clipboard-copy aria-label="Copy" class="ClipboardButton btn btn-invisible js-clipboard-copy m-2 p-0 tooltipped-no-delay d-flex flex-justify-center flex-items-center" data-copy-feedback="Copied!" data-tooltip-direction="w" value="$ export CI_PULL_REQUEST=14
$ export CI_REPO_OWNER=haya14busa
$ export CI_REPO_NAME=reviewdog
$ export CI_COMMIT=$(git rev-parse HEAD)" tabindex="0" role="button">
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-copy js-clipboard-copy-icon">
    <path d="M0 6.75C0 5.784.784 5 1.75 5h1.5a.75.75 0 0 1 0 1.5h-1.5a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-1.5a.75.75 0 0 1 1.5 0v1.5A1.75 1.75 0 0 1 9.25 16h-7.5A1.75 1.75 0 0 1 0 14.25Z"></path><path d="M5 1.75C5 .784 5.784 0 6.75 0h7.5C15.216 0 16 .784 16 1.75v7.5A1.75 1.75 0 0 1 14.25 11h-7.5A1.75 1.75 0 0 1 5 9.25Zm1.75-.25a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-7.5a.25.25 0 0 0-.25-.25Z"></path>
</svg>
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-check js-clipboard-check-icon color-fg-success d-none">
    <path d="M13.78 4.22a.75.75 0 0 1 0 1.06l-7.25 7.25a.75.75 0 0 1-1.06 0L2.22 9.28a.751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018L6 10.94l6.72-6.72a.75.75 0 0 1 1.06 0Z"></path>
</svg>
    </clipboard-copy>
  </div></div>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">并根据需要设置令牌。</font></font></p>
<div class="highlight highlight-source-shell notranslate position-relative overflow-auto" dir="auto"><pre>$ REVIEWDOG_TOKEN=<span class="pl-s"><span class="pl-pds">"</span>&lt;token&gt;<span class="pl-pds">"</span></span>
$ REVIEWDOG_GITHUB_API_TOKEN=<span class="pl-s"><span class="pl-pds">"</span>&lt;token&gt;<span class="pl-pds">"</span></span>
$ REVIEWDOG_GITLAB_API_TOKEN=<span class="pl-s"><span class="pl-pds">"</span>&lt;token&gt;<span class="pl-pds">"</span></span></pre><div class="zeroclipboard-container">
    <clipboard-copy aria-label="Copy" class="ClipboardButton btn btn-invisible js-clipboard-copy m-2 p-0 tooltipped-no-delay d-flex flex-justify-center flex-items-center" data-copy-feedback="Copied!" data-tooltip-direction="w" value="$ REVIEWDOG_TOKEN=&quot;<token>&quot;
$ REVIEWDOG_GITHUB_API_TOKEN=&quot;<token>&quot;
$ REVIEWDOG_GITLAB_API_TOKEN=&quot;<token>&quot;" tabindex="0" role="button">
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-copy js-clipboard-copy-icon">
    <path d="M0 6.75C0 5.784.784 5 1.75 5h1.5a.75.75 0 0 1 0 1.5h-1.5a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-1.5a.75.75 0 0 1 1.5 0v1.5A1.75 1.75 0 0 1 9.25 16h-7.5A1.75 1.75 0 0 1 0 14.25Z"></path><path d="M5 1.75C5 .784 5.784 0 6.75 0h7.5C15.216 0 16 .784 16 1.75v7.5A1.75 1.75 0 0 1 14.25 11h-7.5A1.75 1.75 0 0 1 5 9.25Zm1.75-.25a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-7.5a.25.25 0 0 0-.25-.25Z"></path>
</svg>
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-check js-clipboard-check-icon color-fg-success d-none">
    <path d="M13.78 4.22a.75.75 0 0 1 0 1.06l-7.25 7.25a.75.75 0 0 1-1.06 0L2.22 9.28a.751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018L6 10.94l6.72-6.72a.75.75 0 0 1 1.06 0Z"></path>
</svg>
    </clipboard-copy>
  </div></div>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">如果 CI 服务不提供拉取请求 ID 等信息，reviewdog 可以通过分支名称猜测它并提交 SHA。</font><font style="vertical-align: inherit;">只需传递标志即可</font></font><code>guess</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">：</font></font></p>
<div class="highlight highlight-source-shell notranslate position-relative overflow-auto" dir="auto"><pre>$ reviewdog -conf=.reviewdog.yml -reporter=github-pr-check -guess</pre><div class="zeroclipboard-container">
    <clipboard-copy aria-label="Copy" class="ClipboardButton btn btn-invisible js-clipboard-copy m-2 p-0 tooltipped-no-delay d-flex flex-justify-center flex-items-center" data-copy-feedback="Copied!" data-tooltip-direction="w" value="$ reviewdog -conf=.reviewdog.yml -reporter=github-pr-check -guess" tabindex="0" role="button">
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-copy js-clipboard-copy-icon">
    <path d="M0 6.75C0 5.784.784 5 1.75 5h1.5a.75.75 0 0 1 0 1.5h-1.5a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-1.5a.75.75 0 0 1 1.5 0v1.5A1.75 1.75 0 0 1 9.25 16h-7.5A1.75 1.75 0 0 1 0 14.25Z"></path><path d="M5 1.75C5 .784 5.784 0 6.75 0h7.5C15.216 0 16 .784 16 1.75v7.5A1.75 1.75 0 0 1 14.25 11h-7.5A1.75 1.75 0 0 1 5 9.25Zm1.75-.25a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-7.5a.25.25 0 0 0-.25-.25Z"></path>
</svg>
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-check js-clipboard-check-icon color-fg-success d-none">
    <path d="M13.78 4.22a.75.75 0 0 1 0 1.06l-7.25 7.25a.75.75 0 0 1-1.06 0L2.22 9.28a.751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018L6 10.94l6.72-6.72a.75.75 0 0 1 1.06 0Z"></path>
</svg>
    </clipboard-copy>
  </div></div>
<h4 tabindex="-1" dir="auto"><a id="user-content-jenkins-with-github-pull-request-builder-plugin" class="anchor" aria-hidden="true" tabindex="-1" href="#jenkins-with-github-pull-request-builder-plugin"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">带有 GitHub 拉取请求构建器插件的 Jenkins</font></font></h4>
<ul dir="auto">
<li><a href="https://wiki.jenkins-ci.org/display/JENKINS/GitHub+pull+request+builder+plugin" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">GitHub 拉取请求构建器插件 - Jenkins - Jenkins Wiki</font></font></a></li>
<li><a href="https://docs.cloudbees.com/docs/cloudbees-ci/latest/cloud-admin-guide/github-app-auth" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">配置 GitHub 应用程序帐户 - Jenkins - CloudBees</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;"> - 需要使用 github-pr-check 格式化程序，而无需 reviewdog 服务器或 GitHub 操作。</font></font></li>
</ul>
<div class="highlight highlight-source-shell notranslate position-relative overflow-auto" dir="auto"><pre>$ <span class="pl-k">export</span> CI_PULL_REQUEST=<span class="pl-smi">${ghprbPullId}</span>
$ <span class="pl-k">export</span> CI_REPO_OWNER=haya14busa
$ <span class="pl-k">export</span> CI_REPO_NAME=reviewdog
$ <span class="pl-k">export</span> CI_COMMIT=<span class="pl-smi">${ghprbActualCommit}</span>
$ <span class="pl-k">export</span> REVIEWDOG_INSECURE_SKIP_VERIFY=true <span class="pl-c"><span class="pl-c">#</span> set this as you need</span>

<span class="pl-c"><span class="pl-c">#</span> To submit via reviewdog server using github-pr-check reporter</span>
$ REVIEWDOG_TOKEN=<span class="pl-s"><span class="pl-pds">"</span>&lt;token&gt;<span class="pl-pds">"</span></span> reviewdog -reporter=github-pr-check
<span class="pl-c"><span class="pl-c">#</span> Or, to submit directly via API using github-pr-review reporter</span>
$ REVIEWDOG_GITHUB_API_TOKEN=<span class="pl-s"><span class="pl-pds">"</span>&lt;token&gt;<span class="pl-pds">"</span></span> reviewdog -reporter=github-pr-review
<span class="pl-c"><span class="pl-c">#</span> Or, to submit directly via API using github-pr-check reporter (requires GitHub App Account configured)</span>
$ REVIEWDOG_SKIP_DOGHOUSE=true REVIEWDOG_GITHUB_API_TOKEN=<span class="pl-s"><span class="pl-pds">"</span>&lt;token&gt;<span class="pl-pds">"</span></span> reviewdog -reporter=github-pr-check</pre><div class="zeroclipboard-container">
    <clipboard-copy aria-label="Copy" class="ClipboardButton btn btn-invisible js-clipboard-copy m-2 p-0 tooltipped-no-delay d-flex flex-justify-center flex-items-center" data-copy-feedback="Copied!" data-tooltip-direction="w" value="$ export CI_PULL_REQUEST=${ghprbPullId}
$ export CI_REPO_OWNER=haya14busa
$ export CI_REPO_NAME=reviewdog
$ export CI_COMMIT=${ghprbActualCommit}
$ export REVIEWDOG_INSECURE_SKIP_VERIFY=true # set this as you need

# To submit via reviewdog server using github-pr-check reporter
$ REVIEWDOG_TOKEN=&quot;<token>&quot; reviewdog -reporter=github-pr-check
# Or, to submit directly via API using github-pr-review reporter
$ REVIEWDOG_GITHUB_API_TOKEN=&quot;<token>&quot; reviewdog -reporter=github-pr-review
# Or, to submit directly via API using github-pr-check reporter (requires GitHub App Account configured)
$ REVIEWDOG_SKIP_DOGHOUSE=true REVIEWDOG_GITHUB_API_TOKEN=&quot;<token>&quot; reviewdog -reporter=github-pr-check" tabindex="0" role="button">
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-copy js-clipboard-copy-icon">
    <path d="M0 6.75C0 5.784.784 5 1.75 5h1.5a.75.75 0 0 1 0 1.5h-1.5a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-1.5a.75.75 0 0 1 1.5 0v1.5A1.75 1.75 0 0 1 9.25 16h-7.5A1.75 1.75 0 0 1 0 14.25Z"></path><path d="M5 1.75C5 .784 5.784 0 6.75 0h7.5C15.216 0 16 .784 16 1.75v7.5A1.75 1.75 0 0 1 14.25 11h-7.5A1.75 1.75 0 0 1 5 9.25Zm1.75-.25a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-7.5a.25.25 0 0 0-.25-.25Z"></path>
</svg>
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-check js-clipboard-check-icon color-fg-success d-none">
    <path d="M13.78 4.22a.75.75 0 0 1 0 1.06l-7.25 7.25a.75.75 0 0 1-1.06 0L2.22 9.28a.751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018L6 10.94l6.72-6.72a.75.75 0 0 1 1.06 0Z"></path>
</svg>
    </clipboard-copy>
  </div></div>
<h2 tabindex="-1" dir="auto"><a id="user-content-exit-codes" class="anchor" aria-hidden="true" tabindex="-1" href="#exit-codes"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">退出代码</font></font></h2>
<p dir="auto"><font style="vertical-align: inherit;"></font><code>0</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">默认情况下，即使发现错误，</font><font style="vertical-align: inherit;">reviewdog 也会作为退出代码返回。</font><font style="vertical-align: inherit;">如果标志被传递，</font><font style="vertical-align: inherit;">则当至少发现/报告一个错误时，</font></font><code>-fail-on-error</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">reviewdog 退出。</font></font><code>1</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">当您将其用作 CI 管道中的步骤并希望在 linter 发现任何错误时将该步骤标记为失败时，这会很有帮助。</font></font></p>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">另请参阅</font><a href="#reporter-github-checks--reportergithub-pr-check"><font style="vertical-align: inherit;">github-pr-check/github-check</font></a></font><code>-level</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">记者的标志</font><font style="vertical-align: inherit;">。</font><font style="vertical-align: inherit;">如果报告的检查状态</font><font style="vertical-align: inherit;">也是如果 ，则</font><font style="vertical-align: inherit;">reviewdog 将退出</font><font style="vertical-align: inherit;">。</font></font><a href="#reporter-github-checks--reportergithub-pr-check"><font style="vertical-align: inherit;"></font></a><font style="vertical-align: inherit;"></font><code>1</code><font style="vertical-align: inherit;"></font><code>failure</code><font style="vertical-align: inherit;"></font><code>-fail-on-error=true</code><font style="vertical-align: inherit;"></font></p>
<h2 tabindex="-1" dir="auto"><a id="user-content-filter-mode" class="anchor" aria-hidden="true" tabindex="-1" href="#filter-mode"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">过滤模式</font></font></h2>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">reviewdog 通过 diff 过滤结果，您可以控制 reviewdog 如何通过</font></font><code>-filter-mode</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">标志过滤结果。</font><font style="vertical-align: inherit;">可用的过滤器模式如下。</font></font></p>
<h3 tabindex="-1" dir="auto"><a id="user-content-added-default" class="anchor" aria-hidden="true" tabindex="-1" href="#added-default"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a><code>added</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">（默认）</font></font></h3>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">按添加/修改的行过滤结果。</font></font></p>
<h3 tabindex="-1" dir="auto"><a id="user-content-diff_context" class="anchor" aria-hidden="true" tabindex="-1" href="#diff_context"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a><code>diff_context</code></h3>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">按差异上下文过滤结果。</font><font style="vertical-align: inherit;">即改变了行+-N行（例如N=3）。</font></font></p>
<h3 tabindex="-1" dir="auto"><a id="user-content-file" class="anchor" aria-hidden="true" tabindex="-1" href="#file"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a><code>file</code></h3>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">按添加/修改的文件过滤结果。</font><font style="vertical-align: inherit;">即，只要结果在添加/修改的文件中，即使结果不在实际差异中，reviewdog 也会报告结果。</font></font></p>
<h3 tabindex="-1" dir="auto"><a id="user-content-nofilter" class="anchor" aria-hidden="true" tabindex="-1" href="#nofilter"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a><code>nofilter</code></h3>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">不过滤任何结果。</font><font style="vertical-align: inherit;">对于尽可能将结果作为评论发布并同时在控制台中检查其他结果很有用。</font></font></p>
<p dir="auto"><code>-fail-on-error</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">也适用于任何过滤模式，并且可以捕获任何带有</font></font><code>nofilter</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">模式的 linter 的所有结果。</font></font></p>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">例子：</font></font></p>
<div class="highlight highlight-source-shell notranslate position-relative overflow-auto" dir="auto"><pre>$ reviewdog -reporter=github-pr-review -filter-mode=nofilter -fail-on-error</pre><div class="zeroclipboard-container">
    <clipboard-copy aria-label="Copy" class="ClipboardButton btn btn-invisible js-clipboard-copy m-2 p-0 tooltipped-no-delay d-flex flex-justify-center flex-items-center" data-copy-feedback="Copied!" data-tooltip-direction="w" value="$ reviewdog -reporter=github-pr-review -filter-mode=nofilter -fail-on-error" tabindex="0" role="button">
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-copy js-clipboard-copy-icon">
    <path d="M0 6.75C0 5.784.784 5 1.75 5h1.5a.75.75 0 0 1 0 1.5h-1.5a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-1.5a.75.75 0 0 1 1.5 0v1.5A1.75 1.75 0 0 1 9.25 16h-7.5A1.75 1.75 0 0 1 0 14.25Z"></path><path d="M5 1.75C5 .784 5.784 0 6.75 0h7.5C15.216 0 16 .784 16 1.75v7.5A1.75 1.75 0 0 1 14.25 11h-7.5A1.75 1.75 0 0 1 5 9.25Zm1.75-.25a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-7.5a.25.25 0 0 0-.25-.25Z"></path>
</svg>
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-check js-clipboard-check-icon color-fg-success d-none">
    <path d="M13.78 4.22a.75.75 0 0 1 0 1.06l-7.25 7.25a.75.75 0 0 1-1.06 0L2.22 9.28a.751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018L6 10.94l6.72-6.72a.75.75 0 0 1 1.06 0Z"></path>
</svg>
    </clipboard-copy>
  </div></div>
<h3 tabindex="-1" dir="auto"><a id="user-content-filter-mode-support-table" class="anchor" aria-hidden="true" tabindex="-1" href="#filter-mode-support-table"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">过滤模式支持表</font></font></h3>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">请注意，由于 API 限制，并非所有报告器都提供对过滤器模式的完全支持。</font><font style="vertical-align: inherit;">例如</font></font><code>github-pr-review</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">，记者使用</font></font><a href="https://docs.github.com/en/rest/pulls/reviews"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">GitHub Review API</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">和</font></font><a href="https://docs.github.com/en/rest/pulls/comments"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">GitHub Review Comment API</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">，但这些 API 不支持在 diff 文件之外发布评论，因此 reviewdog 将使用</font></font><a href="https://docs.github.com/en/rest/checks/runs"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Check 注释</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">作为后备来发布这些评论 [1]。</font></font></p>
<table>
<thead>
<tr>
<th><code>-reporter</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">\</font></font><code>-filter-mode</code></th>
<th><code>added</code></th>
<th><code>diff_context</code></th>
<th><code>file</code></th>
<th><code>nofilter</code></th>
</tr>
</thead>
<tbody>
<tr>
<td><strong><code>local</code></strong></td>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">好的</font></font></td>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">好的</font></font></td>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">好的</font></font></td>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">好的</font></font></td>
</tr>
<tr>
<td><strong><code>github-check</code></strong></td>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">好的</font></font></td>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">好的</font></font></td>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">好的</font></font></td>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">好的</font></font></td>
</tr>
<tr>
<td><strong><code>github-pr-check</code></strong></td>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">好的</font></font></td>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">好的</font></font></td>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">好的</font></font></td>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">好的</font></font></td>
</tr>
<tr>
<td><strong><code>github-pr-review</code></strong></td>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">好的</font></font></td>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">好的</font></font></td>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">好的</font></font></td>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">部分支持 [1]</font></font></td>
</tr>
<tr>
<td><strong><code>github-pr-annotations</code></strong></td>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">好的</font></font></td>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">好的</font></font></td>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">好的</font></font></td>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">好的</font></font></td>
</tr>
<tr>
<td><strong><code>gitlab-mr-discussion</code></strong></td>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">好的</font></font></td>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">好的</font></font></td>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">好的</font></font></td>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">部分支持 [2]</font></font></td>
</tr>
<tr>
<td><strong><code>gitlab-mr-commit</code></strong></td>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">好的</font></font></td>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">部分支持 [2]</font></font></td>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">部分支持 [2]</font></font></td>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">部分支持 [2]</font></font></td>
</tr>
<tr>
<td><strong><code>gerrit-change-review</code></strong></td>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">好的</font></font></td>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">好的？</font><font style="vertical-align: inherit;">[3]</font></font></td>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">好的？</font><font style="vertical-align: inherit;">[3]</font></font></td>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">部分支持？</font><font style="vertical-align: inherit;">[2][3]</font></font></td>
</tr>
<tr>
<td><strong><code>bitbucket-code-report</code></strong></td>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">否 [4]</font></font></td>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">否 [4]</font></font></td>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">否 [4]</font></font></td>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">好的</font></font></td>
</tr>
<tr>
<td><strong><code>gitea-pr-review</code></strong></td>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">好的</font></font></td>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">好的</font></font></td>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">部分支持 [2]</font></font></td>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">部分支持 [2]</font></font></td>
</tr>
</tbody>
</table>
<ul dir="auto">
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">[1] 如果在 GitHub 操作而不是 Review API 中运行，则报告 diff 文件外部的结果，并使用 Check 注释作为后备（评论）。</font><font style="vertical-align: inherit;">所有结果也将报告给控制台。</font></font></li>
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">[2] 将 diff 文件之外的结果报告给控制台。</font></font></li>
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">[3] 它应该可以工作，但尚未得到验证。</font></font></li>
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">[4] 暂未实施</font></font></li>
</ul>
<h2 tabindex="-1" dir="auto"><a id="user-content-debugging" class="anchor" aria-hidden="true" tabindex="-1" href="#debugging"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">调试</font></font></h2>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">使用该</font></font><code>-tee</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">标志来显示调试信息。</font></font></p>
<div class="highlight highlight-source-shell notranslate position-relative overflow-auto" dir="auto"><pre>reviewdog -filter-mode=nofilter -tee</pre><div class="zeroclipboard-container">
    <clipboard-copy aria-label="Copy" class="ClipboardButton btn btn-invisible js-clipboard-copy m-2 p-0 tooltipped-no-delay d-flex flex-justify-center flex-items-center" data-copy-feedback="Copied!" data-tooltip-direction="w" value="reviewdog -filter-mode=nofilter -tee" tabindex="0" role="button">
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-copy js-clipboard-copy-icon">
    <path d="M0 6.75C0 5.784.784 5 1.75 5h1.5a.75.75 0 0 1 0 1.5h-1.5a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-1.5a.75.75 0 0 1 1.5 0v1.5A1.75 1.75 0 0 1 9.25 16h-7.5A1.75 1.75 0 0 1 0 14.25Z"></path><path d="M5 1.75C5 .784 5.784 0 6.75 0h7.5C15.216 0 16 .784 16 1.75v7.5A1.75 1.75 0 0 1 14.25 11h-7.5A1.75 1.75 0 0 1 5 9.25Zm1.75-.25a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-7.5a.25.25 0 0 0-.25-.25Z"></path>
</svg>
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-check js-clipboard-check-icon color-fg-success d-none">
    <path d="M13.78 4.22a.75.75 0 0 1 0 1.06l-7.25 7.25a.75.75 0 0 1-1.06 0L2.22 9.28a.751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018L6 10.94l6.72-6.72a.75.75 0 0 1 1.06 0Z"></path>
</svg>
    </clipboard-copy>
  </div></div>
<h2 tabindex="-1" dir="auto"><a id="user-content-articles" class="anchor" aria-hidden="true" tabindex="-1" href="#articles"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">文章</font></font></h2>
<ul dir="auto">
<li><a href="https://medium.com/@haya14busa/reviewdog-a-code-review-dog-who-keeps-your-codebase-healthy-d957c471938b" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">reviewdog——保持代码库健康的代码审查狗</font></font></a></li>
<li><a href="https://medium.com/@haya14busa/reviewdog-github-check-improved-automated-review-experience-58f89e0c95f3" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">reviewdog ♡ GitHub Check — 改进的自动审核体验</font></font></a></li>
<li><a href="https://medium.com/@haya14busa/automated-code-review-on-github-actions-with-reviewdog-for-any-languages-tools-20285e04448e" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">使用 reviewdog 对任何语言/工具在 GitHub Actions 上进行自动代码审查</font></font></a></li>
<li><a href="https://evrone.com/blog/github-actions" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">GitHub Actions 保护您的工作流程</font></font></a></li>
</ul>
<h2 tabindex="-1" dir="auto"><a id="user-content-bird-author" class="anchor" aria-hidden="true" tabindex="-1" href="#bird-author"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">🐦 作者</font></font></h2>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">哈亚14巴士</font></font><a href="https://github.com/haya14busa"><img src="https://camo.githubusercontent.com/8b4f6c8dc674e0bea77661773fa6c5ec81d63ea72e9406d27f216c16211c128d/68747470733a2f2f696d672e736869656c64732e696f2f6769746875622f666f6c6c6f776572732f686179613134627573612e7376673f7374796c653d736f6369616c266c6162656c3d466f6c6c6f77" alt="GitHub 关注者" data-canonical-src="https://img.shields.io/github/followers/haya14busa.svg?style=social&amp;label=Follow" style="max-width: 100%;"></a></p>
<h2 tabindex="-1" dir="auto"><a id="user-content-contributors" class="anchor" aria-hidden="true" tabindex="-1" href="#contributors"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">贡献者</font></font></h2>
<p dir="auto"><a href="https://github.com/reviewdog/reviewdog/graphs/contributors"><img src="https://camo.githubusercontent.com/bd673f7d5dff0ea7869a2ca85057759bef47b0c160e45d1d2daec448ba48d1e3/68747470733a2f2f6f70656e636f6c6c6563746976652e636f6d2f726576696577646f672f636f6e7472696275746f72732e7376673f77696474683d383930" alt="贡献者" data-canonical-src="https://opencollective.com/reviewdog/contributors.svg?width=890" style="max-width: 100%;"></a></p>
<h3 tabindex="-1" dir="auto"><a id="user-content-supporting-reviewdog" class="anchor" aria-hidden="true" tabindex="-1" href="#supporting-reviewdog"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">支持评审狗</font></font></h3>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">成为</font></font><a href="https://github.com/reviewdog/reviewdog/graphs/contributors"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">每个贡献者的 GitHub 赞助商或成为</font></font></a><font style="vertical-align: inherit;"></font><a href="https://opencollective.com/reviewdog" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">opencollective</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">
的支持者或赞助商</font><font style="vertical-align: inherit;">。</font></font></p>
<p dir="auto"><a href="https://opencollective.com/reviewdog#backers" rel="nofollow"><img src="https://camo.githubusercontent.com/94ce96f54c0460cbc7da446824250ab4bf6ccb994f628bb780705f9986a4362c/68747470733a2f2f6f70656e636f6c6c6563746976652e636f6d2f726576696577646f672f74696572732f6261636b65722e7376673f6176617461724865696768743d3634" alt="成为支持者" data-canonical-src="https://opencollective.com/reviewdog/tiers/backer.svg?avatarHeight=64" style="max-width: 100%;"></a></p>
</article></div>
