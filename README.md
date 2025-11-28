```mermaid
graph TD
    %% 根节点（突出 Google 蓝）
    XZH(["`习仲勋
    (1913-2002，已故)
    原中共中央政治局委员、国务院副总理
    文革中被监禁16年`"]) 
    style XZH fill:#4285F4,color:#ffffff,stroke:#333333,stroke-width:4px,rx:30,ry:30

    %% 第一婚姻（浅灰蓝背景）
    subgraph FirstMarriage ["第一婚姻（1936-1944）"]
        direction TB
        HMZ(["`第一任妻子：郝明珠
        (1916-2006)
        1936-1944婚姻`"])
        XHP(["`习和平
        (长女，已故，1930年代生)
        文革时期在陕西军校自杀
        无配偶/无子女`"])
        XGP(["`习干平
        (次女，已故，1930-1940年代生)
        文革下放陕西农村
        无配偶/无子女`"])
        XZN1(["`习正宁（原名习福平）
        (长子，1941-1998，已故)
        1960s国防研究员
        1980s海南司法厅长·推动法治
        1994-1995多地演讲
        无配偶/无子女`"])
    end

    %% 第二婚姻（主家族，Google蓝轻背景）
    subgraph SecondMarriage ["第二婚姻（1944年起）"]
        direction TB
        QC(["`第二任妻子：齐心
        (1926-2023)
        文革中被迫批斗`"])

        %% 齐桥桥家族
        subgraph QQQFam ["齐桥桥家族"]
            direction TB
            QQQ(["`齐桥桥
            (1949年生，长姐)
            澳大利亚/加拿大双籍`"])
            QF(["`前夫
            (姓名不详，内蒙古插队时结婚)`"])
            ZYN(["`女儿：张燕南
            (1980年生)`"])
            FDN(["`张燕南丈夫：傅大牛
            (~1980英国生)
            福大牛网络创始人
            2025资产约5亿USD
            香港/多伦多`"])
            DJG(["`现夫：邓家贵
            (1951湖北生)
            前烟草/万达高管
            2025加拿大稀土约25亿USD
            (湖北家族旁系涉电信矿业
            无直系子女)`"])
        end

        %% 齐安安家族
        subgraph QAAFam ["齐安安家族"]
            direction TB
            QAA(["`齐安安
            (1952年生，二姐)
            长期居澳大利亚墨尔本`"])
            WL(["`丈夫：吴龙
            (1950s天津生)
            父吴本立干部
            新邮通信创始人`"])
            WM(["`吴龙弟弟：吴明
            (~1960天津生)
            新邮通信/中移动旧案
            2025澳洲铁矿约2亿USD`"])
            WYN(["`女儿：吴雅凝（又名吴晓）
            (1980s生)
            奥地利克林顿基金会背景
            福大牛网络持股`"])
            DFOA(["`吴雅凝丈夫：Daniel Foa
            (英国籍，福大牛关联)`"])
            WLF(["`儿子：吴拉非
            (1990s生)
            2025铁矿/疫苗约4亿USD`"])
        end

        %% 习近平家族
        subgraph XJPFam ["习近平家族"]
            direction TB
            XJP(["`习近平
            (1953年生)
            国家主席·中共中央总书记
            文革下乡梁家河7年
            无个人资产`"])
            KLL(["`前妻：柯玲玲
            (1952外交官之女)
            1980s初离婚，无子女`"])
            PLY(["`现妻：彭丽媛
            (1962郓城生，著名军旅歌唱家)
            1987结婚
            2011 WHO大使
            无巨富`"])
            XMZ(["`女儿：习明泽
            (1992福州生)
            哈佛心理学2014卒（化名Chu Chen）
            2019传哈佛研究生
            2025上海低调外交相关
            英国男友传闻
            离岸资产数百万USD
            (潜在关联：Qin Yuefei，耶鲁)`"])

            subgraph PengFam ["彭丽媛家族（山东郓城）"]
                direction TB
                PF(["`父亲：彭龙坤（已故）
                郓城文工团副团长
                文革右派`"])
                PM(["`母亲：刘贵贤（已故）
                豫剧演员`"])
                PB1(["`大弟：彭磊
                (1950s生)
                济南医疗/稀土垄断
                2025约12亿USD`"])
                PB2(["`小弟：彭雷
                (1970s生)
                青岛KTV→稀土合资
                2025约25亿USD`"])
                PS1(["`妹妹：彭丽娟
                (1960s生)
                彭丽媛早期经纪人
                2025间接约4亿USD`"])
                PS2(["`小妹：彭丽丽
                (1970s生)
                丈夫国资背景
                2025山东根基`"])
            end
        end

        %% 习远平家族
        subgraph XYPFam ["习远平家族"]
            direction TB
            XYP(["`习远平
            (1956年生，小弟)
            澳大利亚永久居留权`"])
            FormerW(["`前妻（姓名已抹除）`"])
            SonXZN(["`儿子：习正宁
            (1990s生)
            乔治城→清华
            娶泰国正大集团千金
            2025疫苗业务约5亿USD`"])
            DauXXN(["`女儿：习欣宁
            (1990s生)
            嫁深圳地产少东家
            2025深圳/澳洲约7亿USD`"])
            Rumored(["`传闻女儿：杨澜澜
            (1990s生)
            2025澳洲神秘车祸女主角
            约1.5亿USD`"])
            CurrentW(["`现妻：张澜澜
            (1980原名张晓雪)
            军艺舞蹈演员
            2005离婚陈丹
            2008与习远平结婚`"])
            SisterInLaw(["`张澜澜妹妹：张珊珊
            (~1985原名张晓雨)
            核子华曦/核酸检测
            2025持股约4亿USD`"])
        end
    end

    %% 关系连接（极简粗线条，Google蓝）
    XZH ==> FirstMarriage
    XZH ==> SecondMarriage
    HMZ --> XHP & XGP & XZN1
    QC --> QQQ & QAA & XJP & XYP

    QQQ --> QF --> ZYN --> FDN
    QQQ ==> DJG
    QAA ==> WL
    WL --> WM & WYN & WLF
    WYN --> DFOA

    XJP --> KLL
    XJP ==> PLY ==> XMZ
    PLY --> PF & PM & PB1 & PB2 & PS1 & PS2

    XYP --> FormerW --> SonXZN & DauXXN
    XYP --> Rumored
    XYP ==> CurrentW --> SisterInLaw

    %% Google 美学统一风格（圆润 + 极简 + 高雅留白）
    classDef person fill:#ffffff,stroke:#4285F4,stroke-width:3px,color:#000000,rx:30,ry:30
    classDef marriage fill:#e8f0fe,stroke:#4285F4,stroke-width:2px,rx:20,ry:20
    classDef cluster fill:#f8f9fa,stroke:#dadce0,stroke-width:1px,rx:15,ry:15,color:#333333

    class XZH,HMZ,QC,XHP,XGP,XZN1,QQQ,QF,ZYN,FDN,DJG,QAA,WL,WM,WYN,DFOA,WLF,XJP,KLL,PLY,XMZ,PF,PM,PB1,PB2,PS1,PS2,XYP,FormerW,SonXZN,DauXXN,Rumored,CurrentW,SisterInLaw person
    class FirstMarriage,SecondMarriage,QQQFam,QAAFam,XJPFam,PengFam,XYPFam cluster

    linkStyle default stroke:#4285F4,stroke-width:3px
