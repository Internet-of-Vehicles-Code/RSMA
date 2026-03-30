# Rate Splitting Multiple Access

这是一个围绕 `Rate Splitting Multiple Access (RSMA)` 的研究资料索引，主要整理了相关研究团队、代表性学者、综述论文、带代码论文以及若干优化方法参考文献。

当前内容更偏向“资料导航”而不是“项目使用说明”，适合用来快速了解 RSMA 研究版图、顺着作者找论文，或者从论文跳转到公开代码实现。

## 导航
- [Rate Splitting Multiple Access](#rate-splitting-multiple-access)
  - [导航](#导航)
  - [RSMA 相关研究团队调研（按拼音首字母排序）](#rsma-相关研究团队调研按拼音首字母排序)
    - [国内团队](#国内团队)
    - [International research teams](#international-research-teams)
  - [Collected papers](#collected-papers)
    - [Books](#books)
    - [Survey](#survey)
    - [Letters](#letters)
    - [Paper with code](#paper-with-code)
    - [Optimization](#optimization)

## RSMA 相关研究团队调研（按拼音首字母排序）
### 国内团队
按“学校 / 院系或实验室 / 老师或团队 / 关键词 / 链接”拆成短字段表格，查找会更直接。

| 学校/机构 | 院系/实验室 | 老师/团队 | 关键词 | 主页 | IEEE | Scholar/其他 |
| --- | --- | --- | --- | --- | --- | --- |
| 北京理工大学 | 信息与电子学院 | 高镇团队 | 超5G/6G、智能超表面、通感一体化、空天地一体化、边缘计算、AI for 6G | [教师主页](https://sie.bit.edu.cn/szdw/jsml/fzhjkxtcyjsj/zgzcfz/6072a181c2d442659cbdd4a68f2bc999.htm) | [IEEE](https://ieeexplore.ieee.org/author/37073332000) | [Google Scholar](https://scholar.google.com.hk/citations?user=4ylyExkAAAAJ&hl=zh-CN&oi=sra) |
| 北京邮电大学 | 信息与通信学院（网络与交换国家重点实验室） | 李立华团队 | 无线大数据、泛在智能、宽带移动通信理论与技术 | [教师主页](https://teacher.bupt.edu.cn/lilihua/zh_CN/index/46229/list/index.htm) | [IEEE](https://ieeexplore.ieee.org/author/37293043300) | - |
| 重庆邮电大学 | 通信与信息工程学院 | 徐勇军团队 | B5G/6G、智能超表面、通感一体化、车联网、空天地一体化 | [教师主页](https://faculty.cqupt.edu.cn/xuyj/zh_CN/index.htm) | [IEEE](https://ieeexplore.ieee.org/author/37089732139) | [Google Scholar](https://scholar.google.com.hk/citations?user=dXpIOQUAAAAJ&hl=zh-CN&oi=sra) |
| 大连理工大学 | 信息与通信工程学院 | 刘鑫团队 | 空天地一体化通信、AI无线通信、新一代物联网 | [个人主页](http://faculty.dlut.edu.cn/liuxin/zh_CN/index.htm) | [IEEE](https://ieeexplore.ieee.org/author/37085582074) | [Google Scholar](https://scholar.google.com.hk/citations?hl=zh-CN&user=Tmfs2YAAAAAJ) |
| 东南大学 | 信息科学与工程学院 | 陈明团队 | 信号处理、资源分配、MEC、网络规划、可见光通信、优化 | [个人主页](https://radio.seu.edu.cn/2023/1025/c19937a469621/page.htm) | [IEEE](https://ieeexplore.ieee.org/author/37280976800) | - |
| 东南大学 | 网络空间安全学院（移动通信国家重点实验室） | 王家恒团队 | 5G/6G、密集网络、区块链、物联网、毫米波、鲁棒设计 | [个人主页](https://ncrl.seu.edu.cn/_s257/2023/1023/c17542a469398/page.psp) | [IEEE](https://ieeexplore.ieee.org/author/37539031300) | - |
| 国防科技大学 | - | 许程成（博后） | - | - | [IEEE](https://ieeexplore.ieee.org/author/37086333489) | [Google Scholar](https://scholar.google.com.hk/citations?user=XmL_1zwAAAAJ&hl=zh-CN&oi=sra) |
| 哈尔滨工业大学 | 电子与信息工程学院 | 韩帅团队 | 智能通信、物理层安全、卫星通信与导航 | [个人主页](https://www.x-mol.com/university/faculty/301057) | [IEEE](https://ieeexplore.ieee.org/author/38239008200) | [Google Scholar](https://scholar.google.com.hk/citations?user=wCcwfOcAAAAJ&hl=zh-CN&oi=sra) |
| 哈尔滨工业大学（深圳） | 电子与信息工程学院 | 焦健团队 | 空天地海一体化、深空通信、语义通信、大规模接入、毫米波/激光、通感一体化 | [教师主页](https://faculty.hitsz.edu.cn/jiaojian) | [IEEE](https://ieeexplore.ieee.org/author/37864144200) | [Google Scholar](https://scholar.google.com/citations?user=n6VIqnwAAAAJ&hl=zh-CN&oi=sra) |
| 兰州交通大学 | 电子与信息工程学院 | 黄海燕团队 | 云网边端协同、多址接入、物理层安全、无人机通信 | [教师主页](https://dxxy.lzjtu.edu.cn/info/1364/8422.htm) | [IEEE](https://ieeexplore.ieee.org/author/38266787300) | - |
| 山东交通学院 | 信息科学与电器工程学院 | 刘洪武团队 | 无线多址接入、移动边缘计算、RIS、无线可见光、车联网、无人机通信 | [教师个人主页](https://xdxy.sdjtu.edu.cn/info/1374/5474.htm) | [IEEE](https://ieeexplore.ieee.org/author/38468080300) | - |
| 上海科技大学 | 信息科学与技术学院 | 毛奕婕团队 | RSMA、AI+6G、RIS、ISAC、SAGIN | [教师主页（中）](https://sist.shanghaitech.edu.cn/maoyj/main.htm)<br>[Personal homepage](https://faculty.sist.shanghaitech.edu.cn/faculty/maoyj/index.html) | [IEEE](https://ieeexplore.ieee.org/author/37086178897) | [Google Scholar](https://scholar.google.com.hk/citations?user=PZtdokoAAAAJ&hl=zh-CN&oi=sra) |
| 香港大学 | - | Shengyu Zhang | 车联网、通信系统、非正交多址 | - | [IEEE](https://ieeexplore.ieee.org/author/37088911587) | - |
| 西南交通大学 | 信息科学与技术学院 | 刘刚团队 | 网络协议设计、通感一体化、AI通信、定位、轨交通信、车联网 | [教师主页](https://faculty.swjtu.edu.cn/liugang/zh_CN/zdylm/162052/list/index.htm) | [IEEE](https://faculty.swjtu.edu.cn/liugang/zh_CN/zdylm/162052/list/index.htm) | [Google Scholar](https://scholar.google.com.hk/citations?user=08suZn4AAAAJ&hl=zh-CN&oi=sra) |
| 中国科学技术大学 | 电子工程与信息科学系 | 卢汉成团队 | 5G/B5G/6G、智能通信、多媒体传输、边缘计算、未来网络 | [个人主页](https://eeis.ustc.edu.cn/2010/0825/c2648a19508/page.htm) | [IEEE](https://ieeexplore.ieee.org/author/37289425200) | - |
| 中国矿业大学 | 信息与控制工程学院 | 陈瑞瑞团队 | 涡旋电磁波、无人机通信、B5G/6G | [个人主页](http://faculty.cumt.edu.cn/CRR/zh_CN/index/191484/list/index.htm) | [IEEE](https://ieeexplore.ieee.org/author/37086496651) | - |
| 浙江大学 | 信息与电子工程学院 | 杨照辉团队 | 智能通信计算融合、语义通信、边缘学习、全息通信 | [个人主页](https://person.zju.edu.cn/yangzhaohui) | [IEEE](https://ieeexplore.ieee.org/author/37085667482) | [Google Scholar](https://scholar.google.com/citations?user=YNvyKzAAAAAJ) |

### International research teams
也改成按列展开的资料表。

| 团队 | 实验室入口 |
| --- | --- |
| Imperial College London / Wireless Communications and Signal Processing Lab | [People](http://www.ee.ic.ac.uk/bruno.clerckx/People.html)<br>[Research](http://www.ee.ic.ac.uk/bruno.clerckx/Research.html)<br>[Publication](http://www.ee.ic.ac.uk/bruno.clerckx/Publications.html) |

| 成员 | 关键词 | 主页 | IEEE | Scholar/其他 | 备注 |
| --- | --- | --- | --- | --- | --- |
| Bruno Clerckx | Multiple Access、NOMA、SIC、RSMA、RIS、Beamforming | [Personal homepage](http://www.ee.ic.ac.uk/bruno.clerckx/index.html) | [IEEE](https://ieeexplore.ieee.org/author/37269077900) | [Google Scholar](https://scholar.google.co.uk/citations?user=knPmgzsAAAAJ&hl=en)<br>[YouTube](https://www.youtube.com/@prof.brunoclerckx1530) | - |
| Yijie (Lina) Mao | MIMO、RSMA、NOMA、5G and beyond | [Personal homepage](https://sist.shanghaitech.edu.cn/maoyj/main.htm) | [IEEE](https://ieeexplore.ieee.org/author/37086178897) | [Google Scholar](https://scholar.google.com.hk/citations?user=PZtdokoAAAAJ&hl=zh-CN&oi=sra) | - |
| Onur Dizdar | Communications、Error-Correcting Codes、RSMA、NOMA、Signal Processing | - | [IEEE](https://ieeexplore.ieee.org/author/38266703700) | [Google Scholar](https://scholar.google.com.hk/citations?user=Ws8zBXMAAAAJ&hl=zh-CN&oi=sra) | - |
| Longfei Yin | RSMA、satellite communications、radar and communications | - | [IEEE](https://ieeexplore.ieee.org/author/37088446743) | [Google Scholar](https://scholar.google.com.hk/citations?user=HKV0EWsAAAAJ&hl=zh-CN&oi=sra) | - |
| Yang Zhao | Intelligent Reflecting Surfaces | - | - | [GitHub](https://github.com/snowztail/rate-splitting-multiple-access-for-downlink-communication-systems) | - |
| Xinze Lyu | RSMA、radio system prototyping | - | [IEEE](https://ieeexplore.ieee.org/author/325353694497961) | [Google Scholar](https://scholar.google.com.hk/citations?user=dhAQftoAAAAJ&hl=zh-CN&oi=sra) | - |
| Yunnuo Xu | RSMA | - | [IEEE](https://ieeexplore.ieee.org/author/37088994314) | [Google Scholar](https://scholar.google.com/citations?user=979z53EAAAAJ&hl=zh-CN&oi=sra) | - |
| Jiawei Xu | RSMA | - | [IEEE](https://ieeexplore.ieee.org/author/37089722068) | [Google Scholar](https://scholar.google.com/citations?user=mFRRgPcAAAAJ&hl=zh-CN&oi=sra) | - |
| Anup Mishra | RSMA、Communication Theory、Massive MIMO | - | [IEEE](https://ieeexplore.ieee.org/abstract/document/9663192) | [Google Scholar](https://scholar.google.com.hk/citations?user=NTQbw4wAAAAJ&hl=zh-CN&oi=sra) | - |
| Gui Zhou | RIS、array signal processing | - | [IEEE](https://ieeexplore.ieee.org/author/37088415204) | [Google Scholar](https://scholar.google.com/citations?user=PMLUoekAAAAJ&hl=zh-CN&oi=sra) | - |
| Chengcheng Xu | ISAC、AI-assisted spectrum sensing、VLSI for signal processing | - | [IEEE](https://ieeexplore.ieee.org/author/37086333489) | [Google Scholar](https://scholar.google.com.hk/citations?user=XmL_1zwAAAAJ&hl=zh-CN&oi=sra) | - |
| Huiyun Xia | Physical-layer security、RSMA、interference management、wireless optimization、MIMO | - | [IEEE](https://ieeexplore.ieee.org/author/37087029643) | - | Visiting PhD student from Harbin Institute of Technology |

## Collected papers
### Books
- **Mao, Y., Clerckx, B. (2021). Multiple Access Techniques. In: Lin, X., Lee, N. (eds) [5G and Beyond](https://link.springer.com/chapter/10.1007/978-3-030-58197-8_3). Springer, Cham.**
### Survey
- **Mao Y, Clerckx B, Li V O K. [Rate-splitting multiple access for downlink communication systems: Bridging, generalizing, and outperforming SDMA and NOMA](https://link.springer.com/article/10.1186/s13638-018-1104-7)[J]. EURASIP journal on wireless communications and networking, 2018, 2018: 1-54.[[code]](https://github.com/YijieLinaMao/RSMA)**
- **B. Clerckx et al., "[Is NOMA Efficient in Multi-Antenna Networks? A Critical Look at Next Generation Multiple Access Techniques](https://ieeexplore.ieee.org/document/9451194)," in IEEE Open Journal of the Communications Society, vol. 2, pp. 1310-1343, 2021, doi: 10.1109/OJCOMS.2021.3084799.**
- **Y. Mao, O. Dizdar, B. Clerckx, R. Schober, P. Popovski and H. V. Poor, "[Rate-Splitting Multiple Access: Fundamentals, Survey, and Future Research Trends](https://ieeexplore.ieee.org/document/9831440)," in IEEE Communications Surveys & Tutorials, vol. 24, no. 4, pp. 2073-2126, Fourthquarter 2022, doi: 10.1109/COMST.2022.3191937.**
- **B. Clerckx et al., "[A Primer on Rate-Splitting Multiple Access: Tutorial, Myths, and Frequently Asked Questions](https://ieeexplore.ieee.org/document/10038476)," in IEEE Journal on Selected Areas in Communications, vol. 41, no. 5, pp. 1265-1308, May 2023, doi: 10.1109/JSAC.2023.3242718.[[lecture1]](https://www.youtube.com/watch?v=OB5YzL8pJ48)[[lecture2]](https://www.youtube.com/watch?v=H8e-PLvU3lM)**
- **B. Clerckx et al., "[Multiple Access Techniques for Intelligent and Multifunctional 6G: Tutorial, Survey, and Outlook](https://ieeexplore.ieee.org/document/10562043)," in Proceedings of the IEEE, vol. 112, no. 7, pp. 832-879, July 2024, doi: 10.1109/JPROC.2024.3409428.**
### Letters
- **A. Mishra, Y. Mao, O. Dizdar and B. Clerckx, "[Rate-Splitting Multiple Access for 6G—Part I: Principles, Applications and Future Works](https://ieeexplore.ieee.org/document/9832611)," in IEEE Communications Letters, vol. 26, no. 10, pp. 2232-2236, Oct. 2022, doi: 10.1109/LCOMM.2022.3192012.**
- **L. Yin, Y. Mao, O. Dizdar and B. Clerckx, "[Rate-Splitting Multiple Access for 6G—Part II: Interplay With Integrated Sensing and Communications](https://ieeexplore.ieee.org/document/9832622)," in IEEE Communications Letters, vol. 26, no. 10, pp. 2237-2241, Oct. 2022, doi: 10.1109/LCOMM.2022.3192032.**
- **H. Li, Y. Mao, O. Dizdar and B. Clerckx, "[Rate-Splitting Multiple Access for 6G—Part III: Interplay With Reconfigurable Intelligent Surfaces](https://ieeexplore.ieee.org/document/9832618)," in IEEE Communications Letters, vol. 26, no. 10, pp. 2242-2246, Oct. 2022, doi: 10.1109/LCOMM.2022.3192041.** 


### Paper with code
- **Mao Y, Clerckx B, Li V O K. [Rate-splitting multiple access for downlink communication systems: Bridging, generalizing, and outperforming SDMA and NOMA](https://link.springer.com/article/10.1186/s13638-018-1104-7)[J]. EURASIP journal on wireless communications and networking, 2018, 2018: 1-54.[[code]](https://github.com/YijieLinaMao/RSMA)**
- **H. Joudeh and B. Clerckx, "[Sum-Rate Maximization for Linearly Precoded Downlink Multiuser MISO Systems With Partial CSIT: A Rate-Splitting Approach](https://ieeexplore.ieee.org/document/7555358)," in IEEE Transactions on Communications, vol. 64, no. 11, pp. 4847-4861, Nov. 2016, doi: 10.1109/TCOMM.2016.2603991.[[code]](https://github.com/jhan-04/Sum-Rate-Maximization-for-Linearly-Precoded-Downlink-Multiuser-MISO-Systems-With-Partial-CSIT-A-Rate)**
- **M. Wu, Z. Gao, Y. Huang, Z. Xiao, D. W. K. Ng and Z. Zhang, "[Deep Learning-Based Rate-Splitting Multiple Access for Reconfigurable Intelligent Surface-Aided Tera-Hertz Massive MIMO](https://ieeexplore.ieee.org/document/10032139)," in IEEE Journal on Selected Areas in Communications, vol. 41, no. 5, pp. 1431-1451, May 2023, doi: 10.1109/JSAC.2023.3240781.[[code]](https://github.com/wuminghui123/DL_RSMA)**
- **F. Luo and Y. Mao, "[A Practical Max-Min Fair Resource Allocation Algorithm for Rate-Splitting Multiple Access](https://ieeexplore.ieee.org/document/10304220)," in IEEE Communications Letters, vol. 27, no. 12, pp. 3285-3289, Dec. 2023, doi: 10.1109/LCOMM.2023.3329149.[[code]](https://github.com/YijieLinaMao/RSMA-low-complexity-MaxMin)**
- **B. -J. Chen, R. Y. Chang, F. -T. Chien and H. V. Poor, "[Energy-Efficient Multi-RIS-Aided Rate-Splitting Multiple Access: A Graph Neural Network Approach](https://ieeexplore.ieee.org/document/10530383)," in IEEE Wireless Communications Letters, doi: 10.1109/LWC.2024.3400927.[[code]](https://github.com/BingJiaChen/RSMA_GNN_EE)**
- **R. -J. Reifert, Y. Karacora, D. S. V. Suárez, D. S. R. Rico, D. M. A. Mosquera and A. Sezgin, "[A Practical Study of Rate-Splitting Multiple Access: Single vs. Multiple Common Messages](https://ieeexplore.ieee.org/document/10694543)," 2024 IEEE 25th International Workshop on Signal Processing Advances in Wireless Communications (SPAWC), Lucca, Italy, 2024, pp. 596-600, doi: 10.1109/SPAWC60668.2024.10694543.[[code]](https://github.com/dviracachas/LabVIEW-Tx-Rx-Workbench)**
- **Y. Wang, T. Fang and Y. Mao, "[An Efficient Beamforming Optimization Framework for Generalized Rate-Splitting with Imperfect CSIT](https://ieeexplore.ieee.org/document/10938379)," in IEEE Transactions on Communications, doi: 10.1109/TCOMM.2025.3552748.[[code]](https://github.com/YijieLinaMao/GRS-FP-HFPI)**
- **F. Luo and Y. Mao, "[An Efficient Max-Min Fair Resource Optimization Algorithm for Rate-Splitting Multiple Access](https://ieeexplore.ieee.org/document/11080259)," in IEEE Transactions on Wireless Communications, vol. 25, pp. 787-801, 2026, doi: 10.1109/TWC.2025.3586919.[[code]](https://github.com/YijieLinaMao/RSMA-low-complexity-maxmin-K-user)**



### Optimization
- **Z. -q. Luo, W. -k. Ma, A. M. -c. So, Y. Ye and S. Zhang, "[Semidefinite Relaxation of Quadratic Optimization Problems](https://ieeexplore.ieee.org/document/5447068)," in IEEE Signal Processing Magazine, vol. 27, no. 3, pp. 20-34, May 2010, doi: 10.1109/MSP.2010.936019.**
- **Q. Shi, M. Razaviyayn, Z. -Q. Luo and C. He, "[An Iteratively Weighted MMSE Approach to Distributed Sum-Utility Maximization for a MIMO Interfering Broadcast Channel](https://ieeexplore.ieee.org/document/5756489)," in IEEE Transactions on Signal Processing, vol. 59, no. 9, pp. 4331-4340, Sept. 2011, doi: 10.1109/TSP.2011.2147784.[[code]](https://zhuanlan.zhihu.com/p/586660620)[[lecture1]](https://www.bilibili.com/video/BV1oV4y1L7D3/?spm_id_from=333.337.search-card.all.click&vd_source=466e8bdaaf9c540ba810bf2a935185f9)[[lecture2]](https://www.bilibili.com/video/BV1jS4y1t7aD/?spm_id_from=333.788.recommend_more_video.1&vd_source=466e8bdaaf9c540ba810bf2a935185f9)**
- **X. Zhao, S. Lu, Q. Shi and Z. -Q. Luo, "[Rethinking WMMSE: Can Its Complexity Scale Linearly With the Number of BS Antennas?](https://ieeexplore.ieee.org/document/10054084)," in IEEE Transactions on Signal Processing, vol. 71, pp. 433-446, 2023, doi: 10.1109/TSP.2023.3244104.[[code]](https://github.com/FenghaoZhu/R-WMMSE)**
- **K. Shen and W. Yu, "[Fractional Programming for Communication Systems—Part I: Power Control and Beamforming](https://ieeexplore.ieee.org/document/8314727)," in IEEE Transactions on Signal Processing, vol. 66, no. 10, pp. 2616-2630, 15 May15, 2018, doi: 10.1109/TSP.2018.2812733.[[code]](https://kaimingshen.github.io/publications.html)**
- **K. Shen and W. Yu, "[Fractional Programming for Communication Systems—Part II: Uplink Scheduling via Matching](https://ieeexplore.ieee.org/document/8310563)," in IEEE Transactions on Signal Processing, vol. 66, no. 10, pp. 2631-2644, 15 May15, 2018, doi: 10.1109/TSP.2018.2812748.[[code]](https://kaimingshen.github.io/publications.html)**
- **Y. Sun, P. Babu and D. P. Palomar, "[Majorization-Minimization Algorithms in Signal Processing, Communications, and Machine Learning](https://ieeexplore.ieee.org/document/7547360)," in IEEE Transactions on Signal Processing, vol. 65, no. 3, pp. 794-816, 1 Feb.1, 2017, doi: 10.1109/TSP.2016.2601299.**
- **C. Pan et al., "[An Overview of Signal Processing Techniques for RIS/IRS-Aided Wireless Systems](https://ieeexplore.ieee.org/document/9847080)," in IEEE Journal of Selected Topics in Signal Processing, vol. 16, no. 5, pp. 883-917, Aug. 2022, doi: 10.1109/JSTSP.2022.3195671.[[code]](https://github.com/wkz20042008/An-Overview-of-Signal-Processing-Techniques-for-RIS-IRS-aided-Wireless-Systems)**
- **Y. Shen, J. Zhang, S. H. Song and K. B. Letaief, "[Graph Neural Networks for Wireless Communications: From Theory to Practice," in IEEE Transactions on Wireless Communications](https://ieeexplore.ieee.org/abstract/document/9944643), vol. 22, no. 5, pp. 3554-3569, May 2023, doi: 10.1109/TWC.2022.3219840.[[code]](https://github.com/yshenaw/GNN4Com)**
- **Y. Shen, Y. Shi, J. Zhang and K. B. Letaief, "[Graph Neural Networks for Scalable Radio Resource Management: Architecture Design and Theoretical Analysis](https://ieeexplore.ieee.org/document/9252917)," in IEEE Journal on Selected Areas in Communications, vol. 39, no. 1, pp. 101-115, Jan. 2021, doi: 10.1109/JSAC.2020.3036965.[[code]](https://github.com/yshenaw/GNN-Resource-Management)**
- **G. Zhou, C. Pan, H. Ren, K. Wang and A. Nallanathan, "[A Framework of Robust Transmission Design for IRS-Aided MISO Communications With Imperfect Cascaded Channels](https://ieeexplore.ieee.org/abstract/document/9180053)," in IEEE Transactions on Signal Processing, vol. 68, pp. 5092-5106, 2020, doi: 10.1109/TSP.2020.3019666.[[code]](https://github.com/ken0225/Framework-of-Robust-Transmission-Design-for-IRS-Aided-MISO-Communications)**
- **C. Huang, R. Mo and C. Yuen, "[Reconfigurable Intelligent Surface Assisted Multiuser MISO Systems Exploiting Deep Reinforcement Learning](https://ieeexplore.ieee.org/document/9110869)," in IEEE Journal on Selected Areas in Communications, vol. 38, no. 8, pp. 1839-1850, Aug. 2020, doi: 10.1109/JSAC.2020.3000835. [[code]](https://github.com/baturaysaglam/RIS-MISO-Deep-Reinforcement-Learning)**
- **E. Björnson, M. Bengtsson and B. Ottersten, "[Optimal Multiuser Transmit Beamforming: A Difficult Problem with a Simple Solution Structure [Lecture Notes]](https://ieeexplore.ieee.org/document/6832894)," in IEEE Signal Processing Magazine, vol. 31, no. 4, pp. 142-148, July 2014, doi: 10.1109/MSP.2014.2312183.[[code]](https://zhuanlan.zhihu.com/p/675596614)**
- **X. Zhao, W. Deng, M. Li and M. -J. Zhao, "[Robust Beamforming Design for Integrated Sensing and Covert Communication Systems](https://ieeexplore.ieee.org/document/10599524)," in IEEE Wireless Communications Letters, vol. 13, no. 9, pp. 2566-2570, Sept. 2024, doi: 10.1109/LWC.2024.3429149.**
- **Z. Wang, X. Mu and Y. Liu, "[STARS Enabled Integrated Sensing and Communications](https://ieeexplore.ieee.org/document/10050406)," in IEEE Transactions on Wireless Communications, vol. 22, no. 10, pp. 6750-6765, Oct. 2023, doi: 10.1109/TWC.2023.3245297.[[code]](https://github.com/zhaolin820/stars-enabled-integrated-sensing-and-communications)**
- **Z. Wang, X. Mu and Y. Liu, "[Near-Field Integrated Sensing and Communications](https://ieeexplore.ieee.org/document/10135096)," in IEEE Communications Letters, vol. 27, no. 8, pp. 2048-2052, Aug. 2023, doi: 10.1109/LCOMM.2023.3280132.[[code]](https://github.com/zhaolin820/near-field-integrated-sensing-and-communications)**
- **Y. -F. Liu et al., "[A Survey of Recent Advances in Optimization Methods for Wireless Communications](https://ieeexplore.ieee.org/document/10636212)," in IEEE Journal on Selected Areas in Communications, vol. 42, no. 11, pp. 2992-3031, Nov. 2024, doi: 10.1109/JSAC.2024.3443759.**
- **R. Zhang et al., "[Toward Edge General Intelligence With Agentic AI and Agentification: Concepts, Technologies, and Future Directions](https://ieeexplore.ieee.org/document/11339915)," in IEEE Communications Surveys & Tutorials, vol. 28, pp. 4285-4318, 2026, doi: 10.1109/COMST.2026.3651702.**
- **C. Hu et al., "[Generative AI-Empowered Secure Communications in Space–Air–Ground Integrated Networks: A Survey and Tutorial](https://ieeexplore.ieee.org/document/11309727)," in IEEE Communications Surveys & Tutorials, vol. 28, pp. 4156-4194, 2026, doi: 10.1109/COMST.2025.3646700.**








