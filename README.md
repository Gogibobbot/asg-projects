# Brothers - Professional Project Management Dashboard

A modern, professional-grade project management and kanban board system for team collaboration and task tracking.

## Features

### 📋 Kanban Board
- **5-Stage Workflow**: Backlog → Todo → In Progress → Review → Done
- **Approval System**: Tasks only mark as complete after explicit approval
- **Priority Levels**: High, Medium, Low with visual indicators
- **Progress Tracking**: Real-time progress bars for active tasks
- **Team Assignment**: Track who's working on what

### 📊 Projects Management
- **Active Projects**: Main initiatives and ongoing work
- **Testing & Prototypes**: Experimental projects and POC work
- **Progress Visualization**: Beautiful progress bars and status indicators
- **Metrics Dashboard**: Real-time statistics and KPIs

### 📈 Analytics
- **Team Velocity**: Sprint capacity metrics
- **Completion Rate**: Task completion tracking
- **Cycle Time**: Average time from start to completion
- **On-Time Delivery**: Schedule adherence tracking

## Design Highlights

- **Dark Professional Theme**: Modern gradient background with glassmorphism
- **Responsive Grid**: Auto-adjusting columns based on screen size
- **Real-time Metrics**: Live counting of tasks in each stage
- **Smooth Animations**: Polished interactions and transitions
- **Accessible UI**: Clear typography and color coding

## Tech Stack

- Pure HTML5, CSS3, JavaScript (no dependencies)
- GitHub Pages hosting
- Responsive design (mobile-friendly)

## Usage

### Switch Tabs
Click the navigation buttons at the top to switch between:
- **Kanban**: Task management board
- **Projects**: Active and test projects
- **Analytics**: Performance metrics

### Move Tasks
Click the action buttons on each task card to move it through the workflow:
- **Start Work**: Move from Backlog/Todo to In Progress
- **Ready**: Move from In Progress to Review
- **Approve/Reject**: Review stage decisions

### Add Tasks
Click the "+ Add Task" button in any column (implementation in progress)

## Deployment

### GitHub Pages (Recommended)
1. Push to main branch
2. GitHub Pages auto-deploys from the repository
3. Access via: `https://yourusername.github.io/brothers/`

### Local Development
Simply open `index.html` in a modern web browser.

## Project Structure

```
brothers/
├── index.html      # Main dashboard
├── README.md       # This file
└── .gitignore      # Git ignore rules
```

## Architecture

The dashboard uses a columnar kanban board with:
- **Backlog**: Unstarted work items
- **Todo**: Ready to begin
- **In Progress**: Active work with progress tracking
- **Review**: Awaiting approval
- **Done**: Completed and approved tasks

## Future Enhancements

- Task persistence (localStorage or backend)
- User authentication
- Real-time collaboration
- Custom fields and templates
- Advanced filtering and search
- Export and reporting

## Support

For issues or suggestions, reach out to the team.

---

Built with ❤️ for efficient project management.
