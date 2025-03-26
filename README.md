# leetELO

<p align="center">
  <img src="src/assets/leetELO_logo.png" alt="leetELO Logo" width="200"/>
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

### From Source
1. Clone the repository
```bash
git clone https://github.com/ciaracade/leetelo.git
cd leetelo
```

2. Install dependencies
```bash
npm install
```

3. Generate problem data
```bash
npm run populate
```

4. Load the extension in Chrome
- Open Chrome and navigate to `chrome://extensions/`
- Enable "Developer mode" in the top right
- Click "Load unpacked"
- Select the `leetelo` directory

## Usage

1. Click the leetELO icon in your Chrome toolbar
2. View all LeetCode problems sorted by rating
3. Filter problems by entering min/max ratings
4. Click checkboxes to manually mark problems as completed
5. Problems are automatically marked complete when solved on LeetCode
6. Click "Total" or "Completed" to switch views

## Project Structure

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