---

marp: true
math: katex
size: 16:9
paginate: true
footer: 'Page \$current / \$total — [22f3000814@ds.study.iitm.ac.in](mailto:22f3000814@ds.study.iitm.ac.in)'
theme: my-theme
style: |
/\* ----------------------

* Custom theme: my-theme
* \---------------------- */
  @theme my-theme {
  /* Base */
  section {
  font-family: Inter, system-ui, Segoe UI, Roboto, Helvetica, Arial, sans-serif;
  font-size: 28px;
  color: #0f172a; /* slate-900 */
  background: #f8fafc; /* slate-50 \*/
  padding: 64px;
  }

```
h1, h2, h3 {
```

```
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
pre, code { font-family: ui-monospace, SFMono-Regular, Menlo, Monaco, Consolas, "Liberation Mono", "Courier New", monospace; }
pre { background: #0b1020; color: #e2e8f0; border-radius: 12px; padding: 18px; }

/* Page number placement tweak (optional) */
section::after {
  right: 32px;
  bottom: 22px;
  opacity: 0.6;
}
```

## }

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

## Marp Directives in Use

* `theme: my-theme` — use our custom theme
* `paginate: true` — show page numbers
* `footer:` — show page numbers + email
* `math: katex` — enable equations
* `style:` — inline CSS theme definition

> These are declared in the front matter at the top of this file.

---

<!-- _backgroundImage: 'https://images.unsplash.com/photo-1500530855697-b586d89ba3ee?w=1600&q=80&auto=format&fit=crop' -->

<!-- _backgroundSize: cover -->

<!-- _class: invert -->

# Background Image Slide

This slide demonstrates a **full-bleed background image** with text styled via the `.invert` helper for contrast.

*Tip:* You can swap the URL for a local image stored in your repo, e.g., `./img/bg.jpg`.

---

## Algorithmic Complexity — Math

We can render formulas using **KaTeX**:

* Asymptotic upper bound:

  $T(n) = O(n \log n)$

* Master Theorem (Case 2 example for \$a=2, b=2\$):

  $T(n) = 2\,T\!\left(\frac{n}{2}\right) + n \implies T(n) = \Theta(n \log n)$

* Geometric series used in many recurrences:

  $\sum_{i=0}^{k} r^i = \frac{1-r^{k+1}}{1-r} \quad (r \ne 1)$

---

## Custom Styling Helpers

<div class="card">
  <h3 class="accent">Card with Accent Heading</h3>
  <p class="muted">This block uses the <code>.card</code>, <code>.accent</code>, and <code>.muted</code> helper classes
  defined in the custom theme. It’s great for emphasizing content.</p>
</div>

* Typography tuned for legibility
* Soft shadows and rounded corners
* Works with standard Markdown content

---

## Contact & Credits

* Built with **Marp**
* Theme: **my-theme** (inline)
* Maintainer: **CoderDotPy**
* Email: **[22f3000814@ds.study.iitm.ac.in](mailto:22f3000814@ds.study.iitm.ac.in)**

Thank you!

