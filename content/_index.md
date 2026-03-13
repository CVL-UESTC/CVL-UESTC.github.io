---
# Leave the homepage title empty to use the site title
title: ''
date: 2022-10-24
type: landing

design:
  # Default section spacing
  spacing: '6rem'

sections:
  - block: markdown
    content:
      text: |-
        <style>
          .research-grid {
            display: grid;
            grid-template-columns: repeat(3, 350px);
            gap: 2rem;
            margin-top: 0rem;
            justify-content: center;
            # max-width: 1200px;
          }
          .research-card {
            text-align: center;
            padding: 1.5rem;
            background: #fff;
            border-radius: 10px;
            transition: transform 0.3s ease;
          }
          .research-card:hover {
            transform: translateY(-5px);
            box-shadow: 0 10px 25px rgba(0,0,0,0.1);
          }
          .research-icon {
            font-size: 2.5rem;
            margin-bottom: 1rem;
          }

          .news-list {
            # width: 100%; 
            max-width: 100%;
            display: flex;
            flex-direction: column;
            gap: 8px; /* 卡片之间的间距 */
          }

          .news-card {
              display: flex;
              text-align: center;
              padding: 1.5rem;
              background: #fff;
              transition: transform 0.3s ease;
              border: 1px solid #e2e8f0; /* 浅灰色边框 */
              border-radius: 8px; /* 圆角设计 */
              box-shadow: 0 2px 4px rgba(0, 0, 0, 0.02); /* 极轻微的阴影 */
              transition: transform 0.2s ease, box-shadow 0.2s ease;
          }


          .news-card:hover {
              background-color: #f9fafb; /* 悬停时淡淡的灰色反馈，非常高级 */
              border-color: #cbd5e0;     /* 边框稍微加深 */
              transform: translateY(-2px); /* 轻微上浮感 */
          }
          .news-title {
            margin-top: 10rem;
            text-align: center;
            padding: 1.5rem;
            border-radius: 10px;
          }

          /* 时间戳样式 */
          .news-date {
              font-weight: 600;       /* 加粗时间 */
              color: #4a5568;         /* 深灰色 */
              min-width: 20px;        /* 关键：给时间设置固定最小宽度，确保后面内容对齐 */
              # flex-shrink: 0;         /* 防止时间部分被压缩 */
              margin-right: 160px;     /* 时间与内容之间的间距 */
          }

          /* 消息内容样式 */
          .news-content {
              font-weight: 600;
              # flex-grow: 1;           /* 占据剩余的所有宽度 */
              color: #4a5568;
              line-height: 1.5;
              margin-right: 7px
          }

          .news-conference {
              font-weight: 600;
              color: #2d3748;  
              # flex-grow: 1;           /* 占据剩余的所有宽度 */
              # color: #4a5568;
              line-height: 1.5;
          }
          a {
              text-decoration: none; /* 彻底去掉下划线 */
              color: inherit;        /* 强制字体颜色继承自父元素，不变成蓝色 */
              display: block;        /* 让 a 标签像容器一样占据整行宽度 */
          }

          .connect-grid {
            display: grid;
            grid-template-columns: repeat(2, 250px);
            gap: 10rem;
            margin-top: 10rem;
            justify-content: center;
            # height: 400px;
            # max-width: 1200px;
          }
          .connect-card {
            text-align: center;
            padding: 1.5rem;
            background: #fff;
            border-radius: 10px;
            transition: transform 0.3s ease;
          }
          .connect-card:hover {
            transform: translateY(-5px);
            box-shadow: 0 10px 25px rgba(0,0,0,0.1);
          }


        </style>



        <div style="text-align: center; margin-bottom: 6rem;">
          <div style="display: flex; justify-content: center; margin-bottom: 2rem;">
            <img src="/images/logo3.png" alt="Research" style="max-width: 750px; border-radius: 10px; margin-left: -0px;">
          </div>
          <h1 style="margin: 0.5rem 0; color: #2c3e50;">Computer Vision Lab</h1>
          <h1 style="margin: 0.5rem 0; color: #2c3e50;">UESTC</h1>
        </div>

        <div class="research-grid">
          <!-- 图像复原 -->
          <a href="tags/visual-restoration/">
            <div class="research-card">
              <div class="research-icon">🔄</div>
              <h4>Visual Restoration</h4>
              <p style="color: #666; line-height: 1.6;">
                Visual Restoration technology focuses on recovering and enhancing the quality of degraded visual media.
              </p>
            </div>
          </a>
          <!-- 图像压缩 -->
          <a href="tags/visual-compression/">
            <div class="research-card">
              <div class="research-icon">📦</div>
              <h4>Visual Compression</h4>
              <p style="color: #666; line-height: 1.6;">
                Visual Compression technology reduces the storage and bandwidth requirements while preserving visual quality.
              </p>
            </div>
          </a>
          <!-- 图像生成 -->
          <a href="tags/visual-generation/">
            <div class="research-card">
              <div class="research-icon">🎨</div>
              <h4>Visual Generation</h4>
              <p style="color: #666; line-height: 1.6;">
                Visual Generation​ is a field of artificial intelligence focused on creating new visual content from scratch.
              </p>
            </div>
          </a>
        </div>

        <h1 class="news-title">NEWS</h1>
        <div class="news-list">
          <a href="tags/cvpr-2026/">
            <div class="news-card">
              <span class="news-date">2026.03</span>
              <span class="news-content">5 papers were accepted to </span>
              <span class="news-conference"> CVPR 2026</span>
            </div>
          </a>
          <a href="tags/iclr-2026/">
            <div class="news-card">
              <span class="news-date">2026.01</span>
              <span class="news-content">2 papers were accepted to </span>
              <span class="news-conference"> ICLR 2026</span>
            </div>
          </a>
          <a href="tags/iccv-2025/">
            <div class="news-card">
              <span class="news-date">2025.06</span>
              <span class="news-content">3 papers were accepted to  </span>
              <span class="news-conference"> ICCV 2025</span>
            </div>
          </a>
          <a href="tags/icml-2025/">
            <div class="news-card">
              <span class="news-date">2025.04</span>
              <span class="news-content">1 paper was accepted to  </span>
              <span class="news-conference"> ICML 2025</span>
            </div>
          </a>
          <a href="tags/cvpr-2025/">
            <div class="news-card">
              <span class="news-date">2025.03</span>
              <span class="news-content">3 papers were accepted to  </span>
              <span class="news-conference"> CVPR 2025</span>
            </div>
          </a>
          <a href="tags/neurips-2024/">
            <div class="news-card">
              <span class="news-date">2024.09</span>
              <span class="news-content">1 paper was accepted to </span>
              <span class="news-conference"> NeurIPS 2024</span>
            </div>
          </a>
          <a href="tags/cvpr-2024/">
            <div class="news-card">
              <span class="news-date">2024.03</span>
              <span class="news-content">3 papers were accepted to  </span>
              <span class="news-conference"> CVPR 2024</span>
            </div>
          </a>
        </div>



        <div class="connect-grid">

          <a href="https://github.com/CVL-UESTC">
            <div class="connect-card">
              <img src="/images/github.png" alt="Research" style="max-width: 200px; border-radius: 10px; margin-left: -0px;">
              <h4> Github </h4>
            </div>

          </a>

          <a href="https://huggingface.co/CVLUESTC">
            <div class="connect-card">
              <img src="/images/hugging_face.jpeg" alt="Research" style="max-width: 200px; border-radius: 10px; margin-left: -0px;">
              <h4> Hagging Face </h4>
            </div>
          </a>
        </div>

    design:
      css_class: hbx-bg-gradient

          # .news-card:hover {
          #     transform: translateY(-2px);
          #     box-shadow: 0 4px 12px rgba(0, 0, 0, 0.05);
          #     border-color: #cbd5e0;
          # }
  # - block: markdown
  #   content:
  #     text: |-
  #       <style>
  #         .container {
            
  #           # max-width: 1400px;
  #           margin: 0 auto;
  #           width: 100%;
  #         }
  #         .news-title {
  #           text-align: center;
  #           padding: 1.5rem;
  #           border-radius: 10px;
  #         }
  #         .news-list {
  #           # width: 100%; 
  #           # max-width: 100%;
  #           # display: flex;
  #           # flex-direction: column;
  #           gap: 16px; /* 卡片之间的间距 */
  #         }

  #         /* 4. 单个新闻卡片样式 */
  #         .news-card {
  #             text-align: center;
  #             padding: 1.5rem;
  #             background: #fff;
  #             transition: transform 0.3s ease;
  #             border: 1px solid #e2e8f0; /* 浅灰色边框 */
  #             border-radius: 8px; /* 圆角设计 */
  #             box-shadow: 0 2px 4px rgba(0, 0, 0, 0.02); /* 极轻微的阴影 */
  #             transition: transform 0.2s ease, box-shadow 0.2s ease;
  #         }

  #         /* 鼠标悬停交互效果 */
  #         .news-card:hover {
  #             transform: translateY(-2px);
  #             box-shadow: 0 4px 12px rgba(0, 0, 0, 0.05);
  #             border-color: #cbd5e0;
  #         }

  #         /* 5. 卡片内部文字排版 */
  #         .year {
  #             font-weight: 400;
  #             color: #2d3748;
  #             min-width: 50px;
  #         }

  #         .divider {
  #             margin: 0 15px;
  #             color: #cbd5e0;
  #             font-weight: 300;
  #         }

  #         .paper-title {
  #             font-weight: 700;
  #             color: #000;
  #             flex-grow: 1; /* 让标题占据主要空间 */
  #         }

  #         .authors {
  #             color: #4a5568;
  #             margin-left: 10px;
  #         }

  #         .journal {
  #             color: #a0aec0; /* 对应图中较浅的灰色 */
  #             margin-left: 10px;
  #             font-style: normal;
  #         }
  #       </style>


  #       <div class="container">
  #         <h2 class="news-title">NEWS</h2>
            
  #         <div class="news-list">
  #           <div class="news-card">
  #                 实验室有5篇论文被CVPR2026接收接收接收接收接收接收接收接收接收a
  #           </div>
  #         </div>
  #       </div>


  # - block: markdown
  #   content:
  #     text: |-
  #       <div style="margin-top: 8rem; margin-bottom: 4rem;">
  #         <h1 style="text-align: center; margin-bottom: 3rem; color: #2c3e50; border-bottom: 2px solid #e0e0e0; padding-bottom: 1rem;"> NEWS</h1>
  #         <h4>2026.03.01 实验室5篇论文被CVPR2026录用</h2>
  #       </div>
  #   design:
  #     css_class: hbx-bg-gradient


  # - block: markdown
  #   content:
  #     text: |
  #       # NEWS

  #       实验室5篇论文被CVPR2026录用

  #   design:
  #     css_class: hbx-bg-gradient
  #     columns: "1"
  #     spacing:
  #       padding: ["20px", "20px", "20px", "20px"]

  # - block: markdown
  #   content:
  #     text: |-
  #       <div style="margin-top: 8rem; margin-bottom: 4rem;">
  #         <h1 style="text-align: center; margin-bottom: 3rem; color: #2c3e50; border-bottom: 2px solid #e0e0e0; padding-bottom: 1rem;"> NEWS</h1>
  #         <h4>2026.03.01 实验室5篇论文被CVPR2026录用</h2>
  #       </div>
  #   design:
  #     css_class: hbx-bg-gradient

        # <div style="text-align: center; margin-bottom: 6rem;">
        #   <div style="display: flex; justify-content: center; margin-bottom: 2rem;">
        #     <img src="/images/logo3.png" alt="Research" style="max-width: 1500px; border-radius: 10px; margin-left: -0px;">
        #   </div>
        #   <h1 style="margin: 0.5rem 0; color: #2c3e50;">Computer Vision Lab</h1>
        # </div>

  # - block: markdown
  #   content:
  #     # title: '📚 My Research'
  #     # subtitle: ''
  #     text: |-
  #       <div style="text-align: center; margin-bottom: 2rem;">
  #         <div style="display: flex; justify-content: center; margin-bottom: 1rem;">
  #           <img src="/images/logo2.png" alt="Research" style="max-width: 2000px; border-radius: 10px;">
  #         </div>
  #         <h3 style="margin: 0.5rem 0; color: #2c3e50;">Computer Vision Lab </h3>
  #       </div>
  #   design:
  #     # columns: '1'
  #     css_class: hbx-bg-gradient
  # - block: resume-biography-3
  #   content:
  #     # Choose a user profile to display (a folder name within `content/authors/`)
  #     username: lab
  #     text: ''
  #     # Show a call-to-action button under your biography? (optional)
  #     # button:
  #     #   text: Download CV
  #     #   url: uploads/resume.pdf
  #     headings:
  #       about: ''
  #       education: ''
  #       interests: ''
  #   design:
  #     # Apply a gradient background
  #     css_class: hbx-bg-gradient
  #     # Avatar customization
  #     avatar:
  #       size: medium # Options: small (150px), medium (200px, default), large (320px), xl (400px), xxl (500px)
  #       shape: circle # Options: circle (default), square, rounded


# - block: markdown
#     content:
#       title: '📚 My Research'
#       subtitle: ''
#       text: |-
#         Use this area to speak to your mission. I'm a research scientist in the Moonshot team at DeepMind. I blog about machine learning, deep learning, and moonshots.

#         I apply a range of qualitative and quantitative methods to comprehensively investigate the role of science and technology in the economy.

#         Please reach out to collaborate 😃
#     design:
#       columns: '1'
#   - block: collection
#     id: papers
#     content:
#       title: Featured Publications
#       filters:
#         folders:
#           - publications
#         featured_only: false
#     design:
#       view: article-grid
#       columns: 2
#   - block: collection
#     content:
#       title: Recent Publications
#       text: ''
#       filters:
#         folders:
#           - publications
#         exclude_featured: false
#     design:
#       view: citation
#   - block: collection
#     id: talks
#     content:
#       title: Recent & Upcoming Talks
#       filters:
#         folders:
#           - events
#     design:
#       view: card
#   - block: collection
#     id: news
#     content:
#       title: Recent News
#       subtitle: ''
#       text: ''
#       # Page type to display. E.g. post, talk, publication...
#       page_type: blog
#       # Choose how many pages you would like to display (0 = all pages)
#       count: 5
#       # Filter on criteria
#       filters:
#         author: ''
#         category: ''
#         tag: ''
#         exclude_featured: false
#         exclude_future: false
#         exclude_past: false
#         publication_type: ''
#       # Choose how many pages you would like to offset by
#       offset: 0
#       # Page order: descending (desc) or ascending (asc) date.
#       order: desc
#     design:
#       # Choose a layout view
#       view: card
#       # Reduce spacing
#       spacing:
#         padding: [0, 0, 0, 0]
#   - block: cta-card
#     demo: true # Only display this section in the Hugo Blox Builder demo site
#     content:
#       title: 👉 Build your own academic website like this
#       text: |-
#         This site is generated by Hugo Blox Builder - the FREE, Hugo-based open source website builder trusted by 250,000+ academics like you.

#         <a class="github-button" href="https://github.com/HugoBlox/hugo-blox-builder" data-color-scheme="no-preference: light; light: light; dark: dark;" data-icon="octicon-star" data-size="large" data-show-count="true" aria-label="Star HugoBlox/hugo-blox-builder on GitHub">Star</a>

#         Easily build anything with blocks - no-code required!

#         From landing pages, second brains, and courses to academic resumés, conferences, and tech blogs.
#       button:
#         text: Get Started
#         url: https://hugoblox.com/templates/
#     design:
#       card:
#         # Card background color (CSS class)
#         css_class: 'bg-primary-300 dark:bg-primary-700'
#         css_style: ''
---
