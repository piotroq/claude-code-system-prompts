<!--
name: 'Tool Description: TaskUpdate'
description: Description for the TaskUpdate tool, which updates Claude's task list
ccVersion: 2.0.59
-->
Use this tool to update a task in the task list.

You can update any combination of:
- subject: Change the task title
- description: Change the task description
- status: Change to 'open' or 'resolved'
- owner: Assign or change the task owner
- addComment: Add a comment with author and content
- addReferences: Link to other tasks (bidirectional)
- addBlocks: Mark that this task blocks other tasks
- addBlockedBy: Mark that this task is blocked by other tasks

All fields are optional - only provide the fields you want to update.
