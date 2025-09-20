## Cloud Dashboard
An automatically updated dashboard that collects daily Azure updates from official Microsoft sources and presents them via GitHub Pages.
Website is available via: [https://cloud-dashboard.com](https://cloud-dashboard.com)

## Features

- 🔄 **Automatic updates**: Daily every 3 hours via GitHub Actions
- 📰 **Multiple sources**: Azure Updates, Azure Architecture Center, Azure Status
- 🔍 **Search functionality**: Filter updates by text and source
- 📱 **Responsive design**: Works on desktop and mobile
- 📊 **JSON API**: Updates available as JSON

## Sources

The dashboard collects updates from:

1. **Azure Updates** - Official Azure service updates - (Available)
   - URL: `https://www.microsoft.com/releasecommunications/api/v2/azure/rss`
   
2. **Azure Architecture Center** - New architecture guides and patterns - (Available)
   - URL: `https://learn.microsoft.com/en-us/azure/architecture/feed.atom`
  
3. **Azure Blog** - Newest blogs - (Available)
   - URL: `https://azure.microsoft.com/en-us/blog/feed/`
     
4. **Azure Status** - Service status and incident updates - (Currently working on)
   - URL: `https://azure.status.microsoft/status/feed/`
