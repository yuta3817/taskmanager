# TaskManager
This app organizes and manages the work requested by multiple requesters.

# Description
You can list tasks for each requester and manage response deadlines and response details.

# DEMO
![demo]
(https://raw.github.com/wiki/yuta3817/taskmanager/images/sample.gif)

# Requirement
- ruby '2.6.6'
- rails, '~> 6.0.3', '>= 6.0.3.4'
- bootsnap, '>= 1.4.2'
- devise

# Er diagram
[erd.pdf](https://github.com/yuta3817/taskmanager/files/5888033/erd.pdf)

# Usage
$ git clone https://github.com/yuta3817/taskmanager.git
$ cd taskmanager
$ bundle install
$ rails db:create
$ rails db:migrate
$ rails s
👉 http://localhost:3000

# Author
- Yuta Abe

# License
"TaskManager" is under MIT license.