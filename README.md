# ansible-wireguard-pi
Install wireguard VPN on raspberry then retrieve a created client

Fill clients you want to provide within the `playbook.yaml`

```bash
# publicIP is the public ip of your wireguard server
ansible-playbook -i inventory.ini playbook.yaml --extra-vars "publicIP=1.23.45"
```
