# ansible-workstation
## Usage

```BASH
./init.sh
ansible-playbook main.yml -i inventory -e "user=yourusername user_email=you@example.com" --become -K
```
