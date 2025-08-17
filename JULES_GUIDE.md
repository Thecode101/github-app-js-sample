# How to use Jules, your AI Coding Assistant

Hello! I'm Jules, an AI software engineer designed to help you with your coding tasks. This guide explains how I work and how you can best interact with me.

## My Purpose

My main goal is to help you with software development. You can ask me to:
*   Implement new features.
*   Fix bugs.
*   Write tests.
*   Improve existing code.
*   Answer questions about the codebase.

## How I Work

I follow a structured process to ensure I understand your request and deliver a correct solution.

### 1. Understanding the Task

When you give me a task, my first step is to understand it thoroughly. I will:
*   Read the problem description carefully.
*   Explore the codebase using tools like `ls` to list files and `read_file` to read their contents.
*   Examine any relevant documentation, like `README.md` or `AGENTS.md` files.

If your request is unclear, I will ask for clarification using the `request_user_input` tool.

### 2. Creating a Plan

Once I have a good understanding of the task, I will create a step-by-step plan to solve it. I will present this plan to you using the `set_plan` tool. The plan will look something like this:

```markdown
1.  *First step of the plan.*
    -   A brief description of what I will do.
2.  *Second step of the plan.*
    -   Another description.
3.  *And so on...*
```

I will wait for you to approve my plan before I start working.

### 3. Executing the Plan

After you approve the plan, I will start executing it, one step at a time. I have a variety of tools at my disposal to modify the code, including:
*   `create_file_with_block`: To create new files.
*   `overwrite_file_with_block`: To replace the content of existing files.
*   `replace_with_git_merge_diff`: To make targeted changes to files.
*   `run_in_bash_session`: To run commands, such as installing dependencies (`npm install`), running tests (`npm test`), or running linters.

After each modification, I will verify my work to ensure the changes were applied correctly.

### 4. Code Review and Submission

Before I finish, I will always request a code review using the `request_code_review` tool. This helps catch any issues with my work. After addressing any feedback, I will submit my changes using the `submit` tool.

## How to Interact with Me

*   **Be clear and specific.** The more detailed your request, the better I can understand it.
*   **Review my plan.** Make sure my proposed plan aligns with your expectations.
*   **Provide feedback.** If I'm going in the wrong direction, let me know! Your feedback is crucial for my success.

I look forward to working with you!
