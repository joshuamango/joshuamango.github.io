---
# Feel free to add content and custom Front Matter to this file.
# To modify the layout, see https://jekyllrb.com/docs/themes/#overriding-theme-defaults

layout: home
---

<style>
  .social-button {
    display: inline-flex;
    align-items: center;
    justify-content: center;
    padding: 0.5rem;
    border: 1px solid #e1e4e8;
    border-radius: 6px;
    background-color: #fafbfc;
    transition: all 0.2s ease;
    box-shadow: 0 1px 0 rgba(27,31,35,0.04);
    width: 24px;
    height: 24px;
  }

  .social-button:hover {
    background-color: #f3f4f6;
    border-color: #d1d5da;
    text-decoration: none;
    transform: translateY(-2px);
    box-shadow: 0 4px 8px rgba(0,0,0,0.05);
  }

  .social-button:active {
    background-color: #edeff2;
    box-shadow: inset 0 0.15em 0.3em rgba(27,31,35,0.15);
    transform: translateY(0);
  }

  .social-button .svg-icon {
    fill: #24292e;
    display: block;
    padding: 0;
    margin: 0;
  }
</style>

I'm **Joshua**, a **software engineer** who enjoys building and maintaining
*scalable* applications that create *simple* yet *elegant* experiences for end
users.
<div style="display: flex; gap: 1rem; margin-top: 2rem;">
  <a href="https://www.linkedin.com/in/joshua-odeyemi-88296715b" aria-label="LinkedIn" class="social-button">
    <svg class="svg-icon"><use xlink:href="{{ '/assets/minima-social-icons.svg#linkedin' | relative_url }}"></use></svg>
  </a>
  <a href="https://www.github.com/joshuamango" aria-label="GitHub" class="social-button">
    <svg class="svg-icon"><use xlink:href="{{ '/assets/minima-social-icons.svg#github' | relative_url }}"></use></svg>
  </a>
  <a href="https://stackoverflow.com/users/11262557/joshuamango" aria-label="Stack Overflow" class="social-button">
    <svg class="svg-icon"><use xlink:href="{{ '/assets/minima-social-icons.svg#stackoverflow' | relative_url }}"></use></svg>
  </a>
</div>
