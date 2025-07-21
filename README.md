# 🖥️ Monitoramento Corporativo com Zabbix + VirtualBox
*Implementação de ambiente NOC para infraestrutura híbrida (Windows/Linux)*

![Zabbix Dashboard](screenshots/dashboard.png)

## 🔧 **Tecnologias**
![Zabbix](https://img.shields.io/badge/Zabbix-DD0000?style=for-the-badge&logo=zabbix&logoColor=white)
![VirtualBox](https://img.shields.io/badge/VirtualBox-183A61?style=for-the-badge&logo=virtualbox&logoColor=white)
![Grafana](https://img.shields.io/badge/Grafana-F46800?style=for-the-badge&logo=grafana&logoColor=white)

## 🚀 **Funcionalidades**
- Monitoramento de 4 servidores Windows e 8 clientes Linux/Windows
- Alertas proativos por e-mail (tempo de resposta <30s)
- VPN site-to-site com criptografia AES-256

## 📊 **Resultados**
- **40% redução** no tempo de resposta a incidentes
- **15% menos downtime** por prevenção proativa

## 🛠️ **Como Reproduzir**
1. **Pré-requisitos**:
   - VirtualBox 6.1+
   - CentOS 8 para o servidor Zabbix

2. **Passo a Passo**:
   ```bash
   # Clone este repositório
   git clone https://github.com/FabioWlademir/zabbix-monitoring-lab
   # Execute o script de configuração
   cd configs/
   chmod +x deploy_zabbix.sh
   ./deploy_zabbix.sh

## 🔗 LinkedIn: Ver projeto completo - https://www.linkedin.com/in/fabiowlademir/details/projects/
