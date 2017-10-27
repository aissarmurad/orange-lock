# orange-lock
A simple electronic RFID lock with Orange Pi and MFRC522

Ansible usage examples:


ansible-playbook -i inventory instantiate.yml --extra-vars "target=door01"

ansible-playbook -i inventory instantiate.yml --extra-vars "target=door01" 
--start-at-task='Install "SPI-Py" python package'

