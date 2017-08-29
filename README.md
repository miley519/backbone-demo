# backbone-demo

几乎所有的框架都是在做两件事：一是帮你把代码写在正确的地方；二是帮你做一些脏活累活。Backbone实现一种清晰的MVC代码结构，解决了数据模型和视图映射的问题。虽然所有JS相关的项目都可以用，但Backbone最适合的还是这样一种场景：需要用JS生成大量的页面内容(HTML为主)，用户跟页面元素有很多的交互行为。

Backbone对象有5个重要的函数，Model/Collection/View/Router/History。Router和History是针对Web应用程序的优化，建议先熟悉pushState的相关知识。入门阶段可以只了解Model/Collection/View。将Model视为核心，Collection是Model的集合，View是为了实现Model的改动在前端的反映。

blog url:http://weinian2015.com/?p=1180
