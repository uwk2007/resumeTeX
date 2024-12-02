# Usage of Components

This document demonstrates how to use the components in the `resumeTeX` template. Each component is designed to maintain ATS compatibility while ensuring a clean and professional layout.

## 1. Section (`\cvsection`)

Use the `\cvsection` command to create a section header with a FontAwesome icon and a horizontal rule.

### Syntax

```tex
\cvsection[<bottom-margin>]{<icon>}{<section-title>}
```

- `<bottom-margin>`: The bottom margin of the section (optional, default is set).
- `<icon>`: The FontAwesome icon name (e.g., `briefcase`, `graduation-cap`, `code`, etc.). Check [The fontawesome5 package](http://mirrors.ibiblio.org/CTAN/fonts/fontawesome5/doc/fontawesome5.pdf) for a list of available icons.
- `<section-title>`: The title of the section (e.g., `Work Experience`, `Education`, `Skills`, etc.)

### Example

```tex
\cvsection{briefcase}{Work Experience}
```

## 2. Tagline (`\cvtagline` and `\cvsingletagline`)

### Dual-Line Tagline (`\cvtagline`)

Creates a dual-line tagline with bold text on the first line and italicized text on the second.

### Syntax

```tex
\cvtagline[<bottom-margin>]{<left-top>}{<right-top>}{<left-bottom>}{<right-bottom>}
```

- `<bottom-margin>`: The bottom margin of the tagline (optional, default is set).
- `<left-top>`: The bold text on the left side of the first line.
- `<right-top>`: The bold text on the right side of the first line.
- `<left-bottom>`: The italicized text on the left side of the second line.
- `<right-bottom>`: The italicized text on the right side of the second line.

### Example

```tex
\cvtagline{Nanyang Technological University}{Singapore}{B.S. in Computer Science}{Aug. 2016 - May. 2020}
```

### Single-Line Tagline (`\cvsingletagline`)

_Note: Single-line tagline component has unknown formmating issues. Fix is in progress._

Creates a single-line tagline with bold text.

### Syntax

```tex
\cvsingletagline[<bottom-margin>]{<top>}{<bottom>}
```

- `<bottom-margin>`: The bottom margin of the tagline (optional, default is set).
- `<top>`: The bold text on the top line.
- `<bottom>`: The italicized text on the bottom line.

### Example

```tex
\cvsingletagline{Nanyang Technological University}{B.S. in Computer Science}
```

## 3. Bullet Points (`\cvbullets`)

Use the `\cvbullets` command to create a bullet point list.

### Syntax

```tex
\cvbullets[<bottom-margin>]{<bullet-items>}
```

### Example

```tex
\cvbullets{
  \item Led a team of 5 engineers to build a scalable web application.
  \item Improved system performance by 30\% through code optimization.
  \item Presented findings to senior leadership, securing S\$500K in funding.
}
```

## 4. ATS Invisible Text

```tex
% For ATS systems
% Include information you prefer not to be questioned,
% but that could help you pass ATS screening.
\scalebox{0.001}{\textcolor{white}{<ATS-TEXT>}}
```

- `<ATS-TEXT>`: The text you want to include for ATS screening but not for human readers.
