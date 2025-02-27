# How to set this up once inside github.dev (if you have not already, visit https://tebothegebo.github.io/deepseek-runner)
Press `ctrl + ~` to open the terminal. When opened, you will see a button to create a codespace or something along those lines.<br>
Click the button to create a codespace.<br>
A popup window will show up asking what specs you want for the codespace. You need to click the one with 16 gigabytes of RAM or it usually will not run.<br>
Once the codespace opens, open the terminal with `ctrl + ~` if you haven't already.<br>
Add a tab to your terminal, which I'll call tab two from now on.
![Here's how to add a tab](tab.png)
Switch to your first tab, and type `curl -fsSL https://ollama.com/install.sh | sh`<br>
Now, type ollama serve and press enter.<br>
Switch to tab two, type `ollama run deepseek-r1`. This will get a minimal terminal setup, but if you want a UI, continue with the next steps.<br>
Type `/bye` in deepseek, then `chmod +x setup.sh`, then `./setup.sh`<br>
Go to the ports section, and look for the port 3000. Hover over the forwarded address field, and click the globe icon to open it.
Click Get Started, type your name, email, and password, and then you're in.
