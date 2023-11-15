# <Horiseon Marketing Agency Site Refactoring>

## Description

This project is focused on making Horiseon's marketing agency website meet accessibility standards, with the goal of helping the codebase follow up-to-date practices for search engine optimization and accessibility. The primary focus is updating the HTML and CSS structure while maintaining the appearance of the website. 

## Motivation 
I seek to restructure the codebase of the marketing agency's website to follow a coherent and logical semantic structure. I built this project to help learn the importance of clean HTML and CSS that not only makes the site more accessible and successful for search engine optimization (SEO), but also makes the codebase cleaner and more legible for other developers who would work on the website in the future.

## Problems Solved

 The project solves the issue of hard to read code by eliminating vague HTML tags with up-to-date semantic tags that easily communicate the structure of the page by highlighting the place in flow as well as function of each element within the website. The CSS file was also improved by limiting repeated code. The new HTML tags were appropriately matched to the CSS selectors to ensure the website remained visually identical to the original layout. CSS classes were used in place of attributes in order to make the site more adaptable to more specific individual adjustments if the site is to be built upon in the future.

## Lessons

This project taught me the importance of semantic HTML selectors to make websites more accessible by providing meaningful and clear element labels. This improved accessibility is intended to help visually impaired people as well as people with motor impairments who may use assistance technology in accessing the page. I've also learned how to refactor code carefully, one section at a time, to minimize the risk of breaking a page beyond an easy fix, with all steps able to be retraced. Whenever CSS values are repeated there will be a way to consolidate these into easier to read code free of redundancy.

## Implementation Details

### Semantic HTML

Semantic HTML tags `<header>`, `<nav>`, `<main>`, `<section>`, `<aside>`, and `<footer>` were utilized to replace the vague `<div>` tags in making a clearer, easier to navigate outline of the site's structure. 

### Accessible Alt Attributes for Images

Each image element was provided a clear and concise description to assist the visually impaired.

### Refactored CSS

The initial site had much redundancy in repeated attributes, so these were grouped into larger sections where the attributes only needed to be listed once, making the CSS file easier to navigate and contribute to for a future developer. It was crucial that the refactoring maintained the CSS file's successful linking to the appropriate HTML elements and classes.