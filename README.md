OAU Campus Emergency Resource Map
An interactive web map of critical emergency resources at Obafemi Awolowo University (OAU) campus, developed as part of the HOT Mentorship Program capstone project.
🌐 Live Map:

📋 Project Overview
This project addresses the need for a centralized, accessible map of emergency resources at OAU campus. In emergency situations, quick access to information about medical facilities, security posts, fire hydrants, and assembly points can significantly improve response times and coordination.

Key Features
Interactive Map Interface: Zoom, pan, and explore campus resources
Resource Categorization: Color-coded markers for different resource types
Detailed Information: Click any marker to view contact info, operational status, photos, and more
Mobile-Friendly: Responsive design works on all devices
Layer Control: Toggle different resource types on/off

🗺️ Resource Categories Mapped
Category
Symbol
Examples
🏥 Medical Centers
Red Cross
OAU Health Centre, Campus Clinics
🚔 Security Posts
Blue Shield
Main Security Office, Zone Posts
🔥 Fire Resources
Flame Icon
Fire Hydrants, Fire Service Unit
🟢 Assembly Points
Green Triangle
Hostel Assembly Areas, Academic Zones
🏛️ Administrative
Brown Square
VC Office, Faculty Buildings
💧 Water Points
Blue Drop
Public Water Taps, Storage Tanks


🛠️ Technical Implementation
Workflow Summary
Field Data Collection: KoboToolbox form deployed on mobile devices
Data Processing: QGIS for cleaning, styling, and analysis
Web Export: qgis2web plugin to generate interactive web map
Hosting: GitHub Pages for free, reliable web hosting
Technologies Used
Field Data Collection: KoboToolbox
GIS Software: QGIS 3.28+
Web Mapping: Leaflet.js (via qgis2web plugin)
Hosting: GitHub Pages
Data Formats: GeoJSON, CSV, GeoTIFF

📊 Data Collection Methodology
Survey Form Fields
Asset Type (required)
Asset Name/ID (required)
GPS Coordinates (required)
Operational Status
Contact Number
Operating Hours
Accessibility Level
Photographic Evidence
Additional Notes

Coverage Area
Campus Zones Surveyed: Academic Area, Student Hostels, Administrative Zone
Total Points Collected: 25+ emergency resources
Survey Period: November 2025 - December 2025

📁 Repository Structure
text
oau-emergency-map/
├── index.html                    # Main web map file
├── layers/                       # Map data layers
│   └── oau_resources.geojson     # Emergency resources data
├── css/                          # Stylesheets
│   └── style.css
├── js/                           # JavaScript files
│   ├── leaflet.js
│   └── leaflet.css
├── images/                       # Resource photos
│   └── [resource_photos].jpg
├── data/                         # Raw/processed data
│   ├── oau_resources.csv         # Original survey data
│   └── oau_resources.qgz         # QGIS project file
└── docs/                         # Documentation
    └── methodology.pdf

🚀 How to Use the Map
For General Users
Visit the live map URL
Use mouse/touch to navigate around campus
Click any marker to view detailed information
Use the layer control (top-right) to filter resource types
Search for specific locations using the search bar

For Emergency Responders
Medical Emergency: Locate nearest medical center (red cross icons)
Security Issue: Find closest security post (black shield icons)
Fire Emergency: Identify fire hydrants and fire service 
Evacuation: Direct people to designated assembly points (green triangles)

🔄 Updating the Map
Adding New Resources
Field Survey: Use the KoboToolbox form to collect new data
Data Processing:
 Export new data from KoboToolbox
 Import CSV into QGIS
 Merge with existing GeoJSON layer
 Export updated layer
Web Update: Replace layers/oau_resources.geojson with updated file
Commit Changes: Push updates to GitHub repository

📈 Impact & Future Enhancements
Immediate Applications
Campus security planning
Student orientation material
Emergency response training
Infrastructure gap analysis

Planned Improvements
Real-time status updates (operational/out-of-service)
Routing to nearest resource
Integration with campus alert system
Multi-language support
Offline mobile application

🤝 Contributing
We welcome contributions to improve this resource:
Data Accuracy: Report incorrect or missing information via Issues
New Features: Suggest enhancements in Discussions
Code Improvements: Submit Pull Requests for bug fixes
Reporting Issues: Please use the GitHub Issues page.

📄 License
This project is licensed under the MIT License - see the LICENSE file for details.

🙏 Acknowledgments
HOT Mentorship Program for guidance and support
OAU Campus Security for information verification
QGIS & Leaflet.js communities for excellent open-source tools
OpenStreetMap for base map data

📞 Contact & Support
Project Maintainer: Dayo Oyinloye
Email: thedayooyinloye@gmail.com
GitHub: @dayooyinloye

For Emergency Use:
Campus Security: [Insert emergency number]
Medical Emergency: [Insert medical center number]
Fire Service: [Insert fire service number]

Last Updated: [Current Date]
Data Currency: Survey conducted [December 2025]
Update Frequency: Semi-annual reviews planned
⚠️ Emergency Note: In case of actual emergency, contact campus authorities immediately. This map is for planning and awareness purposes.


