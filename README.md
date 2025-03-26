# leetELO

<p align="center">
  <img src="assets/leetELO_logo.png" alt="leetELO Logo" width="200"/>
</p>

***leetELO*** is a Chrome extension that transforms your LeetCode practice by providing a personalized roadmap based on problem difficulty ratings. Track your progress, filter problems by rating range, and systematically improve your problem-solving skills.

## Features

- 🎯 **ELO-based Problem Tracking**: Navigate LeetCode problems sorted by their contest performance ratings
- ✅ **Progress Syncing**: Automatically tracks your completed problems
- 📊 **Rating Statistics**: View your highest achieved problem rating
- 🔍 **Rating Range Filter**: Find problems within your target difficulty range
- 💾 **Local Storage**: All progress is stored locally in your browser

## Installation

### From Chrome Web Store
1. Visit the [leetELO Chrome Web Store page]() COMING SOON
2. Click "Add to Chrome"

### Setup
1. Clone the repository
```bash
git clone https://github.com/ciaracade/leetelo.git
cd leetelo
```

## Technologies
• Frontend: html/css
• Backend: Node.js
• Extension: Chorme APIs, manifest v3
• Storage: Chrome local storage

## Contribute
This is my first Opensource repo I plan to go into production, and I would LOVE the community to contribute. So if you have any feature ideas, want to fix a big, or just want to help polish up the code before release, PRs and issues are always welcome!

Want to add a new question and ELO rating? Convention goes:
```
        rating: parseFloat(parts[0]),
        id: parseInt(parts[1]),
        title: parts[2],
        titleSlug: parts[4],
        completed: false
```

## Thank you!
<a href="https://github.com/ciaracade/leetELO/graphs/contributors">
  <img src="https://contrib.rocks/image?repo=ciaracade/leetELO" />
</a>