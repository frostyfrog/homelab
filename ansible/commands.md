```
ansible-playbook dummy.yml --ask-pass -v -i dummyinventory.cfg
```
Create a dummy file using host specific variables

```
ansible-playbook dummy_varfile.yml --ask-pass -v -i inventory.cfg
```
Create a dummy file using vars from a varfile
