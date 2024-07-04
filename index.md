# My Simple Web App

Welcome to my simple web app. Below is a list of items.

## List of Items

- Item 1
- Item 2
- Item 3
- Item 4

## Counter

<div id="counter">Number of items: 0</div>

<script>
  // JavaScript to count the list items
  document.addEventListener('DOMContentLoaded', (event) => {
    const itemCount = document.querySelectorAll('ul li').length;
    document.getElementById('counter').textContent = 'Number of items: ' + itemCount;
  });
</script>
