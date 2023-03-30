# Ansible Semaphore

Ansible Semaphore is a modern UI for Ansible. It lets you easily run Ansible playbooks, get notifications about fails, control access to deployment system.

This repository is a slightly altered version of the 2.8.9 release that disables any form of write-access to non global-admins or non project-admins. These changes are not pushed to the main project because of the development effort to implement RBAC.

# Build instructions

To build this version, you need to follow the folling step;

<ul>
  <li>Install Git.</li>
  <li>Install Go.</li>
  <li>Install Go-Task.</li>
  <li>Install Goreleaser.</li>
  <li>Add Go to PATH.</li>
  <li>Clone the repository (git clone https://github.com/Walkablenormal/Semaphore_2.8.9_RBAC_FIX.git).</li>
  <li>Enter the folder.</li>
  <li>Use Go-Task to build (task -t Taskfile.yml all).</li>
  <li>Enter the newly-created 'bin' folder.</li>
  <li>Install Semaphore (./semaphore setup).</li>
</ul>

## Support the developer!

If you like Ansible Semaphore, you can support the project development on [Ko-fi](https://ko-fi.com/fiftin).

[<img src="https://user-images.githubusercontent.com/914224/203517453-4febf7f6-debb-4be9-b6a2-a3b19f5d9f9a.png">](https://ko-fi.com/fiftin)

## License

MIT License

Copyright (c) 2016 Castaway Consulting LLC

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.
