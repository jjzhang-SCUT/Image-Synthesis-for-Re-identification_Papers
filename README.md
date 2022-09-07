# Papers: Data Generation For ReID (CVPR, ICCV, ECCV, NeurIPS, etc.)

## arXiv 2022  
+ BoT-SORT: Robust Associations Multi-Pedestrian Tracking (arXiv 2022-07)  
Nir Aharon, Roy Orfaig, Ben-Zion Bobrovsky   
[[paper](https://arxiv.org/abs/2206.14651)]  [[code](https://github.com/NirAharon/BOT-SORT)]

+ Observation-Centric SORT: Rethinking SORT for Robust Multi-Object Tracking (arXiv 2022-03)  
Jinkun Cao, Xinshuo Weng, Rawal Khirodkar, Jiangmiao Pang, Kris Kitani   
[[paper](https://arxiv.org/pdf/2203.14360.pdf)]  [[code](https://github.com/noahcao/OC_SORT)]

+ TR-MOT: Multi-Object Tracking by Reference (arXiv 2022-03)  
Mingfei Chen, Yue Liao, Si Liu, Fei Wang, Jenq-Neng Hwang   
[[paper](https://arxiv.org/pdf/2203.16621.pdf)]  [code]  


## ECCV 2022  

+ ByteTrack: Multi-Object Tracking by Associating Every Detection Box (arXiv 2021-10)  
Yifu Zhang, Peize Sun, Yi Jiang, Dongdong Yu, Zehuan Yuan, Ping Luo, Wenyu Liu, Xinggang Wang  
[[paper](https://arxiv.org/abs/2110.06864)]  [[code](https://github.com/ifzhang/ByteTrack)]  
  <details>
    <summary>Notes</summary>
     <img src="imgs/mot/byte_track.jpg" width = "267" height = "477" alt="referformer" align=center />  

    - Key points:
         - Low score detection boxes are also associated based on their similarities (IoU) with tracklets to recover true objects and filter out background detections.
         - SOTA performance. MOTA 80.3 HOTA 63.1 on MOT17 and MOTA 77.8 HOTA 61.3 on MOT20.
    </details>


## CVPR 2022  

+ Adiabatic Quantum Computing for Multi Object Tracking. CVPR 2022  
Jan-Nico Zaech, Alexander Liniger, Martin Danelljan, Dengxin Dai, Luc Van Gool   
[[paper](https://openaccess.thecvf.com/content/CVPR2022/papers/Zaech_Adiabatic_Quantum_Computing_for_Multi_Object_Tracking_CVPR_2022_paper.pdf)]  

+ DanceTrack: Multi-Object Tracking in Uniform Appearance and Diverse Motion. CVPR 2022  
Peize Sun, Jinkun Cao, Yi Jiang, Zehuan Yuan, Song Bai, Kris Kitani, Ping Luo   
[[paper](https://arxiv.org/abs/2111.14690)] [[code](https://github.com/DanceTrack/DanceTrack)]
  <details>
    <summary>Notes</summary>
     <img src="imgs/mot/dancetrack.png" width = "643" height = "242" alt="referformer" align=center />  

    - Key points:
         - Proposing a large-scale dataset for multi-human tracking, where humans have similar appearance, diverse motion and extreme articulation.
         - Benchmarking several state-of-the-art trackers on the proposed dataset.
    </details>

