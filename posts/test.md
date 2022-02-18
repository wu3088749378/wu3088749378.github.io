---
title: ' Git操作指令 '
date: 2022-02-18 09:31:08
tags: []
published: true
hideInList: false
feature: https://tse1-mm.cn.bing.net/th/id/R-C.ed53702a1ea8f802982a69de8152cb4b?rik=7PHgnokcEyHOvw&riu=http%3a%2f%2fwww.yh31.com%2fUploadFiles%2fArticle2%2fPZSMK8%2f20111%2f201101291250544684.gif&ehk=%2b20HqCAPjb8TAulgWB4UPa9JIbwINtz1LuPUa%2bh01Ww%3d&risl=&pid=ImgRaw&r=0
isTop: false
---
<div class="demo">
<style>
    .demo{
        width:700px;
        heigth:100%;
        margin:0 auto;
        padding:0;
        background-image:url(https://tse1-mm.cn.bing.net/th/id/R-C.350e884cdb67ba634bcc2bc272d20115?rik=6nZfydRn9R3tXw&riu=http%3a%2f%2fwww.tupian1.cn%2fuploads%2fallimg%2f160907%2f1-160ZH24026.gif&ehk=1viW%2fPwW9WqUaCIZPK2Eh8oXUzzse6YbQgWNGbfji60%3d&risl=&pid=ImgRaw&r=0);
        text-algin:center;
        background-repeat:no-repeat;
        background-size:100% 100%;
    }
    h3{
        color:blue;
    }
</style>
<h2>Git</h2>
<p style="color:red">Workspace：工作区；&nbsp;&nbsp;Index/Stage：暂存区；&nbsp;&nbsp; Repository：仓库区(或本地仓库)&nbsp;&nbsp;Remote：远程仓库</p>
<h3>新建代码仓库</h3>
<p>在当前目录新建一个Git代码库<br>git init</p>
<p>新建一个目录，将其初始化为Git代码库<br>git init [project-name]</p>
<p>下载一个项目和它的整个代码历史<br>git clone [url]</p>
<code>如果想要成功克隆，当前目录必须得是一个git仓库</code>
<h3>配置Git</h3>
<p>Git的设置文件为<mark>.gitconfig</mark>，它可以在用户目录下(全局配置)，也可以在项目目录下(项目配置)</p>
<p>显示当前的Git配置<br>git config --list</p>
<p>编辑Git配置文件<br>git config -e [--global]</p>
<p>设置提交代码时的用户信息<br>git config [--global] user.name "[name]"<br>git config [--global] user.email "[email address]"</p>
<h3>文件添加到暂存区</h3>
<p>添加指定文件到暂存区<br>git add [file1] [file2] ...</p>
<p>添加指定目录到暂存区，包括子目录，目录中不能为空，必须要有文件<br>git add [dir]</p>
<code>添加每个变化前，都会要求确认</code>
<p>对于同一个文件的多处变化，可以实现分次提交<br>git add p</p>
<p>删除工作区文件，并且将这次删除放入暂存区<br>git rm [file1] [file2] ...</p>
<code>已经添加到仓库的文件可以删除，工作区不显示</code>
</div>
