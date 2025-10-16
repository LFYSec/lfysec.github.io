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

Hello, I'm Fengyu Liu, a Ph.D. student in the System and Software Security Laboratory at Fudan University, advised by Prof. [Yuan Zhang](https://yuanxzhang.github.io/) and Prof. [Min Yang](https://scholar.google.com/citations?user=UnKf9FIAAAAJ&hl=en). I am also the captain of Whitzard, a great CTF team at Fudan University.

My research interests includes **web security** and **LLM-based agent security**. To date, I have published several papers at top-tier international security conferences, including IEEE S&P, ACM CCS, USENIX Security, TIFS, and TSE, and have received **Distinguished Paper Awards** from both **S&P'25** and **CCS'25**. Moreover, my research has been adopted by leading companies such as **Alibaba, ByteDance, and Huawei**, and acknowledged in security advisories by major tech companies including Apple, Microsoft, and Intel.

# 🔥 News
- [*2025.10*] &nbsp;🎉 Our paper received <span style="color:#B00C00">**Distinguished Paper Award**</span> at ACM CCS 2025!
- [*2025.10*] &nbsp;🎉 One talk accepted by **BlackHat Europe 2025**!
- [*2025.09*] &nbsp;🎉 One paper accepted by **TIFS 2025**!
- [*2025.09*] &nbsp;🎉 One paper accepted by **TSE 2025**!
- [*2025.08*] &nbsp;🎉 One paper accepted by **CCS 2025**!
- [*2025.08*] &nbsp;🎉 One paper received <span style="color:#B00C00">**Honerable Mention Award**</span> at USENIX Security 2025!
- [*2025.06*] &nbsp;🎉 Three papers accepted by **USENIX Security 2025**!
- [*2025.05*] &nbsp;🎉 One talk accepted by **BlackHat USA 2025**!
- [*2025.05*] &nbsp;🎉 Our paper received <span style="color:#B00C00">**Distinguished Paper Award**</span> at IEEE S&P 2025!
- [*2025.03*] &nbsp;🎉 One paper accepted by **CCS 2025**!
- [*2025.03*] &nbsp;🎉 One paper accepted by **S&P 2025**!
- [*2024.12*] &nbsp;🎉 One paper accepted by **USENIX Security 2025**!
- [*2024.09*] &nbsp;🎉 One paper accepted by **S&P 2025**!


# 📝 Publications 
- `TIFS'25` **Facilitating Access Control Vulnerability Detection in Modern Java Web Applications with Accurate Permission Check Identification** [PDF]  
  Youkun Shi, <u>Fengyu Liu</u>, Guangliang Yang, Yuan Zhang, Yinzhi Cao, Enhao Li, Xin Tan, Xiapu Luo, Min Yang, Siyi Chen.   
  In *IEEE Transactions on Information Forensics and Security*, 2025. (<span style="color:#B00C00">CCF-A</span>)  

- `TSE'25` **PHPJoy: A Novel Extended Graph-based PHP Code Analysis Framework** [PDF]  
  Youkun Shi, Yuan Zhang, Tianhan Luo, Guangliang Yang, Shengke Ye, Chengyu Yang, <u>Fengyu Liu</u>, Xiapu Luo, Min Yang.   
  In *IEEE Transactions on Software Engineering*, 2025. (<span style="color:#B00C00">CCF-A</span>)  

- `CCS'25` **Be Aware of What You Let Pass: Demystifying URL-based Authentication Bypass Vulnerability in Java Web Applications** [PDF]  
  Qiyi Zhang<sup>\*</sup>, <u>Fengyu Liu<sup>*</sup></u>, Zihan Lin, Yuan Zhang (* co-first authors).  
  In *Proceedings of the 32nd ACM Conference on Computer and Communications Security (CCS)*, October 2025. (<span style="color:#B00C00">CCF-A</span>)  

- `USENIX Security'25` **Make Agent Defeat Agent: Automatic Detection of Taint-Style Vulnerabilities in LLM-based Agents** [[PDF](/paper/agentfuzz-security25.pdf)]  
  <u>Fengyu Liu</u>, Yuan Zhang, Jiaqi Luo, Jiarun Dai, Tian Chen, Letian Yuan, Zhengmin Yu, Youkun Shi, Ke Li, Hao Chen, Min Yang.  
  In *Proceedings of the 34th USENIX Security Symposium (USENIX Security)*, August 2025. (<span style="color:#B00C00">CCF-A</span>)   
  Presented at **BlackHat Europe 2025** [[Talk Abstract](https://www.blackhat.com/eu-25/briefings/schedule/#make-agent-defeat-agent-automatic-detection-of-taint-style-vulnerabilities-in-llm-based-agents-48117)]
  
- `USENIX Security'25` **Pig in a Poke: Automatically Detecting and Exploiting Link Following Vulnerabilities in Windows File Operations** [[PDF](/paper/linkzard-security25.pdf)]  
  Bocheng Xiang, Yuan Zhang, <u>Fengyu Liu</u>, Hao Huang, Zihan Lin, Min Yang.  
  In *Proceedings of the 34th USENIX Security Symposium (USENIX Security)*, August 2025. (<span style="color:#B00C00">CCF-A</span>)   
  **<font color="#B00C00">&#9733; Honerable Mention Award (6.1%=25/407)</font>**

- `USENIX Security'25` **XSSky: Detecting XSS Vulnerabilities through Local Path-Persistent Fuzzing** [[PDF](/paper/xssky-security25.pdf)]  
  Youkun Shi, Yuan Zhang, Tianhao Bai, Feng Xue, Jiarun Dai, <u>Fengyu Liu</u>, Lei Zhang, Xiapu Luo, Min Yang.  
  In *Proceedings of the 34th USENIX Security Symposium (USENIX Security)*, August 2025. (<span style="color:#B00C00">CCF-A</span>)   

- `CCS'25` **BACScan: Automatic Black-Box Detection of Broken-Access-Control Vulnerabilities in Web Applications** [PDF]  
  <u>Fengyu Liu</u>, Yuan Zhang, Enhao Li, Wei Meng, Youkun Shi, Qianheng Wang, Chenlin Wang, Zihan Lin, Min Yang.  
  In *Proceedings of the 32nd ACM Conference on Computer and Communications Security (CCS)*, October 2025. (<span style="color:#B00C00">CCF-A</span>)  
  **<font color="#B00C00">&#9733; Distinguished Paper Award (<1% submission)</font>**

- `S&P'25` **Detecting Taint-Style Vulnerabilities in Microservice-Structured Web Applications** [[PDF](/paper/mscan-oakland25.pdf)]  
  <u>Fengyu Liu</u>, Yuan Zhang, Tian Chen, Youkun Shi, Guangliang Yang, Zihan Lin Min Yang, Junyao He, Qi Li.  
  In *Proceedings of the 46th IEEE Symposium on Security and Privacy (S&P)*, May 2025. (<span style="color:#B00C00">CCF-A</span>)  
  **<font color="#B00C00">&#9733; Distinguished Paper Award (<1% submission)</font>**, Presented at **BlackHat USA 2025** [[Talk Abstract](https://www.blackhat.com/us-25/briefings/schedule/#detecting-taint-style-vulnerabilities-in-microservice-structured-web-applications-46427)]

- `USENIX Security'25` **Effective Directed Fuzzing with Hierarchical Scheduling for Web Vulnerability Detection** [[PDF](/paper/WDFuzz-security25.pdf)]  
  Zihan Lin, Yuan Zhang, Jiarun Dai, Xinyou Huang, Bocheng Xiang, Guangliang Yang, Letian Yuan, Lei Zhang, <u>Fengyu Liu</u>, Tian Chen, Min Yang.  
  In *Proceedings of the 34th USENIX Security Symposium (USENIX Security)*, August 2025. (<span style="color:#B00C00">CCF-A</span>)   

- `S&P'25` **MOCGuard: Automatically Detecting Missing-Owner-Check Vulnerabilities in Java Web Applications** [[PDF](/paper/mocguard-oakland25.pdf)]  
  <u>Fengyu Liu</u>, Youkun Shi, Yuan Zhang, Guangliang Yang, Enhao Li, Min Yang.  
  In *Proceedings of the 46th IEEE Symposium on Security and Privacy (S&P)*, May 2025. (<span style="color:#B00C00">CCF-A</span>)     

<!-- # 🎖 Honors and Awards
- *2025.05*: Distinguished Paper Award, S&P 2025 (<1% submission)
 
- *2022.09*: 1st Place of The 13th National College Student Information Security Contest (Final Round) 🏆
-->

# 📖 Educations
- *2021.09 - now*, Ph.D, Fudan University, School of Computer Science.
- *2017.09 - 2021.06*, B.Eng, Northwestern Polytechnical University, School of Computer Science.

# 💻 Internships
- *2020.04 - 2025.04*, [Keen Lab, Tencent](https://keenlab.tencent.com/), China.
- *2019.07 - 2019.09*, [Lark, ByteDance](https://www.bytedance.com/), China.