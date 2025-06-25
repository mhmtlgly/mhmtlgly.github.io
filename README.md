<h1 style="color: crimson;">🚀 Custom Blog Post with Styled HTML + Markdown Code</h1>

<p style="font-size: 1.1rem;">
This post is written in <strong>Markdown</strong> but uses <code>HTML</code> for layout, styling, and control — with native GitHub syntax highlighting for code.
</p>

<h2 style="margin-top: 2rem;">💡 Why This Approach?</h2>

<ul>
  <li>Use <strong>HTML</strong> for styling: headers, layout, blockquotes</li>
  <li>Use <code>```ts</code> for TypeScript code blocks — GitHub will highlight</li>
  <li>Keep everything portable, versionable, and previewable</li>
</ul>

<h2>🧱 Code Example</h2>

```ts
// Pure TypeScript, rendered with GitHub's highlighter
export const greet = (name: string): string => {
  return `Hello, ${name}!`;
};
<h2>📌 Quote Block</h2> <blockquote style="border-left: 4px solid #888; padding-left: 1rem; color: #555;"> Code is cognition — not configuration. </blockquote> <h2>🔗 Links</h2> <p>Visit my <a href="https://mhmtlgly.github.io/" target="_blank">GitHub Pages site</a> for live demos.</p> <h2>📁 Categories</h2> <ul> <li><a href="/categories/architecture">Architecture</a></li> <li><a href="/categories/typescript">TypeScript</a></li> <li><a href="/categories/editor">Editor</a></li> </ul> <hr> <p style="font-size: 0.9rem; color: gray;"> Authored by <strong>@mhmtlgly</strong> · Published June 26, 2025 </p>
```

<h2 style="margin-top: 2rem;">📦 Featured Components</h2>

<div style="display: flex; gap: 1rem; flex-wrap: wrap; margin-top: 1rem;">

  <div style="flex: 1 1 30%; padding: 1rem; border: 1px solid #ddd; border-radius: 6px; background: #f9f9f9;">
    <h3 style="margin-top: 0;">🧱 Atomic Rendering</h3>
    <p>All components are typed, styled, and declared in reusable .ts modules — no JSX, no frameworks.</p>
  </div>

  <div style="flex: 1 1 30%; padding: 1rem; border: 1px solid #ddd; border-radius: 6px; background: #f9f9f9;">
    <h3 style="margin-top: 0;">🎨 Theming</h3>
    <p>Theme switching uses a global state model — every style value comes from a central JS theme file.</p>
  </div>

  <div style="flex: 1 1 30%; padding: 1rem; border: 1px solid #ddd; border-radius: 6px; background: #f9f9f9;">
    <h3 style="margin-top: 0;">🧠 Code Highlighting</h3>
    <p>Render TS code blocks with inline tokenized spans — fully typed, styled, and engine-free.</p>
  </div>

</div>
