# 鬼魂GDP：当AI太成功，经济反而崩了

> 锵锵三人行风格播客脚本 | 预计时长：35分钟 | 约9000字

---

## 第一段：一篇让华尔街睡不着的memo [0:00-5:00]

**老窦：** 各位好，欢迎回来。[PAUSE:0.5s] 今天这个话题吧，我先说，我自己看完那篇文章之后晚上翻了好几次身，真的。有一个叫Citrini Research的机构，写了一篇东西——注意啊，它不是正常的研报——它是以2028年6月的视角，回头看2026到2028年发生了什么。等于是一个人坐着时光机回来，跟你说兄弟你们完蛋了。核心结论就一句话：AI太成功了，然后经济崩了。[PAUSE:1s] Viktor你先说，你看完什么反应？

**Viktor：** 我看完第一反应是——这哥们儿方向是对的。

**老窦：** 哦？

**Viktor：** 但他犯了一个做sell-side research的经典毛病：为了storytelling，把时间线压得太狠了。他说两年内从AI boom到全面economic crisis——SaaS崩盘、private credit爆雷、mortgage market出问题——说白了他是把一部HBO迷你剧八集的剧情塞进一部电影里了。震撼，但不够realistic。

**老窦：** Sarah呢？

**Sarah：** [PAUSE:0.3s] 我同意Viktor这个判断。这大概也是我们今天唯一完全一致的地方，大家享受一下这个稀有时刻。[LAUGH] 文章描述的每一个传导机制——displacement spiral、Ghost GDP、私人信贷链式反应——这些不是科幻小说。这些结构性张力已经存在了，只是还没到临界点。但他把金融危机和劳动力危机压到同一条时间线上，这是分析上最大的软肋。

**老窦：** 等等等等，我先确认一下——你们俩都觉得方向是对的？

**Viktor：** 方向百分之百对。

**Sarah：** 方向没争议。

**老窦：** 那我就害怕了啊。[PAUSE:0.5s] 两个完全不同路数的人——一个天天看deal flow的VC，一个建系统模型的经济学家——都说方向对。这说明什么问题？

**Viktor：** 说明市场还没price in。

**Sarah：** 说明这不是一个"会不会发生"的问题。是"多快发生"和"谁先被打"的问题。

**老窦：** 行，那我们今天的任务就是——把这篇文章咀嚼透，掰碎了聊明白。各位系好安全带。

---

## 第二段：SaaS之死——反身性的收缩螺旋 [5:00-13:00]

**老窦：** 先从最直观的讲起。文章里有个现象我觉得特别直觉——seat-based SaaS的死亡螺旋。Sarah你给科普一下？

**Sarah：** 好。现在绝大多数企业软件是按人头收费的，对吧？你公司有一千个员工用Salesforce，你就买一千个license，每个人每月150美金，乘一千人，就是你的ARR。这个模式过去十五年支撑了整个SaaS行业几万亿美金的市值。它看起来很稳定——recurring revenue嘛——但它有一个致命的reflexivity。

**老窦：** Reflexivity……反身性？索罗斯那个？

**Sarah：** 对，自我强化的循环。逻辑是这样的：你的客户——比如一家保险公司——开始用AI处理理赔，裁掉了15%的人。他第二天就打电话给Salesforce说，我要取消15%的license。你的收入机械性地跟着掉。[PAUSE:0.5s] 然后你Salesforce为了保住利润率也开始裁员——这又导致你的供应商、你旁边的SaaS公司又丢了一个客户。每一个公司的单独行为都是rational的——cut cost, invest in AI——但集体结果是灾难性的。

**老窦：** 就像大家都往门口跑，门反而堵死了。

**Sarah：** 差不多。文章里举的例子是ServiceNow——2026年Q3，座位收入模式正式break，因为客户裁了15%的人就砍了15%的seats。

**Viktor：** 但是！[INTERRUPTION] 但是你们有没有考虑过供给侧？所有人都在说demand destruction——客户裁员所以SaaS完蛋——但没人在看supply creation。你们知道Jevons Paradox吗？

**老窦：** 这词儿今天第二次出现了，你展开说。

**Viktor：** 十九世纪，James Watt改良了蒸汽机，效率提升了，所有人预测煤炭消耗会下降。结果呢？用得更多了。因为效率提升让蒸汽机进入了以前根本不可能用上蒸汽机的领域。AI也是一样的逻辑。当写代码的成本降到原来的百分之一——我跟你讲一个真实的case，我投的一个团队，两个人，用Claude Code三周复制了一个中型CRM的核心功能。三周！以前这是两百个工程师一年的活儿。那你想想——当成本这么低的时候——

**Sarah：** Viktor，我打断一下。[INTERRUPTION]

**Viktor：** 说。

**Sarah：** 这个类比有一个根本性的问题。能源和人类劳动的关系是complementary——互补的。蒸汽机让一个人能干十个人的体力活，但你还是需要人来操作、管理、决策。人和蒸汽机是搭档关系。[PAUSE:0.5s] 但AI和人类认知劳动的关系是substitutive——替代的。AI不是让你写代码写得更快，AI是直接把代码写了。100倍的代码产出，不等于100倍的开发者。Jevons Paradox预测的是更多的intelligence被deployed，不是更多的human被employed。这个区分是critical的。

**老窦：** [PAUSE:1s] 等一下让我消化一下。你的意思是——蒸汽机需要人来开，但AI不需要人来"开"？

**Sarah：** 精准。

**老窦：** 那我再翻译一层——就好比外卖平台确实让大家点了更多外卖，外卖总量暴涨。但是厨师没有变多。反而是中央厨房把小饭馆干掉了，外卖小哥的工资还在降。量涨了，但人的钱少了。

**Sarah：** 这个比喻非常好。

**Viktor：** [PAUSE:1s] 我……好吧。我承认complementarity和substitution这个distinction我之前没想透。但是——

**老窦：** 你认了？[LAUGH]

**Viktor：** 部分认。但我要追加一个更残酷的数字。就算你说得对，100倍的代码确实创造了新市场、新需求——micro-multinational、personalized software、以前根本没人服务的长尾——就算这些都是真的，如果单价掉了99%……

**Sarah：** ——nominal GDP缩。

**Viktor：** 对。Volume up, revenue down。你不能用"我们写了更多代码"去还一笔50亿美金的leveraged loan。银行不接受story，银行要现金流。这是hard math。

**老窦：** [PAUSE:1s] 我听出来了——这一轮Sarah赢了。

**Viktor：** 这一轮她赢了。我大方承认。

**Sarah：** 谢谢。不过别急，后面有你赢回去的地方。

---

## 第三段：2.5万亿的定时炸弹 [13:00-21:00]

**老窦：** 好，接下来进入我最怕的部分。[PAUSE:0.5s] 我先问一个可能很蠢的问题——什么是private credit？为什么一个普通人要关心这东西？

**Sarah：** 不蠢，这是今天最重要的问题。Private credit就是不在公开市场交易的贷款。传统上企业借钱有两种方式——找银行，或者发债券。Private credit是第三条路：直接找一个大型基金——Apollo、Blackstone、KKR——说我要借钱，他们直接放贷。过去五年这个市场从几千亿涨到了2.5万亿美金。

**老窦：** 涨这么猛？

**Sarah：** 因为利率高的时候银行缩贷，企业还要借钱，private credit正好补上。而这里面有一大块——非常大的一块——是PE基金做杠杆收购时借的钱。

**老窦：** 杠杆收购……LBO。就是借钱收购公司，用公司自己的现金流还债？

**Sarah：** 对。2021到2024年有一波疯狂的软件公司LBO。逻辑很简单：SaaS公司有高margins、predictable recurring revenue、低capex——完美的LBO标的。但问题是——这些"predictable revenue"现在不那么predictable了。

**Viktor：** 我给你们讲个具体的。Zendesk，客服软件巨头，2022年被私募以102亿美金收购，massive leverage。现在客服是什么？客服是AI替代最凶猛的赛道，没有之一。你去看看市面上有多少AI chatbot产品——几百个。Zendesk的客户在说：我为什么还要雇人工客服？我为什么还要买那么多seats？

**老窦：** 然后seats减少，收入减少——

**Viktor：** ——debt coverage ratio恶化，lender开始紧张，refinancing成本飙升，最后——boom。50亿级别的direct lending违约事件。这就是文章说的"Zendesk Moment"。

**老窦：** 但这不就一家公司的事儿吗？

**Viktor：** 哥你太天真了。[LAUGH] 2021到2024年那波软件LBO，同样逻辑的公司有一堆。被PE私有化之后外面就看不到数据了——no public filings, no quarterly earnings calls——等你知道出问题的时候已经来不及了。这才是最吓人的地方。

**Sarah：** 而且还有一层传导。这些private credit的钱从哪来的？不是天上掉的。相当一部分来自保险公司。Apollo旗下的Athene，KKR旗下的Global Atlantic——这些是寿险公司。他们拿的是什么？是policyholder的钱。你买的年金险、储蓄险、养老险——

**老窦：** 等一下等一下——[INTERRUPTION]

**Sarah：** ——这些钱被投进了private credit。所以传导链完整版是：AI干掉SaaS收入→SaaS公司还不起debt→private credit基金出现losses→保险公司的asset side受损→保险监管要求补充资本→forced selling→你买的那份保单的收益受影响。

**老窦：** [PAUSE:2s] 我的保险。我爸买的年金。

**Sarah：** 有可能。我不是在制造恐慌，但这个linkage是real的。这就是文章说的"permanent capital"的陷阱——大家以为private credit的钱是"长期的、稳定的"，但bottom-up看，底层资产的质量在结构性恶化。

**老窦：** 好，那现在说到今天我最想聊的一个概念——Super-Prime to Subprime。Sarah你在辩论里用的这个词特别狠。

**Sarah：** 这是这场辩论里我认为最original的insight。2008年次贷危机，问题出在贷款发放的时候就已经是垃圾了——给没工作的人批房贷，NINJA loan，origination就是fraudulent的。但这次完全不同。[PAUSE:0.5s] 你是个放射科医生——

**Viktor：** ——top of the food chain——

**Sarah：** ——信用分780，年收入40万美金，银行批给你150万的房贷，完全reasonable。但是三年后AI影像诊断的准确率超过人类，你的诊所开始缩编，你的收入从40万降到20万——这笔贷款从super-prime变成了subprime。[PAUSE:1s] 不是因为欺诈，不是因为审核不严，而是因为世界变了。贷款在发放那天是好的。是地基后来被抽空了。

**老窦：** 就像你买房子的时候地基是好的，结构完整。但后来有人在你楼底下开始挖矿——地基在你住着的时候被一点点掏空。你每天都觉得没问题，直到有一天裂缝爬上了墙。

**Viktor：** 而且这不是个别案例的问题。13万亿美金的mortgage市场，有多少笔贷款是基于"这个人的职业在未来三十年是stable的"这个assumption？律师、会计师、金融分析师、放射科医生、翻译——哪个职业敢拍胸脯说我未来十年的收入guaranteed？现有的信用模型根本不incorporate这个variable。

**老窦：** 这才是真正可怕的。不是因为坏人做了坏事，而是因为规则变了但模型没跟上。

---

## 第四段：刹车在哪儿——Incompetence Moat与算力天花板 [21:00-28:00]

**老窦：** 行了行了，我听你们说了二十分钟坏消息，我需要一点希望。[PAUSE:0.5s] 有没有什么刹车机制？有什么力量能让这个螺旋不那么快地转下去？

**Viktor：** 有！我说两个，而且第一个特别counter-intuitive。我管它叫Incompetence Moat。[PAUSE:0.3s]

**老窦：** [LAUGH] 无能护城河？

**Viktor：** 对！你们严重高估了大公司执行AI transformation的能力。我每天跟这些企业打交道，我告诉你们，绝大多数Fortune 500公司的IT部门是什么水平？连一个cloud migration都能搞三年搞不完。你让他们deploy agentic AI替代50%的workforce？做梦。[PAUSE:0.5s] 说白了，大多数公司就是封建官僚体制。中层管理者会裁自己团队的人吗？不会。他手下越多人，他的title越大，他的预算越高，他年终review的narrative越好看。你让他去deploy AI替代自己的下属？他会组建一个"AI Strategy Committee"，招三个McKinsey的consultant，出一份150页的报告——然后什么都不做。

**老窦：** 哈哈哈哈！[LAUGH] 太真实了。我见过这种报告。

**Sarah：** 我承认这个observation是accurate的——平均水平来看。[PAUSE:0.5s] 但这里有一个关键的经济学问题：市场定价看的不是平均行为，而是边际行为。

**Viktor：** 什么意思？

**Sarah：** 你不需要每家公司都裁员来改变labor market。你只需要边际上的劳动力买家——就是那些在actively hiring的公司——停止招聘。100家公司里有70家像你说的那样什么都不做。但那30家aggressive的公司已经足够改变整个market的equilibrium。而且更重要的是——那30家公司会吃掉那70家的market share。给你三年时间，你会看到severe的行业整合。所以displacement会是extremely uneven的——某些geography、某些sector会经历deep depression，而aggregate的数据看起来还OK。

**老窦：** 就像一个班级的平均分还是75分，但差距从10分变成了50分。

**Sarah：** 差不多这个意思。

**Viktor：** 好，那我打出真正的王牌。Compute成本刹车。[PAUSE:0.5s]

**老窦：** 展开讲。

**Viktor：** 所有的displacement模型——包括Sarah你的——都有一个implicit assumption：inference成本会持续下降，算力会持续充裕。但如果——如果——所有公司同时冲去搞AI automation，会发生什么？

**老窦：** GPU不够？

**Viktor：** GPU不够，电力不够，数据中心不够，冷却系统不够。算力价格会spike。当inference的单位成本从现在的一分钱涨到一毛钱甚至一块钱——突然之间，人又变得有competitive advantage了。物理世界会给这个displacement spiral踩一脚刹车。这不是你经济学model能predict的，这是物理定律在说话。

**Sarah：** [PAUSE:1.5s] 这个……我得说，这个argument是genuinely important的。我不常在辩论里改立场——

**Viktor：** 哦？[LAUGH]

**Sarah：** ——但这一次我要做个adjustment。我原来的timeline是4到7年出现full-scale labor displacement。考虑到compute bottleneck——特别是如果adoption rate超过infrastructure build-out速度——可能需要向上修正到5到10年。Displacement spiral要维持加速状态，需要持续cheap的inference。如果inference涨价——

**老窦：** 就像油价涨了大家就少开车？

**Sarah：** 类似。但我一定要加一句——[PAUSE:0.3s] 这只是速度调节器，不是方向改变器。该发生的还是会发生。只是physics给了我们一个buffer。

**Viktor：** 我接受这个说法。赢了半个point我就收了。[LAUGH]

**老窦：** 好，所以目前的shared conclusion是——不是会不会，是多快。那从"多快"这个角度，你们怎么看整体timeline？

**Sarah：** 这引出一个更大的reframing。我们辩论到后面有一个重要的概念转变。我们面对的不是什么"智能危机"——这是Citrini的标题党。我们真正面对的，是一场de-leveraging crisis。全球300万亿美金的债务——government debt、corporate debt、household debt——全部是based on人类劳动创造GDP来service的。如果productivity不再通过wages流入households——如果我们进入Ghost GDP的状态——那整个global debt architecture就需要re-base。

**老窦：** Ghost GDP……我理解一下。就是AI创造了很多output——code被写了，报告被生成了，诊断被做了——但这些产出没有通过工资进入到人的口袋里？

**Sarah：** Exactly。GDP数字在涨，corporate profit在涨，但median household income在跌。经济在"增长"，但老百姓感受不到。

**老窦：** 这不就是鬼魂嘛。数字在跳，但钱是虚的。你能看见但抓不住。

---

## 第五段：政府会救吗——三种未来的赛马 [28:00-34:00]

**老窦：** 2008年政府救了银行。这次——政府能救程序员吗？

**Viktor：** 我先说一个judgment，大家可能不爱听。政府不会救失业的programmer。政府会拼命补贴AI。

**老窦：** 啊？这什么逻辑？

**Viktor：** 你想啊。中美之间的AI arms race已经是最高级别的national security issue了。哪个American politician敢站出来说"We should slow down AI to protect jobs"？说出来第二天就被骂成是Chinese agent。[LAUGH] 现实就是这样——defense budget里AI相关的allocation会year over year增长，而labor retraining program？Best case持平，worst case被砍。钱进data center，不进unemployment office。

**老窦：** Sarah你的看法？

**Sarah：** 我从institutional capacity的角度说。2008年bailout为什么能做？三个条件：第一，target清晰——banks。第二，tool明确——注资、担保、TARP。第三，有political consensus——如果不救，ATM明天取不出钱来，everybody能理解这个urgency。[PAUSE:0.5s] 但AI-driven employment crisis，你告诉我这三个条件哪个满足了？Target是谁？是SaaS company还是被裁的员工还是保险公司？Tool是什么？AI tax？Compute royalty？UBI？每一个方案的political controversy都比bank bailout大一百倍。Consensus在哪？一半国会觉得AI是上帝的礼物，另一半觉得是末日。

**老窦：** 所以不是不想救，是不知道怎么救、不知道救谁？

**Sarah：** 是political consensus的formation cost太高了。Fed可以用monetary tools——降息、QE——先buy time，拖个12到18个月。但真正解决问题需要fiscal policy——需要收税和花钱——需要国会立法。你知道国会pass一个major bill平均需要多久。

**Viktor：** 而且我告诉你最dark的scenario。如果同时发生tech unemployment spike和AI military escalation——国会面对两个competing priorities——jobs还是national security——你猜他们选哪个？

**老窦：** [PAUSE:1s] ……选national security。

**Viktor：** 每次都是。

**老窦：** 那有没有办法提前判断——这三种预判哪个会成真？

**Sarah：** 有。一个simple empirical test。等第一次major tech-sector unemployment event发生——比如某个季度tech layoffs超过10万人——然后看国会的response time。如果6个月内有substantive legislation——新的retraining fund也好，compute tax也好——说明fiscal response function还在工作。如果18个月还在hearing和debate，那我的pessimistic view就confirmed了。

**Viktor：** 如果defense AI budget在涨、labor program在砍——

**Sarah：** ——那Viktor是对的。

**老窦：** 三种future，赌谁赢。[PAUSE:0.5s] 你们知道这像什么吗？像三匹马在跑同一场赛马。Financial rescue、political paralysis、military priority——最后哪匹马先到终点，决定了我们所有人的命运。但我们连下注的权利都没有。

---

## 第六段：金丝雀还活着，但在咳嗽 [34:00-38:00]

**老窦：** 最后一个问题，也是最practical的——知道了这些，然后呢？每人给一个must-watch indicator。Viktor你先来。

**Viktor：** Junior hiring rate。就是初级岗位的招聘量。大厂的campus recruiting，consulting firm的analyst class，投行的first-year，全看这个。如果这些数字开始系统性下降——不是某个季度某家公司的调整——而是across the board的structural decline——那金丝雀就死了。

**老窦：** 为什么junior这么重要？

**Viktor：** 因为junior就是seed corn。Sarah之前说得好——eating our seed corn。今天你不招junior，十年后谁来做senior？谁来做decisions？你把梯子最底下两级抽掉了，上面的人迟早也得掉下来。

**老窦：** Sarah？

**Sarah：** SaaS net retention rate。就是existing customers的续费和扩张率。一家SaaS公司如果NRR从120%掉到90%以下，说明客户不仅没在expand，还在actively shrinking。当NRR across the sector开始系统性decline——that's the leading indicator for private credit stress。这个数字public company每季度都报，你可以track。

**老窦：** 从portfolio角度呢？该做什么调整？

**Viktor：** Long vol——波动率会structurally走高。这个transition不可能smooth，任何人告诉你"soft landing"你都可以笑。Short intermediation businesses——保险broker、travel aggregator、financial advisor——所有靠information asymmetry和人类惯性吃饭的中间商。AI agent不会因为habit而选某个品牌。Long physical assets——gold、energy infrastructure、robotics。[PAUSE:0.3s] Atoms over bits。这是我过去六个月最核心的thesis。

**Sarah：** 我加一个analytical framework。一定要把金融危机和劳动力危机分开track。Financial crisis——private credit repricing——could happen fast，12到18个月。Labor crisis——structural employment displacement——是4到7年，可能更长。把两条线分开，你的分析会清晰很多。Citrini那篇文章最大的问题就是把这两条timeline merge了。

**老窦：** 好——[PAUSE:0.5s] 那对一个普通人来说呢？我不是trader，不做portfolio management，我就是一个打工的——

**Viktor：** 别把所有赌注押在一个skill上。认真的。你是做data analysis的，学一点product thinking；你是做marketing的，学一点technical skills。Diversify your human capital就像diversify your portfolio一样。

**Sarah：** 以及——关注你自己行业的AI penetration速度。如果你工作内容中有50%以上可以在3到5年内被AI完成——注意我说的不是"完美替代"，是"good enough替代"——那现在就开始prepare plan B。不是panic，是prudence。

**老窦：** [PAUSE:2s] 好。那我用辩论里的一段话结尾。今天我们聊的所有这些——SaaS的死亡螺旋、private credit的传导链、Super-Prime to Subprime、Ghost GDP——核心不是AI会不会创造价值。它当然会。AI大概是人类发明过的最powerful的productivity tool。[PAUSE:1s] 但问题是——人类历史上最高效的技术，也可能成为最强的通缩力量。如果productivity的gains不经过wages进入千家万户——如果增长变成了ghost——那我们面对的不是一场技术革命，而是一场债务清算。

金丝雀还活着。[PAUSE:1.5s] 但它在咳嗽。

谢谢Sarah，谢谢Viktor。我们下期见。

**Viktor：** 下期见。Hope I'm wrong on this one.

**Sarah：** 我也希望。但我不会bet on hope。[PAUSE:0.5s] 我bet on data。

**老窦：** [LAUGH] 太Sarah了。好，各位下期见。

---

*[END]*
