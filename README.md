# distsys-readings

A collection of research papers on Distributed Systems focusing on the way we could build large scale clusters without heavy coordination between nodes.

# Categories

* [Consistency and Replication](#consistency-and-replication)
* [Conflict-Free Replicated Data Types](#conflict-free-replicated-data-types)
* [Failure detection](#failure-detection)
* [Scheduling](#scheduling)
* [Topology](#topology)
* [Peer to Peer](#peer-to-peer)
* [Language and Tools Support](#language-and-tools-support)

## Consistency and Replication

* [Consistency Without Borders](https://people.ucsc.edu/~palvaro/a23-alvaro.pdf) - Peter Alvaro, Peter Bailis, Neil Conway, Joseph M. Hellerstein
* [Anna: A KVS For Any Scale](http://db.cs.berkeley.edu/jmh/papers/anna_ieee18.pdf) - Chenggang Wu, Jose M. Faleiro, Yihan Lin, Joseph M. Hellerstein
* [Putting Consistency Back into Eventual Consistency](https://hal.inria.fr/hal-01248191/document) - Valter Balegas, Sérgio Duarte, Carla Ferreira, Rodrigo Rodrigues, Nuno Preguiça, Mahsa Najafzadeh, Marc Shapiro
* [Don't Settle for Eventual: Scalable Causal Consistency for Wide-Area Storage with COPS](http://www-cgi.cs.cmu.edu/afs/cs.cmu.edu/Web/People/dga/papers/cops-sosp2011.pdf) - Wyatt Lloyd, Michael J. Freedman, Michael Kaminsky, and David G. Andersen
* [Cure: Strong semantics meets high availability and low latency](https://hal.inria.fr/hal-01270776/document) - Deepthi Devaki Akkoorath, Alejandro Tomsic, Manuel Bravo, Zhongmiao Li, Tyler Crain, Annette Bieniusa, Nuno Preguiça, Marc Shapiro
* [Bolt-On Causal Consistency](https://kelehers.me/others/bolton-sigmod2013.pdf) - Peter Bailis, Ali Ghodsi, Joseph M. Hellerstein, Ion Stoica
* [The Potential Dangers of Causal Consistency and an Explicit Solution](https://people.eecs.berkeley.edu/~alig/papers/dangers-causal-consistency.pdf) - Peter Bailis, Alan Fekete, Ali Ghodsi, Joseph M. Hellerstein, Ion Stoica
* [Geo-Replication: Fast If Possible, Consistent If Necessary]() - Valter Balegas, Cheng Li, Mahsa Najafzadeh, Daniel Porto, Allen Clement, Sérgio Duarte, Carla Ferreira, Johannes Gehrke, João Leitão, Nuno Preguiça, et al.
* [Concise Server-Wide Causality Management for Eventually Consistent Data Stores](https://repositorium.sdum.uminho.pt/bitstream/1822/40555/1/2218.pdf) - Ricardo Gonçalves, Paulo Sérgio Almeida, Carlos Baquero, Victor Fonte

## Conflict-free Replicated Data Types

* [Conflict-free Replicated Data Types](https://hal.inria.fr/inria-00609399/document) - Marc Shapiro, Nuno Preguiça, Carlos Baquero, Marek Zawirski
* [Delta State Replicated Data Types](http://haslab.uminho.pt/ashoker/files/deltacrdts-tr.pdf) - Paulo Sérgio Almeida, Ali Shoker, Carlos Baquero

## Scheduling

* [Omega: flexible, scalable schedulers for large compute clusters](http://people.csail.mit.edu/malte/pub/papers/2013-eurosys-omega.pdf) - Malte Schwarzkopf, Andy Konwinski, Michael Abd-El-Malek, John Wilkes
* [Sparrow: Distributed, Low Latency Scheduling](http://people.eecs.berkeley.edu/~keo/publications/sosp13-final17.pdf) - Kay Ousterhout, Patrick Wendell, Matei Zaharia, Ion Stoica
* [Slot Scheduling: General-Purpose Multiprocessor Scheduling for Heterogeneous Workloads](https://pdfs.semanticscholar.org/c8a5/351c1f43c46427ab86400182d65196d6f3c4.pdf) - Brandon Hall
* [Paired Gang Scheduling](https://www.cs.huji.ac.il/~feit/papers/GangPair03TPDS.pdf) - Yair Wiseman, Drog G. Feitelson
* [Lock-free and Wait-free Slot Scheduling
Algorithms](http://cse.iitd.ac.in/~srsarangi/files/papers/free.pdf) - Pooja Aggarwal, Smruti R. Sarangi

## Failure Detection

* [Failure Detectors for Large-Scale Distributed Systems](https://pdfs.semanticscholar.org/2e55/a86b508305fe775b3bbf3b32c1f00735040d.pdf) - Naohiro Hayashibara, Adel Cherif, Takuya Katayama
* [2W-FD: A Failure Detector Algorithm with QoS](https://hal.archives-ouvertes.fr/hal-01357777/document) - Alejandro Z. Tomsic, Pierre Sens, Joao Coelho Garcia, Luciana Arantes, Julien Sopena
* [The φ Accrual Failure Detector](https://dspace.jaist.ac.jp/dspace/bitstream/10119/4784/1/IS-RR-2004-010.pdf) - Naohiro Hayashibara, Xavier Défago, Rami Yared, Takuya Katayama
* [A Scalable and Efficient Self-Organizing Failure Detector for Grid Applications](https://www.researchgate.net/profile/Takashi_Chikayama/publication/4194216_A_Scalable_and_Efficient_Self-Organizing_Failure_Detector_for_Grid_Applications/links/559143e808ae15962d8d66b7/A-Scalable-and-Efficient-Self-Organizing-Failure-Detector-for-Grid-Applications.pdf) - Yuuki Horita, Kenjiro Taura, Takashi Chikayama

## Topology

* [T-man: Gossip-based Overlay Topology Management](http://publicatio.bibl.u-szeged.hu/1650/1/esoa05.pdf) - Márk Jelasity, Ozalp Babaoglu
* [A fair comparison of gossip algorithms over large-scale random topologies](https://www.researchgate.net/profile/Pierre_Sens3/publication/235007409_Fair_Comparison_of_Gossip_Algorithms_over_Large-Scale_Random_Topologies/links/54ef3da50cf2432ba656320f.pdf) - Ruijing Hu, Julien Sopena, Luciana Arantes, Pierre Sens, Isabelle Demeure

## Peer to Peer

* [A Survey and Comparison of Peer-to-Peer Overlay Network Schemes](http://www.pitt.edu/~dtipper/3350/P2P1.pdf) - Eng Keong Lua, Jon Crowcroft, Marcelo Pias, Ravi Sharma and Steven Lim

## Language and Tools Support

* [Lasp: A Language for Distributed, Coordination-Free Programming](https://www.info.ucl.ac.be/~pvr/ppdp-2015-cr.pdf) - Christopher Meiklejohn, Peter Van Roy
