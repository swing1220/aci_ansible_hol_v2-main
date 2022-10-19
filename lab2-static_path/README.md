# Lab2 - Static Port 작업

- CSV 파일을 읽고, variable 파일 생성

```
ansible-playbook 01_create_vars.yml
```

- 작업 조건 검증 및 Static Port 생성

```
ansible-playbook 02_create_staticport.yml
```

- Static Port 삭제

```
ansible-playbook 03_delete_staticport.yml
```