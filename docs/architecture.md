# Smart-Attend System Architecture

The Smart-Attend system consists of a mobile application that automatically records student attendance when they enter a classroom.

## Components

### Student Mobile App
Students open the mobile application to mark attendance automatically.

### Geo-Fencing Module
The system detects whether the student is within the classroom location using GPS.

### Face ID Verification
The system verifies the student's identity using biometric face recognition to prevent proxy attendance.

### Attendance Server
The backend server processes attendance requests and manages communication between the app and database.

### Attendance Database
Stores student attendance records securely.

### Teacher Dashboard
Teachers can view real-time attendance information and reports through a dashboard.