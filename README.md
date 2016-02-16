# StackStorm Lint Configs

This repository contains lint configs for different programming languages and
tools (flake8, pylint, etc.) used by different StackStorm repositories.

Configs are grouped in sub-directories by programming language.

## Usage

To use those configs, add this repository as a git subtree / submodule to the
repository where you want to utilize those configs. After that is done, update
make targets (or similar) to correctly pass path to the configs to the tools
in question.
