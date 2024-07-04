# My Simple Web App

Welcome to my simple web app. Below is a list of items.

## List of Items

<ul id="item-list">
  <li>Item 1</li>
  <li>Item 3</li>
  <li>Item 3</li>
  <li>Item 3</li>
  <li>Item 3</li>
</ul>

## Counter

<script>
  // JavaScript to count the list items
  document.addEventListener('DOMContentLoaded', (event) => {
    const itemCount = document.querySelectorAll('#item-list li').length;
    document.getElementById('counter').textContent = 'Number of items: ' + itemCount;

