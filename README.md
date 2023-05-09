# APLICAÇÃO WORDPRESS COM A INFRAESTRUTURA DO ANSIBLE

- Requer Ansible 2.10.8 ou superior
- S.O hosts ubuntu/trusty64

### Esse playbook implementa uma configuração simples e completa da popular plataforma de blogging WordPress e CMS, utilizando o MySQL como banco de dados.

## Rodar o projeto
Após o clone deste repositorio, rode o seguinte comando

```
    ansible-playbook -i hosts provisioning.yml
```
Os playbooks configurarão MySQL, WordPress. Quando a execução estiver concluída, você pode acessar o servidor de acesso para iniciar a configuração do WordPress.