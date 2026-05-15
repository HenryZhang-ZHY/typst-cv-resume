# typst-cv-resume

A minimal and fully-customizable CV/resume template for Typst.

## Preview

<table>
  <tr>
    <td align="center"><b>English</b></td>
    <td align="center"><b>简体中文</b></td>
  </tr>
  <tr>
    <td><img src="assets/example_en_us.png" width="380" alt="English resume example" /></td>
    <td><img src="assets/example_zh_cn.png" width="380" alt="中文简历示例" /></td>
  </tr>
</table>

## How to use

### Install mise

We recommend using [mise](https://mise.jdx.dev/installing-mise.html) to manage the typst CLI. Follow the instructions on the mise website to install it.

### Install Fonts

Download Noto Serif CJK SC from one of the following sources and install it on your system:

- [Google Fonts](https://fonts.google.com/noto/specimen/Noto+Serif+SC)
- [Tsinghua University Mirror](https://mirrors.tuna.tsinghua.edu.cn/github-release/googlefonts/noto-cjk/Noto%20Serif%20CJK%20Version%202.002%20(OTF,%20OTC,%20Super%20OTC,%20Subset%20OTF,%20Variable%20OTF_TTF)/09_NotoSerifCJKsc.zip)

### Compile

To compile a Typst file to PDF:

```bash
# Compile and create PDF in the same directory
typst compile example_en_us.typ

# Compile and specify output path
typst compile example_en_us.typ my_resume.pdf

# Compile to PNG
typst compile example_en_us.typ my_resume.png
```

### Watch Mode

To automatically recompile on file changes:

```bash
typst watch example_en_us.typ
```

This is faster than compiling from scratch each time thanks to Typst's incremental compilation.
