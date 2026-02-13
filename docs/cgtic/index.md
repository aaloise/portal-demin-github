# 💻 Tecnologia da Informação (CGTIC)

Bem-vindo ao catálogo de serviços técnicos da SPU. Abaixo encontra os sistemas críticos e o seu status operacional.

## 🚦 Status dos Sistemas

<div class="grid cards" markdown>

-   :material-server-network: **Rede Corporativa**
    ---
    Operacional
    ---
    [:material-arrow-right: Ver Topologia](#)

-   :material-database-check: **Sidor (Patrimônio)**
    ---
    Operacional
    ---
    [:material-arrow-right: Acessar Manual](#)

-   :material-cloud-alert: **VPN (Acesso Remoto)**
    ---
    Instabilidade na Região Sul
    ---
    [:material-arrow-right: Solução de Erros](manual-vpn.md)

</div>

---

## 🔧 Configuração de Ambiente

Selecione o seu sistema operativo para ver as instruções específicas de configuração:

=== ":material-microsoft-windows: Windows 10/11"

    1. Baixe o instalador oficial no **Portal de Software**.
    2. Execute como Administrador.
    3. No campo "Gateway", insira:
        ```bash
        vpn.economia.gov.br:443
        ```
    
    !!! success "Recomendado"
        Utilize sempre a versão **7.0.2** ou superior do cliente VPN para compatibilidade com o Token.

=== ":material-linux: Ubuntu / Debian"

    Instale via terminal utilizando o `openconnect`:

    ```bash
    sudo apt update && sudo apt install openconnect
    sudo openconnect vpn.economia.gov.br
    ```

    !!! warning "Atenção Linux"
        O suporte a Linux é comunitário e não possui SLA de atendimento pela central 0800.

---

[Abrir Chamado Técnico](https://suporte.gov.br){ .md-button .md-button--primary }
[Ver Política de Senhas](#){ .md-button }
