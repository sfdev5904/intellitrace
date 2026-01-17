# IntelliTrace
Google Dorking Simplified - Advanced OSINT & Digital Footprint Analysis

A powerful, single-page OSINT (Open Source Intelligence) tool designed to simplify Google Dorking and digital footprint analysis. Built with a sleek cyan-accented matrix-style aesthetic and featuring a built-in Evidence Archive system.

## ✨ Features

### 🔍 Google Dorking Made Easy
- **Simplified Interface** - No need to remember complex boolean operators
- **Advanced Search Operators** - Built-in support for all major Google dork operators:
  - `site:` - Search specific sites
  - `filetype:` - Search for specific file types
  - `intext:` / `allintext:` - Search in page content
  - `intitle:` / `allintitle:` - Search in page titles
  - `inurl:` / `allinurl:` - Search in URLs
  - `link:` - Find external links
  - `related:` - Find similar pages
  - `cache:` - View cached versions
  - Date ranges, wildcards, and more

### 🌐 Multi-Platform OSINT Search
Generate instant search links across **100+ platforms**:

- **Social Media** - Facebook, Twitter/X, Instagram, TikTok, Snapchat, Threads
- **Professional Networks** - LinkedIn, Indeed, AngelList, Behance
- **Media Platforms** - YouTube, Twitch, Vimeo, SoundCloud, Spotify
- **Search Engines** - Google (with operators), Bing, DuckDuckGo, Yahoo, Yandex, Baidu
- **Developer Platforms** - GitHub, GitLab, Stack Overflow, CodePen, Replit
- **Forums & Communities** - Reddit, Quora, Medium, Dev.to
- **Visual Platforms** - Pinterest, Flickr, DeviantArt, ArtStation, Dribbble
- **Gaming** - Steam, Discord, Xbox, PlayStation

### 📎 Evidence Archive System
**NEW!** IntelliTrace now includes a built-in evidence archiving system for investigation management:

- **Save Evidence** - Click "Save" on any search result to archive it for later
- **Persistent Storage** - All evidence saved to browser localStorage (privacy-focused, client-side only)
- **Archive Modal** - Beautiful full-screen archive view with:
  - Chronological evidence listing
  - Platform icons and metadata
  - Clickable URLs to revisit findings
  - Timestamps for each saved item
- **Export to JSON** - Download your entire archive as a JSON file for backup or sharing
- **Delete Management** - Remove individual items or clear entire archive
- **Badge Counter** - Visual indicator showing number of archived items

### 🎯 Advanced OSINT Features
- **Document Discovery** - Search for PDFs, DOCs, spreadsheets, presentations, config files
- **Contact Information** - Find emails, phone numbers, and contact details
- **Social Mentions** - Track mentions across social media platforms
- **Forum Posts** - Search discussion forums and Q&A sites
- **News Articles** - Find news coverage and media mentions
- **Login Pages** - Discover authentication endpoints

### 🎨 Design
Built with a distinctive **matrix-style aesthetic**:

- Pure black background (#000000)
- **Cyan/turquoise accents** (#00D9FF) with glow effects
- Modern sans-serif typography
- Terminal-inspired interface
- Smooth animations and hover effects
- Fully responsive mobile design
## 🚀 Usage

### 1. Search Any Identifier
Enter any of the following:
- Username
- Full name
- Email address
- Phone number
- Domain name
- Company name
- Any text identifier

### 2. Select Categories
Choose which platforms to search:
- Social Media
- Search Engines (with Google Dorking)
- Developer & Tech platforms
- Visual & Creative platforms

### 3. Generate Results
Click **"Trace"** to instantly generate search links for all selected platforms. Each link opens in a new tab with the appropriate search query pre-configured.

### 4. Save Evidence (NEW!)
- Click the green **"Save"** button next to any search result
- Evidence is automatically archived with:
  - Platform name and icon
  - Full search URL
  - Search query used
  - Timestamp
- Access saved evidence anytime via the **"📎 Archive"** button

### 5. Manage Your Archive
- **View Archive** - Click the Archive button to see all saved evidence
- **Export** - Download your archive as JSON for backup or reporting
- **Delete** - Remove individual items or clear entire archive
- **Persistent** - Data saved in browser localStorage (survives page refreshes)

## 📦 Deployment

### Vercel (Recommended)
This is a static HTML file that deploys instantly to Vercel:

1. Push `index.html` to your GitHub repository
2. Import the project in Vercel
3. Deploy - no configuration needed!

### Other Platforms
Works on any static hosting service:
- Netlify
- GitHub Pages
- CloudFlare Pages
- AWS S3
- Any web server

## ⚙️ Technical Details

- **Single Page Application** - Pure HTML/CSS/JavaScript, no dependencies
- **Zero Backend** - Everything runs client-side (including Evidence Archive)
- **Fast & Lightweight** - Instant load times, ~54KB total
- **Mobile Responsive** - Works perfectly on all devices
- **Privacy Focused** - No tracking, no analytics, no external requests until you click a search link
- **LocalStorage Archive** - Evidence saved locally in browser (never sent to servers)
- **Zero Dependencies** - No frameworks, libraries, or external CDNs required
## 📖 Google Dorking Reference
The tool includes comprehensive documentation for all Google search operators:

### Search Filters:
- `allintext:` - All keywords must appear in page text
- `intext:` - Keywords in text
- `allintitle:` - All keywords must appear in title
- `intitle:` - Keywords in title
- `allinurl:` - All keywords must appear in URL
- `inurl:` - Keywords in URL
- `site:` - Search specific site or domain
- `filetype:` - Search for specific file types
- `link:` - Find pages linking to a URL
- `related:` - Find similar pages
- `cache:` - View Google's cached version

### Operators:
- `|` - OR operator
- `&` - AND operator
- `-` - Exclude term
- `+` - Include term
- `~` - Synonyms
- `*` - Wildcard
- `"exact phrase"` - Exact match search
- `before:` / `after:` - Date range filters
- `numrange:` - Number range filters

## 💼 Use Cases

- **Security Research** - OSINT investigations and reconnaissance
- **Digital Forensics** - Track digital footprints across platforms with archiving
- **Journalism** - Research subjects and build evidence collections
- **HR & Recruitment** - Verify candidate backgrounds and save findings
- **Competitive Intelligence** - Research competitors and maintain organized archives
- **Personal Security** - Check your own digital footprint
- **Penetration Testing** - Authorized information gathering with evidence tracking
- **Investigative Research** - Long-term investigations with persistent evidence storage
## ⚖️ Legal Notice

This tool is designed for **legitimate OSINT (Open Source Intelligence)** purposes:
- Security research
- Competitive intelligence
- Due diligence
- Background verification
- Digital forensics
- Personal security audits

### Use Responsibly:
- ✅ Respect privacy laws and regulations (GDPR, CCPA, etc.)
- ✅ Obtain proper authorization for investigations
- ✅ Follow platform Terms of Service
- ✅ Use for lawful purposes only
- ⚠️ **Evidence Archive is stored locally in your browser** - clear it before sharing devices

## 📄 License

MIT License - Use freely for personal or commercial purposes

## 🤝 Contributing

Contributions welcome! Feel free to:
- Report bugs
- Suggest new platforms to add
- Improve search operators
- Enhance the Evidence Archive system
- Add new features
- Improve UI/UX

## 🏆 Certification

This project is **Open-Source Certified** and promotes ethical OSINT practices.

**#OSINT4GOOD**

## 👨‍💻 Author

Created by **Mr. OSINT Jr.** for simplified OSINT research and Google Dorking operations.

[LinkedIn](https://www.linkedin.com/in/sebastian-figue/)

---

**IntelliTrace** - Google Dorking Simplified | Evidence-Based OSINT Investigations
