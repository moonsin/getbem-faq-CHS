# getbem-faq-CHN-
FAQ of getbem.com in Chinese
#FAQ#
这些频繁被问到的问题是刚刚开始使用BEM的开发者们真实遇到的问题，由GetBEM社区来回答。请不要客气地的随便提问，然后我们也会解答。

为什么我要选择BEM而不是其他的CSS模块化解决方案？
-为什么修饰符(modifier)的CSS类们不能用联合选择器来代表？ 
-为什么我需要用块的CSS类来代替使用语义化的传统标签？ 
-为什么我需要同时使用块和带前缀的修饰符来定义修饰符块？ 
-一个块修饰符能不能影响元素？ 
-我能不能创建一个全局的修饰符(modifier)来适用于任意一个块(block) 
-我能不能联合一个标签和一个类在选择器里，就像button.button？ 
-通过其CSS内容来命名修饰符这样好吗？比如 .block__element--border-bottom-5px 
-当一个元素嵌套在另一个元素里面，应该怎么命名？比如 block__elem1__elem2？ 
-我听说BEM不推荐全局CSS reset ？为什么？ 
-没有找到答案？ 


###为什么我要选择BEM而不是其他的CSS模块化解决方案###

有一些其他的CSS的模块化解决方案（比如OOCSS,AMCSS,SMACSS,SUITCSS)。我们选择BEM的原因们是什么。
BEM为所有的前端技术提供了解决方案：CSS,JavaScript,templating(模板），也有web应用的建立过程。这个方法论适用于任何地方。让这个方法论适用于JavaScript和templating的时候你需要专门的框架，但是用在CSS的时候你可能只需要依照推荐的方法。CSS部分是BEM里最简单的能应用在你的开发过程中的。这就是为什么很多人只用这一部分。另一方面，如果你近来发现你的项目充分的使用了BEM并且你自己因为维护而开心，你大概就准备进行下一步来模块化的你的web应用了。BEM CSS可以更简单的调整模块化JavaScript 和基于块的项目文件结构
如果只谈CSS模块化解决方案，BEM特色的关键是块的相互独立。
