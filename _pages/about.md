---
permalink: /
title: "About me"
excerpt: "About me"
author_profile: true
hide_title: true
redirect_from: 
  - /about/
  - /about.html
---

## About me

I am a postdoctoral researcher at [EPFL](https://www.epfl.ch/en/), working with [Prof. Antoine Bosselut](https://atcbosselut.github.io/). 
I received my Ph.D. from [The Chinese University of Hong Kong](https://www.cuhk.edu.hk/english/index.html), advised by [Prof. Kam-Fai Wong](https://www1.se.cuhk.edu.hk/~kfwong/), 
and was a visiting researcher at [LMU Munich](https://www.lmu.de/en/) with [Prof. Hinrich Schütze](https://cisnlp.github.io/about/). 
Earlier, I received my M.S. from Peking University and B.S. from Northwestern Polytechnical University.


My research goal is to make language models more capable without making them less reliable. In post-training the supervision is always imperfect, yet standard recipes are designed as if it were clean. I work on understanding how that imperfection surfaces in the trained model, and on building training methods that keep models capable and reliable in spite of it.
 
* **Learning from a sparse RL signal.** In practice, RL for LLMs gives sparse rewards at the end of a long trajectory. Through denser credit assignment and wider exploration, we make it a stronger learning signal. [[BRIDGE](https://arxiv.org/pdf/2509.06948) ICML'26, [EEPO](https://openreview.net/pdf?id=ObF4WIMkY6) ICLR'26]
* **Making alignment survive what comes after it.** LLM alignment is fragile: a range of downstream operations can undo it, from adversarial inputs to malicious finetuning. We build robust alignment methods that hold up under such perturbations. [[PEARL](https://openreview.net/pdf?id=txoJvjfI9w) ICLR'25, [VAA](https://openreview.net/pdf?id=EMHED4WTHT) ICML'25]
* **Trusting text the model produced.** Post-training now runs largely on the model's own output. We asked whether that output can be trusted — evaluating LLMs as knowledge generators, and making what they write attributable. [[WatME](https://aclanthology.org/2024.acl-long.496/) ACL'24, [CONNER](https://aclanthology.org/2023.emnlp-main.390.pdf) EMNLP'23]

Feel free to reach out if you’d like to chat about research or explore potential opportunities.

## News

* [05/2026] One paper accepted at EMNLP 2026. 
* [06/2026] Passed my Ph.D. oral defense.
* [05/2026] One paper on [densifying RL rewards](https://arxiv.org/abs/2509.06948) accepted at ICML 2026.
* [01/2026] One paper on [enhancing RL exploration](https://openreview.net/pdf?id=ObF4WIMkY6) accepted at ICLR 2026.
* [05/2025] One paper on [resilient safety alignment](https://openreview.net/pdf?id=EMHED4WTHT) accepted at ICML 2025.
* [02/2025] One paper on [robust instruction tuning](https://openreview.net/pdf?id=txoJvjfI9w) accepted at ICLR 2025.
* [05/2024] One paper on [LLM watermarking](https://aclanthology.org/2024.acl-long.496.pdf) accepted at ACL 2024.
* [10/2023] One paper on [LLM knowledge evaluation](https://aclanthology.org/2023.emnlp-main.390.pdf) accepted at EMNLP 2023.

## Selected publications ([Full list](/publications/))

- [Beyond Two-Stage Training: Cooperative SFT and RL for LLM Reasoning](https://arxiv.org/abs/2509.06948)  
  **Liang Chen**, Xueting Han, Li Shen, Jing Bai, Kam-Fai Wong  
  *ICML 2026*

- [EEPO: Exploration-Enhanced Policy Optimization via Sample-Then-Forget](https://openreview.net/pdf?id=ObF4WIMkY6)  
  **Liang Chen**, Xueting Han, Qizhou Wang, Bo Han, Jing Bai, Hinrich Schütze, Kam-Fai Wong  
  *ICLR 2026*

- [Vulnerability-Aware Alignment: Mitigating Uneven Forgetting in Harmful Fine-Tuning](https://openreview.net/pdf?id=EMHED4WTHT)  
  **Liang Chen**, Xueting Han, Li Shen, Jing Bai, Kam-Fai Wong  
  *ICML 2025*

- [PEARL: Towards Permutation-Resilient LLMs](https://openreview.net/pdf?id=txoJvjfI9w)  
  **Liang Chen**, Li Shen, Yang Deng, Xiaoyan Zhao, Bin Liang, Kam-Fai Wong  
  *ICLR 2025*

- [WatME: Towards Lossless Watermarking Through Lexical Redundancy](https://aclanthology.org/2024.acl-long.496.pdf)  
  **Liang Chen**, Yatao Bian, Yang Deng, Deng Cai, Shuaiyi Li, Peilin Zhao, Kam-Fai Wong  
  *ACL 2024*

- [Beyond Factuality: A Comprehensive Evaluation of Large Language Models as Knowledge Generators](https://aclanthology.org/2023.emnlp-main.390.pdf)  
  **Liang Chen**, Yang Deng, Yatao Bian, Zeyu Qin, Bingzhe Wu, Tat-Seng Chua, Kam-Fai Wong  
  *EMNLP 2023*

  
---

## Talks

- Learning Good LLMs from Imperfect Data   
  *Invited Talk*, Microsoft Research Asia – November 2025  
  Host: Dr. Jing Bai
  
- Learning Good LLMs from Imperfect Data  
  *Invited Talk*, EPFL – October 2025  
  Host: Prof. Antoine Bosselut

- Beyond Two-Stage Training: Cooperative SFT and RL for Improved LLM Reasoning  
  *PhD Seminar*, LMU Munich – August 2025  
  Host: Prof. Hinrich Schütze

- Vulnerability-Aware Alignment: Protect Open-Source LLMs against Unsafe Fine-tuning  
  *AI Time*, Online Live – June 2025  

- Towards Trustworthy LLMs: Improving Robustness via Post-Training Optimization  
  *PhD Seminar*, LMU Munich – May 2025  
  Host: Prof. Hinrich Schütze

---

## Teaching

Teaching assistant at CUHK:

- Operations Research II (SEEM3440)
- Engineering Innovation and Entrepreneurship (SEEM3450)
- Information Technology Management (SEEM5730)
  
---

## Internships

- Microsoft Research, Systems Research Group
- Tencent AI Lab, Machine Learning Center

---

## Community service

- Program Committee for AAAI 2027.

- Reviewer for ICML, ICLR, NeurIPS, TMLR, AISTATS, ACL, EMNLP, and NAACL.

---

## Miscellaneous

Outside of research, I enjoy walking in parks, as well as swimming, hiking, and table tennis.
  
During my undergrad, I was the runner-up in the Freshmen Cup table tennis singles match and won the team championship three times.

---



<blockquote style="text-align: center; font-style: italic; color: #4b5563; font-size: 1.0em; margin: 4rem auto 3rem; max-width: 30em; border: none;">
  Live long enough to live forever
</blockquote>

