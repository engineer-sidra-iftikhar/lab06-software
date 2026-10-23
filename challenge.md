# Challenge Answers

1. htop shows CPU usage, memory usage and the running processes.
   Command: sudo apt install -y htop, then htop

2. Ubuntu offers apache2 version 2.4.xx (write your version here).
   Command: apt show apache2 | head -4

3. There are XXX packages installed now (write your number).
   Command: apt list --installed | wc -l

4. Output: Hello from Alpine
   Command: sudo docker run --rm alpine echo "Hello from Alpine"

5. Docker key file: /etc/apt/keyrings/docker.asc
   Docker sources file: /etc/apt/sources.list.d/docker.sources

6. htop is removed. After removing it, htop says "command not found".
   Command: sudo apt remove -y htop, then hash -r, then htop
