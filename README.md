# portfolio
# Personal Portfolio Website

A mobile-friendly personal portfolio website built with **HTML**, **CSS**, and **Bootstrap**. Features a responsive design, smooth navigation, and all essential portfolio sections.

## Features

✨ **Fully Responsive Design** - Works perfectly on desktop, tablet, and mobile devices  
🎯 **Smooth Navigation** - Smooth scroll navbar with active section highlighting  
🎨 **Modern UI** - Clean, professional design with gradient backgrounds and smooth transitions  
📱 **Mobile-First** - Optimized for all screen sizes using Bootstrap's grid system  
✉️ **Contact Form** - Fully functional contact section with form validation  
💼 **Project Showcase** - Dedicated section to display your projects with links  
🔗 **Social Links** - Easy access to GitHub, LinkedIn, and Twitter profiles  

## Sections

1. **Home (Hero)** - Eye-catching landing section with call-to-action button
2. **Skills** - Display your technical skills with icons and descriptions
3. **Projects** - Showcase your best work with project cards and links
4. **Contact** - Contact form and social media links
5. **Footer** - Copyright information and additional links

## Technologies Used

- **HTML5** - Semantic markup
- **CSS3** - Custom styling with animations and transitions
- **Bootstrap 5.3.3** - Responsive framework
- **JavaScript** - Smooth scroll and form handling

## File Structure

```
portfolio/
├── index.html       # Main HTML file
├── style.css        # Custom CSS styles
└── README.md        # This file
```

## Getting Started

### Prerequisites

- A web browser (Chrome, Firefox, Safari, Edge)
- A text editor (VS Code, Sublime Text, etc.)
- Git (for version control)
- GitHub account

### Local Development

1. **Clone or download the repository:**
   ```bash
   git clone https://github.com/samarthmalgar28-design/portfolio.git
   cd portfolio
   ```

2. **Open in browser:**
   - Simply open `index.html` in your web browser
   - Or use a live server extension in VS Code

3. **Edit your portfolio:**
   - Open `index.html` and customize the content
   - Update your name, bio, skills, and projects
   - Modify `style.css` for custom styling

## Customization Guide

### Update Personal Information

Open `index.html` and replace the following:

```html
<!-- Change this to your name -->
<h1>Hello, I'm Samarth</h1>

<!-- Change your title -->
<h3 class="mb-3">Full Stack Web Developer</h3>

<!-- Update your bio -->
<p class="lead">I build responsive websites using HTML, CSS, Bootstrap and JavaScript.</p>
```

### Add Your Skills

In the Skills section, update the skills with your expertise:

```html
<div class="col-md-3 col-sm-6 mb-4">
  <div class="card skill-card">
    <div class="card-body text-center">
      <div class="skill-icon">📄</div>
      <h5>Your Skill</h5>
      <p class="text-muted small">Skill Description</p>
    </div>
  </div>
</div>
```

### Update Projects

Replace project information with your own:

```html
<div class="col-md-6 col-lg-4 mb-4">
  <div class="card project-card h-100">
    <div class="card-body">
      <h5 class="card-title">Your Project Name</h5>
      <p class="card-text">Project description...</p>
      <div class="project-links">
        <a href="your-project-url" target="_blank" class="btn btn-sm btn-primary">View</a>
        <a href="your-github-url" target="_blank" class="btn btn-sm btn-outline-primary">Code</a>
      </div>
    </div>
  </div>
</div>
```

### Update Social Links

Update your social media URLs in the footer and contact section:

```html
<a href="https://github.com/yourusername" target="_blank">GitHub</a>
<a href="https://linkedin.com/in/yourprofile" target="_blank">LinkedIn</a>
<a href="https://twitter.com/yourprofile" target="_blank">Twitter</a>
```
