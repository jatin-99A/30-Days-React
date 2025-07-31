# Explanation of Key Concepts

### Cross-Origin
Cross-Origin refers to when a website loads resources (like images, scripts) from a different domain or origin than its own.

crossorigin="anonymous" It tells the browser to fetch the resource without sending credentials (like cookies or HTTP authentication), well we don't need to set it anonymous manually.

### CDN in HTML
A CDN (Content Delivery Network) is a network of servers that delivers web resources (such as scripts, stylesheets, libraries) quickly by allowing you to link them directly in your HTML.

### React CDN: Development vs Production
- **Development CDN:** This version of React is unminified and includes extra warnings and error messages to help with debugging during development.
- **Production CDN:** This version is minified and optimized for performance with a smaller file size, but it does not include debugging messages, making it ideal for live websites.