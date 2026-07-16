
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

Hi! This is Qianchi Zhang, a first-year PhD student at **School of Artificial Intelligence, Beihang University**. My research focuses on **LLM Hallucinations** and **Trustworthy Retrieval-Augmented Generation**.



<span class="anchor" id="news"></span>


# 🔥 News
- *2026.04*: &nbsp;🎉🎉 One first-author paper is accepted to <a href="https://2026.aclweb.org/" style="color:#3a6ea5; text-decoration: underline;">ACL 2026 Main</a>!
- *2026.01*: &nbsp;🎉🎉 One first-author paper is accepted to <a href="https://www2026.thewebconf.org/" style="color:#3a6ea5; text-decoration: underline;">WWW 2026</a>!


<span class="anchor" id="publications"></span>

# 📝 Selected Publications

<sup>**\***</sup> Equal Contribution; <sup>**†**</sup> Corresponding Author


<!-- Stable-RAG -->
<ul style="padding-left:22px; margin-bottom:20px;">
  <li style="padding-left:2px;">
    <!-- Title -->
    <a
      href="https://aclanthology.org/2026.acl-long.1188.pdf"
      target="_blank"
      style="
        text-decoration:none;
        color:#3a6ea5;
        font-weight:bold;
      ">
      Stable-RAG: Mitigating Retrieval-Permutation-Induced Hallucinations
      in Retrieval-Augmented Generation.
    </a>
    <!-- Authors -->
    <div
      class="fs-14 lh-15"
      style="
        margin-top:8px;
        display:flex;
        align-items:center;
      "
    >
      <i
        class="fa fa-user"
        title="Authors"
        style="
          width:16px;
          margin-right:4px;
          color:#666;
          text-align:center;
          flex-shrink:0;
        "
      ></i>
      <span>
        <strong><u>Qianchi Zhang</u></strong>,
        Hainan Zhang<sup>†</sup>,
        Liang Pang,
        Hongwei Zheng,
        and Zhiming Zheng.
      </span>
    </div>
    <!-- Venue -->
    <div
      class="fs-14 lh-15"
      style="
        margin-top:3px;
        display:flex;
        align-items:center;
      "
    >
      <i
        class="fa fa-bank"
        title="Venue"
        style="
          width:16px;
          margin-right:4px;
          color:#666;
          text-align:center;
          flex-shrink:0;
        "
      ></i>
      <span>
        <span style="color:#000000;">
          The 64th Annual Meeting of the Association for Computational Linguistics.
        </span>
        <span style="color:#C62828; font-weight:600;">
          (ACL 2026 Main, CCF A) ｜ Acceptance Rate=18.9%
        </span>
      </span>
    </div>
    <!-- Resources -->
    <div
      class="fs-14 lh-15"
      style="
        margin-top:5px;
        display:flex;
        align-items:center;
        flex-wrap:wrap;
        column-gap:6px;
        row-gap:4px;
      "
    >
      <i
        class="fa fa-link"
        title="Resources"
        style="
          width:16px;
          margin-right:4px;
          color:#666;
          text-align:center;
          flex-shrink:0;
        "
      ></i>
      <!-- GitHub -->
      <a
        href="https://github.com/zqc1023/Stable-RAG"
        target="_blank"
        style="
          display:inline-flex;
          align-items:center;
          text-decoration:none;
        "
      >
        <img
          alt="GitHub Repo stars"
          src="https://img.shields.io/github/stars/zqc1023/Stable-RAG?style=flat-square&logo=github&logoColor=black&labelColor=white&color=white&label=Stars&cacheSeconds=10"
          style="
            display:block;
            height:18px;
            border:1px solid #ccc;
            border-radius:4px;
          "
        />
      </a>
      <!-- Google Scholar -->
      <a
        href="https://scholar.google.com/scholar?oi=bibs&hl=zh-CN&cites=13388958562085683949"
        target="_blank"
        style="
          display:inline-flex;
          align-items:center;
          text-decoration:none;
        "
      >
        <img
          alt="Google Scholar Citations"
          src="https://img.shields.io/badge/dynamic/json?url=https%3A%2F%2Fraw.githubusercontent.com%2Fzqc1023%2Fzqc1023.github.io%2Fgoogle-scholar-stats%2Fgs_data.json&query=%24.publications.%5B%27tmmwj04AAAAJ:GnPB-g6toBAC%27%5D.num_citations&label=Citations&color=white&logo=Google%20Scholar&style=flat-square&labelColor=white"
          style="
            display:block;
            height:18px;
            border:1px solid #ccc;
            border-radius:4px;
          "
        />
      </a>
      <!-- PDF -->
      <a
        href="https://aclanthology.org/2026.acl-long.1188.pdf"
        target="_blank"
        style="
          display:inline-flex;
          align-items:center;
          height:18px;
          padding:0 6px;
          box-sizing:border-box;
          border:1px solid #C62828;
          border-radius:4px;
          background-color:#C62828;
          color:#ffffff;
          text-decoration:none;
          font-size:11px;
          line-height:18px;
          font-weight:600;
        "
      >
        <i
          class="fa fa-file-pdf-o"
          style="
            margin-right:4px;
            font-size:11px;
          "
        ></i>
        PDF
      </a>
      <!-- Poster -->
      <a
        href="./images/poster/Stable-RAG.pdf"
        target="_blank"
        style="
          display:inline-flex;
          align-items:center;
          height:18px;
          padding:0 6px;
          box-sizing:border-box;
          border:1px solid #F28C28;
          border-radius:4px;
          background-color:#F28C28;
          color:#ffffff;
          text-decoration:none;
          font-size:11px;
          line-height:18px;
          font-weight:600;
        "
      >
        <i
          class="fa fa-picture-o"
          style="
            margin-right:4px;
            font-size:11px;
          "
        ></i>
        Poster
      </a>
    </div>

  </li>
</ul>


<!-- CompSelect -->
<ul style="padding-left:22px; margin-bottom:20px;">
  <li style="padding-left:2px;">
    <!-- Title -->
    <a
      href="https://dl.acm.org/doi/epdf/10.1145/3774904.3792158"
      target="_blank"
      style="
        text-decoration:none;
        color:#3a6ea5;
        font-weight:bold;
      "
    >
      Less is More: Compact Clue Selection for Efficient
      Retrieval-Augmented Generation Reasoning.
    </a>
    <!-- Authors -->
    <div
      class="fs-14 lh-15"
      style="
        margin-top:8px;
        display:flex;
        align-items:center;
      "
    >
      <i
        class="fa fa-user"
        title="Authors"
        style="
          width:16px;
          margin-right:4px;
          color:#666;
          text-align:center;
          flex-shrink:0;
        "
      ></i>
      <span>
        <strong><u>Qianchi Zhang</u></strong>,
        Hainan Zhang<sup>†</sup>,
        Liang Pang,
        Yongxin Tong,
        Hongwei Zheng,
        and Zhiming Zheng.
      </span>
    </div>
    <!-- Venue -->
    <div
      class="fs-14 lh-15"
      style="
        margin-top:3px;
        display:flex;
        align-items:center;
      "
    >
      <i
        class="fa fa-bank"
        title="Venue"
        style="
          width:16px;
          margin-right:4px;
          color:#666;
          text-align:center;
          flex-shrink:0;
        "
      ></i>
      <span>
        <span style="color:#000000;">
          The ACM Web Conference 2026.
        </span>
        <span style="color:#C62828; font-weight:600;">
          (WWW 2026, CCF A) ｜ Acceptance Rate=20.1%
        </span>
      </span>
    </div>
    <!-- Resources -->
    <div
      class="fs-14 lh-15"
      style="
        margin-top:5px;
        display:flex;
        align-items:center;
        flex-wrap:wrap;
        column-gap:6px;
        row-gap:4px;
      "
    >
      <i
        class="fa fa-link"
        title="Resources"
        style="
          width:16px;
          margin-right:4px;
          color:#666;
          text-align:center;
          flex-shrink:0;
        "
      ></i>
      <!-- GitHub -->
      <a
        href="https://github.com/zqc1023/CompSelect"
        target="_blank"
        style="
          display:inline-flex;
          align-items:center;
          text-decoration:none;
        "
      >
        <img
          alt="GitHub Repo stars"
          src="https://img.shields.io/github/stars/zqc1023/CompSelect?style=flat-square&logo=github&logoColor=black&labelColor=white&color=white&label=Stars&cacheSeconds=10"
          style="
            display:block;
            height:18px;
            border:1px solid #ccc;
            border-radius:4px;
          "
        />
      </a>
      <!-- Google Scholar -->
      <a
        href="https://scholar.google.com/scholar?oi=bibs&hl=zh-CN&cites=31051737733490796,13318791537714013165"
        target="_blank"
        style="
          display:inline-flex;
          align-items:center;
          text-decoration:none;
        "
      >
        <img
          alt="Google Scholar Citations"
          src="https://img.shields.io/badge/dynamic/json?url=https%3A%2F%2Fraw.githubusercontent.com%2Fzqc1023%2Fzqc1023.github.io%2Fgoogle-scholar-stats%2Fgs_data.json&query=%24.publications.%5B%27tmmwj04AAAAJ:vV6vV6tmYwMC%27%5D.num_citations&label=Citations&color=white&logo=Google%20Scholar&style=flat-square&labelColor=white"
          style="
            display:block;
            height:18px;
            border:1px solid #ccc;
            border-radius:4px;
          "
        />
      </a>
      <!-- PDF -->
      <a
        href="https://dl.acm.org/doi/pdf/10.1145/3774904.3792158"
        target="_blank"
        style="
          display:inline-flex;
          align-items:center;
          height:18px;
          padding:0 6px;
          box-sizing:border-box;
          border:1px solid #C62828;
          border-radius:4px;
          background-color:#C62828;
          color:#ffffff;
          text-decoration:none;
          font-size:11px;
          line-height:18px;
          font-weight:600;
        "
      >
        <i
          class="fa fa-file-pdf-o"
          style="
            margin-right:4px;
            font-size:11px;
          "
        ></i>
        PDF
      </a>
    </div>

  </li>
</ul>


<!-- AdaComp -->
<ul style="padding-left:22px; margin-bottom:20px;">
  <li style="padding-left:2px;">
    <!-- Title -->
    <a
      href="https://arxiv.org/pdf/2409.01579"
      target="_blank"
      style="
        text-decoration:none;
        color:#3a6ea5;
        font-weight:bold;
      "
    >
      AdaComp: Extractive Context Compression with Adaptive Predictor
      for Retrieval-Augmented Large Language Models.
    </a>
    <!-- Authors -->
    <div
      class="fs-14 lh-15"
      style="
        margin-top:8px;
        display:flex;
        align-items:center;
      "
    >
      <i
        class="fa fa-user"
        title="Authors"
        style="
          width:16px;
          margin-right:4px;
          color:#666;
          text-align:center;
          flex-shrink:0;
        "
      ></i>
      <span>
        <strong><u>Qianchi Zhang</u></strong>,
        Hainan Zhang<sup>†</sup>,
        Liang Pang,
        Hongwei Zheng,
        and Zhiming Zheng.
      </span>
    </div>
    <!-- Venue -->
    <div
      class="fs-14 lh-15"
      style="
        margin-top:3px;
        display:flex;
        align-items:center;
      "
    >
      <i
        class="fa fa-bank"
        title="Venue"
        style="
          width:16px;
          margin-right:4px;
          color:#666;
          text-align:center;
          flex-shrink:0;
        "
      ></i>
      <span>
        <span style="color:#000000;">
          The 19th International Conference on Knowledge Science,
          Engineering and Management.
        </span>
        <span style="color:#C62828; font-weight:600;">
          (KSEM 2026, CCF C)
        </span>
      </span>
    </div>
    <!-- Resources -->
    <div
      class="fs-14 lh-15"
      style="
        margin-top:5px;
        display:flex;
        align-items:center;
        flex-wrap:wrap;
        column-gap:6px;
        row-gap:4px;
      "
    >
      <i
        class="fa fa-link"
        title="Resources"
        style="
          width:16px;
          margin-right:4px;
          color:#666;
          text-align:center;
          flex-shrink:0;
        "
      ></i>
      <!-- Google Scholar -->
      <a
        href="https://scholar.google.com/scholar?oi=bibs&hl=zh-CN&cites=17212725779623653674"
        target="_blank"
        style="
          display:inline-flex;
          align-items:center;
          text-decoration:none;
        "
      >
        <img
          alt="Google Scholar Citations"
          src="https://img.shields.io/badge/dynamic/json?url=https%3A%2F%2Fraw.githubusercontent.com%2Fzqc1023%2Fzqc1023.github.io%2Fgoogle-scholar-stats%2Fgs_data.json&query=%24.publications.%5B%27tmmwj04AAAAJ:O3NaXMp0MMsC%27%5D.num_citations&label=Citations&color=white&logo=Google%20Scholar&style=flat-square&labelColor=white"
          style="
            display:block;
            height:18px;
            border:1px solid #ccc;
            border-radius:4px;
          "
        />
      </a>
      <!-- PDF -->
      <a
        href="https://arxiv.org/pdf/2409.01579"
        target="_blank"
        style="
          display:inline-flex;
          align-items:center;
          height:18px;
          padding:0 6px;
          box-sizing:border-box;
          border:1px solid #C62828;
          border-radius:4px;
          background-color:#C62828;
          color:#ffffff;
          text-decoration:none;
          font-size:11px;
          line-height:18px;
          font-weight:600;
        "
      >
        <i
          class="fa fa-file-pdf-o"
          style="
            margin-right:4px;
            font-size:11px;
          "
        ></i>
        PDF
      </a>
    </div>

  </li>
</ul>

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
