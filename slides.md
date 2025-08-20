---
marp: true
math: katex
size: 16:9
paginate: true
footer: 'Page $current / $total — [22f3000814@ds.study.iitm.ac.in](mailto:22f3000814@ds.study.iitm.ac.in)'
theme: my-theme
style: |
  /* ----------------------
   * Custom theme: my-theme
   * ---------------------- */
  @theme my-theme {
    /* Base */
    section {
      font-family: Inter, system-ui, Segoe UI, Roboto, Helvetica, Arial, sans-serif;
      font-size: 28px;
      color: #0f172a; /* slate-900 */
      background: #f8fafc; /* slate-50 */
      padding: 64px;
    }

    h1, h2, h3 {
      color: #0b1020;
      letter-spacing: 0.2px;
    }

    h1 { font-size: 64px; }
    h2 { font-size: 44px; }
    h3 { font-size: 36px; }

    /* Accent utilities */
    .accent { color: #2563eb; }
    .muted { color: #475569; }

    /* Card style helper */
    .card {
      border-radius: 18px;
      box-shadow: 0 10px 30px rgba(15, 23, 42, 0.1);
      background: #ffffff;
      padding: 28px;
    }

    /* Invert helper for dark backgrounds */
    .invert { color: #f8fafc; }
    .invert h1, .invert h2, .invert h3 { color: #ffffff; }

    /* Code blocks */
    pre, code {
      font-family: ui-monospace, SFMono-Regular, Menlo, Monaco, Consolas, "Liberation Mono", "Courier New", monospace;
    }
    pre {
      background: #0b1020;
      color: #e2e8f0;
      border-radius: 12px;
      padding: 18px;
    }

    /* Page number placement tweak */
    section::after {
      right: 32px;
      bottom: 22px;
      opacity: 0.6;
    }
  }
---

<!-- _class: card -->

# Marp + Custom Theme

**A minimal, polished deck** using Marp.

* Custom theme (`my-theme`)
* Page numbers in footer
* Background image slide
* Math via KaTeX
* Email included for contact

**Email:** [22f3000814@ds.study.iitm.ac.in](mailto:22f3000814@ds.study.iitm.ac.in)

---

# Background Example

![bg cover](./img/rainbow.jpeg)

This slide uses a full background image 🎨

---

# Math Example

We can render formulas with KaTeX:

$$
T(n) = O(n \log n) \quad \text{(for MergeSort)}
$$
