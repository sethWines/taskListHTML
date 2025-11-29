# Task List Manager

A comprehensive task management application with priorities, categories, subtasks, and advanced editing capabilities.

**✅ FULLY PORTABLE** - This application is completely self-contained with no external dependencies. All CSS, JavaScript, and assets are embedded directly in the HTML files. You can:
- Move the entire folder anywhere
- Copy it to USB drives or cloud storage
- Share it with others
- Open it offline without internet connection
- No external stylesheets, scripts, or resources required

## Features

### Core Functionality
- ✅ **Task Management**: Create, edit, delete, and archive tasks
- 📋 **Subtasks**: Break down larger tasks into manageable steps
- 🎯 **Priorities**: High, Medium, and Low priority levels
- 🏷️ **Categories**: Organize tasks by category (Work, Personal, Shopping, Health, Other)
- 📅 **Completion Tracking**: Automatically tracks completion dates for tasks and subtasks

### Advanced Features
- 📝 **Comprehensive Editor**: Open any task in a dedicated editor window/tab with:
  - Large text areas for detailed descriptions
  - Full subtask management (add, edit, delete, reorder)
  - Easy priority and category changes
  - Changes save back to the main task list automatically

- 🔄 **Cross-Tab Synchronization**: 
  - Open multiple tabs safely - changes sync automatically across all tabs
  - Real-time updates when edits are made in any tab
  - Visual notifications when data syncs from another tab
  - No more lost changes when working across multiple windows

- 💾 **Data Management**:
  - Export tasks for email sharing
  - Manual backup to timestamped JSON files
  - Import tasks (merge or replace)
  - Auto-backup to a folder (Chrome/Edge only)

- 🔍 **Filtering & Organization**:
  - Filter by status (All, Active, Completed)
  - Filter by priority (High, Medium, Low)
  - View archived tasks separately
  - Sort tasks by priority automatically

## Files

- **task-list.html** - Main task list manager application
- **task-list-how.html** - Detailed usage instructions and best practices
- **README.md** - This file

## Usage

### Opening the Task List
1. Open `task-list.html` in any modern web browser
2. Your tasks are automatically saved to browser localStorage

### Using the Comprehensive Editor
1. Click the **📝 Editor** button on any task card
2. A new window will open with a full-featured editor
3. Edit all task details:
   - Title and description (larger text areas)
   - Priority and category
   - Add, edit, or delete subtasks
   - Toggle subtask completion status
4. Click **💾 Save Changes** to save back to the main list
5. Changes sync instantly with the main window

### Auto-Backup (Chrome/Edge only)
1. Click the **Auto-Backup** button
2. Select a folder for automatic backups
3. Your tasks will be saved to `tasks-auto-backup.json`:
   - Every hour automatically
   - When you close the browser
   - File is overwritten each time

### Manual Backups (Recommended)
1. Click **Backup Tasks** to download a timestamped backup file
2. Save multiple versions for different points in time
3. Use **Import Tasks** to restore from backup

## Data Storage

- **Local**: All tasks are stored in browser localStorage (100% private, no servers)
- **Persistent**: Tasks survive browser refreshes and computer restarts
- **Browser-Specific**: Each browser has its own task list
- **Portable**: Use backup/import to move tasks between computers or browsers
- **Multi-Tab Safe**: Changes sync automatically across all open tabs in real-time

## Browser Compatibility

- ✅ **Full Support**: Chrome, Edge, Opera (Chromium-based browsers)
- ⚠️ **Limited Support**: Firefox, Safari (no auto-backup feature)
- 📝 **Editor**: Works in all modern browsers

## Tips

- Use the comprehensive editor for complex tasks with many subtasks
- Create manual backups weekly or before major changes
- Archive completed tasks to keep your active list clean
- Use priorities to focus on what matters most
- Break large tasks into subtasks for better tracking
- **Open multiple tabs safely** - changes sync automatically across all tabs

## Version

Current Version: 1.0

## Location

This task list was moved from `notes/content/` to its own directory at `task-list/` for better organization.

All references in the main hub have been updated to point to the new location.









