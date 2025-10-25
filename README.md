# Bibliography

This is a curated, BibTeX-based bibliography with a primary focus on security and cyber-physical systems research.
Additional entries will be migrated from my private collection following a quality review.

## Usage

Add this repository as a submodule to your LaTeX project:

```shell
$ git submodule add git@github.com:MatthiasEckhart/bibliography.git
```

Then, simply reference the bibliography in your `.tex` document. For example:

```LaTeX
\documentclass[11pt]{article}


\title{Title}
\author{John Doe}
\date{\today}

\begin{document}
\maketitle	

\section{Introduction}

My reference~\cite{Lamport1998}.

\bibliographystyle{plain}
\bibliography{./bibliography/bibliography}

\end{document}
```

## Future Work

- [ ] Convert BibTeX entries to HTML
- [ ] Implement web-based search and query functionality
- [ ] Link to available PDF preprints
