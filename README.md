# Quick Cache Cleaner - Chrome Extension

<div align="center">

![Quick Cache Cleaner Logo](icon512.png)

**🧹 Optimize your browsing experience with intelligent cache management**

[![Chrome Web Store](https://img.shields.io/badge/Chrome%20Web%20Store-Quick%20Cache%20Cleaner-blue?style=for-the-badge&logo=google-chrome)](https://chrome.google.com/webstore)
[![Version](https://img.shields.io/badge/version-1.0.0-green?style=for-the-badge)](https://github.com/TheWonderApps/QuickCacheCleaner)
[![License](https://img.shields.io/badge/license-MIT-orange?style=for-the-badge)](LICENSE)

</div>


## 🚀 Overview

**Quick Cache Cleaner** is a powerful Chrome extension designed to optimize your browsing experience by efficiently managing and clearing browser data. With its intuitive side panel interface, real-time storage analysis, and smart automation features, it helps users maintain optimal browser performance while protecting their privacy.

### 🎯 Why Choose Quick Cache Cleaner?

- **🔍 Real-time Analysis** - See exactly what's taking up space in your browser
- **🎛️ Granular Control** - Choose exactly what to clean and what to keep
- **🛡️ Privacy Focused** - No data collection, everything stays local
- **🎨 Modern Interface** - Beautiful, intuitive side panel design

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


### 📈 **Monitoring Usage**

1. **Daily Monitoring**

   - Check the dashboard regularly for storage trends
   - Use the refresh button to update data

2. **Review Cleaning History**

   - View last cleared timestamp

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
- **Sound Effects** - Toggle notification sounds

**Data Display**

- **Units** - Bytes, KB, MB, or Auto
- **Precision** - Decimal places for size display
- **Chart Type** - Donut, Bar, or List view

### 🛡️ **Privacy Settings**

**Data Handling**

- **Local Storage Only** - All data stays on your device
- **No Telemetry** - No usage data is collected
- **Secure Storage** - Settings encrypted by Chrome

**Permission Management**

- **Review Permissions** - See what the extension can access
- **Revoke Access** - Disable specific permissions if needed


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


**Quick Cache Cleaner v1.0.0**

_Made with ❤️ for a faster, cleaner web experience_

[⬆️ Back to Top](#quick-cache-cleaner---chrome-extension)


## Changelog

### Version 1.0.0

- Initial release
- Core clearing functionality
- Side panel UI
- Basic automation features
- Analytics dashboard
- Settings management
  Best way to clean cache and chrome browsing data! Easily clean history, downloads, cookie or set auto history cleaning!
