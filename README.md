# Smart-alloc-pro
AI SmartAlloc Pro is an advanced, feature-rich intelligent resource allocation system designed for educational institutions and organizations. It uses AI-driven algorithms to allocate rooms based on gender distribution, capacity optimization, and seating balance. 
✨ Key Features Implemented
1. 🔐 Secure Login System
Login page with demo credentials (admin / admin123)

Session-based access control

Smooth transition from login to main dashboard

Logout functionality

2. 🎨 Aesthetic Modern UI
Pink pastel theme with gradient backgrounds

Glassmorphism card design (backdrop-filter blur)

Smooth animations (fade-in, slide-up)

Responsive layout for all screen sizes

Dark mode toggle (preserves all features)

3. 🤖 Smart AI Allocation Engine
Gender-Aware Seating: Automatically optimizes seating based on boys/girls count

Auto-Total Calculation: Total students = Boys + Girls (no manual entry needed)

Minimal Waste Logic: Prefers rooms that don't waste seats, especially for minority gender

Balance Optimization: If gender imbalance exists, chooses slightly larger room for better distribution

Intelligent Scoring: Rooms scored based on waste penalty, imbalance factor, and occupancy bonus

4. 📊 Dashboard Page
Real-time statistics (Total Rooms, Scheduled Classes, Avg Utilization)

Room inventory with live search/filter functionality

Recent activity feed

Quick navigation to allocation module

Print dashboard option

5. 🎯 Smart Allocator Page
Input fields for Boys and Girls (with icons)

Auto-calculated Total Students (read-only, AI-powered)

Gender distribution progress bar

Class type selector (Lecture / Lab / Event)

AI allocation button with instant results

Styled Result Card showing:

Selected Room name

Capacity

AI-generated reason (e.g., "Optimized for seating balance and minimal wastage")

Warning tags (red for imbalance, green for optimal)

Room library grid showing all available rooms with capacity and type

Export allocation history to Excel

6. 📅 Schedule Manager Page
Add classes with custom time slots (you control timings)

AI auto-assigns best room based on student count and class type

Conflict detection (prevents double-booking same room at same time)

Weekly Timetable View showing:

Days (Monday to Saturday)

Time slots

Room name displayed in each class block

Click any class block to delete

Export schedule to Excel

Print timetable

7. 📈 Analytics Page (Graphical)
Gender Distribution Chart (Doughnut chart) - Shows average boys vs girls from allocation history

Room Type Usage Chart (Bar chart) - Lectures vs Labs vs Events allocations

Room Utilization Trends (Line chart) - Usage score per room

Allocation History - Timeline of all past allocations

Charts update automatically when new allocations are made

8. 🔧 Additional Features
Dark Mode Toggle - Switch between pink pastel and dark theme (all features preserved)

Room Search/Filter - Live search in room inventory

Export to Excel - Export allocations and schedule data

Print Functionality - Print dashboard and schedule

20+ Rooms - Lecture halls, Labs, Event spaces with various capacities (32 to 200 seats)

Real-time Updates - All inputs trigger automatic re-allocation

Animated Result Card - Fade-in slide-up effect

🏗️ Room Database (20+ Rooms)
Type	Rooms	Capacities
Lecture	Rose Hall, Ivory Lecture, Harmony Room, Innovation Hub, Royal Hall, Library Hall, Graduation Hall, Star Auditorium	40, 45, 50, 60, 72, 85, 100, 120
Lab	Quantum Lab, Bio Lab, Advanced Lab, Robotics Lab, Computing Lab, Physics Lab	32, 35, 38, 42, 45, 50
Event	Event Space, Grand Hall, Atrium, Garden Pavilion, Concert Hall, Expo Center	80, 95, 110, 130, 150, 200
🧠 AI Logic Explained
The system uses a scoring algorithm to select the optimal room:

text
Score = (Waste Penalty × 0.68) + (Imbalance Factor × 30) + Occupancy Bonus
Waste Penalty: Lower is better (encourages minimal empty seats)

Imbalance Factor: Penalizes gender skew (girls < boys increases penalty)

Occupancy Bonus: Rewards rooms with 70-88% utilization

The room with the lowest score is selected.

📱 Pages Structure
Page	Description
Login	Secure entry point with demo credentials
Dashboard	Overview stats, room inventory, recent activity
Smart Allocator	AI-powered room allocation with gender optimization
Schedule Manager	Add/delete classes, conflict detection, room display in timetable
Analytics	Graphical charts and allocation history
🛠️ Technologies Used
HTML5 - Structure

CSS3 - Styling, animations, glassmorphism, dark mode

JavaScript (ES6) - Core logic, AI algorithm

Chart.js - Graphical analytics charts

SheetJS (XLSX) - Export to Excel functionality

Font Awesome 6 - Icons

Google Fonts (Inter) - Typography

🔄 Complete Workflow
Login → Enter credentials to access the system

Dashboard → View room inventory and system stats

Smart Allocator → Enter boys & girls → AI auto-calculates total and suggests best room

Schedule Manager → Add classes with custom times → AI assigns rooms automatically

Analytics → View graphical insights and allocation history

Dark Mode → Toggle theme anytime

Export/Print → Download data or print schedules

✅ All Requirements Met
Requirement	Status
Total students auto-calculated by AI	✅
Gender-aware seating optimization	✅
Avoid wasting seats for girls	✅
Avoid overcrowding for boys	✅
Choose better room if imbalance exists	✅
Styled result card with reason	✅
Warning messages	✅
Pink pastel theme	✅
Icons for inputs	✅
Animated result card	✅
"Smart AI Suggestion" badge	✅
Login page	✅
Graphical analytics (charts)	✅
Voice removed	✅
Aesthetic starting page	✅
All features preserved	✅
🚀 How to Use
Open the HTML file in any modern browser

Login with:

Username: admin

Password: admin123

Navigate using the top navigation bar

On Allocator page: Enter boys and girls → Click "Run AI Allocation"

On Schedule page: Fill class details → Click "Add" → Room auto-assigns

On Analytics page: View charts and history

Click Dark mode button for theme change

Use Export buttons to download Excel files

🎯 System Demo Credentials
Field	Value
Username	admin
Password	admin123
This system demonstrates a production-ready intelligent resource allocation solution with real-time AI capabilities, beautiful UI, and comprehensive features suitable for educational institutions, corporate training centers, and event management organizations.

