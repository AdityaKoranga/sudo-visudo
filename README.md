# sudo-visudo

sudo su without password

```bash
sudo visudo
```
Find the line that reads root `ALL=(ALL) ALL` and add a new line below it with the following text: `yourusername ALL=(ALL) NOPASSWD: ALL`
Replace yourusername with your actual username.

for example:
```bash
master ALL=(ALL) NOPASSWD: ALL
```
