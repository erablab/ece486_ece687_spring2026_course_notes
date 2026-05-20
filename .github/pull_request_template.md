### Lecture Scribe Submission

Thank you for contributing to the ECE 486 / ECE 687 collaborative course notes! Please complete this checklist before marking your Pull Request as ready for review.

#### Quality Assurance Checklist

- [ ] **Local Verification**: Does your file compile cleanly on your local machine without breaking the global document build?
- [ ] **No Command Overrides**: Have you strictly avoided adding `\documentclass`, `\begin{document}`, or core structural commands to your file? (These break the subfile package integration).
- [ ] **Layout Standards**: Have you used `\sidenote{}` for side comments instead of standard footnotes?
- [ ] **Image Paths**: If you added diagrams or schematics, are the image paths relative to your *specific week's folder* rather than the root directory?
- [ ] **Author Fields**: Have you updated the `\sidenote{\textbf{Scribe}: ...}` block with your real name and GitHub username?

#### Verification Capture
*The automated GitHub Actions compiler will run shortly to generate a live PDF preview link in the checks below.*
