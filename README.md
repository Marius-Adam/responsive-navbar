# Vanilla JS Responsive Nav with Smooth Scroll + Spy Scroll

![Responsive Navbar](README.png?raw=true "Responsive Navbar")

### <a href="https://marius-adam.github.io/responsive-navbar/">LIVE DEMO</a>

## Description

Inittially started this project as part of Learn Vanilla JavaScript Challange No #3. I decided to make it more challanging by implementing SmoothScroll and SpyScroll. I found multiple ways of achieving this and tried out a few methods to gain a better understanding on how they work.
I found Approach 3 (window.requestAnimationFrame()) to have the best browser compatibility.

## Functionality

<strong>Smooth Scroll</stron>

<ul>
  <li>Approach 1: window.scrollTo() - Scrolls to a particular set of coordinates in the document -- <a href="https://developer.mozilla.org/en-US/docs/Web/API/Window/scrollTo">MDN Docs</a> </li>
  <br>
  <li>Approach 2: element.scrollIntoView() - Scrolls the element's parent container such that the element on which scrollIntoView() is called is visible to the user -- <a href="https://developer.mozilla.org/en-US/docs/Web/API/Element/scrollIntoView">MDN Docs</a></li>
  <br>
  <li>Approach 3: window.requestAnimationFrame() - Tells the browser that you wish to perform an animation and requests that the browser calls a specified function to update an animation before the next repaint. The method takes a callback as an argument to be invoked before the repaint -- <a href="https://developer.mozilla.org/en-US/docs/Web/API/window/requestAnimationFrame">MDN Docs</a></li>
</ul>

<strong>ScrollSpy</strong>

<ol>
  <li>Intersection Observer API - The Intersection Observer API provides a way to asynchronously observe changes in the intersection of a target element with an ancestor element or with a top-level document's viewport -- <a href="https://developer.mozilla.org/en-US/docs/Web/API/Intersection_Observer_API">MDN Docs</a></li>
</ol>
