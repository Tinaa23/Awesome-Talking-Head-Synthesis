# Awesome-Talking-Head-Synthesis



This repository organizes papers, codes and resources related to generative adversarial networks (GANs) 🤗 and neural radiance fields (NeRF) 🎨, with a main focus on image-driven and audio-driven talking head synthesis papers and released codes. 👤

Papers for Talking Head Synthesis, released codes collections. ✍️

Most papers are linked to PDFs on "arXiv" or journal/conference websites 📚. However, some papers require an academic license to view 🔐.

🔆 This project Awesome-Talking-Head-Synthesis is ongoing - pull requests are welcome! If you have any suggestions (missing papers, new papers, key researchers or typos), please feel free to edit and submit a PR. You can also open an issue or contact me directly via email. 📩

⭐ If you find this repo useful, please give it a star! 🤩



## Datasets

| Dataset                       | Download Link                                                | Description                                                  |
| ----------------------------- | ------------------------------------------------------------ | ------------------------------------------------------------ |
| VoxCeleb1                     | [Download link](https://www.robots.ox.ac.uk/~vgg/data/voxceleb/vox1.html) |                                                              |
| VoxCeleb2                     | [Download link](https://www.robots.ox.ac.uk/~vgg/data/voxceleb/vox2.html) |                                                              |
| Faceforensics++               | [Download link](https://github.com/ondyari/FaceForensics)    |                                                              |
| CelebV                        | [Download link](https://drive.google.com/file/d/1jQ6d76T5GQuvQH4dq8_Wq1T0cxvN0_xp/view) |                                                              |
| TalkingHead-1KH               | [Download link](https://github.com/deepimagination/TalkingHead-1KH) | Talking-head dataset consisting of YouTube videos            |
| LRW (Lip Reading in the Wild) | [Download link](https://www.robots.ox.ac.uk/~vgg/data/lip_reading/lrw1.html) | Lip Reading in the Wild                                      |
| MEAD 2020                     | [Download link](https://github.com/uniBruce/Mead)            | Talking Head dataset with emotion labels and intensity labels |
| CelebV-HQ                     | [Download link](https://github.com/CelebV-HQ/CelebV-HQ)      | High-quality talking head dataset                            |
| HDTF                          | [Download link](https://github.com/MRzzm/HDTF)               | High-resolution Audio-visual Dataset                         |
| CREMA-D                       | [Download link](https://github.com/CheyneyComputerScience/CREMA-D) |                                                              |
| VoxCeleb                      | [Download link](https://www.robots.ox.ac.uk/~vgg/data/voxceleb/) |                                                              |
| LRS2                          | [Download link](https://www.robots.ox.ac.uk/~vgg/data/lip_reading/lrs2.html) |                                                              |
| GRID                          | [Download link](http://spandh.dcs.shef.ac.uk/avlombard/)     |                                                              |
| SAVEE                         | [Download link](http://kahlan.eps.surrey.ac.uk/savee/Download.html) |                                                              |
| BIWI(3D)                      | [Download link](https://data.vision.ee.ethz.ch/cvl/datasets/b3dac2.en.html) |                                                              |
| VOCA                          | [Download link](https://voca.is.tue.mpg.de/)                 |                                                              |
| Multiface(3D)                 | [Download link](https://github.com/facebookresearch/multiface) |                                                              |

---



## Survey

| Year | Title                                                        | Conference/Journal |
| ---- | ------------------------------------------------------------ | ------------------ |
| 2023 | [From Pixels to Portraits: A Comprehensive Survey of Talking Head Generation Techniques and Applications](https://arxiv.org/abs/2308.16041) | arXiv              |
| 2023 | [Human-Computer Interaction System: A Survey of Talking-Head Generation](https://www.mdpi.com/2079-9292/12/1/218) | IEEE               |
| 2023 | [Talking human face generation: A survey](https://dl.acm.org/doi/10.1016/j.eswa.2023.119678) | ACM                |
| 2022 | [Deep Learning for Visual Speech Analysis: A Survey](https://arxiv.org/abs/2205.10839) | arXiv              |
| 2020 | [What comprises a good talking-head video generation?: A Survey and Benchmark](https://arxiv.org/abs/2005.03201) | arXiv              |

---



## Audio-driven

| Year | Title                                                        | Conference/Journal  | Code                                                         | Project                                                      | Keywords         |
| ---- | ------------------------------------------------------------ | ------------------- | ------------------------------------------------------------ | ------------------------------------------------------------ | ---------------- |
| 2023 | [MODA] [MODA: Mapping-Once Audio-driven Portrait Animation with Dual Attentions](https://arxiv.org/abs/2307.10008) | ICCV 2023           | -                                                            | -                                                            | -                |
| 2023 | [SadTalker] [SadTalker: Learning Realistic 3D Motion Coefficients for Stylized Audio-Driven Single Image Talking Face Animation](https://arxiv.org/pdf/2211.12194.pdf) | CVPR 2023           | [Code](https://github.com/Winfredy/SadTalker)                | [Project](https://sadtalker.github.io/)                      |                  |
| 2023 | [EmoTalk] [EmoTalk: Speech-Driven Emotional Disentanglement for 3D Face Animation](https://arxiv.org/abs/2303.11089) | ICCV 2023           | [Code](https://github.com/ZiqiaoPeng/EmoTalk)                |                                                              | emotion          |
| 2023 | [Emotional Talking Head Generation based on Memory-Sharing and Attention-Augmented Networks](https://arxiv.org/abs/2306.03594) | InterSpeech 2023    |                                                              |                                                              | emotion          |
| 2023 | [High-fidelity Generalized Emotional Talking Face Generation with Multi-modal Emotion Space Learning](https://arxiv.org/abs/2305.02572) | CVPR 2023           |                                                              |                                                              | emotion          |
| 2023 | [StyleSync] [StyleSync: High-Fidelity Generalized and Personalized Lip Sync in Style-based Generator](https://arxiv.org/pdf/2305.05445.pdf) | CVPR 2023           | [Code](https://github.com/guanjz20/StyleSync)                | [Project](https://hangz-nju-cuhk.github.io/projects/StyleSync) | -                |
| 2023 | [TalkLip] [TalkLip: Seeing What You Said - Talking Face Generation Guided by a Lip Reading Expert](https://arxiv.org/pdf/2303.17480.pdf) | CVPR 2023           | [Code](https://github.com/Sxjdwang/TalkLip)                  | -                                                            | -                |
| 2023 | [CodeTalker] [CodeTalker: Speech-Driven 3D Facial Animation with Discrete Motion Prior](https://arxiv.org/abs/2301.02379) | CVPR 2023           | [Code](https://github.com/Doubiiu/CodeTalker)                | -                                                            | codebook         |
| 2023 | [EmoGen] [Emotionally Enhanced Talking Face Generation](https://arxiv.org/pdf/2303.11548.pdf) | Arxiv 2023          | [Code](https://github.com/sahilg06/EmoGen)                   | -                                                            | -                |
| 2023 | [DAE-Talker] [DAE-Talker: High Fidelity Speech-Driven Talking Face Generation with Diffusion Autoencoder](https://arxiv.org/pdf/2303.17550.pdf) | Arxiv 2023          | -                                                            | [Project](https://mstypulkowski.github.io/diffusedheads/)    | 🔥Diffusion:fire: |
| 2023 | [READ] [READ Avatars: Realistic Emotion-controllable Audio Driven Avatars](READ Avatars: Realistic Emotion-controllable Audio Driven Avatars) | Arxiv 2023          | -                                                            | -                                                            | -                |
| 2023 | [DiffTalk] [DiffTalk: Crafting Diffusion Models for Generalized Talking Head Synthesis](https://arxiv.org/abs/2301.03786) | CVPR 2023           | [Code](https://github.com/sstzal/DiffTalk)                   | [Project](https://sstzal.github.io/DiffTalk/)                | 🔥Diffusion🔥      |
| 2023 | [Diffused Heads] [Diffused Heads: Diffusion Models Beat GANs on Talking-Face Generation](https://mstypulkowski.github.io/diffusedheads/diffused_heads.pdf) | Arxiv 2023          | -                                                            | [Project](https://mstypulkowski.github.io/diffusedheads/)    | 🔥Diffusion🔥      |
| 2022 | [MemFace] [Expressive Talking Head Generation with Granular Audio-Visual Control](https://openaccess.thecvf.com/content/CVPR2022/papers/Liang_Expressive_Talking_Head_Generation_With_Granular_Audio-Visual_Control_CVPR_2022_paper.pdf) | CVPR 2022           | -                                                            | -                                                            | -                |
| 2022 | [Talking Face Generation with Multilingual TTS](https://openaccess.thecvf.com/content/CVPR2022/papers/Song_Talking_Face_Generation_With_Multilingual_TTS_CVPR_2022_paper.pdf) | CVPR 2022           | [Demo Track](https://huggingface.co/spaces/CVPR/ml-talking-face) | -                                                            | -                |
| 2022 | [EAMM] [EAMM: One-Shot Emotional Talking Face via Audio-Based Emotion-Aware Motion Model](https://arxiv.org/pdf/2205.15278.pdf) | SIGGRAPH 2022       | -                                                            | -                                                            | emotion          |
| 2022 | [SPACEx] [SPACEx 🚀: Speech-driven Portrait Animation with Controllable Expression](https://arxiv.org/pdf/2211.09809.pdf) | arXiv 2022          | [Project](https://deepimagination.cc/SPACEx/)                | -                                                            | -                |
| 2022 | [AV-CAT] [Masked Lip-Sync Prediction by Audio-Visual Contextual Exploitation in Transformers](https://arxiv.org/pdf/2212.04970.pdf) | SIGGRAPH Asia 2022  | -                                                            | -                                                            | -                |
| 2022 | [MemFace] [Memories are One-to-Many Mapping Alleviators in Talking Face Generation](https://arxiv.org/pdf/2212.05005.pdf) | arXiv 2022          | -                                                            | -                                                            | -                |
| 2021 | [PC-AVS] [PC-AVS: Pose-Controllable Talking Face Generation by Implicitly Modularized Audio-Visual Representation](https://arxiv.org/abs/2104.11116) | CVPR 2021           | [Code](https://github.com/Hangz-nju-cuhk/Talking-Face_PC-AVS) | [Project](https://hangz-nju-cuhk.github.io/projects/PC-AVS)  | -                |
| 2021 | [IATS] [Imitating Arbitrary Talking Style for Realistic Audio-Driven Talking Face Synthesis](https://arxiv.org/abs/2111.00203) | ACM MM 2021         | -                                                            | -                                                            | -                |
| 2021 | [Speech2Talking-Face] [Speech2Talking-Face: Inferring and Driving a Face with Synchronized Audio-Visual Representation](https://www.ijcai.org/proceedings/2021/0141.pdf) | IJCAI 2021          | -                                                            | -                                                            | -                |
| 2021 | [FAU] [Talking Head Generation with Audio and Speech Related Facial Action Units](https://arxiv.org/pdf/2110.09951.pdf) | arxiv 2021          | -                                                            | -                                                            | -                |
| 2021 | [EVP] [Audio-Driven Emotional Video Portraits](https://openaccess.thecvf.com/content/CVPR2021/papers/Ji_Audio-Driven_Emotional_Video_Portraits_CVPR_2021_paper.pdf) | CVPR 2021           | [Code](https://github.com/jixinya/EVP)                       | -                                                            | -                |
| 2021 | [IATS] [IATS: Imitating Arbitrary Talking Style for Realistic Audio-Driven Talking Face Synthesis](https://dl.acm.org/doi/pdf/10.1145/3474085.3475280) | ACM Multimedia 2021 | -                                                            | -                                                            | -                |
| 2020 | [Wav2Lip] [A Lip Sync Expert Is All You Need for Speech to Lip Generation In The Wild](http://arxiv.org/abs/2008.10010) | ACM Multimedia 2020 | [Code](https://github.com/Rudrabha/Wav2Lip)                  | [Project](http://cvit.iiit.ac.in/research/projects/cvit-projects/a-lip-sync-expert-is-all-you-need-for-speech-to-lip-generation-in-the-wild/) | -                |
| 2020 | [RhythmicHead] [Talking-head Generation with Rhythmic Head Motion](https://arxiv.org/pdf/2007.08547v1.pdf) | ECCV 2020           | [Code](https://github.com/lelechen63/Talking-head-Generation-with-Rhythmic-Head-Motion) | -                                                            | -                |
| 2020 | [MakeItTalk] [Speaker-Aware Talking-Head Animation](https://arxiv.org/abs/2006.09661) | SIGGRAPH Asia 2020  | [Code](https://github.com/yzhou359/MakeItTalk)               | [Project](https://people.umass.edu/~yangzhou/MakeItTalk/)    | -                |
| 2020 | [Neural Voice Puppetry] [Audio-driven Facial Reenactment](https://arxiv.org/abs/1912.05566) | ECCV 2020           | -                                                            | [Project](https://justusthies.github.io/posts/neural-voice-puppetry/) | -                |
| 2020 | [MEAD] [A Large-scale Audio-visual Dataset for Emotional Talking-face Generation](https://www.ecva.net/papers/eccv_2020/papers_ECCV/papers/123660698.pdf) | ECCV 2020           | [Code](https://github.com/uniBruce/Mead)                     | [Project](https://wywu.github.io/projects/MEAD/MEAD.html)    | -                |
| 2020 | [Realistic Speech-Driven Facial Animation with GANs](https://arxiv.org/pdf/1906.06337.pdf) | IJCV 2020           | -                                                            | -                                                            | -                |
| 2019 | [DAVS] [Talking Face Generation by Adversarially Disentangled Audio-Visual Representation](https://arxiv.org/abs/1807.07860) | AAAI 2019           | [Code](https://github.com/Hangz-nju-cuhk/Talking-Face-Generation-DAVS) | -                                                            | -                |
| 2019 | [ATVGnet] [Hierarchical Cross-modal Talking Face Generation with Dynamic Pixel-wise Loss](https://www.cs.rochester.edu/~cxu22/p/cvpr2019_facegen_paper.pdf) | CVPR 2019           | [Code](https://github.com/lelechen63/ATVGnet)                | -                                                            | -                |
| 2018 | [Lip Movements Generation at a Glance](https://openaccess.thecvf.com/content_ECCV_2018/papers/Lele_Chen_Lip_Movements_Generation_ECCV_2018_paper.pdf) | ECCV 2018           | [Code](https://github.com/lelechen63/3d_gan)                 | -                                                            | -                |
| 2018 | [VisemeNet] [Audio-Driven Animator-Centric Speech Animation](https://arxiv.org/abs/1805.09488) | SIGGRAPH 2018       | -                                                            | -                                                            | -                |
| 2017 | [Synthesizing Obama] [Learning Lip Sync From Audio](https://grail.cs.washington.edu/projects/AudioToObama/siggraph17_obama.pdf) | SIGGRAPH 2017       | -                                                            | [Project](https://grail.cs.washington.edu/projects/AudioToObama/) | -                |
| 2017 | [You Said That?] [Synthesising Talking Faces From Audio](https://arxiv.org/abs/1705.02966) | IJCV 2019           | [Code](https://github.com/joonson/yousaidthat)               | -                                                            | -                |
| 2017 | [Audio-Driven Facial Animation by Joint End-to-End Learning of Pose and Emotion](https://users.aalto.fi/~laines9/publications/karras2017siggraph_paper.pdf) | SIGGRAPH 2017       | -                                                            | -                                                            | -                |
| 2017 | [A Deep Learning Approach for Generalized Speech Animation](https://home.ttic.edu/~taehwan/taylor_etal_siggraph2017.pdf) | SIGGRAPH 2017       | -                                                            | -                                                            | -                |
| 2016 | [LRW] [Lip Reading in the Wild](https://www.robots.ox.ac.uk/~vgg/publications/2016/Chung16/chung16.pdf) | ACCV 2016           | -                                                            | -                                                            | -                |


---



## Text driven

| Year | Title                                                        | Conference/Journal | Code/Proj                                                   |
| ---- | ------------------------------------------------------------ | ------------------ | ----------------------------------------------------------- |
| 2023 | [TalkCLIP: Talking Head Generation with Text-Guided Expressive Speaking Styles](https://arxiv.org/pdf/2304.00334.pdf) | Arxiv              |                                                             |
| 2021 | [Write-a-speaker: Text-based Emotional and Rhythmic Talking-head Generation](https://arxiv.org/abs/2104.07995) | AAAI               | [Code](https://github.com/FuxiVirtualHuman/Write-a-Speaker) |
| 2021 | [Txt2vid: Ultra-low bitrate compression of talking-head videos via text](https://arxiv.org/abs/2106.14014v3) | Arxiv              | [Code](https://github.com/tpulkit/txt2vid)                  |

---



## NeRF & 3D

| Year | Title                                                        | Conference/Journal | Code                                                  | Project                                                    | Keywords   |
| ---- | ------------------------------------------------------------ | ------------------ | ----------------------------------------------------- | ---------------------------------------------------------- | ---------- |
| 2023 | [ER-NeRF] [Efficient Region-Aware Neural Radiance Fields for High-Fidelity Talking Portrait Synthesis](https://openaccess.thecvf.com/content/ICCV2023/papers/Li_Efficient_Region-Aware_Neural_Radiance_Fields_for_High-Fidelity_Talking_Portrait_Synthesis_ICCV_2023_paper.pdf) | ICCV 2023          | [Code](https://github.com/Fictionarry/ER-NeRF)        | [Project](https://fictionarry.github.io/ER-NeRF/)          | Tri-plane  |
| 2023 | [LipNeRF] [LipNeRF: What is the right feature space to lip-sync a NeRF?](https://www.amazon.science/publications/lipnerf-what-is-the-right-feature-space-to-lip-sync-a-nerf) | FG 2023            | Code                                                  | [Project](https://aggelinacha.github.io/LipNeRF/)          | Wav2lip    |
| 2023 | [GeneFace++] [Generalized and Stable Real-Time Audio-Driven 3D Talking Face Generation](https://arxiv.org/abs/2305.00787) | Arxiv 2023         | -                                                     | [Project](https://genefaceplusplus.github.io/)             | -          |
| 2023 | [GeneFace] [GeneFace: Generalized and High-Fidelity Audio-Driven 3D Talking Face Synthesis](https://arxiv.org/abs/2301.13430) | ICLR 2023          | [Code](https://github.com/yerfor/GeneFace)            | [Project](https://geneface.github.io/)                     | -          |
| 2022 | [RAD-NeRF] [RAD-NeRF: Real-time Neural Talking Portrait Synthesis](https://arxiv.org/pdf/2211.12368.pdf) | Arxiv 2022         | [Code](https://github.com/ashawkey/RAD-NeRF)          | [Project](https://ashawkey.github.io/radnerf/)             | InstantNGP |
| 2022 | [DialogueNeRF] [DialogueNeRF: Towards Realistic Avatar Face-to-face Conversation Video Generation](https://arxiv.org/pdf/2203.07931.pdf) | Arxiv 2022         | -                                                     | -                                                          | -          |
| 2022 | [NeRFInvertor] [NeRFInvertor: High Fidelity NeRF-GAN Inversion for Single-shot Real Image Animation](https://arxiv.org/pdf/2211.17235.pdf) | Arxiv 2022         | [Code](https://github.com/YuYin1/NeRFInvertor)        | [Project](https://yuyin1.github.io/NeRFInvertor_Homepage/) | -          |
| 2022 | [Next3D] [Next3D: Generative Neural Texture Rasterization for 3D-Aware Head Avatars](https://arxiv.org/pdf/2211.11208.pdf) | Arxiv 2022         | [Code](https://mrtornado24.github.io/Next3D/)         | [Project](https://mrtornado24.github.io/Next3D/)           | -          |
| 2022 | [3DFaceShop] [3DFaceShop: Explicitly Controllable 3D-Aware Portrait Generation](https://arxiv.org/pdf/2209.05434) | Arxiv 2022         | [Code](https://github.com/junshutang/3DFaceShop)      | [Project](https://junshutang.github.io/control/index.html) | -          |
| 2022 | [FNeVR] [FNeVR: Neural Volume Rendering for Face Animation](https://arxiv.org/abs/2209.10340) | Arxiv 2022         | [Code](https://github.com/zengbohan0217/FNeVR)        | -                                                          | -          |
| 2022 | [ROME] [ROME: Realistic One-shot Mesh-based Head Avatars](https://arxiv.org/pdf/2206.08343.pdf) | ECCV 2022          | [Code](https://github.com/SamsungLabs/rome)           | [Project](https://samsunglabs.github.io/rome/)             | -          |
| 2022 | [IMavatar] [IMavatar: Implicit Morphable Head Avatars from Videos](https://openaccess.thecvf.com/content/CVPR2022/papers/Zheng_I_M_Avatar_Implicit_Morphable_Head_Avatars_From_Videos_CVPR_2022_paper.pdf) | CVPR 2022          | [Code](https://ait.ethz.ch/projects/2022/IMavatar/)   | [Project](https://ait.ethz.ch/projects/2022/IMavatar/)     | -          |
| 2022 | [HeadNeRF] [HeadNeRF: A Real-time NeRF-based Parametric Head Model](https://openaccess.thecvf.com/content/CVPR2022/papers/Grassal_Neural_Head_Avatars_From_Monocular_RGB_Videos_CVPR_2022_paper.pdf) | CVPR 2022          | [Code](https://github.com/CrisHY1995/headnerf)        | [Project](https://hy1995.top/HeadNeRF-Project/)            | -          |
| 2022 | [SSP-NeRF] [Semantic-Aware Implicit Neural Audio-Driven Video Portrait Generation](https://arxiv.org/pdf/2201.07786.pdf) | Arxiv 2022         | [Code](https://github.com/alvinliu0/SSP-NeRF)         | [Project](https://alvinliu0.github.io/projects/SSP-NeRF)   | -          |
| 2021 | [AD-NeRF] [AD-NeRF: Audio Driven Neural Radiance Fields for Talking Head Synthesis](https://arxiv.org/abs/2103.11078) | ICCV 2021          | [Code](https://github.com/YudongGuo/AD-NeRF)          | [Project](https://yudongguo.github.io/ADNeRF/)             | -          |
| 2021 | [NerFACE] [NerFACE: Dynamic Neural Radiance Fields for Monocular 4D Facial Avatar Reconstruction](https://arxiv.org/pdf/2012.03065) | CVPR 2021 Oral     | [Code](https://github.com/gafniguy/4D-Facial-Avatars) | [Project](https://gafniguy.github.io/4D-Facial-Avatars/)   | -          |
| 2021 | [DFA-NeRF] [DFA-NeRF: Personalized Talking Head Generation via Disentangled Face Attributes Neural Rendering](https://arxiv.org/pdf/2201.00791v1.pdf) | Arxiv 2021         | [Code](https://github.com/ShunyuYao/DFA-NeRF)         | -                                                          | -          |

---



## Metrics

| Metrics                                             | Paper                                                        | Link                                                         |
| --------------------------------------------------- | ------------------------------------------------------------ | ------------------------------------------------------------ |
| PSNR (peak signal-to-noise ratio)                   | -                                                            |                                                              |
| SSIM (structural similarity index measure)          | Image quality assessment: from error visibility to structural similarity. |                                                              |
| CPBD(cumulative probability of blur detection)      | A no-reference image blur metric based on the cumulative probability of blur detection |                                                              |
| LPIPS (Learned Perceptual Image Patch Similarity) - | The Unreasonable Effectiveness of Deep Features as a Perceptual Metric | [paper](https://arxiv.org/pdf/1801.03924.pdf)                |
| NIQE (Natural Image Quality Evaluator)              | Making a ‘Completely Blind’ Image Quality Analyzer           | [paper](http://live.ece.utexas.edu/research/Quality/niqe_spl.pdf) |
| FID (Fréchet inception distance)                    | GANs trained by a two time-scale update rule converge to a local nash equilibrium |                                                              |
| LMD (landmark distance error)                       | Lip Movements Generation at a Glance                         |                                                              |
| LRA (lip-reading accuracy)                          | Talking Face Generation by Conditional Recurrent Adversarial Network | [paper](https://arxiv.org/pdf/1804.04786.pdf)                |
| WER(word error rate)                                | Lipnet: end-to-end sentencelevel lipreading.                 |                                                              |
| LSE-D (Lip Sync Error - Distance)                   | Out of time: automated lip sync in the wild                  |                                                              |
| LSE-C (Lip Sync Error - Confidence)                 | Out of time: automated lip sync in the wild                  |                                                              |
| ACD(Average content distance)                       | Facenet: a unified embedding for face recognition and clustering. |                                                              |
| CSIM(cosine similarity)                             | Arcface: additive angular margin loss for deep face recognition. |                                                              |
| EAR(eye aspect ratio)                               | Real-time eye blink detection using facial landmarks. In: Computer Vision Winter Workshop |                                                              |
| ESD(emotion similarity distance)                    | What comprises a good talking-head video generation?: A Survey and Benchmark |                                                              |

---





[1]: https://github.com/YunjinPark/awesome_talking_face_generation
[2]: https://github.com/LTT-O/Awesome-Talking-Head-Generation
[3]: https://github.com/JosephPai/Awesome-Talking-Face
[4]: https://github.com/weishida01/Awesome-Talking-Face-Generation
[5]: https://github.com/harlanhong/awesome-talking-head-generation
[6]:https://github.com/Curated-Awesome-Lists/awesome-ai-talking-heads
