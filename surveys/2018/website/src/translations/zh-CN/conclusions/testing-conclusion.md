---
type: conclusion
section: testing
locale: zh-CN
---
测试方面的现状则稍显不同。如今，JavaScript 生态系统的其他部分在经过一段时间的发展与沉淀后日渐稳定，且已产生几个公认的解决方案。相比之下，测试方面则还处在混乱时期：许多不同的或相互配合的工具相对平均地瓜分了测试工具体系。尽管如此，开发者对测试环境的解决方案整体上还是满意的。根据今年的调查结果，测试类工具满意度最低的也有 68%。

调查结果还显示，**Mocha** 依旧是当下最热门的单元测试框架，它坐拥超过一万名用户。由于 Mocha 的存在时间较长，因此它拥有测试框架中最大的生态系统，而且大部分 Node.js 开发者也很熟悉它。

**Jest** 在使用量方面仅次于 Mocha；但相对于 Mocha 82% 的满意度，Jest 的满意度为 96%。值得注意的是，Jest 96% 的满意度，在今年调查的所有工具中排名第二，第一名是 ES6。

看来，开发者对 Facebook 提供的这个功能完备的测试框架十分满意。Jest 一开始只是用来测试 React 组件的，但现在它不光可以用来测试前端代码，甚至可以用于测试后端代码。而这一切都不需要进行额外地配置。

在“单页面应用”时代，随着越来越多的逻辑被迁移到客户端，网页应用已经变得越来越复杂。今年的调查也表明，开发者会使用多种测试类工具来测试他们开发的应用。

其实，测试包含很多方面：单元测试、集成测试、端对端测试，同时还有“视觉测试”（visual testing）。值得注意的是 **Storybook**，它是“视觉测试”方面一个很好的应用，同时也是这类工具中满意度第二高的。

测试的其中一个未来趋势就是在浏览器中引入自动化测试。我们会考虑在下一年的调查中添加此类工具，比如 [Cypress](https://www.cypress.io/)。同时，我们应该会在明年看到更多基于 [Puppeteer](https://pptr.dev/) 的新工具。
