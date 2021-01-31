# TaskManager
This app organizes and manages the work requested by multiple requesters.

# Description
You can list tasks for each requester and manage response deadlines and response details.

# DEMO
![demo1](https://user-images.githubusercontent.com/68514078/106384589-0371aa80-640f-11eb-87a9-aac066f13959.gif)

![demo2](https://user-images.githubusercontent.com/68514078/106384642-4469bf00-640f-11eb-9589-ca08c9fd3c74.gif)

![demo3](https://user-images.githubusercontent.com/68514078/106384652-4f245400-640f-11eb-8b99-1f9524021b35.gif)

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