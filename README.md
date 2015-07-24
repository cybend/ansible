[![PyPI version](https://badge.fury.io/py/ansible.png)](http://badge.fury.io/py/ansible)
[![PyPI downloads](https://pypip.in/d/ansible/badge.png)](https://pypi.python.org/pypi/ansible)
[![Build Status](https://travis-ci.org/ansible/ansible.svg?branch=devel)](https://travis-ci.org/ansible/ansible)


Ansible
=======

Ansible是一个极为简便的IT自动化部署系统。它可以进行配置管理、应用程序部署、提供云平台的应用管理、可以进行点对点任务和多节点任务的协调执行，包括可以利用负载均衡冗余技术对系统应

用进行不停机的更新。
获取更多的文档资料请访问：http://ansible.com/ 【英文】

许多用户喜欢使用自己二次开发的分支版本（一般来说这样也是可以的），但希望可以共享出一个新的版本。

在这里你可以找到不同平台的版本，但如果你决定去开发分支版本，请确保在git上签出ansible源码后要进行更新和初始化版本。

安装方面你可以到http://releases.ansible.com/下载一个二进制源码包进行编译安装，同时也可以通过yum、apt或是"pip install ansible"等方式来安装ansible。

设计原则
=================

   *极为简便的安装和极为容易学习掌握
   *可以非常快速的并行管理机器
   *不需使用代理客户端和开放额外的端口，只要使用现有的ssh服务即可
   *脚本语言不管对机器还是使用者都是非常通俗易懂
   *专注于安全性和脚本的可审计/检查/重写的方便性
   *不需要借助其他软件来管理远程的机器
   *可以使用任何一种动态语言来开发ansible的模块，不局限于Python
   *可以使用非超管的权限来操作
   *不管现在还是未来都是最简便的IT自动化管理系统

分支信息
===========

   *版本的命名是以范海伦的歌曲命名
   *许多分支版本都在积极的开发中
   *虽然1.8版本后，有很多不同模块存放在不同的镜像安装源中，但你只要遵循ansible的[内核core](https://github.com/ansible/ansible-modules-core)和[扩展extras](https://github.com/ansible/ansible-modules-extras)的规则即可。
   *过去有很多以 release-X.Y 命名的分支版本
   *我们很乐意收到你贡献的版本，请查看[社区通告Community Information](http://docs.ansible.com/community.html)，通告中会详细介绍，如何发行你的个人开发的版本

作者
=======

Ansible是由[Michael DeHaan](https://github.com/mpdehaan) (michael.dehaan/gmail/com)开发创建，并有超过1000名开源社区开发者贡献了自己的开发代码，谢谢各位。
Ansible是由 [Ansible 公司](http://ansible.com)赞助

