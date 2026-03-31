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

          <h1><strong>欢迎来到上海交通大学智能媒体组 （MediaX@SJTU）</strong></h1>

          <p>
            <strong>MediaX</strong> 隶属于 <a href="https://cmic.sjtu.edu.cn/CN/Default.aspx">上海交通大学未来媒体网络协同创新中心</a>，
            专注于 <span class="highlight">计算机视觉</span>、<span class="highlight">机器学习</span> 与 <span class="highlight">生成式智能媒体</span> 交叉领域的前沿研究。
            我们致力于推动多模态媒体（2D/3D/4D）在生成、修复与增强、重建与压缩、以及质量评价等方向的发展。
            我们的使命是构建能够理解、建模和操控复杂人类中心视觉内容的智能系统，
            以实现高质量、高效率的下一代智能媒体内容生产。
          </p>

          <h2>🎯 研究方向</h2>
          <p>
            <strong>媒体感知与质量评价</strong><br/>
            构建面向UGC、PGC和AIGC内容的多维度智能质量评价体系。（<a href="https://arxiv.org/abs/2412.13155">F-Bench</a>、<a href="https://arxiv.org/pdf/2412.19238">FineVQ</a>等）
          </p>
          <p>
            <strong>视频修复与生成</strong><br/>
            高质量视频增强、可控生成与编辑，支持4K/8K分辨率。（<a href="https://arxiv.org/abs/2511.17138">ODTSR</a>、<a href="https://arxiv.org/abs/2509.25731">LaTo</a>、<a href="https://arxiv.org/abs/2306.00973">StoryGen</a>、<a href="https://arxiv.org/abs/2303.06885">Dr2</a>等）
          </p>
          <p>
            <strong>3D/4D重建与生成</strong><br/>
            基于3D高斯建模与生成式AI，实现沉浸式动态场景的高效表示与压缩。（<a href="https://arxiv.org/abs/2509.17513">4DGCPro</a>、<a href="https://arxiv.org/pdf/2503.18421">4DGC</a>、<a href="https://qianghu-huber.github.io/qianghuhomepage/paper/JSAC.pdf">VARFVV</a>等）
          </p>
          <p>
            <strong>智能媒体创作平台</strong><br/>
            构建协同、多智能体驱动的自动化与交互式媒体生产系统。(央视4K/8K超高清媒体智能增强制作平台、<a href="https://arxiv.org/abs/2510.08508">MoA-VR</a>、<a href="https://arxiv.org/abs/2601.02046">Agentic Retoucher</a>)
          </p>

          <h2>📢 加入我们</h2>
          <p>
            我们长期欢迎 <strong>博士研究生、硕士研究生、本科科研助理</strong> 加入团队。<br/>
            如果你对智能媒体与生成式AI充满热情，欢迎将 <strong>个人简历与成绩单</strong> 发送至：
            <em><span class="highlight">mediax@sjtu.edu.cn</span></em>
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
                    <div class="news-item">[2025/2]   Two papers are accepted to CVPR</div>
                    <div class="news-item">[2026/1]   One paper is accepted to ICLR</div>
                    <div class="news-item">[2025/12]   Cover Paper in IEEE JSTSP</div>
                    <div class="news-item">[2025/12]   IEEE VCIP Best Paper Award</div>
                    <div class="news-item">[2025/12]   Runner-up, SIGGRAPH Asia 2025 Volumetric Video Challenge (Compression Track)</div>
                    <div class="news-item">[2025/11]   One paper is accepted to TCSVT</div>
                    <div class="news-item">[2025/10]   One paper is accepted to TPAMI</div>
                    <div class="news-item">[2025/10]   One paper is accepted to JSTSP</div>
                    <div class="news-item">[2025/9]   First Prize, Intelligent Restoration and Enhancement Track, 4th Broadcast and Online Audio-Visual Artificial Intelligence Application Innovation Competition</div>
                    <div class="news-item">[2025/9]   Two papers are accepted to NeurIPS 2025</div>
                    <div class="news-item">[2025/9]   MediaX团队超高清AI修复技术助力抗战胜利80周年晚会</div>
                    <div class="news-item">[2025/8]   Second Place, ICCV 2025 MIPI Challenge – Detailed Image Quality Assessment</div>
                    <div class="news-item">[2025/7]   Second Place, ICCV 2025 VQualA Challenge – GenAI-Bench AIGC Video Quality Assessment</div>
                    <div class="news-item">[2025/7]   Two papers are accepted to ACM MM 2025</div>
                    <div class="news-item">[2025/6]   Two papers are accepted to ICCV 2025</div>
                    <div class="news-item">[2025/5]   One paper is accepted to ICML 2025</div>
                    <div class="news-item">[2025/3]   Two papers are accepted to ICME 2025</div>
                    <div class="news-item">[2025/2]   Two papers are accepted to CVPR 2025</div>
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

        <table class="paper-table">
          <tr>
            <!-- 左侧：图片单元格（固定宽度400px） -->
            <td>
              <div class="image-container"> <!-- 灰色边框+白色底色的方框 -->
                <img src="images/cvpr2026-2.png" alt="f-bench" class="paper-image">
              </div>
            </td>
            <!-- 右侧：论文信息单元格（自适应剩余宽度） -->
            <td>
              <h1 style="font-size: 27px; font-weight: bold; color: #2c3e50; margin-bottom: 15px; line-height: 1.3;">
                [CVPR'2026] Agentic Retoucher for Text-To-Image Generation
              </h1>
              <p style="font-size: 20px; color: #3498db; margin-bottom: 10px;">
                Shaocheng Shen, Jianfeng Liang, Chunlei Cai, Cong Geng, Huiyu Duan, Xiaoyun Zhang, Qiang Hu, Guangtao Zhai
              </p>
              <p style="font-size: 20px; color: #7f8c8d; margin-bottom: 20px;">
                IEEE/CVF Conference on Computer Vision and Pattern Recognition (CVPR), 2026.
              </p>
              <div>
                <a href="https://arxiv.org/abs/2601.02046" target="_blank" rel="noopener noreferrer" class="paper-link">[Paper]</a>
                <a href="https://github.com/MediaX-SJTU/Agentic-Retoucher" target="_blank" rel="noopener noreferrer" class="paper-link">[Code]</a>
              </div>
            </td>
          </tr>
        </table>

        <table class="paper-table">
          <tr>
            <!-- 左侧：图片单元格（固定宽度400px） -->
            <td>
              <div class="image-container"> <!-- 灰色边框+白色底色的方框 -->
                <img src="images/cvpr2026.png" alt="f-bench" class="paper-image">
              </div>
            </td>
            <!-- 右侧：论文信息单元格（自适应剩余宽度） -->
            <td>
              <h1 style="font-size: 27px; font-weight: bold; color: #2c3e50; margin-bottom: 15px; line-height: 1.3;">
                [CVPR'2026] One-Step Diffusion Transformer for Controllable Real-World Image Super-Resolution
              </h1>
              <p style="font-size: 20px; color: #3498db; margin-bottom: 10px;">
                Yushun Fang, Yuxiang Chen, Shibo Yin, Qiang Hu, Jiangchao Yao, Ya Zhang, Xiaoyun Zhang, Yanfeng Wang
              </p>
              <p style="font-size: 20px; color: #7f8c8d; margin-bottom: 20px;">
                IEEE/CVF Conference on Computer Vision and Pattern Recognition (CVPR), 2026.
              </p>
              <div>
                <a href="https://arxiv.org/abs/2511.17138" target="_blank" rel="noopener noreferrer" class="paper-link">[Paper]</a>
                <a href="https://github.com/MediaX-SJTU/ODTSR" target="_blank" rel="noopener noreferrer" class="paper-link">[Code]</a>
              </div>
            </td>
          </tr>
        </table>

        <table class="paper-table">
          <tr>
            <!-- 左侧：图片单元格（固定宽度400px） -->
            <td>
              <div class="image-container"> <!-- 灰色边框+白色底色的方框 -->
                <img src="images/iclr2026.png" alt="f-bench" class="paper-image">
              </div>
            </td>
            <!-- 右侧：论文信息单元格（自适应剩余宽度） -->
            <td>
              <h1 style="font-size: 27px; font-weight: bold; color: #2c3e50; margin-bottom: 15px; line-height: 1.3;">
                [ICLR'2026] LaTo: Landmark-tokenized Diffusion Transformer for Fine-grained Human Face Editing
              </h1>
              <p style="font-size: 20px; color: #3498db; margin-bottom: 10px;">
                Zhenghao Zhang, Ziying Zhang, Junchao Liao, Xiangyu Meng, Qiang Hu, Siyu Zhu, Xiaoyun Zhang, Long Qin, Weizhi Wang
              </p>
              <p style="font-size: 20px; color: #7f8c8d; margin-bottom: 20px;">
                International Conference on Learning Representations (ICLR), 2026.
              </p>
              <div>
                <a href="https://arxiv.org/abs/2509.25731" target="_blank" rel="noopener noreferrer" class="paper-link">[Paper]</a>
                <a href="https://github.com/MediaX-SJTU/landmark-tokenized-dit" target="_blank" rel="noopener noreferrer" class="paper-link">[Code]</a>
              </div>
            </td>
          </tr>
        </table>


        <table class="paper-table">
          <tr>
            <!-- 左侧：图片单元格（固定宽度400px） -->
            <td>
              <div class="image-container"> <!-- 灰色边框+白色底色的方框 -->
                <img src="images/vcip2025.png" alt="f-bench" class="paper-image">
              </div>
            </td>
            <!-- 右侧：论文信息单元格（自适应剩余宽度） -->
            <td>
              <h1 style="font-size: 27px; font-weight: bold; color: #2c3e50; margin-bottom: 15px; line-height: 1.3;">
                [VCIP'2025] AlignGS: Aligning Geometry and Semantics for Robust Indoor Reconstruction from Sparse Views (Best Paper Award).
              </h1>
              <p style="font-size: 20px; color: #3498db; margin-bottom: 10px;">
                Yijie Gao, Houqiang Zhong, Tianchi Zhu, Zhengxue Cheng, Qiang Hu, Li Song
              </p>
              <p style="font-size: 20px; color: #7f8c8d; margin-bottom: 20px;">
                IEEE Visual Communications and Image Processing (VCIP) 2025.
              </p>
              <div>
                <a href="https://arxiv.org/pdf/2510.07839" target="_blank" rel="noopener noreferrer" class="paper-link">[Paper]</a>
                <a href="https://github.com/MediaX-SJTU/AlignGS" target="_blank" rel="noopener noreferrer" class="paper-link">[Code]</a>
              </div>
            </td>
          </tr>
        </table>

        <table class="paper-table">
          <tr>
            <!-- 左侧：图片单元格（固定宽度400px） -->
            <td>
              <div class="image-container"> <!-- 灰色边框+白色底色的方框 -->
                <img src="images/moavr.png" alt="f-bench" class="paper-image">
              </div>
            </td>
            <!-- 右侧：论文信息单元格（自适应剩余宽度） -->
            <td>
              <h1 style="font-size: 27px; font-weight: bold; color: #2c3e50; margin-bottom: 15px; line-height: 1.3;">
                [JSTSP'2025] MoA-VR: A Mixture-of-Agents System Towards All-in-One Video Restoration
              </h1>
              <p style="font-size: 20px; color: #3498db; margin-bottom: 10px;">
                Lu Liu, Chunlei Cai, Shaocheng Shen, Jianfeng Liang, Weimin Ouyang, Tianxiao Ye, Jian Mao, Huiyu Duan, Jiangchao Yao, Xiaoyun Zhang, Qiang Hu, Guangtao Zhai
              </p>
              <p style="font-size: 20px; color: #7f8c8d; margin-bottom: 20px;">
                IEEE Journal of Selected Topics in Signal Processing (JSTSP), 2025.
              </p>
              <div>
                <a href="https://arxiv.org/abs/2510.08508" target="_blank" rel="noopener noreferrer" class="paper-link">[Paper]</a>
              </div>
            </td>
          </tr>
        </table>

        <table class="paper-table">
          <tr>
            <!-- 左侧：图片单元格（固定宽度400px） -->
            <td>
              <div class="image-container"> <!-- 灰色边框+白色底色的方框 -->
                <img src="images/4dgcpro.png" alt="f-bench" class="paper-image">
              </div>
            </td>
            <!-- 右侧：论文信息单元格（自适应剩余宽度） -->
            <td>
              <h1 style="font-size: 27px; font-weight: bold; color: #2c3e50; margin-bottom: 15px; line-height: 1.3;">
                [NeurIPS'2025] 4DGCPro: Efficient Hierarchical 4D Gaussian Compression for Progressive Volumetric Video Streaming
              </h1>
              <p style="font-size: 20px; color: #3498db; margin-bottom: 10px;">
                Zihan Zheng, Zhenlong Wu, Houqiang Zhong, Yuan Tian, Ning Cao, Lan Xu, Jiangchao Yao, Xiaoyun Zhang, Qiang Hu, Wenjun Zhang
              </p>
              <p style="font-size: 20px; color: #7f8c8d; margin-bottom: 20px;">
                The Thirty-Ninth Annual Conference on Neural Information Processing Systems (NeurIPS), 2025.
              </p>
              <div>
                <a href="https://arxiv.org/abs/2509.17513" target="_blank" rel="noopener noreferrer" class="paper-link">[Paper]</a>
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


        <!-- 表格布局：左右两栏 -->
        <table class="paper-table">
          <tr>
            <!-- 左侧：图片单元格（固定宽度400px） -->
            <td>
              <div class="image-container"> <!-- 灰色边框+白色底色的方框 -->
                <img src="images/finevq.png" alt="seriallora" class="paper-image">
              </div>
            </td>
            <!-- 右侧：论文信息单元格（自适应剩余宽度） -->
            <td>
              <h1 style="font-size: 27px; font-weight: bold; color: #2c3e50; margin-bottom: 15px; line-height: 1.3;">
                [CVPR'2025] FineVQ: Fine-Grained User Generated Content Video Quality Assessment
              </h1>
              <p style="font-size: 20px; color: #3498db; margin-bottom: 10px;">
                Huiyu Duan, Qiang Hu, Wang Jiarui, Liu Yang, Zitong Xu, Lu Liu, Xiongkuo Min, Chunlei Cai, Tianxiao Ye, Xiaoyun Zhang, Guangtao Zhai
              </p>
              <p style="font-size: 20px; color: #7f8c8d; margin-bottom: 20px;">
                IEEE Conference on Computer Vision and Pattern Recognition (CVPR), 2025.
              </p>
              <div>
                <a href="https://arxiv.org/pdf/2503.18421" target="_blank" rel="noopener noreferrer" class="paper-link">[Paper]</a>
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
                <img src="images/jsac.png" alt="TDBFR" class="paper-image">
              </div>
            </td>
            <!-- 右侧：论文信息单元格（自适应剩余宽度） -->
            <td>
              <h1 style="font-size: 27px; font-weight: bold; color: #2c3e50; margin-bottom: 15px; line-height: 1.3;">
                [JSAC'2025]VARFVV: View-Adaptive Real-Time Interactive Free-View Video Streaming with Edge Computing
              </h1>
              <p style="font-size: 20px; color: #3498db; margin-bottom: 10px;">
                Qiang Hu, Qihan He, Houqiang Zhong, GuoLu, Xiaoyun Zhang,Guangtao Zhai,Yanfeng Wang
              </p>
              <p style="font-size: 20px; color: #7f8c8d; margin-bottom: 20px;">
                IEEE Journal on Selected Areas in Communications (JSAC), 2025.
              </p>
              <div>
                <a href="https://qianghu-huber.github.io/qianghuhomepage/paper/JSAC.pdf" target="_blank" rel="noopener noreferrer" class="paper-link">[Paper]</a>
                <a href="https://waveviewer.github.io/" target="_blank" rel="noopener noreferrer" class="paper-link">[Code]</a>
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
                <img src="images/mm2024.png" alt="f-bench" class="paper-image">
              </div>
            </td>
            <!-- 右侧：论文信息单元格（自适应剩余宽度） -->
            <td>
              <h1 style="font-size: 27px; font-weight: bold; color: #2c3e50; margin-bottom: 15px; line-height: 1.3;">
                [MM'2024] HPC: Hierarchical Progressive Coding Framework for Volumetric Video
              </h1>
              <p style="font-size: 20px; color: #3498db; margin-bottom: 10px;">
                Zihan Zheng, Houqiang Zhong, Qiang Hu, Xiaoyun Zhang, Li Song, Ya Zhang, Yanfeng Wang
              </p>
              <p style="font-size: 20px; color: #7f8c8d; margin-bottom: 20px;">
                Proceedings of the ACM International Conference on Multimedia(MM), 2024.
              </p>
              <div>
                <a href="https://arxiv.org/abs/2407.09026" target="_blank" rel="noopener noreferrer" class="paper-link">[Paper]</a>
              </div>
            </td>
          </tr>
        </table>
        
        <table class="paper-table">
          <tr>
            <!-- 左侧：图片单元格（固定宽度400px） -->
            <td>
              <div class="image-container"> <!-- 灰色边框+白色底色的方框 -->
                <img src="images/storygen.png" alt="f-bench" class="paper-image">
              </div>
            </td>
            <!-- 右侧：论文信息单元格（自适应剩余宽度） -->
            <td>
              <h1 style="font-size: 27px; font-weight: bold; color: #2c3e50; margin-bottom: 15px; line-height: 1.3;">
                [CVPR'2024] Intelligent Grimm - Open-ended Visual Storytelling via Latent Diffusion Models
              </h1>
              <p style="font-size: 20px; color: #3498db; margin-bottom: 10px;">
                Chang Liu, Haoning Wu, Yujie Zhong, Xiaoyun Zhang, Yanfeng Wang, Weidi Xie
              </p>
              <p style="font-size: 20px; color: #7f8c8d; margin-bottom: 20px;">
                IEEE Conference on Computer Vision and Pattern Recognition (CVPR), 2024.
              </p>
              <div>
                <a href="https://arxiv.org/abs/2306.00973" target="_blank" rel="noopener noreferrer" class="paper-link">[Paper]</a>
                <a href="https://github.com/haoningwu3639/StoryGen" target="_blank" rel="noopener noreferrer" class="paper-link">[Code]</a>
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