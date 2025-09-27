# DigiDarshan - Temple Management System

DigiDarshan is a web-based temple management system that helps manage temple visits, bookings, and volunteer verifications for multiple temples in Gujarat.

## 🛠️ Prerequisites

Before running this project, make sure you have the following installed:
- A modern web browser (Chrome, Firefox, Safari, or Edge)
- Python 3.x (for running the local development server)
- Git (for version control)
- Basic understanding of HTML, CSS, and JavaScript

## 🚀 Getting Started

### Local Development

1. Clone the repository:
```bash
git clone https://github.com/kadmisettypadmapriyatejaswini-rgb/DIGI-DARSHAN.git
cd DIGI-DARSHAN
```

2. Start the local development server:
```bash
# Using Python's built-in HTTP server
python3 -m http.server 8000
```

3. Open your browser and navigate to:
```
http://localhost:8000
```

## 📁 Project Structure

```
DIGI-DARSHAN/
├── index.html          # Main entry point
├── webpage.html        # Homepage
├── ambaji.html         # Ambaji Temple page
├── somnath.html       # Somnath Temple page
├── dwarka.html        # Dwarka Temple page
├── pavagadh.html      # Pavagadh Temple page
├── *book.html         # Booking pages for each temple
└── volunteerlogin.html # Volunteer verification portal
```

## 🔄 Updating the Code

### Making Local Changes

1. Create a new branch for your changes:
```bash
git checkout -b feature/your-feature-name
```

2. Make your changes to the relevant files

3. Test your changes locally:
```bash
python3 -m http.server 8000
```

4. Stage and commit your changes:
```bash
git add .
git commit -m "Description of your changes"
```

### Pushing to GitHub

1. Push your changes to GitHub:
```bash
git push origin feature/your-feature-name
```

2. Create a Pull Request:
   - Go to the [repository on GitHub](https://github.com/kadmisettypadmapriyatejaswini-rgb/DIGI-DARSHAN)
   - Click on "Pull requests"
   - Click "New Pull Request"
   - Select your branch
   - Add description of your changes
   - Submit the pull request

## 🎯 Features

- Temple Information Pages
  - Details about each temple
  - Visiting hours
  - Special events
  - Location details

- Booking System
  - Online darshan booking
  - Date and time slot selection
  - Visitor information collection

- Volunteer Portal
  - QR code scanning for verification
  - Manual booking ID verification
  - Real-time booking status check
  - Recent verifications tracking

## 💡 Sample Booking IDs for Testing

### Ambaji Temple
- AMB2025091001 (Valid)
- AMB2025091002 (Valid)

### Somnath Temple
- SOM2025091001 (Valid)
- SOM2025091003 (Expired)

### Dwarka Temple
- DWA2025091001 (Valid)
- DWA2025091003 (Expired)

### Pavagadh Temple
- PAV2025091001 (Valid)
- PAV2025091002 (Valid)

## 🔍 Testing

1. Open the volunteer portal:
```
http://localhost:8000/volunteerlogin.html
```

2. Test booking verification:
   - Use the sample booking IDs provided above
   - Try scanning QR codes (if available)
   - Check expired bookings
   - Verify invalid booking IDs

## 📱 Browser Compatibility

The system has been tested and works on:
- Google Chrome (latest)
- Mozilla Firefox (latest)
- Microsoft Edge (latest)
- Safari (latest)

## 🤝 Contributing

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## ⚠️ Important Notes

- Always test your changes locally before pushing
- Keep the booking IDs format consistent (e.g., AMB2025091001)
- Maintain the existing file structure
- Follow the established coding style
- Update documentation when adding new features

## 📄 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 🔮 Future Enhancements

- User authentication system
- Multiple language support
- Online prasad booking
- Special event registration
- Mobile app development
- Payment integration
- Email confirmation system
