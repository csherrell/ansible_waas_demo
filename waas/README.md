## Output of `vagrant provision`
```
❯ vagrant provision
==> om.noc.nas.waas: Running provisioner: ansible...
    om.noc.nas.waas: Running ansible-playbook...
PYTHONUNBUFFERED=1 ANSIBLE_FORCE_COLOR=true ANSIBLE_CONFIG='../ansible/ansible.cfg' ANSIBLE_HOST_KEY_CHECKING=false ANSIBLE_SSH_ARGS='-o UserKnownHostsFile=/dev/null -o IdentitiesOnly=yes -o ControlMaster=auto -o ControlPersist=60s' ansible-playbook --connection=ssh --timeout=30 --limit="om.noc.nas.waas" --inventory-file=/user/home/csherrell/git/faa/ansible_waas_demo/waas/.vagrant/provisioners/ansible/inventory -v ../ansible/om.yml
Using /user/home/csherrell/git/faa/ansible_waas_demo/ansible/ansible.cfg as config file

PLAY [all] *********************************************************************

TASK [Gathering Facts] *********************************************************
ok: [om.noc.nas.waas]

TASK [common : Hello! I am the Common Playbook.] *******************************
ok: [om.noc.nas.waas] =>
  msg: I am everywhere you want to be!

TASK [om : Hello! I am an O&M] *************************************************
ok: [om.noc.nas.waas] =>
  msg: I am special! I have a 3 screen GUI Display!

TASK [om : Fun Group Fact] *****************************************************
ok: [om.noc.nas.waas] =>
  msg: There are 2 O&Ms

TASK [om : Tell Me About Yourself] *********************************************
ok: [om.noc.nas.waas] =>
  msg: My name is om.noc.nas.waas

PLAY RECAP *********************************************************************
om.noc.nas.waas            : ok=5    changed=0    unreachable=0    failed=0    skipped=0    rescued=0    ignored=0

==> om.poc.nas.waas: Running provisioner: ansible...
    om.poc.nas.waas: Running ansible-playbook...
PYTHONUNBUFFERED=1 ANSIBLE_FORCE_COLOR=true ANSIBLE_CONFIG='../ansible/ansible.cfg' ANSIBLE_HOST_KEY_CHECKING=false ANSIBLE_SSH_ARGS='-o UserKnownHostsFile=/dev/null -o IdentitiesOnly=yes -o ControlMaster=auto -o ControlPersist=60s' ansible-playbook --connection=ssh --timeout=30 --limit="om.poc.nas.waas" --inventory-file=/user/home/csherrell/git/faa/ansible_waas_demo/waas/.vagrant/provisioners/ansible/inventory -v ../ansible/om.yml
Using /user/home/csherrell/git/faa/ansible_waas_demo/ansible/ansible.cfg as config file

PLAY [all] *********************************************************************

TASK [Gathering Facts] *********************************************************
ok: [om.poc.nas.waas]

TASK [common : Hello! I am the Common Playbook.] *******************************
ok: [om.poc.nas.waas] =>
  msg: I am everywhere you want to be!

TASK [om : Hello! I am an O&M] *************************************************
ok: [om.poc.nas.waas] =>
  msg: I am special! I have a 3 screen GUI Display!

TASK [om : Fun Group Fact] *****************************************************
ok: [om.poc.nas.waas] =>
  msg: There are 2 O&Ms

TASK [om : Tell Me About Yourself] *********************************************
ok: [om.poc.nas.waas] =>
  msg: My name is om.poc.nas.waas

PLAY RECAP *********************************************************************
om.poc.nas.waas            : ok=5    changed=0    unreachable=0    failed=0    skipped=0    rescued=0    ignored=0

==> a.wre.bet.nas.waas: Running provisioner: ansible...
    a.wre.bet.nas.waas: Running ansible-playbook...
PYTHONUNBUFFERED=1 ANSIBLE_FORCE_COLOR=true ANSIBLE_CONFIG='../ansible/ansible.cfg' ANSIBLE_HOST_KEY_CHECKING=false ANSIBLE_SSH_ARGS='-o UserKnownHostsFile=/dev/null -o IdentitiesOnly=yes -o ControlMaster=auto -o ControlPersist=60s' ansible-playbook --connection=ssh --timeout=30 --limit="a.wre.bet.nas.waas" --inventory-file=/user/home/csherrell/git/faa/ansible_waas_demo/waas/.vagrant/provisioners/ansible/inventory -v ../ansible/wre.yml
Using /user/home/csherrell/git/faa/ansible_waas_demo/ansible/ansible.cfg as config file

PLAY [all] *********************************************************************

TASK [Gathering Facts] *********************************************************
ok: [a.wre.bet.nas.waas]

TASK [common : Hello! I am the Common Playbook.] *******************************
ok: [a.wre.bet.nas.waas] =>
  msg: I am everywhere you want to be!

TASK [wre : Hello! I am a WRE] *************************************************
ok: [a.wre.bet.nas.waas] =>
  msg: I am special! I make all the dataz!

TASK [wre : Fun Group Fact] ****************************************************
ok: [a.wre.bet.nas.waas] =>
  msg: There are 114 WREs

TASK [wre : Tell Me About Yourself] ********************************************
ok: [a.wre.bet.nas.waas] =>
  msg: My name is a.wre.bet.nas.waas

PLAY RECAP *********************************************************************
a.wre.bet.nas.waas         : ok=5    changed=0    unreachable=0    failed=0    skipped=0    rescued=0    ignored=0

==> b.wre.bet.nas.waas: Running provisioner: ansible...
    b.wre.bet.nas.waas: Running ansible-playbook...
PYTHONUNBUFFERED=1 ANSIBLE_FORCE_COLOR=true ANSIBLE_CONFIG='../ansible/ansible.cfg' ANSIBLE_HOST_KEY_CHECKING=false ANSIBLE_SSH_ARGS='-o UserKnownHostsFile=/dev/null -o IdentitiesOnly=yes -o ControlMaster=auto -o ControlPersist=60s' ansible-playbook --connection=ssh --timeout=30 --limit="b.wre.bet.nas.waas" --inventory-file=/user/home/csherrell/git/faa/ansible_waas_demo/waas/.vagrant/provisioners/ansible/inventory -v ../ansible/wre.yml
Using /user/home/csherrell/git/faa/ansible_waas_demo/ansible/ansible.cfg as config file

PLAY [all] *********************************************************************

TASK [Gathering Facts] *********************************************************
ok: [b.wre.bet.nas.waas]

TASK [common : Hello! I am the Common Playbook.] *******************************
ok: [b.wre.bet.nas.waas] =>
  msg: I am everywhere you want to be!

TASK [wre : Hello! I am a WRE] *************************************************
ok: [b.wre.bet.nas.waas] =>
  msg: I am special! I make all the dataz!

TASK [wre : Fun Group Fact] ****************************************************
ok: [b.wre.bet.nas.waas] =>
  msg: There are 114 WREs

TASK [wre : Tell Me About Yourself] ********************************************
ok: [b.wre.bet.nas.waas] =>
  msg: My name is b.wre.zsu.nas.waas

PLAY RECAP *********************************************************************
b.wre.bet.nas.waas         : ok=5    changed=0    unreachable=0    failed=0    skipped=0    rescued=0    ignored=0

==> c.wre.bet.nas.waas: Running provisioner: ansible...
    c.wre.bet.nas.waas: Running ansible-playbook...
PYTHONUNBUFFERED=1 ANSIBLE_FORCE_COLOR=true ANSIBLE_CONFIG='../ansible/ansible.cfg' ANSIBLE_HOST_KEY_CHECKING=false ANSIBLE_SSH_ARGS='-o UserKnownHostsFile=/dev/null -o IdentitiesOnly=yes -o ControlMaster=auto -o ControlPersist=60s' ansible-playbook --connection=ssh --timeout=30 --limit="c.wre.bet.nas.waas" --inventory-file=/user/home/csherrell/git/faa/ansible_waas_demo/waas/.vagrant/provisioners/ansible/inventory -v ../ansible/wre.yml
Using /user/home/csherrell/git/faa/ansible_waas_demo/ansible/ansible.cfg as config file

PLAY [all] *********************************************************************

TASK [Gathering Facts] *********************************************************
ok: [c.wre.bet.nas.waas]

TASK [common : Hello! I am the Common Playbook.] *******************************
ok: [c.wre.bet.nas.waas] =>
  msg: I am everywhere you want to be!

TASK [wre : Hello! I am a WRE] *************************************************
ok: [c.wre.bet.nas.waas] =>
  msg: I am special! I make all the dataz!

TASK [wre : Fun Group Fact] ****************************************************
ok: [c.wre.bet.nas.waas] =>
  msg: There are 114 WREs

TASK [wre : Tell Me About Yourself] ********************************************
ok: [c.wre.bet.nas.waas] =>
  msg: My name is c.wre.bet.nas.waas

PLAY RECAP *********************************************************************
c.wre.bet.nas.waas         : ok=5    changed=0    unreachable=0    failed=0    skipped=0    rescued=0    ignored=0

==> a.wre.zsu.nas.waas: Running provisioner: ansible...
    a.wre.zsu.nas.waas: Running ansible-playbook...
PYTHONUNBUFFERED=1 ANSIBLE_FORCE_COLOR=true ANSIBLE_CONFIG='../ansible/ansible.cfg' ANSIBLE_HOST_KEY_CHECKING=false ANSIBLE_SSH_ARGS='-o UserKnownHostsFile=/dev/null -o IdentitiesOnly=yes -o ControlMaster=auto -o ControlPersist=60s' ansible-playbook --connection=ssh --timeout=30 --limit="a.wre.zsu.nas.waas" --inventory-file=/user/home/csherrell/git/faa/ansible_waas_demo/waas/.vagrant/provisioners/ansible/inventory -v ../ansible/wre.yml
Using /user/home/csherrell/git/faa/ansible_waas_demo/ansible/ansible.cfg as config file

PLAY [all] *********************************************************************

TASK [Gathering Facts] *********************************************************
ok: [a.wre.zsu.nas.waas]

TASK [common : Hello! I am the Common Playbook.] *******************************
ok: [a.wre.zsu.nas.waas] =>
  msg: I am everywhere you want to be!

TASK [wre : Hello! I am a WRE] *************************************************
ok: [a.wre.zsu.nas.waas] =>
  msg: I am special! I make all the dataz!

TASK [wre : Fun Group Fact] ****************************************************
ok: [a.wre.zsu.nas.waas] =>
  msg: There are 114 WREs

TASK [wre : Tell Me About Yourself] ********************************************
ok: [a.wre.zsu.nas.waas] =>
  msg: My name is a.wre.zsu.nas.waas

PLAY RECAP *********************************************************************
a.wre.zsu.nas.waas         : ok=5    changed=0    unreachable=0    failed=0    skipped=0    rescued=0    ignored=0

==> b.wre.zsu.nas.waas: Running provisioner: ansible...
    b.wre.zsu.nas.waas: Running ansible-playbook...
PYTHONUNBUFFERED=1 ANSIBLE_FORCE_COLOR=true ANSIBLE_CONFIG='../ansible/ansible.cfg' ANSIBLE_HOST_KEY_CHECKING=false ANSIBLE_SSH_ARGS='-o UserKnownHostsFile=/dev/null -o IdentitiesOnly=yes -o ControlMaster=auto -o ControlPersist=60s' ansible-playbook --connection=ssh --timeout=30 --limit="b.wre.zsu.nas.waas" --inventory-file=/user/home/csherrell/git/faa/ansible_waas_demo/waas/.vagrant/provisioners/ansible/inventory -v ../ansible/wre.yml
Using /user/home/csherrell/git/faa/ansible_waas_demo/ansible/ansible.cfg as config file

PLAY [all] *********************************************************************

TASK [Gathering Facts] *********************************************************
ok: [b.wre.zsu.nas.waas]

TASK [common : Hello! I am the Common Playbook.] *******************************
ok: [b.wre.zsu.nas.waas] =>
  msg: I am everywhere you want to be!

TASK [wre : Hello! I am a WRE] *************************************************
ok: [b.wre.zsu.nas.waas] =>
  msg: I am special! I make all the dataz!

TASK [wre : Fun Group Fact] ****************************************************
ok: [b.wre.zsu.nas.waas] =>
  msg: There are 114 WREs

TASK [wre : Tell Me About Yourself] ********************************************
ok: [b.wre.zsu.nas.waas] =>
  msg: My name is b.wre.zsu.nas.waas

PLAY RECAP *********************************************************************
b.wre.zsu.nas.waas         : ok=5    changed=0    unreachable=0    failed=0    skipped=0    rescued=0    ignored=0

==> c.wre.zsu.nas.waas: Running provisioner: ansible...
    c.wre.zsu.nas.waas: Running ansible-playbook...
PYTHONUNBUFFERED=1 ANSIBLE_FORCE_COLOR=true ANSIBLE_CONFIG='../ansible/ansible.cfg' ANSIBLE_HOST_KEY_CHECKING=false ANSIBLE_SSH_ARGS='-o UserKnownHostsFile=/dev/null -o IdentitiesOnly=yes -o ControlMaster=auto -o ControlPersist=60s' ansible-playbook --connection=ssh --timeout=30 --limit="c.wre.zsu.nas.waas" --inventory-file=/user/home/csherrell/git/faa/ansible_waas_demo/waas/.vagrant/provisioners/ansible/inventory -v ../ansible/wre.yml
Using /user/home/csherrell/git/faa/ansible_waas_demo/ansible/ansible.cfg as config file

PLAY [all] *********************************************************************

TASK [Gathering Facts] *********************************************************
ok: [c.wre.zsu.nas.waas]

TASK [common : Hello! I am the Common Playbook.] *******************************
ok: [c.wre.zsu.nas.waas] =>
  msg: I am everywhere you want to be!

TASK [wre : Hello! I am a WRE] *************************************************
ok: [c.wre.zsu.nas.waas] =>
  msg: I am special! I make all the dataz!

TASK [wre : Fun Group Fact] ****************************************************
ok: [c.wre.zsu.nas.waas] =>
  msg: There are 114 WREs

TASK [wre : Tell Me About Yourself] ********************************************
ok: [c.wre.zsu.nas.waas] =>
  msg: My name is c.wre.zsu.nas.waas

PLAY RECAP *********************************************************************
c.wre.zsu.nas.waas         : ok=5    changed=0    unreachable=0    failed=0    skipped=0    rescued=0    ignored=0

==> cp1.cv.zdc.nas.waas: Running provisioner: ansible...
    cp1.cv.zdc.nas.waas: Running ansible-playbook...
PYTHONUNBUFFERED=1 ANSIBLE_FORCE_COLOR=true ANSIBLE_CONFIG='../ansible/ansible.cfg' ANSIBLE_HOST_KEY_CHECKING=false ANSIBLE_SSH_ARGS='-o UserKnownHostsFile=/dev/null -o IdentitiesOnly=yes -o ControlMaster=auto -o ControlPersist=60s' ansible-playbook --connection=ssh --timeout=30 --limit="cp1.cv.zdc.nas.waas" --inventory-file=/user/home/csherrell/git/faa/ansible_waas_demo/waas/.vagrant/provisioners/ansible/inventory -v ../ansible/cv.yml
Using /user/home/csherrell/git/faa/ansible_waas_demo/ansible/ansible.cfg as config file

PLAY [all] *********************************************************************

TASK [Gathering Facts] *********************************************************
ok: [cp1.cv.zdc.nas.waas]

TASK [common : Hello! I am the Common Playbook.] *******************************
ok: [cp1.cv.zdc.nas.waas] =>
  msg: I am everywhere you want to be!

TASK [cv : Hello! I am a C&V] **************************************************
ok: [cp1.cv.zdc.nas.waas] =>
  msg: I am special! I am the Master of the WAAS Universe!

TASK [cv : Fun Group Fact] *****************************************************
ok: [cp1.cv.zdc.nas.waas] =>
  msg: There are 3 C&Vs

TASK [cv : Tell Me About Yourself] *********************************************
ok: [cp1.cv.zdc.nas.waas] =>
  msg: My name is cp1.cv.zdc.nas.waas

PLAY RECAP *********************************************************************
cp1.cv.zdc.nas.waas        : ok=5    changed=0    unreachable=0    failed=0    skipped=0    rescued=0    ignored=0

==> cp1.cv.zla.nas.waas: Running provisioner: ansible...
    cp1.cv.zla.nas.waas: Running ansible-playbook...
PYTHONUNBUFFERED=1 ANSIBLE_FORCE_COLOR=true ANSIBLE_CONFIG='../ansible/ansible.cfg' ANSIBLE_HOST_KEY_CHECKING=false ANSIBLE_SSH_ARGS='-o UserKnownHostsFile=/dev/null -o IdentitiesOnly=yes -o ControlMaster=auto -o ControlPersist=60s' ansible-playbook --connection=ssh --timeout=30 --limit="cp1.cv.zla.nas.waas" --inventory-file=/user/home/csherrell/git/faa/ansible_waas_demo/waas/.vagrant/provisioners/ansible/inventory -v ../ansible/cv.yml
Using /user/home/csherrell/git/faa/ansible_waas_demo/ansible/ansible.cfg as config file

PLAY [all] *********************************************************************

TASK [Gathering Facts] *********************************************************
ok: [cp1.cv.zla.nas.waas]

TASK [common : Hello! I am the Common Playbook.] *******************************
ok: [cp1.cv.zla.nas.waas] =>
  msg: I am everywhere you want to be!

TASK [cv : Hello! I am a C&V] **************************************************
ok: [cp1.cv.zla.nas.waas] =>
  msg: I am special! I am the Master of the WAAS Universe!

TASK [cv : Fun Group Fact] *****************************************************
ok: [cp1.cv.zla.nas.waas] =>
  msg: There are 3 C&Vs

TASK [cv : Tell Me About Yourself] *********************************************
ok: [cp1.cv.zla.nas.waas] =>
  msg: My name is cp1.cv.zla.nas.waas

PLAY RECAP *********************************************************************
cp1.cv.zla.nas.waas        : ok=5    changed=0    unreachable=0    failed=0    skipped=0    rescued=0    ignored=0

==> cp1.cv.ztl.nas.waas: Running provisioner: ansible...
    cp1.cv.ztl.nas.waas: Running ansible-playbook...
PYTHONUNBUFFERED=1 ANSIBLE_FORCE_COLOR=true ANSIBLE_CONFIG='../ansible/ansible.cfg' ANSIBLE_HOST_KEY_CHECKING=false ANSIBLE_SSH_ARGS='-o UserKnownHostsFile=/dev/null -o IdentitiesOnly=yes -o ControlMaster=auto -o ControlPersist=60s' ansible-playbook --connection=ssh --timeout=30 --limit="cp1.cv.ztl.nas.waas" --inventory-file=/user/home/csherrell/git/faa/ansible_waas_demo/waas/.vagrant/provisioners/ansible/inventory -v ../ansible/cv.yml
Using /user/home/csherrell/git/faa/ansible_waas_demo/ansible/ansible.cfg as config file

PLAY [all] *********************************************************************

TASK [Gathering Facts] *********************************************************
ok: [cp1.cv.ztl.nas.waas]

TASK [common : Hello! I am the Common Playbook.] *******************************
ok: [cp1.cv.ztl.nas.waas] =>
  msg: I am everywhere you want to be!

TASK [cv : Hello! I am a C&V] **************************************************
ok: [cp1.cv.ztl.nas.waas] =>
  msg: I am special! I am the Master of the WAAS Universe!

TASK [cv : Fun Group Fact] *****************************************************
ok: [cp1.cv.ztl.nas.waas] =>
  msg: There are 3 C&Vs

TASK [cv : Tell Me About Yourself] *********************************************
ok: [cp1.cv.ztl.nas.waas] =>
  msg: My name is cp1.cv.ztl.nas.waas

PLAY RECAP *********************************************************************
cp1.cv.ztl.nas.waas        : ok=5    changed=0    unreachable=0    failed=0    skipped=0    rescued=0    ignored=0

==> gpt.gus.cm1.nas.waas: Running provisioner: ansible...
    gpt.gus.cm1.nas.waas: Running ansible-playbook...
PYTHONUNBUFFERED=1 ANSIBLE_FORCE_COLOR=true ANSIBLE_CONFIG='../ansible/ansible.cfg' ANSIBLE_HOST_KEY_CHECKING=false ANSIBLE_SSH_ARGS='-o UserKnownHostsFile=/dev/null -o IdentitiesOnly=yes -o ControlMaster=auto -o ControlPersist=60s' ansible-playbook --connection=ssh --timeout=30 --limit="gpt.gus.cm1.nas.waas" --inventory-file=/user/home/csherrell/git/faa/ansible_waas_demo/waas/.vagrant/provisioners/ansible/inventory -v ../ansible/gus.yml
Using /user/home/csherrell/git/faa/ansible_waas_demo/ansible/ansible.cfg as config file

PLAY [all] *********************************************************************

TASK [Gathering Facts] *********************************************************
ok: [gpt.gus.cm1.nas.waas]

TASK [common : Hello! I am the Common Playbook.] *******************************
ok: [gpt.gus.cm1.nas.waas] =>
  msg: I am everywhere you want to be!

TASK [gus : Hello! I am an GUS] ************************************************
ok: [gpt.gus.cm1.nas.waas] =>
  msg: I am special! I send the dataz to the satellite!

TASK [gus : Fun Group Fact] ****************************************************
ok: [gpt.gus.cm1.nas.waas] =>
  msg: There are 3 GUSes

TASK [gus : Tell Me About Yourself] ********************************************
ok: [gpt.gus.cm1.nas.waas] =>
  msg: My name is gpt.gus.cm1.nas.waas

PLAY RECAP *********************************************************************
gpt.gus.cm1.nas.waas       : ok=5    changed=0    unreachable=0    failed=0    skipped=0    rescued=0    ignored=0

==> gpt.gus.br1.nas.waas: Running provisioner: ansible...
    gpt.gus.br1.nas.waas: Running ansible-playbook...
PYTHONUNBUFFERED=1 ANSIBLE_FORCE_COLOR=true ANSIBLE_CONFIG='../ansible/ansible.cfg' ANSIBLE_HOST_KEY_CHECKING=false ANSIBLE_SSH_ARGS='-o UserKnownHostsFile=/dev/null -o IdentitiesOnly=yes -o ControlMaster=auto -o ControlPersist=60s' ansible-playbook --connection=ssh --timeout=30 --limit="gpt.gus.br1.nas.waas" --inventory-file=/user/home/csherrell/git/faa/ansible_waas_demo/waas/.vagrant/provisioners/ansible/inventory -v ../ansible/gus.yml
Using /user/home/csherrell/git/faa/ansible_waas_demo/ansible/ansible.cfg as config file

PLAY [all] *********************************************************************

TASK [Gathering Facts] *********************************************************
ok: [gpt.gus.br1.nas.waas]

TASK [common : Hello! I am the Common Playbook.] *******************************
ok: [gpt.gus.br1.nas.waas] =>
  msg: I am everywhere you want to be!

TASK [gus : Hello! I am an GUS] ************************************************
ok: [gpt.gus.br1.nas.waas] =>
  msg: I am special! I send the dataz to the satellite!

TASK [gus : Fun Group Fact] ****************************************************
ok: [gpt.gus.br1.nas.waas] =>
  msg: There are 3 GUSes

TASK [gus : Tell Me About Yourself] ********************************************
ok: [gpt.gus.br1.nas.waas] =>
  msg: My name is gpt.gus.br1.nas.waas

PLAY RECAP *********************************************************************
gpt.gus.br1.nas.waas       : ok=5    changed=0    unreachable=0    failed=0    skipped=0    rescued=0    ignored=0

==> tss.es1.wsf.waas: Running provisioner: ansible...
    tss.es1.wsf.waas: Running ansible-playbook...
PYTHONUNBUFFERED=1 ANSIBLE_FORCE_COLOR=true ANSIBLE_CONFIG='../ansible/ansible.cfg' ANSIBLE_HOST_KEY_CHECKING=false ANSIBLE_SSH_ARGS='-o UserKnownHostsFile=/dev/null -o IdentitiesOnly=yes -o ControlMaster=auto -o ControlPersist=60s' ansible-playbook --connection=ssh --timeout=30 --limit="tss.es1.wsf.waas" --inventory-file=/user/home/csherrell/git/faa/ansible_waas_demo/waas/.vagrant/provisioners/ansible/inventory -v ../ansible/tss.yml
Using /user/home/csherrell/git/faa/ansible_waas_demo/ansible/ansible.cfg as config file

PLAY [all] *********************************************************************

TASK [Gathering Facts] *********************************************************
ok: [tss.es1.wsf.waas]

TASK [common : Hello! I am the Common Playbook.] *******************************
ok: [tss.es1.wsf.waas] =>
  msg: I am everywhere you want to be!

TASK [tss : Hello! I am a TSS] *************************************************
ok: [tss.es1.wsf.waas] =>
  msg: I am special! I make the tests work!

TASK [tss : Fun Group Fact] ****************************************************
ok: [tss.es1.wsf.waas] =>
  msg: I am used to test software

TASK [tss : Tell Me About Yourself] ********************************************
ok: [tss.es1.wsf.waas] =>
  msg: 'My name is tss.es1.wsf.waas '

PLAY RECAP *********************************************************************
tss.es1.wsf.waas           : ok=5    changed=0    unreachable=0    failed=0    skipped=0    rescued=0    ignored=0

==> tss.bs1.wsf.waas: Running provisioner: ansible...
    tss.bs1.wsf.waas: Running ansible-playbook...
PYTHONUNBUFFERED=1 ANSIBLE_FORCE_COLOR=true ANSIBLE_CONFIG='../ansible/ansible.cfg' ANSIBLE_HOST_KEY_CHECKING=false ANSIBLE_SSH_ARGS='-o UserKnownHostsFile=/dev/null -o IdentitiesOnly=yes -o ControlMaster=auto -o ControlPersist=60s' ansible-playbook --connection=ssh --timeout=30 --limit="tss.bs1.wsf.waas" --inventory-file=/user/home/csherrell/git/faa/ansible_waas_demo/waas/.vagrant/provisioners/ansible/inventory -v ../ansible/tss.yml
Using /user/home/csherrell/git/faa/ansible_waas_demo/ansible/ansible.cfg as config file

PLAY [all] *********************************************************************

TASK [Gathering Facts] *********************************************************
ok: [tss.bs1.wsf.waas]

TASK [common : Hello! I am the Common Playbook.] *******************************
ok: [tss.bs1.wsf.waas] =>
  msg: I am everywhere you want to be!

TASK [tss : Hello! I am a TSS] *************************************************
ok: [tss.bs1.wsf.waas] =>
  msg: I am special! I make the tests work!

TASK [tss : Fun Group Fact] ****************************************************
ok: [tss.bs1.wsf.waas] =>
  msg: I am used to test software

TASK [tss : Tell Me About Yourself] ********************************************
ok: [tss.bs1.wsf.waas] =>
  msg: My name is tss.bs1.wsf.waas

PLAY RECAP *********************************************************************
tss.bs1.wsf.waas           : ok=5    changed=0    unreachable=0    failed=0    skipped=0    rescued=0    ignored=0

==> bg1.wsf.waas: Running provisioner: ansible...
    bg1.wsf.waas: Running ansible-playbook...
PYTHONUNBUFFERED=1 ANSIBLE_FORCE_COLOR=true ANSIBLE_CONFIG='../ansible/ansible.cfg' ANSIBLE_HOST_KEY_CHECKING=false ANSIBLE_SSH_ARGS='-o UserKnownHostsFile=/dev/null -o IdentitiesOnly=yes -o ControlMaster=auto -o ControlPersist=60s' ansible-playbook --connection=ssh --timeout=30 --limit="bg1.wsf.waas" --inventory-file=/user/home/csherrell/git/faa/ansible_waas_demo/waas/.vagrant/provisioners/ansible/inventory -v ../ansible/bg.yml
Using /user/home/csherrell/git/faa/ansible_waas_demo/ansible/ansible.cfg as config file

PLAY [all] *********************************************************************

TASK [Gathering Facts] *********************************************************
ok: [bg1.wsf.waas]

TASK [common : Hello! I am the Common Playbook.] *******************************
ok: [bg1.wsf.waas] =>
  msg: I am everywhere you want to be!

TASK [build_generation : Hello! I am a BE] *************************************
ok: [bg1.wsf.waas] =>
  msg: I am special! Can't make software without me!

TASK [build_generation : Fun Group Fact] ***************************************
ok: [bg1.wsf.waas] =>
  msg: I am use to build software

TASK [build_generation : Tell Me About Yourself] *******************************
ok: [bg1.wsf.waas] =>
  msg: My name is bg1.wsf.waas

PLAY RECAP *********************************************************************
bg1.wsf.waas               : ok=5    changed=0    unreachable=0    failed=0    skipped=0    rescued=0    ignored=0
```

## BG
```
❯ ANSIBLE_CONFIG='../ansible/ansible.cfg' ANSIBLE_HOST_KEY_CHECKING=false ANSIBLE_SSH_ARGS='-o UserKnownHostsFile=/dev/null -o IdentitiesOnly=yes -o ControlMaster=auto -o ControlPersist=60s' ansible-playbook --connection=ssh --timeout=30 --limit=bg --inventory-file=./inventory.yml -v ../ansible/bg.yml
Using /user/home/csherrell/git/faa/ansible_waas_demo/ansible/ansible.cfg as config file

PLAY [all] *************************************************************************************************************************************

TASK [Gathering Facts] *************************************************************************************************************************
ok: [bg1.wsf.waas]

TASK [common : Hello! I am the Common Playbook.] ***********************************************************************************************
ok: [bg1.wsf.waas] =>
  msg: I am everywhere you want to be!

TASK [build_generation : Hello! I am a BE] *****************************************************************************************************
ok: [bg1.wsf.waas] =>
  msg: I am special! Can't make software without me!

TASK [build_generation : Fun Group Fact] *******************************************************************************************************
ok: [bg1.wsf.waas] =>
  msg: I am use to build software

TASK [build_generation : Tell Me About Yourself] ***********************************************************************************************
ok: [bg1.wsf.waas] =>
  msg: My name is bg1.wsf.waas

PLAY RECAP *************************************************************************************************************************************
bg1.wsf.waas               : ok=5    changed=0    unreachable=0    failed=0    skipped=0    rescued=0    ignored=0
```

### TSS
```
[csherrell@dvm] (dvm-aUp7nasj-py3.11) (main) ⚡
 ~/git/faa/ansible_waas_demo/waas
❯ ANSIBLE_CONFIG='../ansible/ansible.cfg' ANSIBLE_HOST_KEY_CHECKING=false ANSIBLE_SSH_ARGS='-o UserKnownHostsFile=/dev/null -o IdentitiesOnly=yes -o ControlMaster=auto -o ControlPersist=60s' ansible-playbook --connection=ssh --timeout=30 --limit=tss --inventory-file=./inventory.yml -v ../ansible/tss.yml
Using /user/home/csherrell/git/faa/ansible_waas_demo/ansible/ansible.cfg as config file

PLAY [all] *************************************************************************************************************************************

TASK [Gathering Facts] *************************************************************************************************************************
ok: [tss.bs1.wsf.waas]
ok: [tss.es1.wsf.waas]

TASK [common : Hello! I am the Common Playbook.] ***********************************************************************************************
ok: [tss.es1.wsf.waas] =>
  msg: I am everywhere you want to be!
ok: [tss.bs1.wsf.waas] =>
  msg: I am everywhere you want to be!

TASK [tss : Hello! I am a TSS] *****************************************************************************************************************
ok: [tss.es1.wsf.waas] =>
  msg: I am special! I make the tests work!
ok: [tss.bs1.wsf.waas] =>
  msg: I am special! I make the tests work!

TASK [tss : Fun Group Fact] ********************************************************************************************************************
ok: [tss.es1.wsf.waas] =>
  msg: I am used to test software
ok: [tss.bs1.wsf.waas] =>
  msg: I am used to test software

TASK [tss : Tell Me About Yourself] ************************************************************************************************************
ok: [tss.es1.wsf.waas] =>
  msg: 'My name is tss.es1.wsf.waas '
ok: [tss.bs1.wsf.waas] =>
  msg: My name is tss.bs1.wsf.waas

PLAY RECAP *************************************************************************************************************************************
tss.bs1.wsf.waas           : ok=5    changed=0    unreachable=0    failed=0    skipped=0    rescued=0    ignored=0
tss.es1.wsf.waas           : ok=5    changed=0    unreachable=0    failed=0    skipped=0    rescued=0    ignored=0
```

