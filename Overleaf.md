# Overleaf LaTeX Commands Reference


## 📄 Document Structure
```latex
\documentclass{article}       % Document type (article, report, book)
\begin{document}              % Start of content
...
\end{document}                % End of content
```
**Purpose:** Defines the basic structure of the document to start writing in LaTeX.

---

## 🔹 Title, Author, Date
```latex
\title{Mera Pehla Document}
\author{Ali Khan}
\date{\today}                 % Or \date{1 January 2025}

\maketitle                    % To display the title
```
**Purpose:** Adds the title, author, and date at the top of the document.

---

## 🔹 Sections
```latex
\section{Introduction}
\subsection{Purpose}
\subsubsection{Details}
```
**Purpose:** Divides the document into headings and subheadings for better organization.

---

## 🔹 Text Formatting
```latex
\textbf{Bold Text}
\textit{Italic Text}
\underline{Underlined Text}
```
**Purpose:** Applies text styles to highlight important content.

---

## 🔹 Lists
**Unordered List:**
```latex
\begin{itemize}
  \item First point
  \item Second point
\end{itemize}
```
**Ordered List:**
```latex
\begin{enumerate}
  \item First step
  \item Second step
\end{enumerate}
```
**Purpose:** Displays content as bullet points or numbered lists.

---

## 🔹 Tables
```latex
\begin{tabular}{|c|c|}
\hline
Name & Age \\
\hline
Ali & 20 \\
\hline
\end{tabular}
```
**Purpose:** Presents data in a structured row and column format.

---

## 🔹 Images
```latex
\usepackage{graphicx}  % Add in preamble
\includegraphics[width=0.5\textwidth]{image.png}
```
**Purpose:** Inserts and displays images in the document.

---

## 🔹 Math Mode
**Inline Math:**
```latex
This is inline: $a^2 + b^2 = c^2$
```
**Display Math:**
```latex
\[
E = mc^2
\]
```
**Purpose:** Writes mathematical equations using proper LaTeX formatting.

---

## 🔹 Page Break & New Line
```latex
\newpage        % Page break
\\              % New line
```
**Purpose:** Adds a new page or breaks the line within the text.

---

## 🔹 Comments
```latex
% This is a comment
```
**Purpose:** Adds notes in the code that do not appear in the final output.

---

## 🔹 Packages (In preamble)
```latex
\usepackage{amsmath}      % Advanced math
\usepackage{graphicx}     % For images
\usepackage{hyperref}     % Clickable links
```
**Purpose:** Adds extra functionality like advanced math, images, or links.

---

## 🔹 Hyperlinks
```latex
\href{https://example.com}{Click Here}
```
**Purpose:** Creates clickable links to websites or online resources.

---

## 🔹 Code Snippets
```latex
\begin{verbatim}
This is a code block.
\end{verbatim}
```
**Purpose:** Displays text or programming code exactly as written.

---

## 🔹 Quotes
```latex
\begin{quote}
This is a quoted paragraph.
\end{quote}
```
**Purpose:** Highlights and formats quoted or important text.

---

End of Reference

This file contains the most commonly used LaTeX (Overleaf) commands. It is useful as a quick reference when working on any document.
