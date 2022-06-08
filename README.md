Mod Security
=========

Um instalador simple do ModSecurity

Requisitos
------------

- Servidor HTTPD instalado nos Hosts
- Python >= 3.6
- Centos 7
- Ansible >= 2.0

Variáveis da Role
--------------

É possível selecionar que versão do coreruleset utilizar usando a variável `coreruleset_version`

Dependências
------------

Nenhuma

Playbook de Exemplo
----------------

```yaml
---
- host: all
  roles:
    - role: stephan_lopes.mod_security
      coreruleset_version: 3.3.0
```

Licença
-------

BSD

Informações do Autor
------------------

[Site](https://stephan-lopes.github.io)
