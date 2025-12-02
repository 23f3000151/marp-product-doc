<!-- marp: true -->
<!-- theme: custom -->
<!-- paginate: true -->
<!-- header: "Product Docs — v1.0" -->
<!-- footer: "23f3000151@ds.study.iitm.ac.in — Page $slide$ of $pages$" -->

---
title: Product Documentation
author: 23f3000151@ds.study.iitm.ac.in
marp: true
---

<!-- Custom Theme -->
<style>
section {
  font-family: "Segoe UI", sans-serif;
  letter-spacing: 0.3px;
}
h1 { color: #0a84ff; }
h2 { color: #004c99; }
.bigbox {
  background: #1a1a1a;
  color: white;
  padding: 25px;
  border-radius: 12px;
  box-shadow: 0 0 10px rgba(0,0,0,0.4);
}
</style>

# Product Documentation  
**Author:** 23f3000151@ds.study.iitm.ac.in**

This deck demonstrates a fully customized Marp presentation with:

- Custom theme  
- Page numbers  
- Math equations  
- Background images  
- Styled components  

---

# Overview

- Git-friendly markdown docs  
- Marp for slide generation  
- Custom CSS theme  
- Math notation  
- Background images  
- Architecture diagrams (optional)

---

# Algorithmic Complexity

The time complexity of Merge Sort is:

$$
T(n) = 2T(n/2) + O(n)
$$

Which simplifies to:

$$
O(n \log n)
$$

---

<!-- _background: "https://images.unsplash.com/photo-1504384308090-c894fdcc538d" -->

# Background Image Slide  
### (Requirement: at least one slide with a background image ✔)

- API Gateway  
- Compute Engine  
- Storage Layer  

---

# Architecture Overview

```mermaid
graph LR
 A[Client] --> B[API Gateway]
 B --> C[Compute Engine]
 C --> D[Storage Layer]
