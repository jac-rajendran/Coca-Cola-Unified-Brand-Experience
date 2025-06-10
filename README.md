# 🥤 Coca-Cola Unified Brand Experience – UI/UX Prototype

<div align="center">
  <img src="https://media.giphy.com/media/v1.Y2lkPTc5MGI3NjExcDZ6dW5oM2J2eXl4Z3VxZ3Q0eGJtY2J6bWJlcG5wZ2V5bWZkZ2F0biZlcD12MV9pbnRlcm5hbF9naWZfYnlfaWQmY3Q9Zw/xT5LMHxhOfscxPfIfm/giphy.gif" width="400" alt="Coca-Cola animation">
</div>

A UI/UX case study that reimagines the digital presence of Coca-Cola and its sub-brands with **fluid animations** and a unified design system.

---

## ✨ Animated Features Preview

| Component | Animation |
|-----------|-----------|
| Navigation | Smooth color morphing between brands |
| Bottle Display | 3D rotation on hover |
| Theme Toggle | Liquid transition between light/dark modes |
| Flavor Selector | Bubble effect when changing options |

```html
<!-- Example animation code snippet -->
<div class="coke-bottle">
  <img src="bottle.png" class="hover-rotate">
</div>

<style>
  .hover-rotate {
    transition: transform 0.5s ease-in-out;
  }
  .hover-rotate:hover {
    transform: rotateY(20deg);
  }
</style>

