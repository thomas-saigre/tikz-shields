# Tikz-shields

![logo-tikzshields](https://raw.githubusercontent.com/thomas-saigre/tikz-shields/refs/heads/main/doc/img/logo.svg "Tikz-shields")

[![CTAN](https://img.shields.io/ctan/v/tikz-shields.svg)](https://ctan.org/pkg/tikz-shields)
[![License](https://img.shields.io/github/license/thomas-saigre/tikz-shields)](https://github.com/thomas-saigre/tikz-shields/blob/main/LICENSE)
[![GitHub tag](https://img.shields.io/github/v/release/thomas-saigre/tikz-shields)](https://github.com/thomas-saigre/tikz-shields/releases/latest)
[![GitHub Issues or Pull Requests](https://img.shields.io/github/issues/thomas-saigre/tikz-shields)](https://github.com/thomas-saigre/tikz-shields/issues)


Badges as in shields.io, but in LaTeX.

## Usage

```tex
\documentclass{article}
\usepackage{tikz-shields}

\begin{document}

\drawBadge{Ti\emph{k}Z}{shields}

\githubBadge{thomas-saigre/tikz-shields}

\end{document}
```

![Example badge](./doc/img/example.svg)

For more details, please consult the package documentation.

## License

Copyright @thomas-saigre, maintainer of the package.

This package is published under the GPL-3.0 license, permitting use, modification, and distribution under the terms of the [GNU General Public License version 3.0](LICENSE).
