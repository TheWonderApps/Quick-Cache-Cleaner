# Quick Cache Cleaner - Chrome Extension

<div align="center">

![Quick Cache Cleaner Logo](assets/icons/icon128.png)

**🧹 Optimize your browsing experience with intelligent cache management**

[![Chrome Web Store](https://img.shields.io/badge/Chrome%20Web%20Store-Quick%20Cache%20Cleaner-blue?style=for-the-badge&logo=google-chrome)](https://chrome.google.com/webstore)
[![Version](https://img.shields.io/badge/version-1.0.0-green?style=for-the-badge)](https://github.com/TheWonderApps/QuickCacheCleaner)
[![License](https://img.shields.io/badge/license-MIT-orange?style=for-the-badge)](LICENSE)

</div>

## 📋 Table of Contents

- [Overview](#-overview)
- [Features](#-features)
- [Installation](#-installation)
- [Getting Started](#-getting-started)
- [User Interface Guide](#-user-interface-guide)
- [How to Use](#-how-to-use)
- [Keyboard Shortcuts](#-keyboard-shortcuts)
- [Advanced Features](#-advanced-features)
- [Settings & Configuration](#-settings--configuration)
- [Privacy & Security](#-privacy--security)
- [Troubleshooting](#-troubleshooting)
- [Technical Details](#-technical-details)
- [Support](#-support)

## 🚀 Overview

**Quick Cache Cleaner** is a powerful Chrome extension designed to optimize your browsing experience by efficiently managing and clearing browser data. With its intuitive side panel interface, real-time storage analysis, and smart automation features, it helps users maintain optimal browser performance while protecting their privacy.

### 🎯 Why Choose Quick Cache Cleaner?

- **🔍 Real-time Analysis** - See exactly what's taking up space in your browser
- **🎛️ Granular Control** - Choose exactly what to clean and what to keep
- **⚡ Smart Automation** - Set up automatic cleaning schedules
- **🛡️ Privacy Focused** - No data collection, everything stays local
- **🎨 Modern Interface** - Beautiful, intuitive side panel design
- **⌨️ Keyboard Shortcuts** - Power user features for quick access

## ✨ Features

### 🗄️ **Comprehensive Data Clearing**

- **Browser Cache** - Remove stored web files, images, and scripts
- **Cookies** - Clear session and persistent cookies
- **Browsing History** - Delete visited page records and timestamps
- **Form Data** - Remove autofill entries and form history
- **Local Storage** - Clear website data storage (localStorage)
- **Session Storage** - Remove temporary session data
- **IndexedDB** - Clear advanced web databases
- **WebSQL** - Remove legacy database storage
- **Service Workers** - Clear background scripts cache

### 📊 **Real-Time Storage Analysis**

- **Live Data Monitoring** - See exactly how much space each data type uses
- **Visual Charts** - Beautiful donut charts showing storage breakdown
- **Detailed Statistics** - Precise byte counts and percentages
- **Before/After Comparison** - Track space freed after cleaning
- **Category Breakdown** - Organized view of different data types

### ⚡ **Smart Automation**

- **Scheduled Cleaning** - Set automatic clearing at intervals (hourly, daily, weekly)
- **Idle Detection** - Clean when browser is not in use
- **Custom Rules** - Create personalized automation settings
- **Quick Actions** - One-click clearing with saved preferences
- **Smart Notifications** - Get notified when cleaning is complete

### 🎛️ **Advanced Controls**

- **Selective Clearing** - Choose exactly what to clean with checkboxes
- **Time-Based Filtering** - Clear data from specific time ranges
- **Domain Protection** - Exclude important sites from clearing
- **Backup & Restore** - Save and restore extension settings
- **Import/Export** - Share configurations between devices

## 🔧 Installation

### From Chrome Web Store (Recommended)

1. Visit the [Chrome Web Store page](https://chrome.google.com/webstore)
2. Search for "Quick Cache Cleaner"
3. Click **"Add to Chrome"**
4. Click **"Add extension"** to confirm
5. Grant necessary permissions when prompted

### Manual Installation (Developer Mode)

1. Download the latest release from [GitHub Releases](https://github.com/TheWonderApps/QuickCacheCleaner/releases)
2. Open Chrome and go to `chrome://extensions/`
3. Enable **"Developer mode"** in the top right
4. Click **"Load unpacked"** and select the extension folder
5. The extension will appear in your toolbar

### Required Permissions

The extension requests these permissions for core functionality:

- **`browsingData`** - Clear cache, cookies, history, and other browser data
- **`storage`** - Save user preferences and settings
- **`tabs`** - Manage side panel and get current tab info
- **`alarms`** - Schedule automatic cleaning operations
- **`idle`** - Detect when browser is idle for smart cleaning
- **`sidePanel`** - Display the main interface in the side panel
- **`notifications`** - Show completion notifications

## 🚀 Getting Started

### First Launch

1. **Open Side Panel** - Click the extension icon in your toolbar or press `Ctrl+Shift+C`
2. **Review Current Data** - The dashboard shows your current browser storage usage
3. **Explore Categories** - Click on different data types to see what can be cleared
4. **Perform First Clean** - Select items you want to clear and click the "Clear Selected" button

### Quick Start Guide

```
Step 1: Install Extension → Step 2: Open Side Panel → Step 3: Review Data → Step 4: Start Cleaning
```

## 📱 User Interface Guide

### 🏠 **Main Dashboard**

```
┌─────────────────────────────────────┐
│ 🧹 Quick Cache Cleaner     🔄       │
├─────────────────────────────────────┤
│                                     │
│  📊 Total Clearable: 127.3 MB      │
│                                     │
│  ┌───────────────────────────────┐  │
│  │     📈 Storage Breakdown     │  │
│  │   Cache: 45.2 MB (35.5%)     │  │
│  │   Cookies: 12.8 MB (10.1%)   │  │
│  │   History: 8.1 MB (6.4%)     │  │
│  │   Other: 61.2 MB (48.0%)     │  │
│  └───────────────────────────────┘  │
│                                     │
│  [ ] Cache          [Clear Cache]   │
│  [ ] Cookies        [Clear Cookies] │
│  [ ] History        [Clear History] │
│  [ ] Form Data      [Clear Forms]   │
│                                     │
│  [Select All] [Clear Selected]     │
│                                     │
│  ⚙️ Settings | 📊 Analytics         │
└─────────────────────────────────────┘
```

### 📊 **Storage Analysis Section**

- **Total Storage Display** - Shows combined size of all clearable data
- **Category Breakdown** - Visual representation with donut charts
- **Individual Counters** - Specific sizes for each data type
- **Real-time Updates** - Data refreshes automatically

### 🎛️ **Control Panel**

- **Category Checkboxes** - Select/deselect individual data types
- **Bulk Controls** - "Select All" and "Clear All" buttons
- **Individual Actions** - Quick clear buttons for each category
- **Advanced Options** - Time range and domain filters

### ⚙️ **Settings Panel**

- **Automation Rules** - Configure scheduled cleaning
- **Notifications** - Control clearing alerts and feedback
- **Protected Domains** - Whitelist important sites
- **Backup/Restore** - Import/export configuration

## 🎯 How to Use

### 🧹 **Basic Cleaning**

1. **Open the Extension**

   - Click the extension icon in your toolbar
   - Or press `Ctrl+Shift+C` (Windows/Linux) or `Cmd+Shift+C` (Mac)

2. **Review Available Data**

   - The dashboard shows your current browser storage usage
   - Each category displays its size and impact

3. **Select Items to Clear**

   - Check the boxes next to data types you want to remove
   - Use "Select All" for comprehensive cleaning

4. **Execute Cleaning**

   - Click "Clear Selected" to start the process
   - Watch the progress indicator during cleaning

5. **Review Results**
   - See confirmation message with space freed
   - Updated storage counters reflect the changes

### ⏰ **Setting Up Automation**

1. **Access Settings**

   - Click the gear icon (⚙️) in the side panel
   - Navigate to the "Automation" section

2. **Enable Automatic Cleaning**

   - Toggle on "Scheduled Cleaning"
   - Choose frequency: Hourly, Daily, Weekly, or Custom

3. **Configure What to Clean**

   - Select which data types to include in automatic cleaning
   - Set time ranges if needed

4. **Idle Cleaning (Optional)**

   - Enable "Clean on Idle" for smart cleaning
   - Set idle time threshold (default: 15 minutes)

5. **Save Settings**
   - Click "Save" to confirm your automation preferences

### 🛡️ **Protecting Important Sites**

1. **Open Settings**

   - Go to Settings → Protected Domains

2. **Add Sites to Whitelist**

   ```
   Examples:
   • gmail.com (protects Google Mail)
   • github.com (protects GitHub sessions)
   • mybank.com (protects banking cookies)
   ```

3. **Configure Protection Level**

   - **Cookies Only** - Protect cookies but allow cache clearing
   - **All Data** - Protect all data types for the domain
   - **Subdomains** - Include/exclude subdomains

4. **Test Protection**
   - Perform a test cleaning to verify protected sites remain intact

### 📈 **Monitoring Usage**

1. **Daily Monitoring**

   - Check the dashboard regularly for storage trends
   - Use the refresh button to update data

2. **Review Cleaning History**

   - View last cleared timestamp
   - See amount of data cleared in recent operations

3. **Analyze Patterns**
   - Identify which sites generate the most data
   - Adjust automation frequency based on usage

## ⌨️ Keyboard Shortcuts

| Shortcut            | Action           | Description                             |
| ------------------- | ---------------- | --------------------------------------- |
| `Ctrl+Shift+C`      | Open Side Panel  | Launch the main interface               |
| `Ctrl+Shift+Delete` | Quick Clear      | Instant clearing with saved preferences |
| `Escape`            | Close Panel      | Hide the side panel                     |
| `Tab`               | Navigate         | Move through interface elements         |
| `Space`             | Toggle Selection | Toggle checkbox for focused item        |
| `Enter`             | Activate Button  | Click the focused button                |

### Customizing Shortcuts

1. Go to `chrome://extensions/shortcuts`
2. Find "Quick Cache Cleaner"
3. Modify shortcuts to your preference

## 🔧 Advanced Features

### 📅 **Time-Based Clearing**

Choose specific time ranges for targeted cleaning:

- **Last Hour** - Remove only data from the past hour
- **Last Day** - Clear data from the past 24 hours
- **Last Week** - Remove data from the past 7 days
- **Last Month** - Clear data from the past 30 days
- **All Time** - Remove everything (default)
- **Custom Range** - Set specific start and end dates

**Example Use Cases:**

- Clear only recent browsing for privacy
- Remove old data while keeping recent sessions
- Targeted cleaning after visiting specific sites

### 🌐 **Domain Management**

Advanced domain filtering options:

**Whitelist Protection (Recommended)**

```
Protected Domains:
✅ gmail.com
✅ github.com
✅ mybank.com
✅ work-site.com
```

**Blacklist Targeting**

```
Only Clear These Domains:
❌ ads-tracking.com
❌ social-media.com
❌ temp-site.com
```

**Wildcard Support**

```
Patterns:
• *.google.com (all Google services)
• *facebook* (anything with "facebook")
• test-*.com (all test domains)
```

### 🔄 **Backup & Sync**

**Export Settings**

1. Go to Settings → Backup
2. Click "Export Configuration"
3. Save the `.json` file to your computer

**Import Settings**

1. Go to Settings → Backup
2. Click "Import Configuration"
3. Select your saved `.json` file

**Cloud Sync** (Chrome Sync)

- Settings automatically sync across Chrome browsers
- Sign in to Chrome for cross-device synchronization

### 📊 **Analytics & Reporting**

**Storage Trends**

- Track storage growth over time
- Identify problem sites and data types
- Monitor cleaning effectiveness

**Cleaning Reports**

- See detailed logs of cleaning operations
- Export reports for analysis
- Track storage saved over time

## ⚙️ Settings & Configuration

### 🔧 **General Settings**

**Interface Preferences**

- **Theme** - Light, Dark, or Auto (follows system)
- **Language** - Choose your preferred language
- **Animations** - Enable/disable UI animations
- **Sound Effects** - Toggle notification sounds

**Data Display**

- **Units** - Bytes, KB, MB, or Auto
- **Precision** - Decimal places for size display
- **Chart Type** - Donut, Bar, or List view

### 🔔 **Notification Settings**

**Cleaning Notifications**

- **On Completion** - Show when cleaning finishes
- **On Schedule** - Alert before automatic cleaning
- **On Errors** - Notify if cleaning fails

**Notification Types**

- **Browser Notifications** - System notifications
- **In-Panel Alerts** - Messages within the extension
- **Sound Alerts** - Audio feedback

### 🛡️ **Privacy Settings**

**Data Handling**

- **Local Storage Only** - All data stays on your device
- **No Telemetry** - No usage data is collected
- **Secure Storage** - Settings encrypted by Chrome

**Permission Management**

- **Review Permissions** - See what the extension can access
- **Revoke Access** - Disable specific permissions if needed

### 🔒 **Security Settings**

**Protection Features**

- **Confirmation Dialogs** - Require confirmation for large cleanings
- **Undo Prevention** - Warning for irreversible actions
- **Safe Mode** - Extra protections for important data

## 🔒 Privacy & Security

### 🛡️ **Privacy First Design**

**No Data Collection**

- ❌ No usage analytics or telemetry
- ❌ No personal data sent to external servers
- ❌ No tracking or user profiling
- ✅ Everything operates locally on your device

**Transparent Operation**

- 🔍 Open source code available for review
- 📋 Clear explanation of all permissions
- 🔒 Minimal permission requests
- 🛡️ Secure data storage using Chrome's encrypted APIs

### 🔐 **Security Features**

**Data Protection**

- **Encryption** - Settings stored using Chrome's secure storage
- **Local Processing** - All operations happen on your device
- **No Network Access** - Extension works completely offline
- **Sandboxed Execution** - Runs in Chrome's secure environment

**Permission Security**

```
✅ browsingData - Clear browser data (core function)
✅ storage - Save user preferences securely
✅ tabs - Manage side panel interface
✅ alarms - Schedule cleaning operations
✅ idle - Detect browser inactivity
✅ sidePanel - Display main interface
✅ notifications - Show completion alerts

❌ NO access to:
   • Your personal files
   • Other extensions
   • Website content
   • Network requests
   • System data
```

### 🔍 **What Data is Accessed**

**Browser Data (for cleaning only)**

- Cache files and images
- Cookies and site data
- Browsing history entries
- Form autofill data
- Local storage contents

**Settings Data (stored locally)**

- Your preferences and configuration
- Protected domains list
- Automation rules
- Interface customizations

**The extension NEVER:**

- Sends data to external servers
- Shares information with third parties
- Tracks your browsing habits
- Stores personal information

## 🛠️ Troubleshooting

### ❓ **Common Issues**

**Extension Not Showing Data**

```
Problem: Storage counters show zero or outdated information
Solutions:
✅ Click the refresh button (🔄) in the top right
✅ Close and reopen the side panel
✅ Reload the current browser tab
✅ Restart Chrome browser
```

**Clearing Not Working**

```
Problem: Clear operations fail or don't seem to work
Solutions:
✅ Check extension permissions in chrome://extensions/
✅ Ensure no other cleaning tools are running
✅ Try clearing smaller amounts at a time
✅ Restart Chrome and try again
```

**Protected Sites Being Cleared**

```
Problem: Whitelisted domains are still being cleared
Solutions:
✅ Verify domain format (use "example.com", not "https://example.com")
✅ Check if subdomains need separate entries
✅ Test with a single domain first
✅ Review protection settings in Settings panel
```

**Automation Not Running**

```
Problem: Scheduled cleaning doesn't happen automatically
Solutions:
✅ Verify alarms permission is granted
✅ Check that Chrome is running (not just tabs)
✅ Ensure computer isn't in sleep mode during scheduled time
✅ Test with shorter intervals first
```

**Side Panel Won't Open**

```
Problem: Clicking extension icon doesn't show side panel
Solutions:
✅ Try the keyboard shortcut (Ctrl+Shift+C)
✅ Right-click extension icon and select "Open side panel"
✅ Check if Chrome supports side panels (version 88+)
✅ Disable and re-enable the extension
```

### 🔍 **Diagnostic Tools**

**Built-in Diagnostics**

1. **Refresh Data** - Updates all storage counters
2. **Test Connection** - Verifies extension functionality
3. **Reset Settings** - Returns to default configuration
4. **Clear Extension Data** - Removes all user preferences

**Chrome Developer Tools**

1. Open `chrome://extensions/`
2. Find "Quick Cache Cleaner"
3. Click "Inspect views: side panel"
4. Check Console for error messages

**Manual Testing**

```
Test Checklist:
□ Extension icon appears in toolbar
□ Side panel opens when clicked
□ Storage data displays correctly
□ Clearing operations work
□ Settings save properly
□ Notifications appear
□ Keyboard shortcuts function
```

### 📞 **Getting Help**

**Self-Help Resources**

- 📖 This user manual
- ❓ In-app help tooltips
- 🔧 Built-in diagnostic tools
- 📋 Chrome extension troubleshooting guides

**Community Support**

- 🐛 [GitHub Issues](https://github.com/TheWonderApps/QuickCacheCleaner/issues) - Report bugs
- 💬 [Discussions](https://github.com/TheWonderApps/QuickCacheCleaner/discussions) - Ask questions
- ⭐ [Chrome Web Store Reviews](https://chrome.google.com/webstore) - Leave feedback

## 💻 Technical Details

### 🔧 **System Requirements**

**Minimum Requirements**

- **Browser** - Chrome 88+ (Manifest V3 support)
- **Memory** - 50 MB available RAM
- **Storage** - 5 MB free disk space
- **Network** - None required (works offline)

**Recommended**

- **Browser** - Chrome 100+ (latest features)
- **Memory** - 100+ MB available RAM
- **Storage** - 10+ MB free disk space

### 🏗️ **Technical Architecture**

**Extension Structure**

```
Quick Cache Cleaner/
├── manifest.json (Extension configuration)
├── src/
│   ├── background/
│   │   └── service-worker.js (Background processes)
│   ├── sidepanel/
│   │   ├── sidepanel.html (Main interface)
│   │   ├── sidepanel.js (UI logic)
│   │   └── styles.css (Visual styling)
│   └── shared/
│       ├── utils.js (Common utilities)
│       ├── storage-analyzer.js (Data analysis)
│       └── chart-renderer.js (Visual charts)
└── assets/
    └── icons/ (Extension icons)
```

**Key Technologies**

- **Manifest V3** - Latest Chrome extension standard
- **Service Workers** - Background processing
- **Side Panel API** - Modern UI framework
- **Chrome Storage API** - Secure settings storage
- **Browser Data API** - Core cleaning functionality

### 📊 **Performance Specifications**

**Memory Usage**

- **Idle** - ~5-10 MB RAM
- **Active Cleaning** - ~15-25 MB RAM
- **Peak Usage** - ~30 MB RAM (large cleanings)

**Storage Impact**

- **Extension Size** - ~2 MB installed
- **Settings Data** - ~50 KB maximum
- **Cache** - Minimal (cleared regularly)

**Processing Speed**

- **Small Cleanings** - < 1 second (< 10 MB)
- **Medium Cleanings** - 1-5 seconds (10-100 MB)
- **Large Cleanings** - 5-30 seconds (100+ MB)

### 🔌 **API Dependencies**

**Chrome APIs Used**

```javascript
chrome.browsingData; // Core cleaning functionality
chrome.storage; // Settings and preferences
chrome.tabs; // Side panel management
chrome.alarms; // Scheduled operations
chrome.idle; // Inactivity detection
chrome.sidePanel; // Main user interface
chrome.notifications; // User feedback
```

**No External Dependencies**

- ✅ No third-party libraries
- ✅ No external API calls
- ✅ No network requirements
- ✅ Completely self-contained

## 📞 Support

### 🆘 **Getting Help**

**Documentation**

- 📖 **User Manual** - This comprehensive guide
- 🔧 **Setup Guide** - Installation and configuration
- ❓ **FAQ** - Frequently asked questions
- 🎥 **Video Tutorials** - Visual guides (coming soon)

**Community Support**

- 💬 **GitHub Discussions** - Ask questions and share tips
- 🐛 **Issue Tracker** - Report bugs and request features
- ⭐ **Reviews** - Share feedback on Chrome Web Store

### 🔄 **Updates & Maintenance**

**Automatic Updates**

- Chrome automatically updates extensions
- New features and fixes delivered seamlessly
- Notification of major updates

**Release Schedule**

- 🐛 **Bug Fixes** - As needed
- ✨ **Minor Features** - Monthly
- 🚀 **Major Updates** - Quarterly

**What's Coming**

- 📊 Enhanced analytics and reporting
- 🎨 Additional themes and customization
- 🔧 More automation options
- 🌐 Multi-language support

### 🤝 **Contributing**

**How to Contribute**

- 🐛 Report bugs and issues
- 💡 Suggest new features
- 📝 Improve documentation
- 🔧 Submit code improvements
- ⭐ Leave positive reviews

**Development**

- 📋 [Contributing Guidelines](CONTRIBUTING.md)
- 🔧 [Development Setup](docs/DEVELOPMENT.md)
- 📝 [Code Style Guide](docs/STYLE.md)

---

## 📜 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 🙏 Acknowledgments

- Chrome Extension APIs and documentation
- User feedback and feature requests
- Open source community contributions

---

<div align="center">

**Quick Cache Cleaner v1.0.0**

_Made with ❤️ for a faster, cleaner web experience_

[⬆️ Back to Top](#quick-cache-cleaner---chrome-extension)

</div>
- **Smart categorization** of cache data (images, scripts, stylesheets)
- **Domain-specific clearing** for targeted cleanup

### ⏰ Time Range Options

- Preset ranges: Last hour, 4 hours, 1 day, 1 week, 4 weeks, all time
- Custom date/time range picker
- Quick filters for common scenarios

### 🎯 Domain Controls

- Clear data for active tab only
- Advanced whitelist/blacklist management
- Regex support for advanced filtering
- Category-based protection (banking, work, social)

### 🤖 Smart Automation

- **Scheduled clearing** (hourly/daily/weekly/custom)
- **Threshold triggers** (clear when cache > X MB)
- **Performance-based triggers** (clear on slow page load)
- **Idle-time clearing** (clear after inactivity)

### 📊 Analytics & Monitoring

- Real-time storage usage metrics
- Interactive visualizations (pie charts, timelines)
- Before/after comparison views
- Weekly/monthly usage reports
- Performance impact tracking

### 🔒 Security & Privacy

- Minimum necessary permissions
- GDPR/CCPA compliance
- Secure deletion protocols
- Audit logging for enterprise users

### 🎨 Modern UI/UX

- **Chrome Side Panel** integration
- Dark/light theme with system sync
- Responsive design optimized for side panel
- Accessibility compliance (WCAG 2.1 AA)
- Keyboard navigation support

## Installation

1. Download or clone this repository
2. Open Chrome and navigate to `chrome://extensions/`
3. Enable "Developer mode" in the top right
4. Click "Load unpacked" and select the extension directory
5. The QuickCache Cleaner icon will appear in your Chrome toolbar

## Usage

### Opening the Side Panel

- Click the extension icon in the toolbar
- Use keyboard shortcut: `Ctrl+Shift+C` (Windows/Linux) or `Cmd+Shift+C` (Mac)
- The side panel will open showing the main interface

### Quick Clear

- Click "Quick Clear All" for instant cache clearing
- Use keyboard shortcut: `Ctrl+Shift+Delete` for quick access
- Customize quick clear options in settings

### Custom Clearing

1. Select desired data categories using toggles
2. Choose time range (last hour, day, week, etc.)
3. Set domain scope (all domains, current tab, or custom)
4. Click "Clear Selected Data"

### Automation Setup

1. Open Settings → Automation
2. Enable automation features
3. Configure triggers:
   - **Schedule**: Set specific times/intervals
   - **Threshold**: Clear when storage exceeds limit
   - **Idle**: Clear during browser inactivity

### Analytics Dashboard

- View storage breakdown by category
- Monitor trends over time
- Get cleanup recommendations
- Track cleaning history and statistics

## File Structure

```
QuickCacheCleaner/
├── manifest.json                 # Extension manifest
├── src/
│   ├── background/
│   │   └── service-worker.js     # Background service worker
│   ├── sidepanel/
│   │   ├── sidepanel.html        # Main UI
│   │   ├── sidepanel.js          # UI logic
│   │   └── styles.css            # Side panel styles
│   └── shared/
│       ├── common.css            # Shared styles and variables
│       ├── utils.js              # Utility functions
│       ├── storage-analyzer.js   # Storage analysis engine
│       └── chart-renderer.js     # Chart rendering
└── assets/
    └── icons/                    # Extension icons
```

## Permissions

The extension requests the following permissions:

- `browsingData`: Clear browser data
- `storage`: Save settings and analytics
- `tabs`: Get current tab information
- `activeTab`: Access current tab for domain-specific clearing
- `alarms`: Schedule automated clearing
- `idle`: Detect browser idle state
- `sidePanel`: Use Chrome's side panel API

## Configuration

### Settings Structure

```javascript
{
  theme: 'system',              // 'light', 'dark', 'system'
  autoBackup: true,             // Backup before clearing
  confirmBeforeClear: true,     // Show confirmation dialog
  showNotifications: true,      // Show success/error notifications
  quickClearOptions: {
    cache: true,
    cookies: true,
    history: false,
    formData: false,
    passwords: false
  },
  automation: {
    enabled: false,
    triggers: [],               // Automation rules
    schedule: null
  },
  whitelist: [],                // Protected domains
  analytics: {
    enabled: true,
    trackUsage: true
  }
}
```

### Automation Triggers

```javascript
{
  id: 'unique-id',
  type: 'schedule',             // 'schedule', 'threshold', 'idle'
  options: {                    // What to clear
    cache: true,
    cookies: false,
    // ...
  },
  schedule: {
    type: 'daily',              // 'interval', 'daily', 'weekly'
    time: '02:00',              // For daily/weekly
    interval: 'hourly'          // For interval type
  }
}
```

## Development

### Building

No build process required - this is a pure JavaScript extension.

### Testing

1. Load the extension in Chrome developer mode
2. Open the side panel and test functionality
3. Check browser console for any errors
4. Test automation features with short intervals

### Debugging

- Enable "Developer mode" in Chrome extensions
- Use Chrome DevTools for the side panel
- Check service worker logs in `chrome://extensions/`

## Browser Compatibility

- **Chrome**: Version 88+ (Manifest V3 support)
- **Edge**: Version 88+ (Chromium-based)
- **Opera**: Version 74+

## Privacy Policy

This extension:

- Only accesses data necessary for cache clearing
- Does not transmit any personal data externally
- Stores settings and analytics locally
- Complies with Chrome Web Store policies

## Contributing

1. Fork the repository
2. Create a feature branch
3. Make your changes
4. Test thoroughly
5. Submit a pull request

## License

MIT License - see LICENSE file for details

## Support

For issues, feature requests, or questions:

- Create an issue on GitHub
- Email: support@quickcachecleaner.com

## Roadmap

### Upcoming Features

- [ ] Advanced scheduling with cron-like syntax
- [ ] Cloud backup and sync
- [ ] Integration with external tools
- [ ] Multi-language support
- [ ] Voice commands
- [ ] API endpoints for automation

### Performance Optimizations

- [ ] Lazy loading of analytics data
- [ ] Background processing improvements
- [ ] Memory usage optimization
- [ ] Faster storage analysis algorithms

## Changelog

### Version 1.0.0

- Initial release
- Core clearing functionality
- Side panel UI
- Basic automation features
- Analytics dashboard
- Settings management
  Best way to clean cache and chrome browsing data! Easily clean history, downloads, cookie or set auto history cleaning!
