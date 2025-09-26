# Enclave Software Organization Website

This is the official website for Enclave Software, automatically updated with the latest repository information.

## 🚀 Features

- **Auto-updating**: Syncs with GitHub organization repositories daily
- **Responsive design**: Works on all devices
- **Modern UI**: Clean, professional design using your existing style system
- **Dynamic content**: Repository information updated automatically
- **GitHub Pages**: Deployed automatically on commits

## 🤖 Auto-Update System

The website automatically updates when:
- **Daily**: Runs at 6:00 UTC to sync latest repository data
- **Manual**: You can trigger updates manually from Actions tab
- **On push**: Updates when you push to the main branch
- **Repository changes**: Can be triggered when repositories are created/updated

### How it works:
1. Fetches all public repositories from Enclave Software organization
2. Updates the Products section with current repository information
3. Updates statistics (repository count, etc.)
4. Adds any new repositories to the "Other Projects" section
5. Deploys updated site to GitHub Pages

## 📝 Customization

### Repository Categories
The system automatically categorizes repositories:
- **Main Products**: `Enclave-Messenger`, `Enclave-Site`, `Accounts.enclave`
- **Other Projects**: All other public, non-archived repositories

### Status Indicators
- 🟢 **Active Development**: Enclave-Messenger
- 🟢 **Deployed**: Enclave-Site
- 🟠 **In Development**: Accounts.enclave (messenger authentication only)
- 🔵 **Available**: Other repositories

## 🔒 Authentication Context

**Accounts.enclave** is specifically for Enclave Messenger authentication, not for the organization website. The organization site is public and doesn't require user authentication.

## 📱 Sections

1. **Home**: Overview and main call-to-action
2. **Products**: Auto-updated list of repositories
3. **About**: Organization mission, values, and team
4. **Security**: Security practices and vulnerability reporting
5. **Contact**: Links to GitHub, demo, and contact information

## 🎨 Design System

Uses your existing CSS design system with:
- Modern teal color scheme
- Responsive grid layouts
- Smooth animations
- Dark/light mode support
- Professional typography

## 🚀 Deployment

The site is automatically deployed to GitHub Pages via GitHub Actions. Any push to the main branch triggers a new deployment.

## 📊 Analytics

The auto-update system tracks:
- Repository count
- Stars and forks
- Last updated timestamps
- Repository languages and topics
