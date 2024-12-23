# Documentação do Desafio: Criação de um Ransomware em Python

## Bootcamp DIO + Santander: Cybersecurity

### **Objetivo do Desafio**
Criar uma aplicação em Python que simula o funcionamento básico de um ransomware. Este exercício faz parte do Bootcamp da Digital Innovation One (DIO) em parceria com o Santander, com foco em conceitos de cibersegurança.

#### **O que é um Ransomware?**
Um ransomware é um tipo de malware (software malicioso) projetado para bloquear o acesso aos dados de um sistema, criptografando-os, e exigir um resgate ("ransom") para liberar o acesso. Esse tipo de ataque pode causar prejuízos financeiros e operacionais significativos às vítimas.

#### **Características principais de um ransomware:**
- **Criptografia de dados**: Os arquivos do sistema são criptografados com algoritmos robustos, tornando-os inacessíveis sem a chave correta.
- **Mensagem de resgate**: Uma notificação é exibida, informando que os dados estão bloqueados e fornecendo instruções para o pagamento do resgate.
- **Propagação**: Alguns ransomwares possuem mecanismos para se espalhar por redes e dispositivos conectados.

> **Nota**: Este desafio tem como único objetivo educacional e prático. É extremamente importante nunca usar scripts maliciosos para fins ilegais.

---

### **Descrição do Script**
O script desenvolvido simula um ransomware de forma segura e controlada, com o intuito de demonstrar os conceitos envolvidos. Ele utiliza o módulo `pyaes` para realizar a criptografia e descriptografia de arquivos.

#### **Funcionalidades:**
1. **Criptografia de Arquivos**:
   - O script percorre um diretório-alvo e criptografa os arquivos encontrados utilizando o algoritmo AES (Advanced Encryption Standard).

2. **Descriptografia de Arquivos**:
   - Após a chave correta ser fornecida, os arquivos criptografados podem ser restaurados ao estado original.

3. **Mensagem Simulada**:
   - Uma mensagem de "resgate" é exibida ao usuário, indicando que os arquivos estão bloqueados e instruindo como proceder (simulado para fins educacionais).

#### **Principais Dependências:**
- Python 3.8 ou superior
- Módulo `pyaes` (instalado via `pip`)

#### **Estrutura do Código:**
- **encrypter.py**: Arquivo principal que contém a lógica para criptografia e descriptografia.
- **utils.py**: (Opcional) Pode conter funções auxiliares para manipulação de arquivos.

### **Avisos Legais e Éticos**
Este projeto foi desenvolvido exclusivamente para fins educacionais e de aprendizado. A criação e disseminação de ransomware ou qualquer tipo de malware para fins maliciosos é ilegal e pode resultar em consequências graves, tanto legais quanto éticas. Use o conhecimento adquirido de forma responsável!

---

### **Referências**
- [Documentação do Python](https://docs.python.org/3/)
- [Digital Innovation One (DIO)](https://web.dio.me/)
- [Documentação do módulo pyaes](https://pypi.org/project/pyaes/)
