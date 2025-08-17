---
marp: true
theme: pink
style: |
  .columns {
    display: grid;
    grid-template-columns: repeat(var(--cols, 2), minmax(0, 1fr));
    gap: 1rem;
  }
  .full-bleed {
    position: absolute;
    top: 0;
    left: 0;
    right: 0;
    bottom: 0;
    margin: 0;
    padding: 0;
  }
  .full-bleed img {
    width: 100%;
    height: 100%;
    object-fit: cover; /* scale without distortion */
    border-radius: 0;  /* remove rounded corners */
    box-shadow: none;  /* remove shadows if you want */
  }
  .border-and-shadow {
    border-radius: 12px;
    box-shadow: 2px 4px 12px rgba(0,0,0,0.8);
  }
---

# How to add a slide with different background color

---

<!-- class: pink-slide -->

# White text on pink
This slide has a pink background with white text.


---

<!-- class: default-slide -->

# And now we go back to the original style