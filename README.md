# Paper-Diffusion-T2M
个人看的Diffusion model 和 T2M论文的分类


目录 difussion and  text2motiondiffusion理论应用GANtoVedioText2MotionMusic2Dance



diffusion

理论

DDPM (NeurIPS-20) Denoising Diffusion Probabilistic Models

DDIM(NeurIPS-21)：Improved Denoising Diffusion Probabilistic Models

参考视频: 54、Diffusion Model扩散模型理论与完整PyTorch代码详细解读

应用

Stochastic Trajectory Prediction via Motion Indeterminacy Diffusion(CVPR202):通过diffusion model预测trajectory [code] [paper]

Vector Quantized Diffusion Model for Text-to-Image Synthesis(CVPR2022) :为了解决diffusion速度慢，需要上千次的迭代才能生成最终的结果。提出了改进方案：通过 VQVAE 降低 inference 的图像尺寸 [github] [paper]  [video]

GANtoVedio

Diffusion Models for Video Prediction and Infilling  [paper]

MCVD: Masked Conditional Video Diffusion for Prediction, Generation, and Interpolation  以前或者后视频帧作为条件去预测所需要的视频帧 [code] [paper]

Text2Motion

Generating Diverse and Natural 3D Human Motions from Text  (CVPR2022) [code] [paper]

TM2T: Stochastic and Tokenized Modeling for the Reciprocal Generation of 3D Human Motions and Texts (ECCV2022)  [code] [paper]

Diverse Dance Synthesis via Keyframes with Transformer Controllers    [paper]

TEMOS: Generating diverse human motions from textual descriptionsECCV 2022 (Oral)           [Code] [Paper]      

Music2Dance

A Brand New Dance Partner: Music-Conditioned Pluralistic Dancing Controlled by Multiple Dance Genres(CVPR2022)  [code] [paper]

Bailando: 3D Dance Generation by Actor-Critic GPT with Choreographic Memory (CVPR2022) [code] [paper]  [vedio]
