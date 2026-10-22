```html
---
layout: default
---

<style>
/* General text */
body {
  font-size: 19px;
  line-height: 1.8;
}

/* Main title */
h1 {
  font-size: 44px !important;
  color: #88c0d0 !important;
  letter-spacing: 1px;
  margin-bottom: 12px;
}

/* Section headings */
h2 {
  font-size: 29px !important;
  color: #a3be8c !important;
  border-bottom: 1px solid #4c566a;
  padding-bottom: 8px;
  margin-top: 38px;
}

/* Links */
a {
  color: #88c0d0;
}

a:hover {
  color: #b48ead;
}

/* About section */
.about-section {
  display: flex;
  align-items: center;
  gap: 35px;
  margin-top: 25px;
}

.about-text {
  flex: 1;
  min-width: 0;
}

.about-photo {
  width: 230px;
  max-width: 35%;
  height: auto;
  border-radius: 15px;
  object-fit: cover;
}

/* Lists */
li {
  margin-bottom: 8px;
}

/* Mobile layout */
@media (max-width: 650px) {
  .about-section {
    flex-direction: column-reverse;
    align-items: flex-start;
  }

  .about-photo {
    width: 220px;
    max-width: 100%;
    align-self: center;
  }

  h1 {
    font-size: 34px !important;
  }
}
</style>

# Nimrod Dushnik Shamir

*MSc Student | Brain Sciences | Weizmann Institute of Science*

<div class="about-section">
  <div class="about-text">
    <h2>About Me</h2>

    <p>
      My name is <strong>Nimrod Dushnik Shamir</strong>.
      I am an MSc student in
      <a href="https://www.weizmann.ac.il/brain-sciences/labs/livneh/">
      Yoav Livneh's lab</a>.
    </p>

    <p>
      My research focuses on the role of
      <strong>intestinal signals</strong> in
      interoception and behavior.
    </p>
  </div>

  <img
    class="about-photo"
    src="/pic.jpg"
    alt="Portrait of Nimrod Dushnik Shamir">
</div>

## Research Interests

- Brain and behavior
- Brain–body axis
- Interoception

## My Goals for the Course

1. Understand the basics of coding in Python.
2. Learn the fundamentals of using GitHub.
3. Practice writing code and debugging.
4. Explore how these tools can support my research.

## Find Me Online

[**My GitHub Profile →**](https://github.com/nimrodushnik)
```
