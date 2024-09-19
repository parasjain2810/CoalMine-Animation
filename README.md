# Coal Mine Management System

This project is a web and app-based solution designed to enhance productivity and safety in coal mining operations. The system provides a **digital shift handover log** and a **safety management plan** as per DGMS guidelines, ensuring seamless transition and safety for workers and supervisors.

## Key Features
- **Manager Dashboard**: 
  - Manages and assigns shifts to the Head (Mining Sardar).
  - Oversees productivity and performance reports.
  
- **Head (Mining Sardar) Dashboard**: 
  - Receives shift notifications 30 minutes before start time.
  - Marks worker attendance using **facial recognition** and verifies safety gear with the help of **AI/ML models**.
  - Records shift data like gas readings, temperature, and machine failures.
  - Generates detailed **PDF reports** at the end of each shift.
  - Next shift Head can view previous shift details, ensuring continuity.

- **Automated Report Generation**: 
  - Each shift generates a **PDF report** that includes attendance, safety gear status, and key shift metrics like gas readings and equipment failures.

- **AI/ML Integration**:
  - Utilizes **OpenCV** (computer vision) and suitable algorithms to verify workers' safety gear, ensuring accuracy in identifying missing or incomplete gear.

- **Databases**:
  - **Shift Database**: Manages shift creation and assignments.
  - **Workers Database**: Stores worker profiles and work shifts.
  - **Attendance Database**: Tracks attendance and safety gear checks.
  - **Users Database**: Holds login credentials and role assignments.

## Tech Stack
- **Frontend**: React.js for an interactive user interface.
- **Backend**: Node.js and Express.js for handling requests and data flow.
- **Database**: MongoDB for storing shift, worker, attendance, and user data.
- **AI/ML**: Python and OpenCV for facial recognition and safety gear verification.

