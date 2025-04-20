# MinimaLIST

A minimalist to-do list application inspired by the Analog system by Ugmonk.

![MinimaLIST Preview](https://example.com/screenshot.png)

## Features

- **Simple Task Management**: Create, edit, and track tasks with a three-state completion system (empty, half-filled, complete)
- **Day Organization**: Separate cards for Today and Tomorrow to help manage your priorities
- **Monthly Archives**: Save completed cards organized by month for easy reference
- **User Accounts**: Register and login to save your data across devices
- **Night Mode**: Toggle between light and dark themes for comfortable viewing in any environment
- **Responsive Design**: Works on mobile, tablet, and desktop screens
- **Local Storage**: Data is saved locally, with optional account sync

## Getting Started

### Prerequisites

- A modern web browser (Chrome, Firefox, Safari, Edge)
- Web hosting for deployment (see Deployment options below)

### Installation

1. Clone the repository:
   ```
   git clone https://github.com/yourusername/minimalist.git
   ```

2. Open `index.html` in your web browser to run locally

### Deployment Options

You can deploy MinimaLIST on any static web hosting service. Here are some recommended free options:

- **GitHub Pages**: Free hosting directly from your GitHub repository
- **Netlify**: Free tier with continuous deployment and HTTPS support
- **Vercel**: Free hosting with automatic deployments from GitHub
- **Static.app**: Simple one-click deployment
- **Cloudflare Pages**: Fast global CDN with free static website hosting

## Usage

### Adding Tasks

1. Click on any empty input field to add a task
2. Tasks are automatically saved as you type

### Task Status

Click on the circle next to each task to change its status:
- Empty circle: Task not started
- Half-filled circle: Task in progress
- Filled circle: Task completed

### Day Management

- **Today**: For tasks that need to be completed today
- **Tomorrow**: For upcoming tasks
- Use the "Move to Today" button to transfer tomorrow's tasks to today

### Archiving

1. Complete your tasks for the day
2. Click "Archive Card" to store the completed card
3. View past cards in the Archive section, organized by month

### User Accounts

1. Click the hamburger menu (☰) in the top left
2. Register with an email and password
3. Your data will automatically sync when you're logged in

### Night Mode

1. Open the hamburger menu (☰)
2. Toggle the Night Mode switch to change themes

## Customization

MinimaLIST can be customized by modifying the CSS variables in the `:root` selector:

```css
:root {
    --bg-color: #e8ecee;
    --card-color: #f3f5f6;
    --text-color: #333;
    --accent-color: #555;
    --border-color: #ddd;
    --wood-color: #8b5a2b;
    --nav-bg: white;
    --footer-bg: white;
}
```

## Technical Details

MinimaLIST is built with:
- HTML5
- CSS3 (with CSS variables for theming)
- Vanilla JavaScript (no frameworks or libraries)
- LocalStorage for data persistence

The application uses a clean, modular structure:
- CSS variables for easy theming
- JavaScript modules organized by functionality
- Responsive design using CSS flexbox and grid

## Contributing

1. Fork the repository
2. Create your feature branch: `git checkout -b feature/amazing-feature`
3. Commit your changes: `git commit -m 'Add some amazing feature'`
4. Push to the branch: `git push origin feature/amazing-feature`
5. Open a Pull Request

## License

This project is licensed under the MIT License - see the LICENSE file for details.

## Acknowledgments

- Inspired by the [Analog system by Ugmonk](https://ugmonk.com/analog)
- Icons from [SVG Repo](https://www.svgrepo.com/)
- Font: Helvetica Neue

---

## Contact

Your Name - your.email@example.com

Project Link: [https://github.com/yourusername/minimalist](https://github.com/yourusername/minimalist)
