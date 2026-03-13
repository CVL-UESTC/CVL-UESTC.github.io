---
title: ''
date: 2022-10-24
type: landing


# View.
view: citation

# # Optional header image (relative to `static/media/` folder).
banner:
  caption: ''
  image: ''

design:
  spacing: "6rem"
# design:
  # Default section spacing
  # spacing: '6rem'


sections:
  # - block: hero
  #   content:
  #     title: Build Your Landing Pages with Hugo Blox
  #     text: 🧱 EASY. FREE (OPEN SOURCE). NO-CODE  🧱
  #     primary_action:
  #       text: Get Started
  #       url: https://hugoblox.com/templates/
  #       icon: rocket-launch
  #     secondary_action:
  #       text: Read the docs
  #       url: https://docs.hugoblox.com
  #     announcement:
  #       text: "Announcing the release of version 1."
  #       link:
  #         text: "Read more"
  #         url: "/blog/"
  #   design:
  #   #   spacing:
  #   #     padding: [0, 0, 0, 0]
  #   #     margin: [0, 0, 0, 0]
  #     # For full-screen, add `min-h-screen` below
  #     css_class: "dark"
  #     background:
  #       color: "navy"
  #       image:
  #         # Add your image background to `assets/media/`.
  #         filename: bg-triangles.svg
  #         filters:
  #           brightness: 0.5
  #         size: cover
  #         position: center
  #         parallax: false
  # - block: stats
  #   content:
  #     items:
  #       - statistic: "1M+"
  #         description: |
  #           Websites built  
  #           with Hugo Blox
  #       - statistic: "10k+"
  #         description: |
  #           GitHub stars  
  #           since 2016
  #       - statistic: "3k+"
  #         description: |
  #           Discord community  
  #           for support
  #   design:
  #     # Section background color (CSS class)
  #     css_class: "bg-gray-100 dark:bg-gray-900"
  #     # Reduce spacing
  #     spacing:
  #       padding: ["1rem", 0, "1rem", 0]

  - block: markdown
    content:
      title: Faculty
      text: |
        
        <style>
          .team-grid-faculty {
            display: grid;
            grid-template-columns: repeat(1, 250px); /* 固定列宽 */
            justify-content: center; /* 关键：网格居中 */
            gap: 55px;
            padding: 0 0;
          }
          .team-member {
            display: flex;
            flex-direction: column;
            align-items: center;
            text-align: center;
          }
          .team-photo {
            width: 250px; /* 图片填充列宽 */
            height: auto;
            object-fit: cover;
          }
        </style>
        <div class="team-grid-faculty">
          <div class="text-center">
            <img src="/images/gushuhang.jpg" class="team-photo">
            <div class="team-member"><strong>ShuHang Gu(顾舒航)</strong><br>Professor<br>shuhanggu@gmail.com</div>
            <a href="https://shuhanggu.github.io/"><div class="team-member">Personal homepage</div></a>
          </div>
        </div>
    design:
      # Section background color (CSS class)
      css_class: hbx-bg-gradient
      # css_class: "bg-gray-100 dark:bg-gray-900"
      # css_class: hbx-bg-gradient
  - block: markdown
    content:
      title: PhD Student
      text: |
        
        
        <style>
          .team-grid-phd {
            display: grid;
            grid-template-columns: repeat(5, 250px); /* 固定列宽 */
            grid-template-rows: repeat(1, 500px);
            justify-content: center; /* 关键：网格居中 */
            gap: 55px;
            padding: 0 420px;
          }
          .team-member {
            display: flex;
            flex-direction: column;
            align-items: center;
            text-align: center;
          }
          .team-photo-phd {
            width: 250px; /* 图片填充列宽 */
            height: auto;
            object-fit: cover;
          }
        </style>
        <div class="team-grid-phd">
          <!-- 添加其他成员 -->
          <div class="text-center">
            <img src="/images/zhangleheng.jpg" class="team-photo-phd">
            <div class="team-member"><strong>Leheng Zhang (张乐恒)</strong><br>Image Restoration<br>lehengzhang12@gmail.com</div>
          </div>
          <div class="text-center">
            <img src="/images/longwei.png" class="team-photo-phd">
            <div class="team-member"><strong>Wei Long (龙伟)</strong><br>Image Restoration<br>lwsch5940@163.com</div>
          </div>
          <div class="text-center">
            <img src="/images/youweiyi.jpg" class="team-photo-phd">
            <div class="team-member"><strong>Weiyi You (游炜熠)</strong><br>Diffusion Models, Image Super-Resolution<br>weiyiyou.ywy@gmail.com</div>
          </div>
          <div class="text-center">
            <img src="/images/zhangjinhua.jpg" class="team-photo-phd">
            <div class="team-member"><strong>Jinhua Zhang (张进华)</strong><br>Visual Content Generation<br>jinhua.zjh@gmail.com</div>
          </div>
          <div class="text-center">
            <img src="/images/zhouxingyu.jpg" class="team-photo-phd">
            <div class="team-member"><strong>Xingyu Zhou (周星宇)</strong><br>Image/Video Restoration and Generation<br>xy.chous526@gmail.com</div>
          </div>
        </div>
    design:
      # Section background color (CSS class)
      css_class: hbx-bg-gradient
  - block: markdown
    content:
      title: Master Student
      text: |
        
        <style>
          .team-grid-compact {
            display: grid;
            grid-template-columns: repeat(5, 250px); /* 固定列宽 */
            justify-content: center; /* 关键：网格居中 */
            gap: 55px;
            padding: 0 420px;
          }
          .team-member {
            display: flex;
            flex-direction: column;
            align-items: center;
            text-align: center;
          }
          .team-photo {
            width: 250px; /* 图片填充列宽 */
            height: autopx;
            object-fit: cover;
          }
        </style>
        <div class="team-grid-compact">
          <div class="text-center">
            <img src="/images/chenkai.png" class="team-photo">
            <div class="team-member"><strong>Kai Chen (陈恺)</strong><br>Image Signal Processor, Image Denoising<br>kkchen318@gmail.com</div>
          </div>
          <div class="text-center">
            <img src="/images/jiangshiyin.jpg" class="team-photo">
            <div class="team-member"><strong>Shiyin Jiang (江世银)</strong><br>Image and Video Coding<br>shiyin.jsy@gmail.com</div>
          </div>
          <div class="text-center">
            <img src="/images/lijiafeng.jpg" class="team-photo">
            <div class="team-member"><strong>Jiafeng Li (李珈锋)</strong><br>Image Compression<br>ljiafeng798@gamil.com</div>
          </div>
          <div class="text-center">
            <img src="/images/loujunyu.jpg" class="team-photo">
            <div class="team-member"><strong>Junyu Lou (娄峻瑜)</strong><br>Image Enhancement<br>202421081125@std.uestc.edu.cn</div>
          </div>
          <div class="text-center">
            <img src="/images/lujingbo.jpg" class="team-photo">
            <div class="team-member"><strong>Jingbo Lu (卢景博)</strong><br>Learned Image Compression<br>jingbolu2023@163.com</div>
          </div>
          <div class="text-center">
            <img src="/images/luojiajie.jpg" class="team-photo">
            <div class="team-member"><strong>Jiajie Luo (罗嘉杰)</strong><br>Novel View Synthesis<br>exclibersaber@outlook.com</div>
          </div>
          <div class="text-center">
            <img src="/images/mengchunyu.jpg" class="team-photo">
            <div class="team-member"><strong>Chunyu Meng (蒙春雨)</strong><br>Image Super-Resolution<br>202421081123@std.uestc.edu.cn</div>
          </div>
          <div class="text-center">
            <img src="/images/wangzhaoxun.jpg" class="team-photo">
            <div class="team-member"><strong>Zhaoxun Wang (王兆旬)</strong><br>Image denoising<br>1875363937@qq.com</div>
          </div>
          <div class="text-center">
            <img src="/images/zhangzihong.jpg" class="team-photo">
            <div class="team-member"><strong>Zihong Zhang (张子宏)</strong><br>Learned Image Compression<br>zihong.zhz@gmail.com</div>
          </div>
          <div class="text-center">
            <img src="/images/zhaoxiaorui.jpg" class="team-photo">
            <div class="team-member"><strong>Xiaorui Zhao (赵小锐)</strong><br>Image Super-resolution, Image Restoration<br>zzzhaoxiaorui@gmail.com</div>
          </div>
          <div class="text-center">
            <img src="/images/zoujiale.jpg" class="team-photo">
            <div class="team-member"><strong>Jiale Zou (邹佳乐)</strong><br>Representation Learning<br>sean2074575405@gmail.com</div>
          </div>
        </div>
    design:
      # Section background color (CSS class)
      css_class: hbx-bg-gradient
      # css_class: "bg-gradient-to-t"
      # css_class: "bg-gradient-to-br"

  - block: markdown
    content:
      title: Alumni
      text: |
        
        <style>
          .team-grid-alumni {
            display: grid;
            grid-template-columns: repeat(2, 600px); /* 固定列宽 */
            justify-content: center; /* 关键：网格居中 */
            gap: 55px;
            padding: 0 420px;
          }
          .team-member {
            display: flex;
            flex-direction: column;
            align-items: center;
            text-align: center;
          }
        </style>
        <div class="team-grid-alumni">
          <div class="text-center">
            <div class="team-member"><strong>Kexuan Shi (施柯煊)</strong> 2023-2024, Research Intern <br> The Chinese University of Hong Kong</div>
          </div>
          <div class="text-center">
            <div class="team-member"><strong>Ziheng Liao (廖孜恒)</strong> 2022-2024, Master Student <br> VeriSilicon</div>
          </div>
          <div class="text-center">
            <div class="team-member"><strong>Minghao Han (韩铭昊)</strong> 2023-2025, Research Intern <br> Institute of Automation, Chinese Academy of Sciences</div>
          </div>
          <div class="text-center">
            <div class="team-member"><strong>Mingyang Zhang (张铭洋)</strong> 2024-2025, Research Intern <br> Sun Yat-sen University</div>
          </div>
          <div class="text-center">
            <div class="team-member"><strong>Jinchen Wang (汪锦琛)</strong> 2024-2025, Research Intern <br> HKUST (GZ)</div>
          </div>
          <div class="text-center">
            <div class="team-member"><strong>Qifan Li (李祺帆)</strong> 2024-2025, Research Intern <br> ****</div>
          </div>
        </div>
    design:
      # Section background color (CSS class)
      css_class: hbx-bg-gradient
      # css_class: "bg-gradient-to-br"
---