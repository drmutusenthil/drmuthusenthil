# How to Use Your Updated Portfolio

## Overview

Your portfolio has been successfully updated with all your professional information organized into collapsible accordion sections. Here's how to navigate and use the new features.

## Navigation Structure

### Main Menu

The navigation menu now includes:

1. **Home** - Landing page with your introduction
2. **About** - Brief bio and personal details
3. **Resume** - Education and work experience
4. **Research & Publications** - Click to view:
   - Doctoral Research (Post-Doc & PhD)
   - Patents (Granted & Filed)
   - Funding Received & Proposals
   - Supervisor Guide-ship & Scholars
   - International Journal & Conference Publications
5. **Academic Contributions** - Click to view:
   - Subjects Handled
   - Additional Responsibilities
   - Online Courses & Certifications
   - Accolades & Professional Memberships
6. **Professional Activities** - Dropdown menu with:
   - Invited Talks & Workshops
   - International Collaboration
   - Online Courses & Certifications
   - Countries Visited
7. **Contact** - Contact information and form

## How Accordions Work

### What are Accordions?

Accordions are collapsible content sections that hide/show information when you click on them.

### Using the Accordions:

1. **Click on a heading** (button) to expand the section
2. **Click again** to collapse it
3. **Only one section** stays open at a time (previous section closes automatically)
4. **Active sections** are highlighted in blue color

### Example:

```
▶ Doctoral Research           (Click to open)
✓ Doctoral Research           (Currently open - click to close)
  - Post-Doctoral Thesis
  - Ph.D Thesis
```

## Sections Explained

### Research & Publications Section

Located where "Portfolio" used to be. Contains:

- **Doctoral Research**: Your Post-Doc and PhD thesis details
- **Patents**: 2 granted + 3 filed patents
- **Funding**: ₹90 Lakhs AICTE grant + other proposals
- **PhD Scholars**: 6 scholars under your guidance
- **Publications**: 35+ journals, 16+ conferences

### Academic Contributions Section

Located where "Services" used to be. Contains:

- **Subjects Handled**: 22+ subjects you've taught
- **Responsibilities**: HOD, IDEA Lab, coordinators
- **Online Courses**: NPTEL, Coursera certifications
- **Memberships**: ISTE, CSI, IACSIT, etc.

### Professional Activities Sections

Three new standalone sections:

1. **Invited Talks & Workshops**

   - Guest lectures at various institutions
   - Workshops organized and attended
   - Projects guided (75+ UG, 15+ PG)

2. **International Collaboration**

   - Your role at WookYoung IT, South Korea
   - Four international collaborators with contact details

3. **Countries Visited**
   - 6 countries displayed as cards
   - Dates of visits included

## Viewing on Different Devices

### Desktop/Laptop

- Full navigation menu visible on left
- Accordion sections display with good spacing
- Two-column layouts for subjects and responsibilities

### Tablet

- Navigation menu collapses to hamburger icon
- Accordion content remains readable
- Columns may stack for better fit

### Mobile Phone

- Hamburger menu for navigation
- Single column layout for all content
- Touch-friendly accordion buttons
- Fully responsive design

## Tips for Best Experience

1. **Start from Top**: Read through Hero → About → Resume first
2. **Use Navigation**: Jump to specific sections using the menu
3. **Expand What Interests You**: Only open accordions you want to read
4. **Check All Sections**: Each section contains valuable information
5. **Mobile Friendly**: Works perfectly on phones and tablets

## Making Updates

### To Update Content:

1. Open `index.html` in a text editor
2. Find the accordion section you want to update
3. Edit the content within `<div class="accordion-body">` tags
4. Save and refresh your browser

### Example:

```html
<div class="accordion-body">
  <p>Your content here</p>
  <ul>
    <li>Item 1</li>
    <li>Item 2</li>
  </ul>
</div>
```

### To Add New Items:

- **Patents**: Add to the `<ol>` list in Patents section
- **Publications**: Add to the list in Publications section
- **Courses**: Add to the `<ul>` list in Online Courses section

## Key Features

✅ **Organized Information**: Everything categorized logically
✅ **Easy Navigation**: Click to expand/collapse sections
✅ **Professional Design**: Clean, modern Bootstrap 5 styling
✅ **Mobile Responsive**: Works on all screen sizes
✅ **Fast Loading**: Lightweight accordion implementation
✅ **SEO Optimized**: Proper page structure and metadata

## Troubleshooting

### Accordion Not Opening?

- Check if JavaScript files are loaded (bottom of page)
- Clear browser cache and reload

### Content Not Displaying?

- Verify HTML tags are properly closed
- Check for any syntax errors in the code

### Mobile Menu Not Working?

- Ensure Bootstrap JavaScript is loaded
- Check viewport meta tag is present

## Next Steps

1. **Add Your Photo**: Replace `assets/img/my-profile-img.jpg`
2. **Update Social Links**: Edit social media links in header
3. **Add Contact Details**: Update contact section with your info
4. **Test Everything**: Check all accordion sections work
5. **Go Live**: Upload to your web hosting

## Need Help?

If you need to make changes or add more content:

1. Locate the section in the HTML file
2. Follow the existing pattern
3. Copy/paste accordion item structure
4. Update IDs to be unique
5. Test in browser

---

**Your portfolio is now ready to showcase your impressive academic and research career!**

All content is organized, easy to navigate, and professionally presented.
