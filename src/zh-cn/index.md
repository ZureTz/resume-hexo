---
# 语言 （可选）
lang: zh-cn
# 网页关键词和描述
keywords: 计算机科学, 软件开发, 个人简历
description: 黄劲松的个人简历 - 计算机科学与技术专业
# 简历标题
resume_title: 黄劲松的简历
# 应聘者姓名
name: 黄劲松
avatar: https://cdn.jsdelivr.net/gh/xaoxuu/cdn-assets/avatar/avatar.png
# 联系方式
contact:
  - icon: fas fa-globe-asia
    text: https://resume.trozure.uk
    url: https://resume.trozure.uk/zh-cn/
  # 邮箱
  - icon: fas fa-envelope
    text: pineehuang@icloud.com
    url: mailto:pineehuang@icloud.com
  # 电话号码
  - icon: fas fa-phone-alt
    text: +86 18163384338
    url: tel:+86-18163384338
# PDF下载链接
download:
  title: 下载本站源码
  icon: fas fa-download fa-fw
  url: https://github.com/ZureTz/resume-hexo
---

{% raw %}
<center>
<a href='/'>English</a> | <a href='/zh-cn/'>简体中文</a>
</center>
{% endraw %}

## <i class="fas fa-clipboard-check"></i> 个人优势

- **技术能力**: 掌握C/C++, Python, JavaScript等主流编程语言, 了解Go/Java等语言, 知道RESTful API的基本工作流程, 以及后端编程语言实现所需要的技术栈, 熟悉基本的数据结构和算法/操作系统/网络原理的知识, 熟悉Socket编程, 参照RFC 959设计和实现了FTP的客户端和服务器端
- **运维能力**: 熟悉Linux系统, 能够熟练使用Linux命令行, 了解Docker容器化技术, 了解 CI/CD 流程
- **学习效率**: 自学能力强, 能够快速适应新技术栈和开发环境, 具备持续学习的意愿和能力, 能够流畅阅读英文技术文档, 具备独自学习和解决问题的能力
- **团队协作**: 沟通表达清晰, 团队合作意识强, 有良好的项目协调能力和责任心, 熟悉Git和GitHub, 有过开源经验, 知道如何提出Issue, 提出过Pull Request并且获得维护者认可

## <i class="fas fa-user-graduate"></i> 教育背景

**中国石油大学(北京)(211)** 
- **本科 人工智能学院 计算机科学与技术专业**
- **预计毕业时间: 2026年6月**
- **学习成绩: GPA 4.0/5.0（专业前5%）**
- **英语能力: IELTS 7.5(6.5)**

## <i class="fas fa-award"></i> 项目经历

### os-webserver - 高性能Web服务器
**2024年5月 ~ 2024年6月** 架构设计和实现

自主设计并实现的高性能HTTP服务器, 从零开始构建的高性能Web服务器架构 

技术栈: `C` `Make` `Pthread` `GLib` `FUSE`
- 针对高并发访问需求，通过Linux Pthread线程池技术实现性能提升1000%以上
- 为减少重复请求处理开销，采用glib数据结构(二叉排序树和哈希表)构建HTTP请求缓存机制
- 为提升文件访问效率，集成fuse等核心库构建轻量级内存文件系统，访问速度提升100%
- 个人收获: 深入理解HTTP协议和Web服务器架构设计原理，掌握Linux系统编程和多线程并发控制技术，熟悉文件系统底层接口和内存映射机制
- 项目成果: 通过系统级优化实现了传统单线程服务器无法达到的性能指标，项目代码质量和技术创新获得校内操作系统课程最高评价
- 项目地址: [https://github.com/ZureTz/os-web-server](https://github.com/ZureTz/os-web-server)

### shorter-url - 短链接生成服务
**2025年3月 ~ 2025年4月** 核心功能设计和实现

为解决长URL分享不便和链接管理困难的问题，设计并实现了该短链接生成服务。系统提供短链接生成、自定义别名、有效期管理等核心功能，通过集中化的链接管理平台提升链接分享的效率。

技术栈: `Go` `Echo` `JWT` `PostgreSQL` `Redis`

- 为满足现代Web应用的用户体验需求，采用前后端分离架构，通过Go/Echo构建高性能RESTful API，Next.js/React构建响应式界面
- 为解决大量链接访问的性能瓶颈，通过PostgreSQL存储核心数据，Redis缓存热门链接，显著提升用户访问体验
- 为保障用户数据安全，集成JWT用户认证机制和Bcrypt密码加密，并提供邮箱验证码找回功能
- 为满足用户个性化需求，实现短链接自定义别名、有效期设置、个人管理面板等实用功能
- 为降低运维成本，通过定时任务自动清理过期数据，数据库迁移工具管理结构变更，Docker容器化简化部署
- 项目仓库: [https://github.com/ZureTz/shorter-url](https://github.com/ZureTz/shorter-url)
- 即刻使用: [https://s.trozure.uk](https://s.trozure.uk)

## <i class="fas fa-code"></i> 开源贡献

- **[KhronosGroup/Vulkan-Samples](https://github.com/KhronosGroup/Vulkan-Samples)**: 发现并修复API文档中的技术错误, 提交完整文档改进方案, 获项目维护者认可并合并
- **[MaiM-with-u/MaiBot](https://github.com/MaiM-with-u/MaiBot)**: 修复了WebUI动态配置功能模块, 解决配置难点问题, 获得同项目维护者好评

## <i class="fas fa-laptop-code"></i> 技能证书/其他

- **编程语言**: C/C++, Go, TypeScript, Python
- **技术框架**: Linux系统编程, Gin/Echo, SQLc, PostgreSQL, Redis, RESTful API调试(Postman), Web后端开发(Go), Web前端开发(React, TypeScript)
- **开发工具**: Linux, Git, VS Code, Docker
- **软技能**: 具备良好的团队协作和沟通能力; 英语能力强(IELTS 7.5), 有独立阅读英文技术文档的能力

## <i class="fas fa-user-tie"></i> 在校经历

#### 教学助理(TA) 
**2025年3月 ~ 2025年6月**

- 部分负责学院Online Judge系统(acm.cup.edu.cn)的维护与优化
- 协助教授组织和迁移100+编程题库, 设计评分标准和自动化测试用例, 提高评测准确性
- 一对一辅导20+名本科生, 解决技术难题, 进行代码审核, 提升了学生编程能力
- 主持编程实践课程, 培训50+名学生掌握标准开发流程和工具链, 提升教学反馈满意度

## <i class="fas fa-phone-alt"></i> 与我联系

当前状态: 在校学生, 可实习时间三个月以上, 一周内可到岗

<i class="fas fa-envelope fa-fw"></i> [pineehuang@icloud.com](mailto:pineehuang@icloud.com)
<i class="fas fa-phone-alt fa-fw"></i> [+86 18163384338](tel:+86-18163384338)

## 评论

{% raw %}
<script src="https://utteranc.es/client.js"
        repo="ZureTz/resume-hexo"
        issue-number="18"
        theme="github-light"
        crossorigin="anonymous"
        async>
</script>
{% endraw %}
</script>
{% endraw %}
</script>
{% endraw %}
</script>
{% endraw %}
