# A development container for Elixir

This is an opinionated [Dev Container](https://containers.dev) for Elixir (1.18).

## Using with Visual Studio Code

Follow the steps below to use the Dev Container with Visual Studio Code:

1. Follow the [Getting Started](https://code.visualstudio.com/docs/remote/containers#_getting-started) instructions to configure Visual Studio Code and Docker for use with Dev Containers;
2. Copy the `.devcontainer` folder in this repository to the root of your project;
3. Reload the project by opening the command palette (<kbd>Ctrl</kbd> + <kbd>Shift</kbd> + <kbd>P</kbd> or <kbd>Cmd</kbd> + <kbd>Shift</kbd> + <kbd>P</kbd>) and executing the command `>Reload Window` or by closing and re-opening Visual Studio Code;
4. Click `Reopen in Container` when Visual Studio Code prompts you (see image below), or by opening the command palette (<kbd>Ctrl</kbd> + <kbd>Shift</kbd> + <kbd>P</kbd> or <kbd>Cmd</kbd> + <kbd>Shift</kbd> + <kbd>P</kbd>) and executing the command `>Dev Containers: Reopen in Container`;
5. (Optional) Copy `.vscode` and `.iex.exs` in this repository to the root of your project.

## How does it work

Visual Studio Code supports [Dev Containers](https://code.visualstudio.com/docs/remote/containers) (i.e. using a Docker image as a development environment). It automates the hassle of setting up a proper development environment.

## What's in the box

The container comes with the following (relevant) software pre-installed:

- [`elixir:1.18.2-otp-25`](https://hub.docker.com/_/elixir) as a base image;
- [GNU Bash](https://www.gnu.org/software/bash/);
- [Git](https://git-scm.com/);
- [Neovim](https://neovim.io/);
- [Mix](https://hexdocs.pm/mix/Mix.html);
- [Dialyzer](https://www.erlang.org/doc/apps/dialyzer/dialyzer.html).

Following VSCode extensions are automatically installed after container is started:

- [ElixirLS: Elixir support and debugger](https://marketplace.visualstudio.com/items?itemName=jakebecker.elixir-ls);
- [Credo (Elixir Linter)](https://marketplace.visualstudio.com/items?itemName=pantajoe.vscode-elixir-credo).