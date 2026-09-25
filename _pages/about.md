---
permalink: /
title: ""
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

{% if site.google_scholar_stats_use_cdn %}
{% assign gsDataBaseUrl = "https://cdn.jsdelivr.net/gh/" | append: site.repository | append: "@" %}
{% else %}
{% assign gsDataBaseUrl = "https://raw.githubusercontent.com/" | append: site.repository | append: "/" %}
{% endif %}
{% assign url = gsDataBaseUrl | append: "google-scholar-stats/gs_data_shieldsio.json" %}

<span class='anchor' id='about-me'></span>
I am a postdoctoral researcher in the [Advanced Software Technologies (AST) Lab](https://ast.ethz.ch/) at ETH Zürich, working under the supervision of Prof. [Zhendong Su](https://people.inf.ethz.ch/suz/). I received my Ph.D. from Fudan University in 2026, advised by Prof. [Yuan Zhang](https://yuanxzhang.github.io/) and Prof. [Min Yang](https://min-yang-fudan.github.io/), and received my B.Eng. from Northwestern Polytechnical University in 2021.

My research focuses on **web security** and **LLM-based agent security**. My work has appeared in leading security conferences, including IEEE S&P, ACM CCS, and USENIX Security. My papers have received **Distinguished Paper Awards** at **IEEE S&P 2025** and **ACM CCS 2025**, as well as **Honorable Mention Award** at **USENIX Security 2025**. My research has been adopted by leading technology companies, including **Alibaba, ByteDance, and Huawei**, and acknowledged in security advisories published by Apple, Microsoft, and Intel.

# 📝 Publications 

## Selected Publications

- `ACM CCS'26` **BACAgent: LLM-Powered Detection of Broken-Access-Control Vulnerabilities in Web Applications** [[PDF](/paper/bacagent-ccs26.pdf)]  
  <u>Fengyu Liu</u>, Yuan Zhang, Zheng Lou, Tian Chen, Youkun Shi, Jiarun Dai, Enhao Li, Guangyu Zhou, Zhongfu Su, Zequn Fang.  
  In *Proceedings of the 33rd ACM Conference on Computer and Communications Security (CCS)*, November 2026. (<span style="color:#B00C00">CCF-A</span>)  

- `USENIX Security'25` **Make Agent Defeat Agent: Automatic Detection of Taint-Style Vulnerabilities in LLM-based Agents** [[PDF](/paper/agentfuzz-security25.pdf)]  
  <u>Fengyu Liu</u>, Yuan Zhang, Jiaqi Luo, Jiarun Dai, Tian Chen, Letian Yuan, Zhengmin Yu, Youkun Shi, Ke Li, Hao Chen, Min Yang.  
  In *Proceedings of the 34th USENIX Security Symposium (USENIX Security)*, August 2025. (<span style="color:#B00C00">CCF-A</span>)   
  Presented at **BlackHat Europe 2025** [[Talk Abstract](https://www.blackhat.com/eu-25/briefings/schedule/#make-agent-defeat-agent-automatic-detection-of-taint-style-vulnerabilities-in-llm-based-agents-48117)]
  
- `IEEE S&P'25` **Detecting Taint-Style Vulnerabilities in Microservice-Structured Web Applications** [[PDF](/paper/mscan-oakland25.pdf)]  
  <u>Fengyu Liu</u>, Yuan Zhang, Tian Chen, Youkun Shi, Guangliang Yang, Zihan Lin Min Yang, Junyao He, Qi Li.  
  In *Proceedings of the 46th IEEE Symposium on Security and Privacy (S&P)*, May 2025. (<span style="color:#B00C00">CCF-A</span>)  
  **<font color="#B00C00">&#9733; Distinguished Paper Award (<1% submission)</font>**, Presented at **BlackHat USA 2025** [[Talk Abstract](https://www.blackhat.com/us-25/briefings/schedule/#detecting-taint-style-vulnerabilities-in-microservice-structured-web-applications-46427)]

- `IEEE S&P'25` **MOCGuard: Automatically Detecting Missing-Owner-Check Vulnerabilities in Java Web Applications** [[PDF](/paper/mocguard-oakland25.pdf)]  
  <u>Fengyu Liu</u>, Youkun Shi, Yuan Zhang, Guangliang Yang, Enhao Li, Min Yang.  
  In *Proceedings of the 46th IEEE Symposium on Security and Privacy (S&P)*, May 2025. (<span style="color:#B00C00">CCF-A</span>)  

- `ACM CCS'25` **BACScan: Automatic Black-Box Detection of Broken-Access-Control Vulnerabilities in Web Applications** [[PDF](/paper/bacscan-ccs25.pdf)]  
  <u>Fengyu Liu</u>, Yuan Zhang, Enhao Li, Wei Meng, Youkun Shi, Qianheng Wang, Chenlin Wang, Zihan Lin, Min Yang.  
  In *Proceedings of the 32nd ACM Conference on Computer and Communications Security (CCS)*, October 2025. (<span style="color:#B00C00">CCF-A</span>)  
  **<font color="#B00C00">&#9733; Distinguished Paper Award (<1% submission)</font>**

- `ACM CCS'25` **Be Aware of What You Let Pass: Demystifying URL-based Authentication Bypass Vulnerability in Java Web Applications** [PDF]  
  Qiyi Zhang<sup>\*</sup>, <u>Fengyu Liu<sup>*</sup></u>, Zihan Lin, Yuan Zhang (* co-first authors).  
  In *Proceedings of the 32nd ACM Conference on Computer and Communications Security (CCS)*, October 2025. (<span style="color:#B00C00">CCF-A</span>)  


## Other Publications

- `IEEE S&P'27` **Babel of Voices: Demystifying Security Threats Arising from Cross-Specification URL Parsing Inconsistencies in Web Applications**  
  Qiyi Zhang, Anmao Gou, Youkun Shi, <u>Fengyu Liu</u>, Yuan Zhang.  
  In *Proceedings of 48th IEEE Symposium on Security and Privacy (S&P)*, May 2027.

- `IEEE S&P'27` **FBOLA: Detecting Broken Object-Level Authorization Vulnerabilities via Frontend-Backend Integrated Static Analysis**  
  Ziao Li, Youkun Shi, Jiarun Dai, Yuanhao Li, <u>Fengyu Liu</u>, Yi Xu, Lei Zhang, Yuan Zhang.  
  In *Proceedings of 48th IEEE Symposium on Security and Privacy (S&P)*, May 2027.

- `ACM CCS'26` **Reproducing Web Application Vulnerabilities with Patch-Guided Routing Inference and Sink Exploration**  
  Youkun Shi, Yuan Zhang, Feng Xue, Jiarun Dai, Lei Zhang, <u>Fengyu Liu</u>, Bocheng Xiang, Xiapu Luo.  
  In *Proceedings of the 33rd ACM Conference on Computer and Communications Security (CCS)*, November 2026. (<span style="color:#B00C00">CCF-A</span>)  

- `ACM CCS'26` **VUnitFuzz: Decoupling PHP Sink Verification from Monolithic Execution for Taint-Style Vulnerability Detection**  
  Youkun Shi, Yuan Zhang, Tianhao Bai, Jiarun Dai, <u>Fengyu Liu</u>, Xiapu Luo.
  In *Proceedings of the 33rd ACM Conference on Computer and Communications Security (CCS)*, November 2026. (<span style="color:#B00C00">CCF-A</span>)  

- `ACM CCS'26` **PHPBench: Automated Generation of Verifiable and Hierarchical Benchmarks for PHP Web Fuzzing**  
  Youkun Shi, Yuan Zhang, Lei Zhang, Jiarun Dai, Tianhao Bai, <u>Fengyu Liu</u>, Bocheng Xiang, Xiapu Luo, Min Yang.  
  In *Proceedings of the 33rd ACM Conference on Computer and Communications Security (CCS)*, November 2026. (<span style="color:#B00C00">CCF-A</span>)  

- `TIFS'26` **Measuring and Understanding Expectation Inconsistency in Java Libraries**  
  Zihan Lin, Yuan Zhang, Letian Yuan, Guangliang Yang, Youkun Shi, <u>Fengyu Liu</u>, Xin Tan, Min Yang.
  In *IEEE Transactions on Information Forensics and Security*, 2026. (<span style="color:#B00C00">CCF-A</span>)  
  
- `USENIX Security'26` **Autonomy Comes with Costs: Detecting Denial-of-Service Vulnerabilities Caused by Resource Abusing in LLM-based Agents**  
  Jiaqi Luo, Jiarun Dai, <u>Fengyu Liu</u>, Songyang Peng, Youkun Shi, Tong Bu, Geng Hong, Xudong Pan, Yuan Zhang.  
  In Proceedings of the 35th USENIX Security Symposium (USENIX Security), Baltimore, MD, USA, August 12-14, 2026. (<span style="color:#B00C00">CCF-A</span>)

- `NDSS'26` **LinkGuard: A Lightweight State-Aware Runtime Guard Against Link Following Attacks in Windows File System**  
  Bocheng Xiang, Yuan Zhang, Hao Huang, <u>Fengyu Liu</u>, Youkun Shi.  
  In *Proceedings of the Network and Distributed System Security (NDSS)*, February 2026. (<span style="color:#B00C00">CCF-A</span>)  

- `USENIX Security'25` **Pig in a Poke: Automatically Detecting and Exploiting Link Following Vulnerabilities in Windows File Operations**  
  Bocheng Xiang, Yuan Zhang, <u>Fengyu Liu</u>, Hao Huang, Zihan Lin, Min Yang.  
  In *Proceedings of the 34th USENIX Security Symposium (USENIX Security)*, August 2025. (<span style="color:#B00C00">CCF-A</span>)   
  **<font color="#B00C00">&#9733; Honerable Mention Award (6.1%=25/407)</font>**

- `USENIX Security'25` **XSSky: Detecting XSS Vulnerabilities through Local Path-Persistent Fuzzing**  
  Youkun Shi, Yuan Zhang, Tianhao Bai, Feng Xue, Jiarun Dai, <u>Fengyu Liu</u>, Lei Zhang, Xiapu Luo, Min Yang.  
  In *Proceedings of the 34th USENIX Security Symposium (USENIX Security)*, August 2025. (<span style="color:#B00C00">CCF-A</span>)   

- `USENIX Security'25` **Effective Directed Fuzzing with Hierarchical Scheduling for Web Vulnerability Detection**  
  Zihan Lin, Yuan Zhang, Jiarun Dai, Xinyou Huang, Bocheng Xiang, Guangliang Yang, Letian Yuan, Lei Zhang, <u>Fengyu Liu</u>, Tian Chen, Min Yang.  
  In *Proceedings of the 34th USENIX Security Symposium (USENIX Security)*, August 2025. (<span style="color:#B00C00">CCF-A</span>)   

- `TIFS'25` **Facilitating Access Control Vulnerability Detection in Modern Java Web Applications with Accurate Permission Check Identification**   
  Youkun Shi, <u>Fengyu Liu</u>, Guangliang Yang, Yuan Zhang, Yinzhi Cao, Enhao Li, Xin Tan, Xiapu Luo, Min Yang, Siyi Chen.   
  In *IEEE Transactions on Information Forensics and Security*, 2025. (<span style="color:#B00C00">CCF-A</span>)  

- `TSE'25` **PHPJoy: A Novel Extended Graph-based PHP Code Analysis Framework**  
  Youkun Shi, Yuan Zhang, Tianhan Luo, Guangliang Yang, Shengke Ye, Chengyu Yang, <u>Fengyu Liu</u>, Xiapu Luo, Min Yang.   
  In *IEEE Transactions on Software Engineering*, 2025. (<span style="color:#B00C00">CCF-A</span>)  


# 🎖 Honors and Awards
- 2026, Outstanding Doctoral Dissertation Award, ACM SIGSAC China (Winner)
- 2025, [Huawei TopMinds Program Offer](https://career.huawei.com/reccampportal/portal5/topminds.html)
- 2025, [ByteDance Jindouyun Program Offer](https://jobs.bytedance.com/campus/jindouyun)
- 2025, [Alibaba A-Star Program Offer](https://talent.alibaba.com/activity/ali-star)
- 2025, [Tencent Qingyun Program Offer](https://join.qq.com/qingyun.html)
- 2025, National Scholarship for Ph.D. Candidates
- 2025, ACM CCS Student Travel Grant Award
- 2025, Outstanding Collaboration Project Award, Alibaba
- 2024, Outstanding Technical Collaboration Project Award, Huawei
- 2023, Tencent Business Breakthrough Award


# 🏆 Selected Competitions
- 2022, 🏆 Champion, 4th "QiangWang" Cup International Elite Challenge On Cyber Mimic Defense (￥80,000)
- 2021, 🏆 Champion, 6th XCTF International League (￥100,000)
- 2021, 🏆 Champion, 13th National College Student Information Security Contest 
- 2020, 🏆 Champion, 4th Peak Geek Cyber Security Skills Challenge (￥100,000)
- 2020, 🏆 Champion, 2nd "WangDing" Cup Qinglong Group  (￥30,000)
- 2019, 🏆 Champion, 4th "Hu-Xiang" Cup (￥160,000)
  
  
# 💻 Internships
- *2020.04 - 2025.04*, [Keen Lab, Tencent](https://keenlab.tencent.com/), China.
- *2019.07 - 2019.09*, [Lark, ByteDance](https://www.bytedance.com/), China.