// Automated task creation based on project type
function automateProjectWorkflow(project) {
    const workflows = {
        'water': [
            { title: 'Initial damage assessment', priority: 'high', duration: 2 },
            { title: 'Water extraction', priority: 'high', duration: 4 },
            { title: 'Set up drying equipment', priority: 'medium', duration: 3 },
            { title: 'Monitor moisture levels', priority: 'medium', duration: 24 },
            { title: 'Final inspection', priority: 'low', duration: 2 }
        ],
        'fire': [
            { title: 'Safety assessment', priority: 'high', duration: 3 },
            { title: 'Smoke damage evaluation', priority: 'high', duration: 4 },
            { title: 'Content inventory', priority: 'medium', duration: 6 },
            { title: 'Cleaning and deodorization', priority: 'medium', duration: 48 },
            { title: 'Restoration work', priority: 'medium', duration: 72 }
        ]
    };
    
    const tasks = workflows[project.type] || [];
    tasks.forEach((task, index) => {
        createTask({
            ...task,
            projectId: project.id,
            assignee: getAvailableTeamMember(),
            startDate: addHours(project.startDate, index * 4)
        });
    });
}
