# Behavior Data Collection Tool

![React](https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react&logoColor=61DAFB)
![Vite](https://img.shields.io/badge/Vite-B73BFE?style=for-the-badge&logo=vite&logoColor=FFD62E)
![Firebase](https://img.shields.io/badge/firebase-ffca28?style=for-the-badge&logo=firebase&logoColor=black)

A comprehensive, easy-to-use web application designed specifically for **behavior tracking in the autism and Intellectual and Developmental Disabilities (IDD) population**. 

This tool allows direct support professionals, clinicians, and educators to accurately record, monitor, and export longitudinal behavioral data, ensuring that interventions are data-driven and effective.

## ✨ Features

- **Customizable Behavior Tracking:** Track a wide range of topographies including Aggression, Self-Injury, Elopement, Pica, Disruptive Behaviors, and more.
- **Multi-Dimensional Metrics:** Record data across multiple dimensions:
  - Frequency
  - Intensity (1-4 scale)
  - Duration
  - Attempts vs. Successes
- **Crisis Intervention Tracking:** Built-in support for logging SCIP-R (Strategies for Crisis Intervention and Prevention - Revised) maneuvers, categorized by Core, Specialized, and Restrictive techniques.
- **Shift-Based Logging:** Easily log data across standard shifts (e.g., 7am-3pm, 3pm-11pm, 11pm-7am) to maintain consistent 24-hour records.
- **Client & Residence Management:** Organize clients by residence or classroom, allowing for scalable use across multiple locations or organizations.
- **Longitudinal History & Export:** View historical data and export comprehensive reports directly to Excel (XLSX) for clinical review and graphing.
- **Secure Authentication:** Integrated with Firebase Auth to ensure HIPAA-compliant data access and secure user management.

## 🚀 Getting Started

### Prerequisites

- Node.js (v18 or higher recommended)
- npm or yarn
- A Firebase project (for authentication and Firestore database)

### Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/behavior_data_collection.git
   cd behavior_data_collection
   ```

2. Install dependencies:
   ```bash
   npm install
   ```

3. Set up Firebase:
   - Create a project in the [Firebase Console](https://console.firebase.google.com/).
   - Enable Authentication (Email/Password) and Firestore Database.
   - Update `src/firebase.js` with your Firebase config credentials.

4. Start the development server:
   ```bash
   npm run dev
   ```

5. Build for production:
   ```bash
   npm run build
   ```

## 🛠 Built With

- **React 19** - Front-end library
- **Vite** - Build tool and development server
- **Firebase** - Authentication and Cloud Firestore
- **Lucide React** - UI Icons
- **SheetJS (xlsx)** - Excel data export
- **jsPDF** - PDF generation

## 🤝 Contributing

Contributions are welcome! If you are a developer, clinician, or educator with ideas on how to improve this tool for the autism and IDD community, please feel free to submit a Pull Request or open an Issue.

1. Fork the Project
2. Create your Feature Branch (`git checkout -b feature/AmazingFeature`)
3. Commit your Changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the Branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## 📄 License

This project is licensed under the MIT License - see the LICENSE file for details.

## 🙏 Acknowledgments

Dedicated to the direct support professionals, clinicians, and educators who work tirelessly to improve the quality of life for individuals with autism and IDD.
