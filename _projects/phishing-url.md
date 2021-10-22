---
title: Phishing URL Detection
header:
  teaser: /assets/images/phishing.png
excerpt: Research internship project
---

During the summer of 2020, in the height of coronavirus pandemic, my plans to travel to Israel for an overseas internship as a research assistant at Cyber@BGU was unfortunately derailed. Nevertheless, the people at Cyber@BGU were kind enough to allow me to complete the internship while still in Singapore, thus telecommuting overseas across a 5 hour time gap.

My research during this internship focused on developing machine learning models that were able to distinguish between malicious and benign URLs. While competitive models already existed, it was found that they were only tuned on standard datasets, and failed to generalise on "in-the-wild data".

I proposed a model which combined an auto-encoder network (trained on unlabelled URLs) with a classifier network. The model not only achieved competitive performances on the standard datasets, but also outperformed other models when evaluated against "in-the-wild data".

![](/assets/images/phishing2.png)

The technical report can be found [here](/assets/papers/phishing.pdf), and a poster (used for my school's submission) can be found [here](/assets/others/cbgu.pdf).