
<link
  rel="stylesheet"
  href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/4.7.0/css/font-awesome.min.css"
>


{% if site.google_scholar_stats_use_cdn %}
{% assign gsDataBaseUrl = "https://cdn.jsdelivr.net/gh/" | append: site.repository | append: "@" %}
{% else %}
{% assign gsDataBaseUrl = "https://raw.githubusercontent.com/" | append: site.repository | append: "/" %}
{% endif %}
{% assign url = gsDataBaseUrl | append: "google-scholar-stats/gs_data_shieldsio.json" %}

<span class='anchor' id='about-me'></span>



# 💡 About Me

Hi! This is Qianchi Zhang (张谦驰), a first-year PhD student at **School of Artificial Intelligence, Beihang University**. My research focuses on **LLM Hallucinations** and **Trustworthy Retrieval-Augmented Generation**.



<span class="anchor" id="news"></span>


# 🔥 News
- *2026.04*: &nbsp;🎉🎉 One first-author paper is accepted to <a href="https://2026.aclweb.org/" style="color:#3a6ea5; text-decoration: underline;">ACL 2026 Main</a>!
- *2026.01*: &nbsp;🎉🎉 One first-author paper is accepted to <a href="https://www2026.thewebconf.org/" style="color:#3a6ea5; text-decoration: underline;">WWW 2026</a>!


<span class="anchor" id="publications"></span>

# 📝 Selected Publications

<sup>**\***</sup> Equal Contribution; <sup>**†**</sup> Corresponding Author; AR=Acceptance Rate


<!-- Stable-RAG -->
<table style="width:100%; border-collapse:collapse; border-spacing:0 18px; border:none; background:none;">
  <tr style="border:none; background:none;">
    <td style="width:200px; vertical-align:top; border:none!important; background:none!important;">
    <!-- Figure -->
  <img
    src="./images/paper/Stable-RAG.png"
    style="width:185px; max-width:100%; display:block; border-radius:6px;"
  />
</td>
    <!-- Title -->
    <td style="vertical-align:top; border:none!important; background:none!important;">
      <a href="https://aclanthology.org/2026.acl-long.1188.pdf" target="_blank" style="text-decoration: none; color: #3a6ea5; font-weight: bold;">
    Stable-RAG: Mitigating Retrieval-Permutation-Induced Hallucinations in Retrieval-Augmented Generation.
</a>
    <!-- Author & Venue -->
      <div class="fs-14 lh-15" style="margin-top:8px;">
    <i class="fa fa-user"></i>
    <strong><u>Qianchi Zhang</u></strong>, Hainan Zhang<sup>†</sup>, Liang Pang, Hongwei Zheng, and Zhiming Zheng.
  </div>
      <div class="fs-14 lh-15" style="margin-top:3px;"><i class="fa fa-bank"></i>  <strong> ACL 2026 Main, AR=18.9% </strong> ｜ <span style="color:#C62828; font-weight:600;">CCF A</span> ｜ <a href="./images/poster/Stable-RAG.pdf" target="_blank" style="
    display:inline-block;
    padding:2px 7px;
    background-color:#C62828;
    color:#ffffff;
    text-decoration:none;
    border-radius:4px;
    font-weight:600;
  ">
  <i class="fa fa-picture-o"></i> Poster
</a>
        </div>
    </td>
  </tr>
</table>


<!-- CompSelect -->
<table style="width:100%; border-collapse:collapse; border-spacing:0 18px; border:none; background:none;">
  <tr style="border:none; background:none;">
    <td style="width:200px; vertical-align:top; border:none!important; background:none!important;">
      <img
    src="./images/paper/CompSelect.png"
    style="width:185px; max-width:100%; display:block; border-radius:6px;"
      />
    </td>
    <td style="vertical-align:top; border:none!important; background:none!important;">
      <a href="https://dl.acm.org/doi/epdf/10.1145/3774904.3792158" target="_blank" style="text-decoration: none; color: #3a6ea5; font-weight: bold;">
    Less is More: Compact Clue Selection for Efficient Retrieval-Augmented Generation Reasoning.
</a>
      <div class="fs-14 lh-15" style="margin-top:8px;">
    <i class="fa fa-user"></i>
    <strong><u>Qianchi Zhang</u></strong>, Hainan Zhang<sup>†</sup>, Liang Pang, Yongxin Tong, Hongwei Zheng, and Zhiming Zheng.
  </div>
        <div class="fs-14 lh-15" style="margin-top:3px;"><i class="fa fa-bank"></i> <strong> WWW 2026, AR=20.1% </strong> ｜ <span style="color:#C62828; font-weight:600;">CCF A</span>
        </div>
​      <br/>
​    </td>
  </tr>
</table>


 <!-- AdaComp -->
<table style="width:100%; border-collapse:collapse; border-spacing:0 18px; border:none; background:none;">
  <tr style="border:none; background:none;">
    <td style="width:200px; vertical-align:top; border:none!important; background:none!important;">
      <img
    src="./images/paper/AdaComp.png"
    style="width:185px; max-width:100%; display:block; border-radius:6px;"
      />
    </td>
    <td style="vertical-align:top; border:none!important; background:none!important;">
      <a href="https://arxiv.org/pdf/2409.01579" target="_blank" style="text-decoration: none; color: #3a6ea5; font-weight: bold;">
    AdaComp: Extractive Context Compression with Adaptive Predictor for Retrieval-Augmented Large Language Models.
</a>
       <div class="fs-14 lh-15" style="margin-top:8px;">
    <i class="fa fa-user"></i>
    <strong><u>Qianchi Zhang</u></strong>, Hainan Zhang<sup>†</sup>, Liang Pang, Hongwei Zheng, and Zhiming Zheng.
  </div>
      <div class="fs-14 lh-15" style="margin-top:3px;"><i class="fa fa-bank"></i> <strong> KSEM 2026 </strong> ｜ <span style="color:#C62828; font-weight:600;">CCF C</span>
        </div>
    </td>
  </tr>


</table>

<span class="anchor" id="awards"></span>

# 🎖 Honors and Awards

- *2025*: Second Prize Outstanding Student Scholarship, Beihang University

- *2023*: Outstanding Graduate in Beijing Forestry University.
- *2020-2022*: China National Encouragement Scholarship.



<span class="anchor" id="talks"></span>

# 🎤 Invited Talks

- *2026.07*: “Stable-RAG: Mitigating Retrieval-Permutation-Induced Hallucinations in Retrieval-Augmented Generation”, YSSNLP 2026 Poster.

- *2026.03*: “Stable-RAG: Mitigating Retrieval-Permutation-Induced Hallucinations in Retrieval-Augmented Generation”, CCIR PhD Forum.



<span class="anchor" id="services"></span>

# 🧑‍⚖️ Academic Services

- **Journal Reviewer**: TKDE, TMM, TAI
- **Conference Reviewer**: ACL Rolling Review



<span class="anchor" id="educations"></span>

# 📖 Educations
- *2025.9 – Present*, Ph.D. Student, School of Artificial Intelligence, Beihang University.
  
- *2023.9 – 2025.6*, M.S. Student, School of Artificial Intelligence, Beihang University.
  
- *2019.9 – 2023.6*, B.S. Student, School of Information Science and Technology, Beijing Forestry University.



<span class="anchor" id="internships"></span>

# 💻 Internships
- *2022.10 - 2023.01*, Zhihu. Beijing, China.
