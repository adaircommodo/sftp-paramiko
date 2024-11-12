Aqui está o README.md atualizado com o link para o LinkedIn:

# SFTP Paramiko

Este projeto implementa uma automação utilizando o **Paramiko**, uma biblioteca Python para interagir com servidores SFTP. Ele realiza tarefas como transferência de arquivos, descompactação e manipulação de conteúdo, otimizando processos de integração de dados.

---

## 🚀 Funcionalidades

- **Conexão SFTP**: Realiza conexão segura com o servidor SFTP utilizando credenciais e parâmetros configuráveis.
- **Download de Arquivos**: Faz o download de arquivos no formato `.zip` a partir do servidor SFTP.
- **Descompactação de Arquivos**: Automatiza a extração dos arquivos `.zip` para diretórios locais.
- **Manipulação de Arquivos**: Realiza substituição de caracteres específicos dentro de arquivos de texto.
- **Exclusão Automática**: Remove arquivos desnecessários após a execução dos processos.

---

## 📋 Pré-requisitos

- **Python 3.x**
- Biblioteca `paramiko`
- Biblioteca `zipfile`

---

## ⚙️ Configuração

1. Clone este repositório:
   ```bash
   git clone https://github.com/adaircommodo/sftp-paramiko.git
   cd sftp-paramiko
   ```

2. Instale as dependências necessárias:
   ```bash
   pip install paramiko
   ```

3. Configure as variáveis no script `sftp_paramiko.py`:
   ```python
   HOST = 'exemplo.com.br'
   USER = 'usuario'
   SENHA = 'senha'
   PORTA = 22
   ```

4. Personalize os diretórios e nomes de arquivos:
   ```python
   pastaFtp = "./pasta_no_servidor/"
   pastaDestino = "./destino_local/"
   ```

---

## 🛠️ Como usar

1. Execute o script:
   ```bash
   python sftp_paramiko.py
   ```

2. O script irá:
   - Conectar ao servidor SFTP.
   - Realizar o download de arquivos `.zip`.
   - Descompactar os arquivos.
   - Substituir caracteres específicos nos arquivos `.txt`.
   - Excluir os arquivos `.zip` após o processamento.

---

## 📄 Estrutura do Código

- **ConectaSFT**: Estabelece a conexão com o servidor.
- **DescompatarArquivo**: Extrai o conteúdo dos arquivos `.zip`.
- **SubstituirCaracter**: Realiza substituição de strings nos arquivos.
- **ExcluirArquivo**: Remove arquivos desnecessários.

---

## 📝 Contribuições

Sinta-se à vontade para contribuir com melhorias ou sugestões. Para isso, abra uma issue ou envie um pull request.

---

## ⚖️ Licença

Este projeto está sob a licença [MIT](https://opensource.org/licenses/MIT). Para mais informações, consulte o arquivo LICENSE no repositório.

---

## 📧 Contato

Criado por [adaircommodo](https://github.com/adaircommodo).  
Conecte-se no [LinkedIn](https://www.linkedin.com/in/adaircommodo/).  
Dúvidas ou sugestões? Entre em contato!
