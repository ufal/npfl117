# Deep Learning Seminar, Summer 2018/19

## Tab: Home

In recent years, **deep neural networks** have been used to solve complex
machine-learning problems and have achieved significant **state-of-the-art**
results in **many** areas. The whole field of deep learning has been developing
**rapidly**, with **new methods** and **techniques** emerging steadily.

The goal of the seminar is to follow the **newest advancements** in the deep
learning field. The course takes form of a **reading group** – each lecture
a paper is presented by one of the students. The paper is announced in advance,
hence all participants can read it beforehand and can take part in the
**discussion of the paper**.

If you want to receive announcements about chosen paper, sign up to our
[mailing list ufal-rg@googlegroups.com](https://groups.google.com/forum/#!forum/ufal-rg).

### About

SIS code: [NPFL117](https://is.cuni.cz/studium/eng/predmety/index.php?do=predmet&kod=NPFL117)<br>
Semester: winter + summer<br>
E-credits: 3<br>
Examination: 0/2 C<br>
Guarantor: [Milan Straka](https://ufal.mff.cuni.cz/milan-straka)

### Timespace Coordinates

The Deep Learning Seminar takes place on **Tuesday** at **10:40** in **S8**. We will first meet on Tuesday **Mar 05**.

### Requirements

To pass the course, you need to **present a research paper** and sufficiently
attend the presentations.

## Tab: Program

If you want to receive announcements about chosen paper, sign up to our
[mailing list ufal-rg@googlegroups.com](https://groups.google.com/forum/#!forum/ufal-rg).

To add your name to a paper the table below, edit the
[source code on GitHub](https://github.com/ufal/npfl117/edit/master/1819-summer/README.md) and send a PR.

<div class="program"><style>
  .program td { vertical-align: middle !important}
  .program tr>td:nth-of-type(1), .program tr>td:nth-of-type(2), .program tr>td:nth-of-type(3) {white-space: nowrap}
</style>

| Date        | Who                | Topic | Paper(s)
| ----        | ---                | ----- | --------
| 05 Mar 2019 | Milan Straka       | Optimization | Noam Shazeer, Mitchell Stern: **[Adafactor: Adaptive Learning Rates with Sublinear Memory Cost](https://arxiv.org/abs/1804.04235)**<br>Ilya Loshchilov, Frank Hutter: **[Decoupled Weight Decay Regularization](https://arxiv.org/abs/1711.05101)**<br>Sashank J. Reddi, Satyen Kale, Sanjiv Kumar: **[On the Convergence of Adam and Beyond](https://openreview.net/forum?id=ryQu7f-RZ)**<br>Liangchen Luo, Yuanhao Xiong, Yan Liu, Xu Sun: **[Adaptive Gradient Methods with Dynamic Bound of Learning Rate](https://openreview.net/forum?id=Bkg3g2R9FX)**
|*12 Mar 2019*|*No DL Seminar*     |              |
| 19 Mar 2019 | Milan Straka       | Optimization | James Martens, Roger Grosse: **[Optimizing Neural Networks with Kronecker-factored Approximate Curvature](https://arxiv.org/abs/1503.05671)**<br>Roger Grosse, James Martens: **[A Kronecker-factored approximate Fisher matrix for convolution layers](https://arxiv.org/abs/1602.01407)**<br>Jimmy Ba, Roger Grosse, James Martens: **[Distributed Second-Order Optimization using Kronecker-Factored Approximations](https://jimmylba.github.io/papers/nsync.pdf)**<br>James Martens, Jimmy Ba: **[Kronecker-Factored Curvature Approximations for Recurrent Neural Networks](https://openreview.net/pdf?id=HyMTkQZAb)**<br>Thomas George, César Laurent, Xavier Bouthillier, Nicolas Ballas, Pascal Vincent: **[Fast Approximate Natural Gradient Descent in a Kronecker-factored Eigenbasis](https://arxiv.org/abs/1806.03884)**
| 26 Mar 2019 | Milan Straka       | AutoML       |Hieu Pham, Melody Y. Guan, Barret Zoph, Quoc V. Le, Jeff Dean: **[Efficient Neural Architecture Search via Parameter Sharing](https://arxiv.org/abs/1802.03268)**<br>Hanxiao Liu, Karen Simonyan, Yiming Yang: **[DARTS: Differentiable Architecture Search](https://arxiv.org/abs/1806.09055)**<br>Han Cai, Ligeng Zhu, Song Han: **[ProxylessNAS: Direct Neural Architecture Search on Target Task and Hardware](https://arxiv.org/abs/1812.00332)**<br>David R. So, Chen Liang, Quoc V. Le: **[The Evolved Transformer](https://arxiv.org/abs/1901.11117)**
| 02 Apr 2019 | Martin Víta        | NLP          | Alexis Conneau, Douwe Kiela, Holger Schwenk, Loic Barrault, Antoine Bordes: **[Supervised Learning of Universal Sentence Representations from Natural Language Inference Data](https://arxiv.org/abs/1705.02364)**<br>Adam Poliak, Jason Naradowsky, Aparajita Haldar, Rachel Rudinger, Benjamin Van Durme: **[Hypothesis Only Baselines in Natural Language Inference](https://arxiv.org/abs/1805.01042)**<br>Amit Gajbhiye, Sardar Jaf, Noura Al Moubayed, A. Stephen McGough, Steven Bradley: **[An Exploration of Dropout with RNNs for Natural Language Inference](https://arxiv.org/abs/1810.08606)**
| 09 Apr 2019 | Tomas Soucek       | GANs         |Zhiming Zhou, Yuxuan Song, Lantao Yu, Hongwei Wang, Jiadong Liang, Weinan Zhang, Zhihua Zhang, Yong Yu: **[Understanding the Effectiveness of Lipschitz-Continuity in Generative Adversarial Nets](https://arxiv.org/abs/1807.00751)**<br>Takeru Miyato, Toshiki Kataoka, Masanori Koyama, Yuichi Yoshida: **[Spectral Normalization for Generative Adversarial Networks](https://arxiv.org/abs/1802.05957)**
| 16 Apr 2019 | Jakub Arnold       | Glow         | Laurent Dinh, David Krueger, Yoshua Bengio: **[NICE: Non-linear Independent Components Estimation](https://arxiv.org/abs/1410.8516)**<br>Laurent Dinh, Jascha Sohl-Dickstein, Samy Bengio: **[Density estimation using Real NVP](https://arxiv.org/abs/1605.08803)**<br>Diederik P. Kingma, Prafulla Dhariwal: **[Glow: Generative Flow with Invertible 1x1 Convolutions](https://arxiv.org/abs/1807.03039)**
| 23 Apr 2019 | Tomáš Gavenčiak    | Value learning | Joel Lehman et al.: **[The Surprising Creativity of Digital Evolution](https://arxiv.org/abs/1803.03453)**<br>P Abbeel, AY Ng: **[Apprenticeship learning via inverse reinforcement learning](http://people.eecs.berkeley.edu/~russell/classes/cs294/s11/readings/Abbeel+Ng:2004.pdf)**<br>Paul Christiano, Jan Leike, Tom B. Brown, Miljan Martic, Shane Legg, Dario Amodei: **[Deep reinforcement learning from human preferences](https://arxiv.org/abs/1706.03741)**<br>Possibly: other IRLs, notes on CIRL, CRMDP, IGT.
| 30 Apr 2019 | Štěpán Hojdar      | Computer vision | Tsung-Yi Lin, Priya Goyal, Ross Girshick, Kaiming He, Piotr Dollár: **[Focal Loss for Dense Object Detection](https://arxiv.org/abs/1708.02002)**<br>Xuebo Liu, Ding Liang, Shi Yan, Dagui Chen, Yu Qiao, Junjie Yan: **[FOTS: Fast Oriented Text Spotting with a Unified Network](https://arxiv.org/abs/1801.01671)**
| 07 May 2019 | Petra Doubravová   | RL as planning  | Danijar Hafner, Timothy Lillicrap, Ian Fischer, Ruben Villegas, David Ha, Honglak Lee, James Davidson: **[Learning Latent Dynamics for Planning from Pixels](https://arxiv.org/abs/1811.04551)** https://planetrl.github.io/
|*14 May 2019*|*No DL Seminar*     |              | *Rector's Day*
| 21 May 2019 |          Surya Prakash          |       AutoRL       |  Hao-Tien Lewis Chiang, Aleksandra Faust, Marek Fiser, Anthony Francis: **Learning Navigation Behaviors End-to-End with AutoRL**.  https://arxiv.org/abs/1809.10124
  Anthony Francis, Aleksandra Faust, Hao-Tien Lewis Chiang, Jasmine Hsu, J. Chase Kew, Marek Fiser, Tsang-Wei Edward Lee: **Long-Range Indoor Navigation with PRM-RL**.  https://arxiv.org/abs/1902.09458

### Preliminary Plan

The topics are in arbitrary order, you can choose any free time slot.

- AutoRL
  - Hao-Tien Lewis Chiang, Aleksandra Faust, Marek Fiser, Anthony Francis: **Learning Navigation Behaviors End-to-End with AutoRL**.  https://arxiv.org/abs/1809.10124
  - Anthony Francis, Aleksandra Faust, Hao-Tien Lewis Chiang, Jasmine Hsu, J. Chase Kew, Marek Fiser, Tsang-Wei Edward Lee: **Long-Range Indoor Navigation with PRM-RL**.  https://arxiv.org/abs/1902.09458

- Delayed reward decomposition
  - Jose A. Arjona-Medina, Michael Gillhofer, Michael Widrich, Thomas Unterthiner, Johannes Brandstetter, Sepp Hochreiter: **RUDDER: Return Decomposition for Delayed Rewards**.  https://arxiv.org/abs/1806.07857

- Large batch training
  - Sam McCandlish, Jared Kaplan, Dario Amodei, OpenAI Dota Team: **An Empirical Model of Large-Batch Training**.  https://arxiv.org/abs/1812.06162


## Tab: Related Courses

### Related Coursed

#### [Deep Learning](https://ufal.mff.cuni.cz/courses/npfl114)
Course introducing deep neural networks, from the basics to the latest advances,
focusing both on **theory** as well as on **practical aspects**.

#### [Deep Reinforcement Learning](https://ufal.mff.cuni.cz/courses/npfl122)
Course introducing reinforcement learning, from basic tabular methods to
involvement of deep neural networks, focusing both on **theory** as well as on
**practical aspects**.

#### [ÚFAL Reading Group](https://ufal.mff.cuni.cz/courses/rg)
Previously, Deep Learning Seminar was held unofficially as ÚFAL Reading Group,
you can see the discussed paper here:
- [ÚFAL Reading Group 2016](https://ufal.mff.cuni.cz/courses/rg/2016)
- [ÚFAL Reading Group 2015](https://ufal.mff.cuni.cz/courses/rg/2015)
- [ÚFAL Reading Group 2014](https://ufal.mff.cuni.cz/courses/rg/2014)

## Tab: Archive

### Archive

#### [Deep Learning Seminar, Winter 2018/19](https://ufal.mff.cuni.cz/courses/npfl117/1819-winter)

#### [Deep Learning Seminar, Summer 2017/18](https://ufal.mff.cuni.cz/courses/npfl117/1718-summer)

#### [Deep Learning Seminar, Summer 2016/17](https://ufal.mff.cuni.cz/courses/npfl117/1617-summer)
