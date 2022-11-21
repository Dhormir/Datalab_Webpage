+++
title = "Extended Shortcodes"
description = "Few more shortcodes provided by DeepThought."
date = 2020-08-29

[extra]
toc = true
comments = true
+++

DeepThought theme provides multiple shortcodes on top of built-in ones in Zola.
Please, have a look at the [Config Options](/docs/config-options#external-libraries)
that explain how to enable them.

<!-- more -->

# Lines of Research

[Galleria](https://galleriajs.github.io/) is a framework that simplifies the process of creating beautiful image galleries for the web and mobile devices.

**Code**

```
{%/* galleria() */%}
{
  "images": [
    {
      "src": "alexandre-dinaut-GHxr3O6yZ1c-unsplash.jpg",
      "title": "Clouds & Mountains",
      "description": "Just hanging out with each other."
    },
    {
      "src": "chandler-cruttenden-YYemke7BfuE-unsplash.jpg",
      "title": "Crop",
      "description": "Waiting for the harvest."
    },
    {
      "src": "jung-ho-park-7aZtpsyaWVM-unsplash.jpg",
      "title": "The Fog",
      "description": "Engulfing everything."
    },
    {
      "src": "kitera-dent-BIj4LObC6es-unsplash.jpg",
      "title": "Just Plants",
      "description": "Backdrop of ocean."
    },
    {
      "src": "koes-nadi-XkUFF1nnbA8-unsplash.jpg",
      "title": "Whoa",
      "description": "Something to look at."
    },
    {
      "src": "lazyartistgallery-HHaIRbgzcGw-unsplash.jpg",
      "title": "Let's Chill",
      "description": "Three birds just chilling !!"
    },
    {
      "src": "saira-nUxdL_19OQw-unsplash.jpg",
      "title": "Canyon",
      "description": "Might of nature."
    },
    {
      "src": "waldemar-brandt-2hAEHCt25eM-unsplash.jpg",
      "title": "Evening",
      "description": "Time to wind down."
    }
  ]
}
{%/* end */%}
```

**Output**

{% galleria() %}
{
  "images": [
    {
      "src": "alexandre-dinaut-GHxr3O6yZ1c-unsplash.jpg",
      "title": "Clouds & Mountains",
      "description": "Just hanging out with each other."
    },
    {
      "src": "chandler-cruttenden-YYemke7BfuE-unsplash.jpg",
      "title": "Crop",
      "description": "Waiting for the harvest."
    },
    {
      "src": "jung-ho-park-7aZtpsyaWVM-unsplash.jpg",
      "title": "The Fog",
      "description": "Engulfing everything."
    },
    {
      "src": "kitera-dent-BIj4LObC6es-unsplash.jpg",
      "title": "Just Plants",
      "description": "Backdrop of ocean."
    },
    {
      "src": "koes-nadi-XkUFF1nnbA8-unsplash.jpg",
      "title": "Whoa",
      "description": "Something to look at."
    },
    {
      "src": "lazyartistgallery-HHaIRbgzcGw-unsplash.jpg",
      "title": "Let's Chill",
      "description": "Three birds just chilling !!"
    },
    {
      "src": "saira-nUxdL_19OQw-unsplash.jpg",
      "title": "Canyon",
      "description": "Might of nature."
    },
    {
      "src": "waldemar-brandt-2hAEHCt25eM-unsplash.jpg",
      "title": "Evening",
      "description": "Time to wind down."
    }
  ]
}
{% end %}

# NLP
[KaTeX](https://katex.org/) is a math typesetting library based on TeX.

**Code**

```
{%/* katex(block=true) */%}
\KaTeX
{%/* end */%}
```

**Output**

{% katex(block=true) %}
\KaTeX
{% end %}


# GNN

[KaTeX](https://katex.org/) is a math typesetting library based on TeX.

**Code**

```
{%/* katex(block=true) */%}
\KaTeX
{%/* end */%}
```

**Output**

{% katex(block=true) %}
\KaTeX
{% end %}

# RNN

[KaTeX](https://katex.org/) is a math typesetting library based on TeX.

**Code**

```
{%/* katex(block=true) */%}
\KaTeX
{%/* end */%}
```

**Output**

{% katex(block=true) %}
\KaTeX
{% end %}

**Photos By:**
- [ALEXANDRE DINAUT](https://unsplash.com/@alexdinaut?utm_source=unsplash&amp;utm_medium=referral&amp;utm_content=creditCopyText) on [Unsplash](https://unsplash.com/@alexdinaut?utm_source=unsplash&amp;utm_medium=referral&amp;utm_content=creditCopyText)
- [Chandler Cruttenden](https://unsplash.com/@chanphoto?utm_source=unsplash&amp;utm_medium=referral&amp;utm_content=creditCopyText) on [Unsplash](https://unsplash.com/@chanphoto?utm_source=unsplash&amp;utm_medium=referral&amp;utm_content=creditCopyText)
- [Jung Ho Park](https://unsplash.com/@mylovefromjesus?utm_source=unsplash&amp;utm_medium=referral&amp;utm_content=creditCopyText) on [Unsplash](https://unsplash.com/@mylovefromjesus?utm_source=unsplash&amp;utm_medium=referral&amp;utm_content=creditCopyText)
- [Kitera Dent](https://unsplash.com/@kitera?utm_source=unsplash&amp;utm_medium=referral&amp;utm_content=creditCopyText) on [Unsplash](https://unsplash.com/@kitera?utm_source=unsplash&amp;utm_medium=referral&amp;utm_content=creditCopyText)
- [Koes nadi](https://unsplash.com/@bangkoes?utm_source=unsplash&amp;utm_medium=referral&amp;utm_content=creditCopyText) on [Unsplash](https://unsplash.com/@bangkoes?utm_source=unsplash&amp;utm_medium=referral&amp;utm_content=creditCopyText)
- [Lazyartistgallery](https://unsplash.com/@rahulp9800?utm_source=unsplash&amp;utm_medium=referral&amp;utm_content=creditCopyText) on [Unsplash](https://unsplash.com/@rahulp9800?utm_source=unsplash&amp;utm_medium=referral&amp;utm_content=creditCopyText)
- [Saira](https://unsplash.com/@sairaa?utm_source=unsplash&amp;utm_medium=referral&amp;utm_content=creditCopyText) on [Unsplash](https://unsplash.com/@sairaa?utm_source=unsplash&amp;utm_medium=referral&amp;utm_content=creditCopyText)
- [Waldemar Brandt](https://unsplash.com/@waldemarbrandt67w?utm_source=unsplash&amp;utm_medium=referral&amp;utm_content=creditCopyText) on [Unsplash](https://unsplash.com/@waldemarbrandt67w?utm_source=unsplash&amp;utm_medium=referral&amp;utm_content=creditCopyText)
