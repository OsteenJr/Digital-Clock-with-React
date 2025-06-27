# Digital-Clock-with-React
Built a Digital Clock with React
✨ Feature: Digital Clock Component

Overview:
Implemented a real-time digital clock component that displays the current time in a user-friendly 12-hour format with automatic updates.

Features:
Real-time Updates: Clock refreshes every second using setInterval
12-Hour Format: Displays time in standard 12-hour format with AM/PM indicator
Zero-Padding: Ensures consistent formatting (e.g., "09:05:03" instead of "9:5:3")
Memory Management: Proper cleanup of intervals to prevent memory leaks
React Hooks: Utilizes modern React patterns with useState and useEffect

Technical Implementation:
State management with useState to store current time
useEffect hook with cleanup function for interval management
Custom updateClock() function for time formatting logic
Modular component design for easy reuse and maintenance