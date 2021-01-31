# TaskManager
This app organizes and manages the work requested by multiple requesters.

# Description
You can list tasks for each requester and manage response deadlines and response details.

# DEMO
![sample](https://user-images.githubusercontent.com/68514078/106378576-5d5f7980-63e9-11eb-9d93-ed8ec37f853f.gif)

![sample2](https://user-images.githubusercontent.com/68514078/106378656-e080cf80-63e9-11eb-9e62-2d61a612b336.gif)

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