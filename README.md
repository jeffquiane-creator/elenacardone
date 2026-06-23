# Resources

Drop the companion PDFs from the Build An Empire real estate series here (e.g. `listing-presentation-playbook.pdf`). Then in `index.html`, swap each "Coming Soon" resource card's `<span class="res-link disabled">` for:

```html
<a href="resources/your-file.pdf" class="res-link" target="_blank">
  <span>Download PDF</span><span class="arrow">→</span>
</a>
```

and remove the `<div class="resource-status">Coming Soon</div>` line.
