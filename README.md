# Sripion 🦂 - Lightweight desktop script manager

<p align="center">
<img width="300" alt="Group 97" src="https://github.com/nomadiz/scripion/assets/56880684/c097d4fe-386a-4c33-a280-e92f7308c852">
</p>

Scripion is a versatile tool designed to streamline command management on your device. For developers and engineers who often find themselves navigating the intricacies of the shell and terminal, Scripion is a trusted companion. While these command-line interfaces are invaluable for complex tasks, not all commands require their full attention.

With Scripion, you can effortlessly organize and execute a wide range of commands without the need for constant terminal interaction. This user-friendly application simplifies the process of handling basic scripts, allowing you to focus your valuable terminal resources on more critical tasks.

# Features
## Store commands in your workspace
![Group 98](https://github.com/nomadiz/scripion/assets/56880684/13835986-a107-4935-a04e-1e7326874e50)


Scripion allows you to store, update workspace name, and remove workspaces easily. Regarding privacy concerns, workspaces are stored locally on your device using SQLite3. 
### Integrate with different framework projects
Support: `package.json` projects
Scripion automatically reads package.json from the imported workspaces and stores them as Scripion's workspace scripts with interactive UI. To import the workspace, click on the **+ Add workspace** button. If the workspace is not a valid project, it won't be imported to Scripion.
## Execute command with one click


## View script history of multiple shells
![Group 99](https://github.com/nomadiz/scripion/assets/56880684/ab16c06c-7ad3-4ec3-a439-06fdf97e4ff0)

Scripion streamlines script history management by offering a unified view of scripts executed across various shells. This feature simplifies record-keeping, ensuring that you can efficiently trace your scripting activities.

**📝 Scripion does not store your data**, it is designed to utilize the `history` command of the shell feature.
