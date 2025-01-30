# KanDo

A **no-build** kanban board todo app

Deployed at [KanDo](https://kando.kvrt.xyz)

## Features

- [x] Drag and drop
- [x] Theme engine
- [x] Tag engine
- [x] Task management
- [x] Task sorting
- [x] Task filtering
- [x] Task editing
- [x] Task deleting

## Roadmap

- [ ] Persist data to db (edge or traditional | shoot me some bleeding edge ideas)
- [ ] User authentication (login, register, logout)
- [ ] Task priority (this is possible right now with tags, albiet not in a way that is intuitive)
- [ ] Task dependencies (relation to another task, this can also besubtasks)
- [ ] Task scheduling (recurring tasks, dealines, expirations, etc)
- [ ] Task notifications (email, push, etc)
- [ ] Task sharing (create public and private tasks, task lists, and boards)

## Installation

- Clone the repo `git clone https://github.com/kmal808/KanDo`
- Use the "Live Server" vscode extension or a local http server such as the nodejs package `http-server` to run the app

## Considerations

- Until an API is implemented, the tasks are stored in local storage
- The markup, interactivity, and styling all live in one file
