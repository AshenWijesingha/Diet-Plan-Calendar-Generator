# Diet Plan Calendar Generator Pro

A comprehensive web-based application for creating personalized diet plans with calendar synchronization, PDF export, and ICS file validation.

## Features

### Core Features
- 🍽️ **Meal Planning**: Create customized daily meal schedules
- 📅 **Calendar Integration**: Generate ICS files for calendar apps
- 📄 **PDF Export**: Export diet plans as PDF documents
- 💾 **Save & Load**: Save plans locally and reload them anytime
- 📋 **Templates**: Pre-made diet plan templates (Weight Loss, Muscle Gain, Wellness)

### New Feature: ICS File Validation ✅
The application now includes a comprehensive ICS file validation feature that checks the generated calendar files for:

- **Structure Validation**: Ensures proper VCALENDAR format
- **Event Integrity**: Verifies all events are properly structured
- **Date Format Checking**: Validates date/time formats
- **Required Fields**: Checks for mandatory ICS components
- **Alarm Configuration**: Validates reminder/alarm settings
- **Standards Compliance**: Ensures ICS 2.0 specification compliance

#### How to Use ICS Validation

1. Fill out the diet plan form with patient information and meal schedules
2. Click **"📅 Generate Calendar (.ics)"** to create the ICS file
3. Click **"✅ Validate ICS File"** to check the generated file
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

## Usage

1. Open `index.html` in a web browser
2. Fill in patient/client information
3. Add meals with times and descriptions
4. Configure reminders (water, supplements, workout, etc.)
5. Generate calendar file
6. Validate the generated ICS file
7. Optionally export as PDF or save the plan

## Testing

A test file `test_ics_validation.html` is included to demonstrate the validation functionality with various test cases:
- Valid ICS files
- Invalid structures
- Missing required fields
- Various edge cases

## Browser Compatibility

Works in all modern browsers that support:
- HTML5
- CSS3
- ES6 JavaScript
- Local Storage
- Blob API

## Dependencies

- Tailwind CSS (styling)
- ICS.js (calendar file generation)
- jsPDF (PDF export)
- html2canvas (PDF rendering)

## License

Open source - free to use and modify.
