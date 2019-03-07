# LaMetric Git

This project allows you to push a notification to the LaMetric clock from your `git commit` command using the `prepare-commit-msg` hook.

This notification will include the first two characters of your Git name with the issue number.

Note: This hook will will force you to write the issue number in your commit message.

# Requirements

- LaMetric clock connected to the same network.

# Installation

1. Please make sure to define the LaMetric clock IP in your command by executing the command `export LAMETRIC_IP=192.168.1.101;` * Make sure to write your LaMetric IP here.

2. Copy the `prepare-commit-msg` file into you .git/hooks path inside your project.

3. Edit the `prepare-commit-msg` that you just copied and write your LaMetric Key there.

Happy coding!
