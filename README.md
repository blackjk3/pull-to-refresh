# pull-to-refresh
A simple pull-to-refresh library that uses css3 transforms and a rAF loop for smooth animations.

# Usage
```javascript

// Basic usage
new PullToRefresh(options, callback);

// Options
options.el - The pull to refresh element selector
options.scrollEl - The container that needs to scroll selector
options.offset - If there is a fixed header you can set an offset.

// Example
new PullToRefresh({ el: '.pull-to-refresh', scrollEl: '.table-container', offset: 50 }, callback);
```

# Pull to Refresh Template
```html
<div class="pull-to-refresh">
  <div class="rband">
    <i class="icon-refresh"></i> <span class="text">Pull to refresh...</span>
  </div>
</div>
```