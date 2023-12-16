# Objective
The primary aim of this project is to **enhance your teamwork skills** and provide hands-on experience in **collaborative software development**. As you embark on this journey, you'll gain insights into dividing and conquering coding tasks while ensuring a comprehensive understanding of every component.

# Project Breakdown
**Minishell** can be logically split into two main parts:
1. **Parsing**: This segment involves interpreting and processing user input.
2. **Execution**: This phase focuses on the execution of parsed commands.

It's crucial for each team member to grasp both areas to maintain a seamless and cohesive development process.

# Preparation and Documentation
Before diving into the coding, a thorough review of relevant documentation is highly recommended. This preparatory step is key to saving time and enhancing the quality of your project. Even if you decide not to tackle bonus features, understanding their implementation can guide you towards a more robust project architecture.

## Essential Documentation
For a successful implementation, please refer to the [GNU Bash Manual](https://www.gnu.org/savannah-checkouts/gnu/bash/manual/bash.html). Adhering to these guidelines will steer your project in the right direction.

# Personal Insights
Personally, I find the **Minishell project** quite satisfying. Although it might seem like a simple task to create your own shell, it's an engaging and rewarding experience.

# Common Pitfalls
- **Command Handling**: Beware of specific commands like `cat | cat | ls`. These can often lead to blocking issues due to flawed execution logic.
- **File Descriptor Leaks**: Pay close attention to avoid leaking file descriptors, which can be a common oversight in such projects.
- **Memory Management**: Instead of resorting to a garbage collector, explore alternative methods for memory management. This approach not only helps in efficient resource utilization but also aids in better understanding of variable scope and function-specific requirements.
