## Example Code
##### Provision New LXCs:
`ansible-playbook -i inventory lxc_prov.yml --vault-password-file [VAULTPASSWORDFILE]`


##### Configure home automation LXC:
`ansible-playbook -i inventory homeassistant.yml --vault-password-file [VAULTPASSWORDFILE]`

##### Run playbook against specific IP:
`ansible-playbook -i 192.168.20.71, homeassistant.yml --vault-password-file [VAULTPASSWORDFILE]`

##### Ignore host key checking:
`export ANSIBLE_HOST_KEY_CHECKING=False`