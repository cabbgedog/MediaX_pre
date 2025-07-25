---
# Leave the homepage title empty to use the site title
title:
date: 2022-10-24
type: landing

sections:
  - block: contact
    content:

      text: |-

        <head>
          <meta charset="UTF-8" />
          <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
          <style>
            body {
              font-family: Arial, sans-serif;
              line-height: 1.4;
              margin: 0;
              padding: 40px;
              background-color: #ffffff;
              color: #333333;
            }
            h1, h2, h3 {
              color: #1a1a1a;
            }
            h1 {
              font-size: 38px;
              margin-bottom: 20px;
            }
            h2 {
              font-size: 27px;
              margin-top: 40px;
            }
            .highlight {
              color: #c0392b;
              font-weight: bold;
            }
          </style>
        </head>
        <body>

          <h1><strong>Welcome to MediaX@SJTU (上交智能媒体组)</strong></h1>

          <p>
            <strong>MediaX</strong> is a research group under the <a href="https://cmic.sjtu.edu.cn/CN/Default.aspx">Cooperative Medianet Innovation Center</a> at Shanghai Jiao Tong University, focusing on cutting-edge research at the intersection of <span class="highlight">computer vision</span>, <span class="highlight">machine learning</span>, and <span class="highlight">generative intelligent media</span>. We aim to advance the frontiers of multi-modal media (2D/3D/4D) across generation, restoration and enhancement, reconstruction and compression, and quality assessment. Our mission is to build intelligent systems capable of understanding, modeling, and manipulating complex human-centric visual content, enabling the high-quality and efficient creation of next-generation intelligent media.
          </p>

          <h2>🎯 Research Focus</h2>
          <p>
            <strong>Media Perception & Quality Assessment</strong><br/>
            Developing intelligent, multi-dimensional evaluation systems for UGC, PGC, and AIGC content.
          </p>
           <p>
            <strong>Video Restoration & Generation</strong><br/>
            Enhancing, controllably generating and editing 4K/8K video content.
          </p>
           <p>
            <strong>3D/4D Reconstruction & Generation</strong><br/>
            Leveraging 3DGS and GenAI for efficient representation and compression of immersive dynamic scenes.
          </p>
           <p>
            <strong>Intelligent Media Creation Platform</strong><br/>
            Building collaborative, multi-agent systems for automated and interactive media production.
          </p>

          <h2>📢 Join Us</h2>
          <p>
            We are always looking for <strong>self-motivated PhD students, Master's students, and undergraduate RA</strong> to join our team.<br/>
            If you're passionate about intelligent media and generative AI, please send your <strong>CV and transcript</strong> to: <em><span class="highlight">mediax@sjtu.edu.cn</span></em>
          </p>

          <a href="mailto:mediax@sjtu.edu.cn" target="_blank">
          <i class="fas fa-envelope"></i> 联系我们
          </a>


          <a href="https://github.com/MediaX-SJTU" target="_blank">
              <i class="fab fa-github"></i> GitHub
          </a>


          <a href="https://notes.sjtu.edu.cn/s/9NKUMusdX" target="_blank">
              <i class="fab fa-weixin"></i> 微信
          </a>
        </body>

    design:
        columns: '1'


  - block: contact
    content:

      text: |-

        <html lang="en">
        <head>
            <meta charset="UTF-8">
            <meta name="viewport" content="width=device-width, initial-scale=1.0">
            <title>News</title>
            <style>
                body {
                    margin: 0;
                    padding: 0;
                }
                .container {
                    display: flex;
                    justify-content: space-between;
                    align-items: flex-start;
                    padding: 20px;
                }
                .title {
                    flex: 0 0 auto;
                    margin-top: 0;
                }
                .news-list {
                    flex: 1 1 auto;
                    margin-left: 120px; /* 标题和新闻列表之间的间距 */
                    margin-top: 30px;
                }
                .news-item {
                    margin: 6px 0;
                }
            </style>
        </head>
        <body>
            <div class="container">
                <div class="title">
                    <h1>🔥 News: </h1>
                </div>
                <div class="news-list">
                    <div class="news-item">[2025/6]   Two paper is accepted to ICCV 2025</div>
                    <div class="news-item">[2025/5]   One paper is accepted to ICML 2025</div>
                    <div class="news-item">[2025/3]   Two paper is accepted to ICME 2025</div>
                    <div class="news-item">[2025/2]   Two paper is accepted to CVPR 2025</div>
                    <div class="news-item">[2025/2]   NTIRE 2025 XGC Quality Assessment Challenge Organizer</div>
                    <div class="news-item">[2025/1]   One paper is accepted to JSAC 2025</div>
                    <div class="news-item">[2024/12]  One paper is accepted to AAAI 2025</div>
                    <div class="news-item">[2024/7]   One paper is accepted to TCSVT 2024</div>
                    <div class="news-item">[2024/7]   One paper is accepted to ACM MM 2024</div>
                    <div class="news-item">[2024/6]   One paper is accepted to ICIP 2024</div>
                </div>
            </div>
        </body>
        </html>
      
    design:
        columns: '1'



  - block: contact
    content:
      title: Publications
      text: |-

        <style>
          body, html { margin: 0; padding: 0; }
          
          /* 表格布局：左右两栏，去除默认边框 */
          .paper-table { 
            border-collapse: collapse; 
            width: 100%; 
            margin: 30px 0; /* 表格上下间距 */
          }
          
          /* 单元格样式：左侧固定宽度，右侧自适应 */
          .paper-table td { 
            vertical-align: middle; /* 左右单元格垂直居中对齐 */
            padding: 0 40px 0 0; /* 左侧单元格右间距（与右侧文字的距离） */
          }
          
          /* 左侧图片容器（灰色边框+白色底色方框） */
          .image-container {
            width: 400px; /* 固定宽度（核心需求） */
            height: 280px;
            max-width: 100%; /* 响应式：不超过父容器宽度 */
            border: 1px solid #e0e0e0; /* 灰色边框 */
            background-color: #ffffff; /* 白色底色 */
            border-radius: 8px; /* 圆角（可选，提升美观度） */
            padding: 15px; /* 图片与边框的内边距（可选） */
            box-sizing: border-box; /* 确保padding不增加容器宽度 */
            display: flex; /* Flex布局：图片居中 */
            justify-content: center; /* 水平居中 */
            align-items: center; /* 垂直居中 */
            margin-top: 30px
          }
          
          /* 图片样式：等比例缩放，不超出容器 */
          .paper-image {
            max-width: 100%; /* 不超过容器宽度 */
            max-height: 100%; /* 不超过容器高度 */
            width: auto; /* 保持比例 */
            height: auto; /* 保持比例 */
            display: block; /* 去除图片底部间隙 */
          }
          
          /* 链接样式（保持原风格） */
          .paper-link { 
            color: #3498db; 
            text-decoration: none; 
            margin-right: 20px; 
            font-size: 0.95em; 
          }
          .paper-link:hover { text-decoration: underline; }
          
          .bottom-link { 
            color: #3498db; 
            text-decoration: underline; 
            font-size: 25px; 
            display: block; 
            margin-top: 10px; 
          }
        </style>

        <!-- 表格布局：左右两栏 -->
        <table class="paper-table">
          <tr>
            <!-- 左侧：图片单元格（固定宽度400px） -->
            <td>
              <div class="image-container"> <!-- 灰色边框+白色底色的方框 -->
                <img src="images/f-bench.png" alt="f-bench" class="paper-image">
              </div>
            </td>
            <!-- 右侧：论文信息单元格（自适应剩余宽度） -->
            <td>
              <h1 style="font-size: 27px; font-weight: bold; color: #2c3e50; margin-bottom: 15px; line-height: 1.3;">
                [ICCV'2025] F-Bench: Rethinking Human Preference Evaluation Metrics for Benchmarking Face Generation, Customization, and Restoration
              </h1>
              <p style="font-size: 20px; color: #3498db; margin-bottom: 10px;">
                Lu Liu, Huiyu Duan, Qiang Hu, Liu Yang, Chunlei Cai, Tianxiao Ye, Huayu Liu, Xiaoyun Zhang, Guangtao Zhai
              </p>
              <p style="font-size: 20px; color: #7f8c8d; margin-bottom: 20px;">
                IEEE/CVF International Conference on Computer Vision (ICCV), 2025.
              </p>
              <div>
                <a href="https://arxiv.org/abs/2412.13155" target="_blank" rel="noopener noreferrer" class="paper-link">[Paper]</a>
              </div>
            </td>
          </tr>
        </table>

        <!-- 表格布局：左右两栏 -->
        <table class="paper-table">
          <tr>
            <!-- 左侧：图片单元格（固定宽度400px） -->
            <td>
              <div class="image-container"> <!-- 灰色边框+白色底色的方框 -->
                <img src="images/seriallora.png" alt="seriallora" class="paper-image">
              </div>
            </td>
            <!-- 右侧：论文信息单元格（自适应剩余宽度） -->
            <td>
              <h1 style="font-size: 27px; font-weight: bold; color: #2c3e50; margin-bottom: 15px; line-height: 1.3;">
                [ICME'2025] Serial Low-rank Adaptation of Vision Transformer
              </h1>
              <p style="font-size: 20px; color: #3498db; margin-bottom: 10px;">
                Houqiang Zhong, Shaocheng Shen, Ke Cai, Zhenglong Wu, Jiangchao Yao, Yuan Cheng, Xuefei Li, Xiaoyun Zhang, Li Song, Qiang Hu
              </p>
              <p style="font-size: 20px; color: #7f8c8d; margin-bottom: 20px;">
                IEEE International Conference on Multimedia and Expo (ICME), 2025.
              </p>
              <div>
                <a href="https://arxiv.org/pdf/2503.17750" target="_blank" rel="noopener noreferrer" class="paper-link">[Paper]</a>
              </div>
            </td>
          </tr>
        </table>

        <table class="paper-table">
          <tr>
            <!-- 左侧：图片单元格（固定宽度400px） -->
            <td>
              <div class="image-container"> <!-- 灰色边框+白色底色的方框 -->
                <img src="images/TDBFR.png" alt="TDBFR" class="paper-image">
              </div>
            </td>
            <!-- 右侧：论文信息单元格（自适应剩余宽度） -->
            <td>
              <h1 style="font-size: 27px; font-weight: bold; color: #2c3e50; margin-bottom: 15px; line-height: 1.3;">
                [ICME'2025]TD-BFR: Truncated Diffusion Model for Efficient Blind Face Restoration
              </h1>
              <p style="font-size: 20px; color: #3498db; margin-bottom: 10px;">
                Ziying Zhang, Xiang Gao, Zhixin Wang, Qiang Hu, Xiaoyun Zhang
              </p>
              <p style="font-size: 20px; color: #7f8c8d; margin-bottom: 20px;">
                IEEE International Conference on Multimedia and Expo (ICME), 2025.
              </p>
              <div>
                <a href="https://arxiv.org/pdf/2503.20537" target="_blank" rel="noopener noreferrer" class="paper-link">[Paper]</a>
              </div>
            </td>
          </tr>
        </table>
        

        <table class="paper-table">
          <tr>
            <!-- 左侧：图片单元格（固定宽度400px） -->
            <td>
              <div class="image-container"> <!-- 灰色边框+白色底色的方框 -->
                <img src="images/4dgc.png" alt="seriallora" class="paper-image">
              </div>
            </td>
            <!-- 右侧：论文信息单元格（自适应剩余宽度） -->
            <td>
              <h1 style="font-size: 27px; font-weight: bold; color: #2c3e50; margin-bottom: 15px; line-height: 1.3;">
                [CVPR'2025]4DGC: Rate-Aware 4D Gaussian Compression for Efficient Streamable Free-Viewpoint Video
              </h1>
              <p style="font-size: 20px; color: #3498db; margin-bottom: 10px;">
                Qiang Hu, Zihan Zheng, Houqiang Zhong, Sihua Fu, Li Song, Xiaoyun Zhang, Guangtao Zhai, Yanfeng Wang.
              </p>
              <p style="font-size: 20px; color: #7f8c8d; margin-bottom: 20px;">
                IEEE/CVF Conference on Computer Vision and Pattern Recognition (CVPR), 2025.
              </p>
              <div>
                <a href="https://arxiv.org/pdf/2412.19238" target="_blank" rel="noopener noreferrer" class="paper-link">[Paper]</a>
                <a href="https://github.com/qianghu-huber/4DGC" target="_blank" rel="noopener noreferrer" class="paper-link">[Code]</a>
              </div>
            </td>
          </tr>
        </table>

        <table class="paper-table">
          <tr>
            <!-- 左侧：图片单元格（固定宽度400px） -->
            <td>
              <div class="image-container"> <!-- 灰色边框+白色底色的方框 -->
                <img src="images/aaai2025.png" alt="f-bench" class="paper-image">
              </div>
            </td>
            <!-- 右侧：论文信息单元格（自适应剩余宽度） -->
            <td>
              <h1 style="font-size: 27px; font-weight: bold; color: #2c3e50; margin-bottom: 15px; line-height: 1.3;">
                [AAAI'2025] VRVVC: Variable-Rate NeRF-Based Volumetric Video Compression
              </h1>
              <p style="font-size: 20px; color: #3498db; margin-bottom: 10px;">
                Qiang Hu,Houqiang Zhong,Zihan Zheng,Xiaoyun Zhang,Zhengxue Cheng,Li Song,Guangtao Zhai,Yanfeng Wang
              </p>
              <p style="font-size: 20px; color: #7f8c8d; margin-bottom: 20px;">
                The Association for the Advancement of Artificial Intelligence (AAAI), 2025.
              </p>
              <div>
                <a href="https://qianghu-huber.github.io/qianghuhomepage/paper/AAAI_VRVVC_CameraReady.pdf" target="_blank" rel="noopener noreferrer" class="paper-link">[Paper]</a>
              </div>
            </td>
          </tr>
        </table>

        <table class="paper-table">
          <tr>
            <!-- 左侧：图片单元格（固定宽度400px） -->
            <td>
              <div class="image-container"> <!-- 灰色边框+白色底色的方框 -->
                <img src="images/wacv2025.png" alt="f-bench" class="paper-image">
              </div>
            </td>
            <!-- 右侧：论文信息单元格（自适应剩余宽度） -->
            <td>
              <h1 style="font-size: 27px; font-weight: bold; color: #2c3e50; margin-bottom: 15px; line-height: 1.3;">
                [WACV'2025] MegaFusion: Extend Diffusion Models towards Higher-resolution Image Generation without Further Tuning
              </h1>
              <p style="font-size: 20px; color: #3498db; margin-bottom: 10px;">
                Haoning Wu, Shaocheng Shen, Qiang Hu, Xiaoyun Zhang, Ya Zhang, Yanfeng Wang
              </p>
              <p style="font-size: 20px; color: #7f8c8d; margin-bottom: 20px;">
                Winter Conference on Applications of Computer Vision (WACV), 2025.
              </p>
              <div>
                <a href="https://arxiv.org/abs/2408.11001" target="_blank" rel="noopener noreferrer" class="paper-link">[Paper]</a>
              </div>
            </td>
          </tr>
        </table>
        
        
        <a href="https://cabbgedog.github.io/MediaX_pre/publication/" class="bottom-link" target="_blank" rel="noopener noreferrer">More on publication page</a>
    design:
        columns: '1'

        

  - block: markdown
    content:
      title:
      subtitle:
      text: |
        {{% cta cta_link="./people/" cta_text="Meet the team →" %}}
    design:
      columns: '1'
---