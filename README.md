
# Fix the issue in ubuntu cannot be install

- follow all this command one by one
```python
sudo apt clean
sudo apt --fix-broken install

sudo apt update
sudo rm /var/lib/apt/extended_states
sudo apt update
sudo rm /var/lib/apt/extended_states

sudo apt update


```
