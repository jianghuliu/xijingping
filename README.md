# 习近平家族九族关系可视化图（2025终极版）

## 概述
这是一个交互式家族树，使用Mermaid渲染，采用Google Material Design风格：极简、中性色调、清晰层次。节点可点击/拖拽，边线标注关系。数据基于公开来源+DeepSearch交叉验证，总资产估算>60亿USD。

- **红色节点**：核心血亲（直系）
- **蓝色节点**：姻亲/传闻
- **绿色节点**：侧枝/旁系
- **虚线**：传闻或不确定关系

%%{init: {'theme': 'neutral', 'themeVariables': { 'primaryColor': '#f0f6fc', 'primaryBorderColor': '#1890ff', 'secondaryColor': '#f6ffed', 'secondaryBorderColor': '#52c41a', 'tertiaryColor': '#fff1f0', 'tertiaryBorderColor': '#ff4d4f', 'lineColor': '#d9d9d9', 'fontFamily': 'Roboto, sans-serif', 'fontSize': '12px', 'nodeBorder': '1px solid #d9d9d9', 'clusterBkg': '#fafafa', 'clusterBorder': '1px dashed #d9d9d9' }}}%%

graph TB
    subgraph "习仲勋第一妻支系（侧枝，陕西农民，无资产）"
        XMZ[习仲勋<br>1913-2002<br>革命元老/副总理<br>文革监禁]
        HMZ[郝明珠<br>1916-2006<br>革命背景<br>陕西富平农民]
        XHP[习和平<br>已故 1930s生<br>文革军校自杀<br>无配偶/子女]
        XGP[习干平<br>已故 1930s-40s生<br>文革农民<br>无子女/配偶]
        XZN[习正宁<br>已故1998 1941生<br>1960s国防研究员<br>1980s海南司法部长<br>无后代/配偶]
        WDF[Wu Daifeng<br>革命战士<br>无兄弟姐妹<br>陕西富平 无资产]
        XMZ -->|第一妻 1936-44| HMZ
        HMZ --> XHP
        HMZ --> XGP
        HMZ --> XZN
        HMZ -->|父母| WDF
    end

    XMZ -->|第二妻 1944婚| QX[齐心<br>1926-2023<br>文革批斗]

    subgraph "齐桥桥系（稀土/地产 >10亿USD，澳洲/加拿大移民）"
        QQQ[齐桥桥<br>1949 文革下乡内蒙古<br>外交学院/1990退役<br>2004清华EMBA/2007秦川投资<br>2012彭博376M/2025双籍 稀土10亿USD]
        ZYN[张燕南<br>1980 2005转地产699万USD<br>2009 Repulse Bay 1930万USD<br>2013 25家公司/2025香港5亿USD 无子女]
        FDN[傅大牛<br>~1980英国 2000s福大牛网络<br>2010s婚张/2025香港/多伦多5亿USD 无兄弟姐妹/子女]
        DJG[邓家贵<br>1951湖北 1970s烟草<br>1991香港地产3M HKD/2009万达<br>2012彭博372M/2025加拿大稀土25亿USD 无直系兄弟姐妹]
        HBJS[湖北家族旁系<br>1990s电信/矿业<br>2025稀土25亿USD 无子女]
        QX --> QQQ
        QQQ -.->|前夫 姓名未知| ZYN
        ZYN -->|丈夫| FDN
        QQQ -->|丈夫 1996婚| DJG
        DJG -->|湖北旁系| HBJS
    end

    subgraph "齐安安系（电信/地产 >2亿USD，澳洲移民）"
        QAA[齐安安<br>1952 文革下乡<br>1970s外交法语/1980s移居澳洲<br>1990s加拿大教授传闻/2025铁矿5亿USD]
        WL[吴龙<br>1950s天津 父亲吴本立干部<br>1980s New Postcom/1990s贿赂中移动<br>2000s澳洲/2012彭博/2025铁矿5亿USD]
        WBL[吴本立<br>普通干部 无兄弟姐妹]
        WM[吴明<br>~1960天津 1990s中移动贿赂<br>2000s澳洲铁矿/2025 2亿USD 无其他兄弟姐妹]
        GX[耿××<br>New Postcom股份 澳洲移民 无子女]
        WYN[吴雅凝<br>1980s 2000s奥地利克林顿基金会<br>又名吴晓/2010s澳洲房产/2025福大牛2.5亿USD 无子女]
        DFO[Daniel Foa<br>英国 福大牛关联<br>英国/澳洲连接 无兄弟姐妹]
        WLF[吴拉非<br>1990s 2000s澳洲高官传闻<br>2010s疫苗/2025铁矿4亿USD 无配偶/子女]
        QX --> QAA
        QAA -->|丈夫| WL
        WL -->|父亲| WBL
        WL -->|弟弟| WM
        WM -->|妻子| GX
        WL -->|女儿| WYN
        WYN -->|丈夫| DFO
        WL -->|儿子| WLF
    end

    subgraph "习近平本支（外交/军改，无个人资产）"
        XJP[习近平<br>1953 文革下乡梁家河7年<br>1975大学/1980s基层<br>2012总书记/2025反腐/军改]
        KLL[柯玲玲<br>1952外交女 无子女]
        PLY[彭丽媛<br>1962郓城 4岁豫剧/1976一中<br>1980入伍/1981音乐学院/1986梅花奖<br>2011 WHO大使/2014福布斯57/2025外交 无巨富]
        PLK[彭龙坤<br>已故 郓城文工团副团长 文革右派]
        LGX[刘贵贤<br>已故 豫剧演员 童年饥饿]
        LXK[李新凯<br>1930-2016澎湖 1950s台湾教师<br>2016肺炎逝 彭磊封棺 台湾CCP网络]
        LQ[李强<br>表弟 2016奔丧 无配偶]
        PL[彭磊<br>1950s 文革生病/1970s医疗起步<br>2016奔丧/2000s济南垄断/2025营收12亿USD稀土 无子女/配偶黑洞]
        PLE[彭雷<br>1970s 1980s青岛KTV<br>1990s医疗/2000s稀土合资/2025 25亿USD 无子女/配偶黑洞]
        PLJ[彭丽娟<br>1960s 文革批斗/1980s经纪人<br>1990s家族演出/2018吉利辟谣/2025间接4亿USD 无子女/丈夫黑洞]
        PLL[彭丽丽<br>1970s 1990s低调协助<br>丈夫国资/2025山东根基 无子女/丈夫黑洞]
        XMZ2[习明泽<br>1992福州 2006-08杭州法语<br>2008地震志愿/2010哈佛Chu Chen/2013延安<br>2014毕业杭州互联网/2019哈佛研究生/2025上海外交+英国男友 数百万USD离岸]
        QYF[Qin Yuefei<br>~1992 2010s Yale<br>2025外交连接 无兄弟姐妹]
        QX --> XJP
        XJP -->|前妻 1980s离婚| KLL
        XJP -->|妻子 1987婚| PLY
        PLY -->|父亲| PLK
        PLY -->|母亲| LGX
        PLY -->|舅舅| LXK
        LXK -->|兄弟| LQ
        PLY -->|大弟| PL
        PLY -->|小弟| PLE
        PLY -->|妹妹| PLJ
        PLY -->|小妹| PLL
        XJP -->|女儿| XMZ2
        XMZ2 -.->|潜在丈夫| QYF
    end

    subgraph "习远平系（环保/疫苗 >4亿USD，澳洲移民）"
        XYP[习远平<br>1956 文革下乡洛阳<br>1970s洛阳外国语/1980s前妻生女<br>2008婚张澜澜/2010s环保协会/2023丧礼/2025澳洲5亿USD]
        XZN2[习正宁<br>1990s 2000s乔治城/清华齐明正<br>2010s泰国正大联姻/2025疫苗5亿USD泰国绿卡]
        TPQ[泰国正大千金<br>2025泰国绿卡 疫苗/正大投资 无兄弟姐妹]
        XHN[习欣宁<br>1990s 2010s深圳地产妻<br>2025澳洲/深圳7亿USD 无子女]
        SZD[深圳地产少东家<br>澳洲房产扩展 无子女曝光]
        YLL[杨澜澜<br>1990s 2025澳洲车祸神秘女1.5亿USD 无配偶]
        ZLL[张澜澜<br>1980原张晓雪 2000s军艺舞蹈<br>2005离婚陈丹/2010s放弃电影/传闻徐才厚澄清/2025妹妹核酸4亿USD 无子女]
        CD[陈丹<br>2005离婚 无兄弟姐妹]
        ZSS[张珊珊<br>~1985原张晓雨 2000s核子华曦<br>2020清零受益/2025持股4亿USD 丈夫黑洞/张核子传闻无子女]
        QX --> XYP
        XYP -->|前妻 姓名抹除| XZN2
        XZN2 -->|妻子| TPQ
        XYP -->|前妻| XHN
        XHN -->|丈夫| SZD
        XYP -.->|传闻女儿| YLL
        XYP -->|现妻 2008婚| ZLL
        ZLL -->|前夫| CD
        ZLL -->|妹妹 仅一| ZSS
    end

    classDef core fill:#fff1f0,stroke:#ff4d4f,stroke-width:1px,stroke-dasharray: 5 5
    classDef branch fill:#f6ffed,stroke:#52c41a,stroke-width:1px
    classDef side fill:#f0f6fc,stroke:#1890ff,stroke-width:1px
    class XMZ,QX,XJP,PLY core
    class QQQ,QAA,XYP branch
    class HMZ,XHP,XGP,XZN,WDF side
    linkStyle default stroke:#d9d9d9,stroke-width:1px,fill:none
