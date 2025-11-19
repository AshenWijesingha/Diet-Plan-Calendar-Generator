# Diet Plan Calendar Generator Pro

A comprehensive, SEO-optimized, and mobile-friendly web application for creating personalized diet plans with calendar synchronization, PDF export, and ICS file validation.

## 🌟 Features

### Core Features
- 🍽️ **Meal Planning**: Create customized daily meal schedules with detailed macros
- 📅 **Calendar Integration**: Generate ICS files for Google Calendar, Apple Calendar, Outlook, and more
- 📄 **PDF Export**: Export professional diet plans as PDF documents
- 💾 **Save & Load**: Save plans locally using browser storage and reload anytime
- 📋 **Templates**: Pre-made diet plan templates (Weight Loss, Muscle Gain, Wellness)
- 🌙 **Dark Mode**: Full dark mode support with persistent preferences
- 📱 **Mobile Optimized**: Fully responsive design for all device types

### New Feature: ICS File Validation ✅
The application now includes a comprehensive ICS file validation feature that checks the generated calendar files for:

- **Structure Validation**: Ensures proper VCALENDAR format
- **Event Integrity**: Verifies all events are properly structured
- **Date Format Checking**: Validates date/time formats
- **Required Fields**: Checks for mandatory ICS components
- **Alarm Configuration**: Validates reminder/alarm settings
- **Standards Compliance**: Ensures ICS 2.0 specification compliance

### SEO & GenAI Optimization 🚀
- **Comprehensive Meta Tags**: Open Graph, Twitter Card, and social media optimization
- **Structured Data**: JSON-LD schema for WebApplication, FAQ, and BreadcrumbList
- **AI-Friendly**: Optimized for GenAI crawlers (GPTBot, ClaudeBot, etc.)
- **Rich Snippets**: Enhanced search engine visibility with detailed metadata
- **Semantic HTML**: Proper HTML5 semantic markup with ARIA labels

### Mobile & Performance Optimization 📱
- **Touch Optimized**: Minimum 44x44px touch targets for all interactive elements
- **Responsive Design**: Breakpoints for mobile (375px+), tablet (768px+), and desktop (1440px+)
- **Performance**: DNS prefetch, preconnect, and deferred script loading
- **Accessibility**: WCAG compliant with proper focus indicators and screen reader support
- **PWA Ready**: Progressive Web App manifest for installable experience

## 🎯 SEO Features

- **Open Graph Tags**: Optimized for Facebook, LinkedIn sharing
- **Twitter Cards**: Enhanced Twitter sharing with large image cards
- **Canonical URLs**: Proper canonical URL structure
- **Robots.txt**: Configured for all major search engines and AI crawlers
- **Sitemap.xml**: Complete sitemap for better indexing
- **Schema.org Markup**: Rich structured data for search engines
- **Meta Keywords**: Relevant keywords for better discoverability
- **Alt Text**: All images and icons have descriptive alt text

#### How to Use ICS Validation

1. Fill out the diet plan form with patient information and meal schedules
2. Click **"📅 Generate Calendar (.ics)"** to create the ICS file
3. Click **"✅ Validate ICS File"** (appears after generation) to check the file
4. Review the validation results showing:
   - ✅ **Passed Checks**: All validated elements
   - ⚠️ **Warnings**: Non-critical issues or recommendations
   - ❌ **Errors**: Critical problems that need fixing

#### Validation Checks Performed

The validator performs 10 comprehensive checks:

1. **Basic Structure**: ICS content is not empty
2. **VCALENDAR Tags**: Required BEGIN and END tags are present
3. **Version**: ICS version 2.0 specification
4. **Events**: At least one event is present
5. **Event Structure**: All events properly opened and closed
6. **Required Fields**: DTSTART, SUMMARY, and UID in events
7. **Date Formats**: Valid date/time format (YYYYMMDDTHHMMSS)
8. **PRODID**: Calendar identification (recommended)
9. **Character Encoding**: Proper encoding of special characters
10. **Alarm Structure**: Valid alarm/reminder configuration

## 📱 Mobile Optimization

### Touch-Friendly Interface
- **44x44px minimum** touch targets for all buttons and interactive elements
- **No accidental zoom** on iOS devices (16px minimum font size for inputs)
- **Touch gestures** supported throughout the interface
- **Swipe-friendly** cards and templates

### Responsive Breakpoints
- **Mobile**: < 768px (single column layout, stacked buttons)
- **Tablet**: 768px - 1024px (2-column grids, optimized spacing)
- **Desktop**: > 1024px (multi-column layouts, hover effects)
- **Landscape Mode**: Optimized for mobile devices in landscape orientation

### Mobile-Specific Features
- Larger buttons and form inputs on mobile
- Full-width action buttons on small screens
- Optimized modal and toast notifications
- Better checkbox and radio button sizes
- Touch-optimized dark mode toggle

## 🎨 UI/UX Improvements

- **Progress Indicator**: Visual step-by-step progress tracking
- **Live Preview**: Real-time preview of diet plan as you build it
- **Form Validation**: Instant feedback on required fields
- **Dark Mode**: Complete dark theme with smooth transitions
- **Animations**: Smooth fade-in and slide animations (respects prefers-reduced-motion)
- **Tooltips**: Helpful context on form fields
- **Keyboard Navigation**: Full keyboard support with proper tab order

## Usage

1. Open `index.html` in a web browser
2. Fill in patient/client information
3. Add meals with times and descriptions
4. Configure reminders (water, supplements, workout, etc.)
5. Generate calendar file (ICS format)
6. Validate the generated ICS file (optional)
7. Optionally export as PDF or save the plan

## 📊 Screenshots

### Desktop View
![Desktop View](https://github.com/user-attachments/assets/27f2c324-941c-4311-b5e5-66e275af371c)

### Mobile View
![Mobile View](https://github.com/user-attachments/assets/73a38303-4b45-4f51-91aa-4297bf217902)

### Dark Mode
![Dark Mode](https://github.com/user-attachments/assets/277c1f5f-f7f5-4666-9fe5-3e11411c9e32)

### Tablet View
![Tablet View](https://github.com/user-attachments/assets/3d71c3b3-202d-4cc5-8df9-af3308706476)

### Preview Mode
![Preview Mode](https://github.com/user-attachments/assets/26db5403-c8b7-4371-aca6-a4bb0d410e00)

## 🚀 Performance

- **Fast Load Times**: Optimized with DNS prefetch and preconnect
- **Efficient Rendering**: CSS containment and will-change properties
- **Deferred Loading**: External scripts loaded asynchronously
- **Lazy Loading**: Resources loaded on demand
- **Minimal Dependencies**: Only essential libraries included

## ♿ Accessibility

- **WCAG 2.1 AA Compliant**: Meets accessibility standards
- **Screen Reader Support**: Full ARIA labels and descriptions
- **Keyboard Navigation**: Complete keyboard support
- **Focus Indicators**: Clear focus states for all interactive elements
- **Color Contrast**: Sufficient contrast ratios in both light and dark modes
- **Skip Links**: Skip to main content link for keyboard users
- **Reduced Motion**: Respects prefers-reduced-motion user preference

## Testing

A test file `test_ics_validation.html` is included to demonstrate the validation functionality with various test cases:
- Valid ICS files
- Invalid structures
- Missing required fields
- Various edge cases

## 🌐 Browser Compatibility

Works in all modern browsers that support:
- HTML5
- CSS3 (Grid, Flexbox, Custom Properties)
- ES6 JavaScript
- Local Storage API
- Blob API
- File Download API

### Tested Browsers
- ✅ Chrome/Edge 90+
- ✅ Firefox 88+
- ✅ Safari 14+
- ✅ Opera 76+
- ✅ Mobile Safari (iOS 14+)
- ✅ Chrome Mobile (Android 10+)

## 📦 Dependencies

All dependencies are loaded from CDN:
- **Tailwind CSS**: Utility-first CSS framework for styling
- **ICS.js**: Calendar file generation library
- **jsPDF**: PDF export functionality
- **html2canvas**: HTML to canvas rendering for PDF
- **Google Fonts (Inter)**: Modern, readable typography

## 🔒 Privacy & Security

- **No Server Required**: Runs entirely in the browser
- **No Data Collection**: All data stays on your device
- **Local Storage Only**: Plans saved using browser's local storage
- **No Tracking**: No analytics or tracking scripts
- **Secure Resources**: All CDN resources use integrity checks

## 🛠️ Development

### File Structure
```
Diet-Plan-Calendar-Generator/
├── index.html              # Main application file
├── test_ics_validation.html # ICS validation tests
├── manifest.json           # PWA manifest
├── robots.txt             # SEO robots configuration
├── sitemap.xml            # SEO sitemap
├── .gitignore             # Git ignore rules
└── README.md              # This file
```

### Key Technologies
- **HTML5**: Semantic markup with ARIA accessibility
- **CSS3**: Modern styling with Grid and Flexbox
- **Vanilla JavaScript**: No framework dependencies
- **Progressive Enhancement**: Works without JavaScript (basic view)

## 🤝 Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

## 📄 License

Open source - free to use and modify.

## 🙏 Acknowledgments

- Icons: Emoji icons for better cross-platform compatibility
- Fonts: Inter font family from Google Fonts
- Libraries: ICS.js, jsPDF, html2canvas, Tailwind CSS

## 📞 Support

For issues, questions, or suggestions, please open an issue on GitHub.

---

**Made with ❤️ for health professionals, nutritionists, and fitness enthusiasts**
