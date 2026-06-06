# XTU Math Exam site instructions for Codex

This is a Jekyll AcademicPages GitHub Pages site for 湘潭大学数学课程真题合集.

Goal:
- Make this site structurally and visually imitate https://ustcmathexam.github.io/
- Use the local reference repository at `_reference/ustc` as the template source.
- Imitate structure, layout, navigation style, Markdown table style, page organization, and PDF-linking conventions.
- Do NOT copy USTC-specific exam PDFs, contributor names, school text, or course data unless explicitly asked.
- Preserve XTU identity, XTU wording, XTU email, XTU file paths, and GitHub Pages baseurl.

Important constraints:
- Keep `_config.yml` url as `https://xtu-math.github.io`.
- Keep baseurl as `/xtu_math_exam.github.io` unless the repository is renamed to `xtu-math.github.io`.
- Use stable English permalink slugs with no spaces:
  - `/analysis/`
  - `/algebra/`
  - `/probability/`
  - `/applied/`
  - `/public-courses/`
  - `/entrance/`
  - `/submit/`
- Avoid permalinks containing spaces, such as `/applied math/`.
- Use `{{ site.baseurl }}/files/...` for internal PDF links.
- Prefer Markdown tables like the USTC pages:
  `| 年份 | 学期 | 期中考试 | 期末考试 | 答案/解析 | 授课教师 | 备注 |`
- Put XTU PDFs under `files/<category>/...`.
- Remove AcademicPages placeholder social links such as Google Scholar, ORCID, PubMed unless they are intentionally used.
- Do small, reviewable edits. Explain changed files after each task.