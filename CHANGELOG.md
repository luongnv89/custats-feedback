# Changelog

All notable changes to CUStats are documented here.

## [1.4.0] - Under Testing

**Multi-Account & Historical Views Release**

This release adds multi-account support and brings back enhanced historical usage views.

### New Features
- **Multi-Account Support** - Manage multiple Claude accounts in one app
- **Account Switching** - Easily switch between accounts with unified tab bar
- **Add Account Button** - Quick setup for additional accounts in Settings
- **Overview Tab** - All-new Day/Week/Month historical usage views
- **GitHub-Style Charts** - Beautiful monthly activity visualization
- **Demo Mode** - Use "demo" or "demo2" tokens to preview all features

### Improvements
- **4-Tab Navigation** - Redesigned with Live, Overview, Settings, About tabs
- **Modern Tab Bar** - Clean icons and streamlined design
- **100% Badge Fix** - Usage percentage badge now shows full value
- **Popover Positioning** - Better behavior with auto-hide menu bar
- **Google OAuth Handling** - Improved error handling for OAuth users
- **Week View Alignment** - Aligned with 7-day limit reset timing

### Privacy & Security
- All sensitive data (org IDs, tokens) masked in logs
- Enhanced security for debugging without exposing PII
- App Sandbox enabled for maximum security

---

## [1.3.0] - 2024-12-20

**Claude-Focused Release**

Major rebrand and UI overhaul focused on Claude usage monitoring.

### New Features
- **Unified Dashboard** - Redesigned stats panel with sidebar navigation
- **Chart Hover Tooltips** - Interactive data visualization
- **Consumption Peak Chart** - Dedicated chart with fixed 0-3% scale
- **Current Session Stats** - Token, message, and cache tracking
- **Auto-Update Toggle** - Control session history refresh
- **Release Announcement View** - In-app update notifications

### Changes
- Removed API Key authentication (Session Token only)
- Rebranded UI text and redesigned AboutView layout
- Improved Live Session UI

---

## [1.0.0] - 2024-12-01

**Initial Release**

First public release of CUStats (formerly Claude Usage Status / Claude Monitor).

### Features
- **Menubar Integration** - Lives in macOS menubar, always accessible
- **Real-time Usage Tracking** - Monitor 5-hour, 7-day, and Sonnet-specific limits
- **Visual Progress Bars** - Color-coded indicators (green/orange/red)
- **Live Countdown Timer** - See exactly when limits reset at 100% usage
- **Dark Theme Support** - System, Light, or Dark theme options
- **Configurable Refresh** - Set interval from 10 seconds to 10 minutes
- **Secure Storage** - Credentials encrypted with AES-GCM
- **Native macOS App** - Built with SwiftUI
- **Demo Mode** - Animated usage cycling for preview
- **Claude Code Integration** - Local log stats support
- **Scheduled Session Triggers** - Automatic usage refresh
- **Sessions Tab** - Dedicated full-width data table
- **Period Filtering** - Tool usage filtering in Overview dashboard

### Requirements
- macOS 13.0 (Ventura) or later
