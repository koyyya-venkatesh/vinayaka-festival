# Vinayaka Festival Tracker

A web-based donation and expense tracking system for PINNINTIPALEM village's annual Vinayaka festival celebrations.

## Features

- **Live Data Sharing**: Real-time data synchronization between all users
- **Donation Tracking**: Record donor details, amounts, payment types, and who received the money
- **Expense Management**: Track festival expenses with item details and purchase information
- **Admin Controls**: Password-protected admin mode with edit/delete capabilities
- **View-Only Mode**: Safe sharing mode for village members to view data
- **Data Export**: Backup functionality with JSON export
- **Responsive Design**: Works on mobile phones, tablets, and computers
- **Indian Theme**: Styled with Indian flag colors and cultural elements

## How to Use

### For Live Data Sharing (Recommended)

1. **Start the Server**:
   ```bash
   python server.py
   ```

2. **Access Locally**:
   - Open `http://localhost:8000` in your browser

3. **Share with Village**:
   - Find your computer's IP address (e.g., 192.168.1.100)
   - Share link: `http://192.168.1.100:8000`
   - Everyone sees the same live data!

### For Offline Use

1. Download `festival_tracker.html`
2. Double-click to open in your web browser
3. Data stays local to your device only

## Admin Features

- **Password**: `vinayaka2025`
- **Admin Mode**: Full access to add, edit, and delete entries
- **View-Only Mode**: Safe mode for sharing with village members
- **Export Data**: Download backup of all donations and expenses
- **Auto-Refresh**: Data updates automatically every 30 seconds

## Live Sharing Benefits

✅ **Real-time Updates**: Any addition is instantly visible to everyone
✅ **No File Sharing**: No need to download/upload files
✅ **Mobile Friendly**: Works on any smartphone or tablet
✅ **Centralized Data**: Single source of truth for all festival data
✅ **Easy Access**: Just share one link with the entire village

## Technical Requirements

- Python 3.6 or higher (for server)
- Any modern web browser
- WiFi network for sharing with village members

## File Structure
```
vinayaka-festival/
├── festival_tracker_server.html (Live server version)
├── festival_tracker.html (Offline version)
├── server.py (Python server for live sharing)
├── start_server.py (Simple server launcher)
└── README.md (This instruction file)
```

## Data Storage

- **Server Mode**: Data stored in `festival_data.json` file
- **Offline Mode**: Data stored in browser only
- Use export feature to backup data anytime

## Tips for Village Use

1. **One Computer as Server**: Keep one computer running the server
2. **Share WiFi Password**: Make sure all users can connect to same network
3. **Admin Access**: Only give admin password to trusted committee members
4. **Regular Backups**: Use export feature daily to backup data
5. **Mobile Access**: All villagers can use their phones to view and add data

## Troubleshooting

- **Cannot Connect**: Check if server computer and user are on same WiFi
- **Data Not Showing**: Click "Refresh Data" button
- **Server Stopped**: Restart `python server.py` on main computer
- **Mobile Issues**: Rotate phone to landscape for better view

---
**Created for:** PINNINTIPALEM Village Vinayaka Festival Committee
**Year:** 2025
**Live Data Sharing**: Enabled for real-time transparency
