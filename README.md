# MediMetrics
**Personal Health Data Tracker & Communication Hub**

## Team Members
- **Ece Kobanç** (283531)
- **Seda Türköz** (283477)

## Project Description
MediMetrics is a platform for tracking health metrics such as weight, blood pressure, heart rate, step count, calories burned, and heart rate variability (HRV). Users can manually input metrics or sync with IoT devices. The platform provides alerts for water intake, movement, and allows users to join support groups based on health goals. Doctor users can evaluate patient data and offer expert advice. Data is securely stored in XML format and shared among users and healthcare professionals.

## Functional Features
- **User Health Data Tracking**: Users can manually enter health metrics or sync them with IoT devices. Doctors can view patient data for evaluation.
- **Alerts and Notifications**: Reminders for water intake and movement, along with critical health alerts for doctors.
- **Health Goals and Support Groups**: Users can join peer-to-peer support groups, with doctors acting as consultants.
- **User Authentication**: Managed via Firebase for secure user access.
- **Data Entry and Communication**: Health data is stored in XML format and shared securely with stakeholders.

## Technology Stack
- **Frontend**: Flutter for cross-platform mobile development.
- **Backend**: 
  - Firebase Authentication for user management.
  - Firestore for database storage.
  - Cloud Functions (TypeScript) for backend logic.
  - Firebase Cloud Messaging (FCM) for notifications.
- **IoT Integration**: 
  - MQTT protocol for communication between devices.
  - Cloud Functions for processing IoT data.
