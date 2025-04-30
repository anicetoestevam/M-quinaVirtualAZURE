
# 🖥️ Configuração de Máquina Virtual no Azure

Este guia detalha como criar uma máquina virtual (VM) no Microsoft Azure com Windows Server 2022 Datacenter e configurar acesso via HTTPS.

## 📌 Pré-requisitos

- Conta ativa no Microsoft Azure (https://portal.azure.com/#home).

## 🔧 Passo a Passo

### 1. **Acessar o Serviço de Máquinas Virtuais**
1. Em https://portal.azure.com/#home, digite **"Máquinas virtuais"** na barra de pesquisa.
2. Clique em **Máquinas virtuais** nos resultados do serviço.

### 2. **Criar a Máquina Virtual**
1. Na página **Máquinas virtuais**, clique em **Criar** > **Máquina virtual do Azure**.
2. Na página **Criar uma máquina virtual**, preencha as informações:
   - **Nome da máquina virtual**: `projetoDIO`
   - **Região**: Escolha a região mais próxima de você.
   - **Imagem**: Selecione **Windows Server 2022 Datacenter: Azure Edition - x64 Gen 2**.
   - **Tamanho**: Deixe o padrão.

### 3. **Configurar a Conta de Administrador**
1. Em **Conta de administrador**:
   - **Nome de usuário**: Exemplo: `anicetoestevam`
   - **Senha**: Insira uma senha forte (mínimo 12 caracteres, letras, números e símbolos).

### 4. **Configurar Regras de Rede**
1. Em **Regras de porta de entrada**:
   - Selecione **Permitir portas selecionadas**.
   - Marque a opção HTTPS (443).

### 5. **Revisar e Criar**
1. Deixe os padrões restantes nas demais seções (Rede, Gerenciamento, etc.).
2. Clique no botão **Examinar + criar** na parte inferior.
3. Após a validação bem-sucedida, clique em **Criar**.

### 6. **Acessar a VM após a Implantação**
1. Após a conclusão da implantação, clique em **Ir para o recurso**.
2. Anote o **Endereço IP público** gerado para acessar a VM.


## 📚 Recursos Adicionais
- https://learn.microsoft.com/pt-br/azure/virtual-machines/windows/quick-create-portal




