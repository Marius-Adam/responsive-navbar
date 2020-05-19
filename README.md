# Responsive Navbar with SmoothScroll and Spy Scroll in vanilla JS.

![Responsive Navbar](README.png?raw=true "Responsive Navbar")

### <a href="https://marius-adam.github.io/local-storage-todo-list/">LIVE DEMO</a>

## Description

Inittially started this project as part of Learn Vanilla JavaScript Challange No #3. I decided to make it more challanging by implementing SmoothScroll and SpyScroll. I found multiple ways of achieving this and tried out a few methods to gain a better understanding on how they work.
I found Approach 3 (window.requestAnimationFrame()) to have the best browser compatibility.

## Functionality

Smooth Scroll

<ol>
  <li>Approach 1: window.scrollTo() - <a href="https://developer.mozilla.org/en-US/docs/Web/API/Window/scrollTo">MDN Docs</a></li>
  <li>Approach 2: element.scrollIntoView() - <a href="https://developer.mozilla.org/en-US/docs/Web/API/Element/scrollIntoView">MDN Docs</a></li>
  <li>Approach 3: window.requestAnimationFrame() - <a href="https://developer.mozilla.org/en-US/docs/Web/API/window/requestAnimationFrame">MDN Docs</a></li>
</ol>

ScrollSpy

<ol>
  <li>Intersection Observer API - <a href="https://developer.mozilla.org/en-US/docs/Web/API/Intersection_Observer_API">MDN Docs</a></li>
</ol>
