# Winter-Vacation-Record

> 我现在觉得，没有什么比坚持记录自己的成长一段时间后再回头感受更有成就感的事情了。

## Focusing On...?

- useAxios（`<GlobalConfig>`、`cancelToken`） :fire:
- 逃避闭包&useRef，why and why not:ambulance:

## 计划剩余部分

- 当前进行的

  - 小程序服务端
  - Mutable-App
  - Docker使用
  - 复习JavaScript基础/设计模式
  
- 计划

  - MySQL与MongoDB深入点
  - Ts！

- 等待优化/单测/e2e/重构/部署的

  - 美团app，重构数据流，优化配置，测试，tsx等
  - ssr-github，优化细节表现
  - ts-axios，等找一个能替代jasmine-ajax的库
  - Apollo，client（react）和server，各种相关工具链以及它们应当如何被测试？尤其是useQuery和useMutation。

- 未开始/刚有想法/犹豫的

  - 脚手架、生成器、构建器，把准备抽的模板也放在这里吧

  - 仿Sentry的前端错误监控系统
  - Flutter
  - Taro？
  - vuepress-theme-penumbra，可以顺便复习vue，待定
  - 一个VS Code插件，待定

- 计划中的剩余技术栈
  - umi dva antd-pro，不确定是不是要试着写一个umi插件，之前想过的那个
  - rx.js  
  - TypeDI TypeOrm

## 2020-2-20

- 我怎么感觉复习基础比写代码还累呢，大概四个小时就感觉脑子转不动了˚̑̑̑̑̑༾(-᷄◞८̻◟-᷅)༿˚̑̑̑̑̑ 还是说寒假快结束了感觉开始犯懒了？醒醒啊大哥，下个月20号你估计要正式开始面试了
- 因为脑子转不动了感觉效率变低，就想做点简单的，把之前的美团app掏出来重构了，然后正式决定放弃这个鬼玩意( -᷅_-᷄ )，升级了下react-redux(因为要用它的hook)，结果babel崩了，reset了一下，继续小心翼翼的尝试，结果另外一个崩了，爬爬爬，有这时间我还不如再认真写一个。于是准备就把这个东西复盘一下好了。毕竟当时数据流还挺折磨我的，感觉写这种带好几种筛选条件的数据还是直接从后端取好啊。前端一次性把数据全取回来不是安排自己呢嘛
- useSelector性能优化的博客写到一半，原本能写完的，结果发现了可以扩展开来的地方，一时收不住了。(其实寒假能写博客整理的东西多了去了，就是懒)
- 还准备过几天写一篇事件循环的
- 明天搞一哈ci/cd，还有看下博客还需要哪些技术栈~

## 2020-2-19

- 确定了一下准备复习的重点，还有准备做在简历上的项目。最“有亮点的”应该就是博客CMS了，但是完全不同之前做的那个练手的，准备用Gatsby，配Apollo和GraphQL，然后做成SSR的形式，自己写（学）一个SSR框架。然后后端用正宗的ts+koa来做（是的我觉得以前挺不正宗的，只用到了ts的类和接口，连工具类型都只用过一两个...）。但是还要焦头烂额的准备基础等等。
- 还准备做几个工程化方面的玩意，希望会有用。
- 手动要看的书，数据结构&设计模式&http&css世界&深入浅出nodejs，呜呜呜。

## 2020-2-18

- 准 备 面 试
- 心 力 交 瘁
- 啊我真的好希望能再多一点时间，真想回到几个月前给自己一个嘴巴子，只会点Vue还沾沾自喜我真是佛了！
- 我能感觉到自己的学习能力比以前强很多很多了，但是还是不够，事实上我感觉进了家园以后才是真正的学习，不论是上来就做的一个React项目（那时甚至还不会React），还是接下来加入大家一起写新的云家园，我都感觉这才是真正的学习。去年9月到现在，也不过半年不到，我需要赶上别人三年的进度。太艰难啦
- ...也没啥好说的，努力就是了。

## 2020-2-17

- 啊西巴，手动导完表才知道是created_at设置为0000:00:00有的版本会有问题，不管是不是浪费了我十分钟也蛮火大的。
- 还是这边写一点那边写一点的状态，优化了一下这个修了一下那个，oss的ci报错了淦，因为从`"antd/es/form"` 引入了类型定义，但是ci的时候直接把它当成模块了？是要再找个ts的set-up的意思吗？
- 不行明天不能拖了，就搞单测和e2e。还有http起个头
- 呜呜呜没时间啦

## 2020-2-16

- 今天主要复习了一下this和作用域，我发现人的大脑好像真的是越学越好用的，搁几个月前让我看怎么看也看不懂估计只能死记硬背，但是现在读起来就顺顺当当地。明天复习下闭包和原型，先把这几座大山给放下来吧。
- immutable这个课买的也太值了，全是我感觉很宝贵的新思路，比如二次封装better-scroll地思路，还有forwardRef这玩意之前我咋就是没搞懂，现在一瞅觉得就是挺简单一小玩意儿。
- 小程序地后端真的写的累人，不知道是不是我用了ts的关系经常报奇怪的错，感觉每跑通一个接口都开心的不行。对了之前对验证器的想法真的太蠢了，万一有人用脚本或者postman这种工具呢？对吧对吧

## 2020-2-15

- 看了一下这个仓库也40个commit了，惊觉寒假其实已经过去了...，如果是按照正常的寒假开学，那我绝对极度没信心吧，因为cms、小程序前后端都是真·寒假结束后才开始的。如果不和人比那我绝对还对自己有信心，但随手看到的面经都是这么厉害的...。已经开始准备面试，大致包括算法/数据结构/网络/html/css及布局/js基础/ts/工程化/Vue基本使用/React底层这些方面，怎么算都要一个月吧...，准备好一边练科二科三一边复习了。
- 完成了cms的大致功能，后面就是继续优化细节和新增功能咯。
- 开始新坑，React+Immutablejs实现一个音乐app~，明天要不把美团app重构了吧。

## 2020-2-14

- 抓抓脑壳，才发现OSS里面我转发的时候用了流，我以为可读流pipe可写流是同步的，结果今天随手复习下node发现它们都是EventEmitter的实例！那上面肯定有on监听！试了下监听end和finish（是这个），鬼鬼看到文件上传成功我真的眼泪都下来了呜呜呜。一鼓作气写好了大致的功能，还是专心做成图床好点感觉，不然弹框返回链接和markdown图片就没啥意义了啊。
- 其余之外十分平淡，写小程序服务端，ts重构了下xlog，顺手加了个boxen让打印结果更骚皮一点点。
- react-redux的useSelector API感觉挺有意思的。
- 说到ts，突然想到我好像没怎么用过泛型和工具类型相关的知识...，就算有也是简单的入参T出参T这种，要不再琢磨琢磨？
- 明日：
  - OSS界面右侧加个Bucket信息展示，有心情的话把多图片的实现考虑下。诶要不还是做个网盘，但是检测到类型是图片会返回md？否则就一个单独的链接？可！那把文件夹也安排上。
  - 小程序服务端，之前总觉得校验器没必要，后面才想到不是什么时候接口都有一个UI界面的，有时候就是接口和接口之间通信。这么想还是有必要的。
  - useSelector重构demo~
  - docker开个头

## 2020-2-13

- 真是见了鬼了今天，被bug缠身。早上写小程序服务端，MySQL一直报错，多一个额外的字段`true`，是的不是值是字段！最开始查了说是编码的问题，把所有表都换成utf-8和general_ci也不行，瑞了，一扔准备明天手动建表完事。
- 然后写OSS，前面都顺顺利利，搭建项目（再次提醒我要早点把cli做起来了），前端页面、Koa接收文件然后转发给OSS SDK...，对就卡在这里了。大概是这样，Koa接收到文件存在临时文件夹下，调用我封装了一层的OSS函数，把文件传到OSS上再返回地址，再对地址做一下处理，结果传上去发现是0KB大小！检查了路径/入参/权限等等问题，都没有发现是哪里的bug。我把路径log出来，直接放到oss的函数里就可以...，真是见鬼了。
- 接着写CMS，这个时候已经到晚上了，可想而知今天到底有多自闭。有效编码时间大概只有两个小时，其他时候都在绞尽脑汁地找bug。写cms的时候也遇到问题了，不过简单一些，因为路由部分是直接复制的之前代码，登陆之后使用`window.location.replace()`方法跳转的而不是 `props.push()`，然后session丢失了（这个我还不清楚具体原因关联，因为最后还是用replace但也解决了问题），不过也有可能是axios配置的问题。
- node的万字长文还没看，koa的源码也还没看，flutter的环境也还没搭好...，想了一下当前计划（这个鬼计划反而越来越长了）的进度，估计寒假前能够呛完成把。

## 2020-2-12

- 小程序服务端，新增了小程序登陆方式，wx的api有点鬼畜..
- 聊天聊着聊着就被拉去开黑了，意志力薄弱舍我其谁，原本今天准备写个OSS的上传器也只是大概读完了相关文档，准备用流来写，明天整活！
- 今天玩得是很爽，但又有负罪感了...，列个明天的计划：
  - Koa源码
  - 小程序后端继续跟进，写完/v1/classic/latest下3个api
  - CMS的三个地方，继续跟进。快写完了，继续确定优化，考虑后端切成ts的必要性？
  - 再看一下graphql里面的单测？
  - node的那篇文章！
  - 阅读

## 2020-2-11

- 开始看设计模式了，原本没打算这么早，但是今天看redux源码的时候发现设计模式真的重要哦，一边读一边搭flutter环境，果然，没搞定哈哈哈哈哈。
- 写CMS和小程序~，感觉博客的中台前端要做好得很下功夫啊，毕竟自己用的，肯定精雕细琢诶嘿嘿嘿，然后会非常下功夫的把这个项目做到尽力的好。把这个做成简历上敢拿出来讲的一个系统。
- 好像每一天都更坚定一点，也更有自信一点。

## 2020-2-10

- 感觉在电脑面前坐了很久，又感觉什么都没做。被seqeulize和ts搭配的两个小bug卡了好久，感觉每次被bug卡住都很耗脑力，这次的bug是在源码和StackOverflow上找了好久才解决的，虽然只是两个小选项的事。
- 博客cms感觉花时间会比预计长很多，因为对每一个页面我都有自己的想法，比如登录准备加个游客模式，在前端做正则校验blabla（虽然也妹必要但就当练手了）。
- 说到校验我就感觉小程序的后端有点诡异，我个人倾向把大部分校验放在前端来做，比如基础的非空、格式、字段长度和安全系数blabla，阻止不符的提交，感觉实在没有必要在后端扩展一堆类对应不同的错误类型啊...，也可能是我小农意识了（小声bb）
- 突然想起来还有几个坑没填啊...，ts-axios的单测，美团app的重构，useAxios的逻辑...

## 2020-2-09

- 正常跟进所有项目，但是进度一般，主要是精确定位bug的能力不足，经常找bug半天发现是一个弱智错误...
- 今天瑞了  就不总结了

## 2020-2-08

- 感觉忙了很久又感觉啥都没做，主要熟悉了下sequelize，折腾了下和ts的协作，看到有个包叫sequelize-typescript，用的装饰器语法，有点畏惧，就没上了。虽然语法是真的简化了很多。
- 小程序后端，我吐了接近三百多行的js代码我重构成ts了，一小部分暂时不确定先用any（anyscript成了）代替，明天要从头研究下这个校验器，因为这种能大大简化开发流程的东西真的挺让人心动的，整个@budu/koa-validator？
- 再去看了下之前写的Apollo App，修复了一个小bug，不过不是官方的是我瞎改改的。突然想到时候把这个也重构下部署到服务器上...，多加点功能啥的，但是！还是没有开始看react-apollo！
- 回头复习了下泛型等一些概念，觉得果然还是得不断回头才会感觉自己学到了。
- enzyme和hooks...，我有点头疼。
- 搭好了CMS的前端，吐血了等抽出手来一定要把所有常用的都弄个构建器！！！
- 明天，cms前后端，琢磨下校验器，写一下小程序后端，找一下高程第四版，nginx的文章，用egg写个rest的模板熟悉下。

## 2020-2-07

- 小程序后端，只写好了全局错误处理等几个小功能，因为视频是js我直接用的ts，在定义错误基类上有些地方不一样，折腾了下，明天应该能把进度跟到下一个难点之前。
- 回头复习了下ES6的类和装饰器几个地方，感觉有必要把es6标准入门再拾起来复习几遍。感！觉！自己！有点！会写代码！了！
- 开始写博客的CMS了，读了一个小时egg文档，记录了大概600+行的重点。感觉和koa像又不像，但是我还是挺喜欢的...，真实，用一个框架爱一个框架，只要是新的东西几乎我就喜欢。还有，发现约定式配置这个东西真的好玩欸，之前用 Next.js 的时候就感到了，有一种爱不释手的感觉。开始想这背后的加载器逻辑应该挺好玩的，根据文件名把控制器/服务挂载到全局上下文blabla
- 阿西吧还是漏了一些事情没做  比如看到了新的apollo-client教程，还有就是之前写的哪个app好像有点老了？要不要重新整个活？

## 2020-2-06

- 。。。今天是被装环境折磨的一天，天知道为什么装个MySQL也能这么麻烦啊，前面以为是和MongoDB数据文件位置冲突了，改配置，不行，换成装 MSI Installer，结果卡在检查密码可用性了，我真是醉了...，后面大概是重装到第四次的时候用命令行的方式装好跑起服务连上Navicat了。
- 写了下Jest和Enzyme，觉得这个就没必要也搞个Jest-pratice了。但是忘记再去研究ts-axios的单测了...
- 小程序的后端，原本因为有基础的原因乐悠悠开着视频两倍速装MySQL，结果后面搞出真火了。本来打算今天把前面的二十来节零基础全看完的也耽搁了。我好恨！！
- 小程序后端这个模块我准备做成Koa的RESTFUL，看了些中间件，大概之前没见过而又感觉有用的有 `koa.io` `koa-logger` `koa-onerror`等几个小玩意。好玩！
- 早上复习了下ts和es6的类，然后重写了下@budu/xlog，觉得有那么点明白面向对象的好处了。得劲！
- 看`parcel`的时候注意到了动态import，又去研究了一下webpack和tc39的实现。
- 明天，jest、小程序后端继续搭模板（到时候会把整个抽出来做一个构建器，对这个项目多余的就删掉），再开一个线程，博客的CMS，原课程用的js，准备逼自己写tsx。
- 至于开什么小线程就看明天会瞄到什么文章吧~

## 2020-2-05

- 昨天其实也做了不少事情。但后面被拉去开黑一时兴奋忘掉了做总结...，昨天写完了小程序，写了Apollo服务端和客户端的文章，（码字真的前面很兴奋后面慢慢麻木了）
- 今天翻书签看到`Docs`里有个`Parcel`还没用过，就去尝试了一下，做了个简单的SPA模板丢到了GitHub上，感觉这玩意比webpack简单、快速太多了，但是灵活性就一般，毕竟少了那么多配置项。当然也可以猜测它是在内部自动做好了一些事情，比如ignore掉一些目录、针对性寻找扩展名等等。自带的HMR 服务器也不错奥。
- 开始学那门Jest的课了，之前的问题一直没解决。只看到了mock axios回应之类的解决方案，但由于ts-axios是个请求库，单测要事无巨细的跟踪请求，项目里的用的是有点老的jasime-ajax，我再找找吧。
- 开始写小程序后端，感觉到时候写脚手架花样真的太多了，前端 react/vue/svetle，服务端Koa/Egg，打包器 Webpack/Parcel，数据库 MongoDB / MySQL，还有REST/GraphQL，Apollo...，鬼鬼，有丶意思。
- 明天要继续跟进jest、小程序后端，同时做一些零碎的小的项目，感觉这种两三个大进程配几个小进程还挺好玩的。

## 2020-2-03

- 今天好像有点PTSD的意味，没法专心下来写代码。写Apollo-App的时候也基本都是copy的，没有很仔细地看每一步是为什么。跟着小册学ts也有点晕，准备暂停一下小册学习了，否则会有点眼高手低的意味。
- 小程序还剩最后一节了，遗留了一个BUG给明天，希望明天的我不会痛骂今天的我...
- 稍微整理了下首屏加载方案
- 明天，写完小程序，打磨优化一下交互（借这个机会认真读下文档），试下WeUI，试下上线工作。美团app继续重构下吧。

## 2020-2-02

- 这么浪漫的日子里我竟然享受到了报警和伤情鉴定还有民事调解，真是十分开心呢。
- 写好了 Apollo文档里全栈app服务端的基础部分，不确定是现在学Sequelize还是等微信小程序后端用到了再学。讲道理我咋感觉这个教程设计者也太有心了，连单测啥的都给你写好了。不管我要删掉然后根据每个unit的描述自己写一下。
- @budu/xlog，新增了一个问询保存的交互与跳过问询的选项，越写越乱了啊，一大堆if /else if/else 的，重点是各个选项之间有可能矛盾啊... 是因为我没用面向对象的思维写吗
- 希望明天不要有事情了，突然觉得能安心写代码是福气

## 2020-2-01

- 鬼使神差的决定给自己放一天假，因为好像放假回来还没有放肆地玩一天，于是写完小程序的搜索组件就奖励自己当一天废物了。顺便整理了下寒假计划剩余部分。
- 整理完感觉应该能完成的差不多，毕竟又延后开学了。等把这些东西都完善、丰满起来，应该就能放心的

## 2020-1-31

- 计划被打乱咯，失去五点到八点这段最宝贵的时间，导致原本准备安排在这段时间的Apollo教程的全栈APP没能完成（或者说没能正式开始）。我觉得支撑我努力下去的理由之一就是为了能不做自己不喜欢的事吧。问题不大，明天补回来就是了。
- 写了个命令行工具，比较简陋，用来当todolist/idea之类的用，纯粹是想熟练下commander一类的命令行工具还有Node-fs的API，到时候写cli会熟练点，结果发现好像真的挺好玩的。如果不是要紧的事太多估计会开开心心的玩下去。
- 小程序今天写了蛮多的，书籍详情一整个界面和交互。突然想到一个问题，服务端是根据什么来判断当前用户的，微信的token？
- 又发现了几个很心动的项目... 但是真的怕没时间...

## 2020-1-30

- 美团外卖APP重构工作好像比我想得难，数据流有点绕，MPA是每个入口维护一个数据流的？热重载的时候还要专门处理下数据流的问题？重点是页面间的数据流也有点诡异，今天还有个诡异的BUG，一个组件，用FC写不行，但是用类组件写就可以！淦，我估计又是闭包，但是最后才缩小到闭包上，建议明天给它冲掉。
- GraphQL，没想到Apollo-Server的文档上的graphql教程比官网详细这么多，但是估计得把前面的demo推翻重来了，也准备留到明天。
- 学了一下Node的进程和线程，想到之前自制的API其实有几个地方也可以用子进程来做？但是Node的确挺好玩的，收集了点Node教程准备看
- 小程序，进展正常，但是CSS部分现在都是直接粘贴的，准备在复习的时候再掏出来看。

### 明

- 明天是1月的最后一天咯，总有一种诡异的仪式感，估计明天会做不少事。

## 2020-1-29

- 美团app 页面（jsx）部分重构完成，接下来安排：先搭建一个简易服务端读JSON文件，优化数据流，看是否能直接上dva，然后再重构服务端，预计还是用MongoDB。再用tsx重构页面，然后进行工程化方面的优化（是的，我觉得配webpack是末尾奖励...）
- GraphQL今天进展还行，明天准备上Apollo-Client，这玩意感觉也是个大生态啊...，Apollo-react/vue，Apollo-server-express/koa/hapi...，Apollo-Link，...，喵喵喵？然后这个搞完了还有TypeGraphQL和PostGraphQL，或许这就是前端吧...
- 复习了下Node，感觉得更重视一些Node了...，再过几年估计页面就是拖拽可视化了...
- 小程序，准备接下来的异步不用async/await了，感觉自己有点舍本逐末了，很多情况下Promise性能更好吧，毕竟js最怕的就是阻塞。

## 2020-1-28

### 今

- 小程序编译一直通不过，以为是应用了regenerator.runtime.js的问题，但是又不舍得把async/await全部搞掉换成callback，查了好久发现竟然是开发者工具版本问题！！！回退了之后立马就好了，我人傻了。今天写好了音乐组件，原本想着剩下50节一天学个十几二十节几天就搞定了，结果剩下里面起码有十来节长度一个小时左右的。果然小程序花样多啊...，但是也感觉到了，缓存的重要性，虽然可能会成倍提升开发难度，但对于用户体验和性能优化（减少请求数量、载荷）是值得入坑的。
- GraphQL，搞定了输入对象类型，疑惑自己前几天到底为啥能卡在这。剩下指令、内联片段需要再研究一下。需要开始研究Apollo了，否则写原生GraphQL语法真的要人老命。
- CLI，emmm需要挺多时间的，新东西yeoman全家桶、各种“调味料”、可配置/交互项考量啥的。还需要写generator和builder，还不能够通用。要不要先把builder内置在构建器里？比如直接集成nodemon/ts-node/pm2到koa项目依赖？
- 把科学上网的教程整理收集了下收录到博客了，有点灌水的感觉。
- 美团APP页面部分全部重构完成，接下来开始研究数据流及逻辑的优化咯
- 读掘金小册深入浅出TS，感觉写的挺好的奥，又有新收获了。

### 明

- GraphQL
- meituan APP
- 小程序
- TS

## 2020-1-27

### 今

- ...为啥每次只要有过长时间的集中精神就会晕晕乎乎啊...。
- 早上集中时间复习了下useState和闭包的相关知识，感觉懂了七成，更多的估计要深入源码/看更多拆解文章了。
- 准备 看AST --> 写webpack loader和plugin的时候见鬼了，被那篇介绍AST的文章吸引住了，跟着写了个npm包，可以把原本普通的js文件转换为可导出的模块（commonjs），但是！发包的时候卡住了...，我到处没找到和我一样错的，403，被安全机制阻止，啥办法都试了就是不行。我今天心态大甭
- 搭了个飞机，还是挺快乐的，三端通用，网速超快。妈妈再也不用担心我翻不了墙了。一个月5美元大概30+人名币，但是上StackOverflow啥的都是秒开了。
- 重构美团app的代码重构的我想吐，一个600多行的类组件，里面是层层嵌套的函数...，写了将近两个小时因为牵一发动全身，特别是原作者的函数名和内部的dispatch名字是一样的，类组件没问题一换FC立马全部循环引用栈溢出了。原本commit完刚好1000新增还觉得长出一口气，结果发现还有一整个文件夹数十个component要重构。啊我s
- 没开始读深入浅出ts！我好恨
- 小程序，因为我全部采用的是async/await的写法，教程用的是回调函数，所以凡是异步逻辑我就得万分小心。今天就是，调BUG调了好久... 发现resolve的参数只能是res.data，否则写入缓存的时候取不到key，淦！

### 明

- 再尝试下发包，然后就是plugin/loader
- 美团app剩下的重构，就算是shi我也忍了，毕竟都快吃完了
- cli
- ts
- graphql-codesandbox

## 2020-1-26

### 今

- 开始读源码（lodash和useAxios）的时候发现了一件事情，我对读源码并不是很有兴趣，而且能力也并不是很够，比如useAxios里的泛型套泛型就把我整的够呛，是的我最后还是放弃了...，等ts学的再好一点吧。在掘金买了本小册，因为看试读感觉还挺好的，至少不是照抄文档了。但是Redux和Koa的源码我应该还是会去看的~
- GraphQL解决昨天遗留的，但是又碰到了新问题...，怎么嵌套的传递参数啊呜呜呜，比如我先根据id查用户，再根据年龄选定符合条件的。。。，我觉得应该就是查询树或者变更树嵌套啊但是一直报错（field）？有一篇教程写的很好但是是用python跑的，语法不太一样。俺自闭了，还要继续研究研究...
- 拾起了快忘掉了的美团app，这代码重构的我想死，全是巨大的类组件，还有一层接一层的div...，准备先简单的用FC和基础Hooks重构，后面上ts和dva的时候再推翻。
- 不知道为啥突然想到了本来准备留给寒假末尾的cli，因为估计要延迟开学了，末尾啥的没啥意义了。找到了一个大佬写的精简版cli，准备基于它搞二次开发。但是！！！！为什么我好像真的对Class理解不了啊呜呜呜，更没想到这个也是基于class写的...所以我一边痛苦一边快乐
- 今天没写小程序...

### 明

- 手写webpack-plugin，并整理AST相关到penumbra
- 美团app，完成基础重构
- cli，升级依赖，如commander
- graphql再试试，看看codesandbox上有没有相关模板资源

## 2020-1-25

### 今

- 啊...GraphQL的文档属实写的不好，每个知识点就写那么一段没啥意义的代码？？今天用比较粗糙的方式写好了CRUD，但是发现几个地方文档里并没有提到或者提了的示例代码没啥用。重新找了一个大佬做的教程准备明天重新搞以下。感觉这东西学好了用处多多？GitHub的api V4就开始使用GraphQL了，说不定到时候SSR-GitHub也可以用这个版本的API重构下。还剩下几个问题，输入对象类型无法使用，内联片段，拆分查询/操作树等。
- 新开了个记录读源码的库，过程中瞄到了另外一篇挺有意思的文章，埋点方案设计的，感觉挺好玩并且值得整理，就记录到了[Penumbra](https://github.com/linbudu599/Penumbra/blob/master/FE/Track/main.md)里，过程耗时两个小时，各种工具和方案都好奇地试了下。emmm明天开始读Lodash源码整体架构？感谢这些写文章的带哥门
- 小程序的事件机制有点抓瞎，拆分组件的思路很是值得学习！专注于组件自身的事，但又能灵活的被调用~

- 被疫情吓到了，赶紧多买了口罩，YZB标准以上的都被抢完了，害。
- 再尝试了下读useAxios源码，啊啊啊读不进去。明天一早起来读吧

### 明

- 读useAxios
- 写GraphQL
- 写小程序
- 读Lodash
- 写单测
- 美团APP

## 2020-1-24

### 今

- 单测稳定进行，虽然磕磕绊绊的但好歹写的越来越得心应手了。有几个问题还没有解决，关于部分诡异的异步逻辑，还有之前明明感觉天衣无缝的代码竟然跑测试不通过，鬼鬼，果然很有必要搞这个。
- 主要的时间在研究GraphQL，总是想把暂时复杂度不高的逻辑就用高级API来写，结果撞得头破血流呜呜呜我图啥啊，还不是希望以后再写复杂逻辑的时候能得心应手...，比如GraphQLInputObject‘Type，愣是报错，不知道是因为ts的原因没引用正确的泛型还是用的地方错了...koa和ts也有些地方还要研究下。
- 突然发现读源码其实也可以作为一个新线程啊...，和手撕代码写项目并不冲突，还可以当成调剂！明天开始读Lodash源码！
- 给博客配了埋点~

### 明

- 继续跟进现在的任务就好啦，最好开始搞一下react-apollo

## 2020-1-23

### 今

- ts-axios功能至此已经完成（课程部分），后续会再根据官方axios的功能进行扩展，考虑包含Node部分的封装。开始写单测，感觉还挺有意思？？就是边界情况要考虑的真的多诶。而且Jest文档功能一堆，有时间会精读一下选一些可能用得上的功能。
- 练手GraphQL的时候遇到了不少问题，比如MongoDB和TS协作、Koa开启GraphiQL（这个其实百度一下就有，只是我一开始先入为主的去npm上找了），以及GraphQL的Mutation问题。
- 小程序！进展一般，今天没有特别惊艳的收获或者特别烦人的坑。剩余80节课程。

### 明

- MongoDB与TS协作问题！
- 写完大部分单测，或者至少写到50%覆盖率左右
- graphql连接数据库的CRUD
- 小程序预计20节？写一个完整的有交互能力的页面先

## 2020-1-22

### 今

- 啊...，又要开新坑了，准备用graphql+dva+ts+apollo等等写一个todolist，预计会有一次很大的突破，以controller和decorator等语法来写，顺便为nest.js打基础
- 感觉写脚手架要提上日程了，每次都是把之前配好的复制下也太没牌面了，但是现在进度比较赶，再推一推吧...，等到有空了一定要整一个具有牌面的
- ts-axios，重新配一下server，估计要开始写单测了...，cover6、70先将就一下吧
- 小程序，按照每天15~20小节的进度来。今天发现要在小程序里痛痛快快地写原本的代码还真没那么方便，想用async/await还需要专门去拷贝regenerator包里packages/runtime.js这个文件，对版本还有要求，得是0.7左右的，惊了

### 明

- 搭好整个todolist项目结构
- ts-axios/小程序/react-hooks-axios
- 淦，进度真的得加快了，寒假还有读源码这个环节

## 2020-1-21

### 今

- 开始过年了...，往年封建迷信和拜年让我觉得挺好玩的，今年就让我感觉是在浪费大好时光了。主要写了 ts-axios 和继续阅读小程序文档，东西真的还蛮多的。
- 继续学 GraphQL，一时被 Mutation 和 constructing type 搞得有点绕
- useAxios 在看原作者的实现的时候发现 tsx 还有一部分知识需要补一下，于是把原本的自定义 hooks 仓库改成了用于整理写 react 中的经验收集

### 明

- 灵活安排，仍然主要是 GraphQL（Mongoose？）/小程序/useAxios/ts-axios 这几驾马车

## 2020-1-20

### 今

- 新开线程：小程序，评估了一下难度，感觉不是完全崭新的东西，稍微有难度就是 API 和布局啥的了，生命周期的特性我很喜欢，像回到了写 Vue 的青涩年华（？）。预计这门课只需要一周左右，比较有难度的是后面要给茵茵整一个用来记录恋爱琐事防止欠亲亲不给的小程序。
- ts-axios 进度正常，每天写几个 feature，再用自己对 ts 的浅薄认识优化下（我也不知道是不是真的优化了...），看着它一点点完善起来就好兴奋。明天后面的功能就简单得多了，可以补一下几个模块的 doc。
- 开始学 GraphQL，感觉比起 REST 是的确更有优势，无冗余、易维护、要啥就给啥...，得劲！虽然还没学到但是大概有思路后面要怎么在 resolver 里连数据库来进行图式查询了。
- 还是感觉时间不够用，剩下三周左右里还需要完成一个 RN-APP 和一个用于博客的 CMS，以及 Nest 啊 Rx.js 啊等等

### 明

- useAxios，用 ts 推翻重构（跟随原作者思路），全局配置、取消等，从 Umi-hooks 或者 react-use 找几个比较有意义的 hooks 记录等待学习（临幸）
- 跟进小程序、GraphQL、ts-axios

## 2020-1-19

### 今

- 上午主要以 ts-axios 为主，项目庞大之后要弄懂各个功能需要的时间更多了。但是也体会到了用 ts 的好处，不管是 vscode 的强力支持还是各个接口严丝合缝的吻合都有点带劲。
- 复习了一下移动端的知识，包括 JSBridge、Hybrid、rem、vw/vh/vmin/vmax...等等等等，美团 APP 不准备从头到尾跟着视频学了，时间不够。并且这个项目不像 ssr-github 一样那么复杂而且都是新东西，都是已经有不错熟练度的技能如 redux 等。但是准备换一种思路，把它重构一遍，从升级依赖到 tsx 重写，到服务端 RESTFul 等等。应该算个不大不小的挑战。

### 明

- 考虑加一个进程，Blog-CMS 或者小程序。
- 看了一下需要再开始学一门新的东西了，GraphQL/Rx.JS/Immutable.JS/...
- ！忘记非攻老师的公众号还剩一些文章没看完了。

## 2020-1-18

### 今

- 给 hacker-srcipt 提了个[pr](https://github.com/NARKOZ/hacker-scripts/pull/186)，但不是新增语言实现的...，而是很弟弟的把它的 README 翻译了下，虽然应该要很长时间才会收到这个回应（作者好像不咋维护这个仓库了），最近的一个被 close 的 pr 已经是两个月前了。但还是感觉挺有成就感的，或许再过不久我就能给一些开源项目提正经的 PR 了。
- 开始整移动端，感觉好久没写移动端了...JSBridge 啥的都忘光了。准备寒假学两门 APP 开发的课，RN 和 Hybrid。
- ts-axios，今天写了三个 feature，默认配置合并、axios.create()方法扩展、transform 方法实现。准备写完之后看完 axios 源码再继续向着官方完善

### 明

- 为 Penumbra 增添一篇新的文章，[你不知道的 JSON.stringify()](https://github.com/)，学问深的很啊...
- 移动端。（冷漠）

## 2020-1-17

### 今

- ssr-github 完成，但是出现了一个教程里没有的 bug，估计是 GitHub Api 变更了，就像 GitHub OAuth 登陆拿 token 的时候也和视频里的不一样，从对象变成了字符串（字典？）形式，暂时没有处理。

- puppteer 真的好好玩啊，感觉可以用来抢票、爬虫、各种模拟机器人等等，下午花了一个下午的时间研究了几个比较有意思的功能，最后也卡在了一个 bug 上：

  - `evaluate` 方法内无法调用全局函数（模块），即是用 `exposeFucntion` 挂载到 windows 上也是一样...，issues 里有条遇到了和我一样的问题就是用 `exposeFucntion` 解决的，我这是被安排了？

- ts-axios 的配置合并部分，需要的时间超出预期，因此今天没有完成。
- useAxios 重新看和实现了一遍，仍旧没有解决，忐忑不安的把代码都贴给那位前辈了
- 接触了下 feflow，觉得挺简单易上手的，脚手架和构建器知识估计后面写 wss-generator 的时候也可以用上。
- 还是感觉进度偏慢了，觉得自己定位 bug 并迅速解决的能力还有待提升，经常卡在莫名其妙的 bug 上。

### 明

- ssr-github，定位问题并解决
- ts-axios，配置合并、axios.create() 方法扩展
- useAxios，看看作者会不会回复 issue
- 小程序

## 2020-1-16

### 今

- useAxios，作者回复了 issue，但是我今天再看发现估计是我自己的问题，可能又是闭包的锅，准备明天沉下心来再推翻重来。
- ssr-github，issues 界面比我想得难不少...，进度得再推后一到两天，哈哈哈哈想把部署环节当成奖励。今天发现了几个可以再度优化的点：
  - 是否需要把封装过的 `api请求方法` 再封装一层，或者提高原来的封装程度，但这样会不会过于耦合了？
  - 有几个组件感觉还能复用，尤其是拆分成多个文件，但这样可能会影响 `getInitialProps` 或者使得数据流更复杂？需要思考下组件复用的相关思维了
- ts-axios，继续完成了拦截器部分，越来越庞大了整个结构，但是也越来越兴奋了，ts 真的太适合用来写这种复杂应用了。
- dracula，一个新的仓库，主要是之前看了英剧德古拉之后觉得伯爵吸了别人的血就拥有了别人的记忆、能力这点很有意思哈哈哈哈哈。主要突然有这个想法也是因为在群里看到一个学弟自己写的一个 npm 包 [inob](https://github.com/kidonng/inob)，自叹弗如。再次遗憾自己要是大一就进家园就好了。不求像一些神仙一样小学开始学 VB 啥的。

#### 明

- puppeteer，搞一下基本操作，把之前看的那本 ts 入门教程爬下来试试
- feflow 的使用！一直想学一下来的
- 完善 ssr-github 到可部署上线阶段
- ts-axios，跟进到测试部分之前
- h5（孙哥哥的那个仓库）

## 2020-1-15

### 今

- ts-axios 基础工作已经完成，准备开始后续的拦截器、cancelToken 部分，我说 axios 源码怎么有 15k 呢...，这考虑的是真的多。学习到了 typescript 继承内置对象 Error 时需要手动 `Object.setPrototypeOf(this, AxiosError.prototype)` 一下。然后就是觉得这个思路如果让我自己来写起码要有一年工作经验才能写得出来，各处泛型、将类实例和函数结合到一起的思路等等。
- ssr-github 已经接近尾声，剩余 issues 界面的开发，感觉很喜欢这个老师的授课方式，和你一起把坑踩一遍，然后告诉你为啥这是个坑，或者推翻重来告诉你如何提高程序性能（缓存、复用等）。应该会继续完善下去，毕竟 GitHub API 那么完善。如果 next 支持 ts 的话也准备用 ts 重构一下，感觉这个项目还是挺有必要的，各种各样的数据类型、函数重载等。
- 准备开始搞 puppeteer 的时候，被安排的明明白白，因为担心只下 core 可能以后搞大的不够，所以下的完整版，但是一下下了半个小时，所以我就只能孤零零的整个 README 放上学习资源。

### 明

- puppeteer 的基础使用，完成部分功能如爬虫、合并 PDF，考虑基于 puppeteer 写个爬虫工具，React+TS+Koa+MongoDB？再议
- ssr-github，完成、样式调整、撰写文档、测试（暂无）、部署上线，github.linbudu.top
- ts-axios，继续推进
- 准备开始移动端的学习了

## 2020-1-14

### 今

- ssr-github 与 ts-axios 进展顺利，准备给 ts-axios 写下具体的分析文档，作者的思路有点跳跃，需要缓缓。
- useAxios 卡住了，估计不是我的理解问题，去作者源码看了一下，作者写在专栏文章里的应该是简化了 80%的版本。给作者提了个 issue 看看有什么办法先把简易版本的实现了再向源码进发。（ps：作者是 17 年毕业的，现在在饿了么工作，比一下感觉自己太弱了...）
- 配了下 webpack5，目前还没遇到破坏性变更，体会到了编译速度提升的确挺大。
- 今天看了集英剧（德古拉），结果时间被吞噬了，一个半小时...

### 明

- useAxios 简化版本
- ts-axios 和 ssr-github
- 感觉之前的战线太分散了，这边开一个仓库那边开一个仓库，但是都没怎么捣鼓就停了。准备集中火力，解决掉一个再开始下一个。

## 2020-1-13

### 今

- 今天开开心心的用自己写的 API 来 Mock 的时候 MongoDB 突然崩了...，慌的一批，因为这个东西之前跑了一个多月都没出过问题，难道是哪里边界情况没考虑到？用配置文件重启了 Mongod 之后就好了。
- 今天主要跟着网课学习，ssr-github 的 bug 修好了，ts-axios 也完成了基本功能，到时候还是得去研究下 axios 源码看看人家 node 端的实现方式。说到这个，明天研究下 node 的 buffer 和流吧，感觉挺重要的。
- 跟着知乎一篇文章写了个[useAxios](https://github.com/linbudu599/Effective-Customize-Hooks/blob/master/hooks/useAxios)，真是鬼才，用 `context` 来实现全局配置，但是这部分今天有点看不懂...
- 整理了闭包到[linbudu599/Penumbra](https://github.com/linbudu599/Penumbra)，不清楚自己是不是真的掌握了？咋会觉得它很简单呢。还有闭包和模块、React 组件、Hooks 的联系，JS 博大精深。
- 开始学 webpack5 了，做好了全英文开始的准备。

### 明

- webpack5 优先，先搞一部分新的东西再整理下新特性
- 继续 ssr-github 和 ts-axios，还剩下好几门网课，移动 app、测试、两门小程序（前&后端）
- 再议，根据可用时间灵活安排（真实还没过年就事情一堆）

## 2020-1-12

### 今

- 淦，写 hooks 的时候发现自己对闭包的理解不够深，于是复习了下闭包...，发现自己之前为啥就是搞不懂闭包呢，明明挺美妙的啊哈哈哈哈哈。顺便把之前的倒计时逻辑也用自定义 hooks 重写了，[useCountDown](https://github.com/linbudu599/Effective-Customize-Hooks)，这期间又发现了一个在字节工作的大神有个专栏专门介绍自定义 hooks，如获至宝！可以安排一哈
- 昨天刚立的 flag 说可以放一段时间 webpack 了，今天准备开始看 5 的时候发现有些地方还是需要琢磨琢磨，再借这个机会配成能开箱即用的模板配置吧。
- 今天的可用时间比较少，ssr-github 也只跟进了一小点，出了点奇怪的 bug，搜索结果添加筛选条件时会报错，待研究。

### 明

- 专注于研究 hooks 以及 umi

### 明

### 2020-1-11

### 今

- [webpack](https://github.com/linbudu599/Webpack4.x-Template)遗留很久的一个问题突然解决了，感谢 umi，使用 dev-server-middleware 起服务的时候配置项直接引入 `webpack.conf.dev.js` 即可，其中的配置项已经被合并过一次了，不用再在 server 里合并一次。
- [Log Server](https://github.com/linbudu599/Log_Server)上线了，也接入了天气应用，测试的时候看到成功记录下日志简直不要太开心！但是 PM2 启动问题还是没法解决，不清楚是配置项有问题还是依赖没装好...
- ts-axios，因为有电子书就跟着电子书敲了，效率高的很，但是担心会不会效果不太好...，想着到时候再全面重构优化一下。君 ts 当上手

- ssr-github，今天没怎么跟进课程，稍微写了一部分搜索页面，阿西吧又是排序又是限制条件的，但是 GitHub 竟然 api 细致到了这种程度...，给劲！
- 一个月前看 `Umi` 文档还一头雾水，但今天就感觉这文档写的真是浅显易懂啊...，我觉得大概可以把 `Umi` 理解成 webpack 上层封装 + Next.js 式路由 + 强化过的 html-webpack-plugin + 一堆灵活的插件。准备这样，写几个 demo，fork 下社区/官方配置的模板，写个插件，和 `dva`、`antd pro` 搭配，估计四到五天，然后再开始写家园的项目。
- hooks 真的好用啊...，今天稍微学习了下优化 hooks，不愧是 **hooks 哲学**

### 明

> 开始按照重要顺序排序

- （整活）开始写 generate 天气应用模板的 cli 了，但是不着急封装成 npm，重点是命令行交互一定要骚 ​
- ts-axios
- ssr-github
- umi-pratice

- 应该这些够了...

## 2020-1-10

### 今

- [webpack](https://github.com/linbudu599/Webpack4.x-Template)的问题解决了，怎么也没想到是 `autoDllPlugin` 的问题，难道是没把 dll 文件引入好？那这样 webpack 的配置暂时先告一段落了，现在这个已经可以平时写 demo 拿来用了。准备开始看 webpack5-alpha
- 是真没想到一时心血来潮结果花了好久时间在日志模块上，[半成品](https://github.com/linbudu599/Log_Server)，但是接近五脏俱全了，踩了几个 koa 和 ts 搭配的坑，比如声明文件和引入方式啥的，还好很快爬出来了。需要注意下 koa 把路由分离的方式 `newRouterInstance(server)`，还有就是！PM2 和 ts 的协作有些问题，已经把 PM2 的解释器配成 `ts-node` 了，但是一直报错，自闭。实在不行在服务器上挂一个终端窗口？这个使用方式（向我自己的域名发起一个 POST 请求，记录到对应日志）应该还有很大改进空间。
- 还踩了个坑，`Options`请求和跨域，要在 koa 多配一下对 `options` 请求返回 200，不能只配个允许跨域。浏览器级别行为可还行
- 也正是写这个日志服务的时候再次感受到了 ts 的强大和重要性，于是准备先完成 ts 实现 axios 的课程，学完这个我就敢在简历上写自己会 ts 了吧...
- ssr-GitHub 项目，害好讲究啊用户体验，缓存策略啥的，写的有点懵但还是觉得很好玩。

### 明

- 8 要留给自己太多任务，万一有个突发情况看着这一堆未完成就心塞
- 开始复盘 react？umi&hooks
- ssr-github，搜索模块占了一整章可还行。
- ts-axios，看看能不能把 ts 之前读文档一直云里雾里的部分解决了，非科班真是有点难...

## 2020-1-9

### 今

- 继续配[webpack](https://github.com/linbudu599/Webpack4.x-Template)，原本配好了垫片和多页面还是挺带劲的，还配了一个挺好玩的 [webpackbar](https://www.npmjs.com/package/webpackbar)，就是 vuepress 打包的时候会有的那两个进度条，贼有逼格。还有一个[speed-measure-webpack-plugin](https://github.com/stephencookdev/speed-measure-webpack-plugin)，在性能分析上也挺有用的，但是，但是！！全部搞完再优化了一些零碎的配置之后发现出问题了，启动后的页面里明明 js 和 css 文件都被注入了，但是 js 文件并不执行...，用排除法大概锁定范围在了 **optimization.splitChunks** 里，但进一步注释掉有嫌疑的配置项后发现整个模板崩了，js 文件直接不被注入...，淦，我头疼。好像每天都是解决前一天遗留的 :bug:，再留给明天一只更大只的 :bug:
- 看了云谦老师关注的工具，[awesome-f2e-libs](https://github.com/linbudu599/awesome-f2e-libs)，先用的 [**projj**](https://github.com/popomore/projj) 想着管理下项目吧，结果一添加项目就报错，看了下大概一年前就有 issue 提这个问题了，但并没解决...，想着那算了，[**fx**](https://github.com/antonmedv/fx)看起来也不错，可以在命令行打开折叠的 json 对象，好的，`fx data.json` 没反应。打扰了，卑微的 Windows
- [天气小应用](https://github.com/linbudu599/weather-msg-sender)用 ts 重构完了，但是，[那个问题](#2020-1-8)其实算不上被解决了，我最后用的方法是得到返回信息后用 node 写到文件里，然后别的模块再去读取、处理。因为我的思路就是要把异步返回的结果释放到全局里...
- [ssr-github](https://github.com/linbudu599/SSR-Github)，写好首页啦，还是成就感 max 的，突然感觉以后用 ts 重构这个项目不会太简单...，明天继续写仓库详情页啥的。
- 开始学小程序咯~，但是今天就只是开了个头，稍微复习了下文档
- 家园的项目准备再推一下，把 umi、dva、antd pro、react 更深入一些应该会更得心应手

### 明

- 解决 webpack 的 bug，多页面用动态入口配置？
- 继续写 ssr-GitHub、小程序，瞅了一下寒假计划，感觉得再加两个线程了
- [How-to-learn-node-correctly](https://github.com/i5ting/How-to-learn-node-correctly)，写写 node！
- 云谦老师 B 站的 UMI 教程
- 读一读 hooks 相关的文章
- 阮一峰老师的 koa 教程，之前一直想看来着，好像有几个知识点挺重要的
- 新线程：ts 实现 axios
- 新线程：graphql 初体验

## 2020-1-8

### 今

- 继续配置自己的 [`webpack` 模板](https://github.com/linbudu599/Webpack4.x-Template)，主要是 dll 和一些零碎的地方，还剩下**垫片**和**多页面**几个地方没有处理，可能要开始准备看 `webpack5` 的 alpha 了？
- 用 `GitHub Actions` 配好了 CD，先给自己的博客配上了，但是配上之后 nginx 马上崩了，不清楚有没有直接关系，观望一下。主要是感觉 `JenKins` 太折磨了，而且很多功能我远远用不上。
- 新开了个记录 `actions` 的[仓库](https://github.com/linbudu599/Enjoy-Github-Actions)，因为觉得 `GitHub Actions` 还是挺有趣强大的，玩法挺多
- 用 `typescript` 重构了之前的[天气小应用](https://github.com/linbudu599/weather-msg-sender)，同时换了 API 接口（淦，转化逻辑又要重写，原本的那个外国网站崩了..），但是有几个地方卡住了，又是请教大佬又是在思否提问的...
- 继续跟着视频写之前的 [`ssr-github` 项目](https://github.com/linbudu599/SSR-Github)，终于搞懂了代理接口同时区分 csr/ssr 的配置代码...

### 明

- 把那个天气小应用完成好，今天的主要问题是需要得到异步流程结果并且作为模块导出，看了思否大佬的回答大概有思路了
- ssr-github，开始写页面和逻辑
- **家园的项目！** 害我都忘记这一茬了...，验证码的逻辑大概解决了。可能是我写的太远了，需要的接口多了十来个...，后端同学知道估计要鲨了我
- 配完 webpack 剩下的部分
- 写写 node 和 ts
