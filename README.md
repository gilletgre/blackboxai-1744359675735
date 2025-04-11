
Built by https://www.blackbox.ai

---

```markdown
# Projet de connectivité Wi-Fi Outdoor – Brussels Major Event (BME)

## Project Overview
The Brussels Major Event (BME) project aims to establish a robust, mobile, and supervised temporary Wi-Fi infrastructure to provide reliable, secure, and high-performance connectivity during large public events organized by the ASBL Brussels Major Event (BME). This application offers an interactive web tool that features a modern map displaying the Wi-Fi access points and coverage areas for various event zones.

## Installation
To set up this project locally, follow these simple steps:

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/bme-wifi-connectivity.git
   ```
   
2. Navigate to the project directory:
   ```bash
   cd bme-wifi-connectivity
   ```

3. Open `index.html` in a web browser to view the application.

## Usage
This project is designed to provide an interactive map that covers the different event zones for the Brussels Major Event. Users can view Wi-Fi access points and their coverages, allowing for better management of connectivity during events.

## Features
- Interactive map using OpenStreetMap.
- Dynamic visualization of outdoor Wi-Fi access points (APs).
- Coverage circles indicating the estimated radius of each site (40-60m).
- Supports multiple connectivity scenarios for events:
  - **Scenario 1:** Fallback mobile connectivity using APs, PoE switch, and 5G router.
  - **Scenario 2:** Hybrid connectivity using existing fiber with 5G backup.
  - **Scenario 3:** Multi-event resource sharing with sustainable investment.

## Dependencies
The project uses the following dependencies:
- **Tailwind CSS:** For utility-first CSS framework.
- **Font Awesome:** For vector icons and social logos.

These libraries are included via CDN links in the `index.html` file.

## Project Structure
The project consists of the following files:
```
/bme-wifi-connectivity
│
├── index.html            # Main HTML file providing project overview and interactive features
```

## Conclusion
This project represents a modern solution for providing outdoor Wi-Fi connectivity at major events in Brussels, enhancing the experience for attendees and organizers alike.

### License
This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
```