## Установить роли можно следующими командами
```SHELL
ansible-galaxy role install ovirt.infra -p roles/
ansible-galaxy role install ovirt.vm-infra -p roles/
ansible-galaxy role install ovirt.image-template -p roles/
```

Также для корректной работы, в роли `image-template`, в тасках `qcow2_image.yaml` была убран параметр `statin: no` у таски `import_tasks` (начинается в 171 строке)