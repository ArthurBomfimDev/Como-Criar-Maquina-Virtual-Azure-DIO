<div align="center">
<br>
<h1> Como Criar uma Máquina Virtual na Azure - Desafio DIO</h1>
</div>

📝 Sobre o que se trata este repositório?
Este repositório contém um guia completo e visual para a criação de uma máquina virtual (VM) no Microsoft Azure, como parte do desafio de projeto do Bootcamp .NET, C#, Docker e Azure oferecido pela DIO.

O objetivo deste documento é registrar o passo a passo da criação da VM, aplicando na prática os conhecimentos sobre computação em nuvem e documentando a experiência.

<div align="center">
<img src="https://hermes.digitalinnovation.one/assets/diome/logo.png" width="250" alt="Logo DIO">
<img src="https://upload.wikimedia.org/wikipedia/commons/a/a8/Microsoft_Azure_Logo.svg" width="300" alt="Logo Azure">
</div>

---

# 🚀 Passo a Passo para Criar sua VM no Azure
Siga as etapas detalhadas abaixo para provisionar e configurar sua máquina virtual com o sistema operacional Ubuntu.

# 1️⃣ Acessando o Portal do Azure e Iniciando a Criação
Acesse o Portal: Primeiro, faça login no portal do Azure.

Localize as VMs: Na página inicial, localize e clique no ícone de "Máquinas virtuais".
<img src="https://github.com/ArthurBomfimDev/Como-Criar-Maquina-Virtual-Azure-DIO/blob/main/imagens/Maquina%20Virtual%201.png?raw=true" alt="Tela inicial do portal do Azure, destacando a opção Máquinas virtuais.">

Inicie a Criação: Na página "Máquinas virtuais", clique no botão "+ Criar" e selecione "Máquina virtual do Azure" para começar.
<img src="https://github.com/ArthurBomfimDev/Como-Criar-Maquina-Virtual-Azure-DIO/blob/main/imagens/Maquina%20Virtual%202.png?raw=true" alt="Tela de gerenciamento de máquinas virtuais, destacando o botão para criar uma nova VM.">

Tela de configuração:
<img src="https://github.com/ArthurBomfimDev/Como-Criar-Maquina-Virtual-Azure-DIO/blob/main/imagens/Maquina%20Virtual%203.png?raw=true" alt="Tela de configuração da máquinas virtual">

# 2️⃣ Configurando as Informações Básicas da VM
Esta é a etapa principal, onde definimos todas as características da nossa máquina virtual. O formulário é dividido em várias seções para facilitar a configuração.
<img src="https://github.com/ArthurBomfimDev/Como-Criar-Maquina-Virtual-Azure-DIO/blob/main/imagens/todos%20tipos%20de%20config.png?raw=true" alt="Cabeçalho da página de criação de máquina virtual, mostrando as abas de configuração.">

Detalhes do Projeto e da Instância
Aqui, organizamos a VM dentro da nossa subscrição e definimos suas características principais. A escolha mais importante nesta seção foi a Imagem, onde optei por criar uma máquina Ubuntu Server 24.04 LTS, uma distribuição Linux popular e robusta, ideal para servidores.

Tipo de segurança: Máquinas virtuais de início seguro
<img src="https://github.com/ArthurBomfimDev/Como-Criar-Maquina-Virtual-Azure-DIO/blob/main/imagens/config%201.png?raw=true" alt="Primeira parte do formulário de informações básicas, com os campos de subscrição, grupo de recursos, nome, região e imagem preenchidos.">

Conta de Administrador e Portas de Entrada
Nesta parte, configuramos o acesso à VM e os recursos de hardware. Para a autenticação, escolhi usar Chave pública SSH, que é um método muito mais seguro do que senhas. Também liberei a porta SSH (22) para permitir o acesso remoto seguro.

Selecionei as portas de entrada: SSH (22)
<img src="https://github.com/ArthurBomfimDev/Como-Criar-Maquina-Virtual-Azure-DIO/blob/main/imagens/config%202.png?raw=true" alt="Segunda parte do formulário de informações básicas, com as configurações de tamanho, conta de administrador e regras de porta de entrada.">

# 3️⃣ Revisão e Criação da VM
Clique no botão "Rever + criar" no final da página.

O Azure validará suas configurações. Se tudo estiver correto, a mensagem "A validação passou" será exibida.
<img src="https://github.com/ArthurBomfimDev/Como-Criar-Maquina-Virtual-Azure-DIO/blob/main/imagens/Validacao%20concluida.png?raw=true" alt="Tela de revisão final mostrando que a validação foi bem-sucedida e o resumo das configurações da VM.">

Confira os detalhes e clique em "Criar".

⚠️ IMPORTANTE
Uma janela pop-up aparecerá para você baixar a chave privada SSH. Faça o download e guarde-a em um local seguro, pois ela é a única forma de acessar sua VM.

# 4️⃣ Implantação Concluída
Aguarde alguns instantes enquanto o Azure provisiona sua máquina virtual.

Quando o processo for finalizado, você verá a tela de confirmação: "A sua implantação está concluída".
<img src="https://github.com/ArthurBomfimDev/Como-Criar-Maquina-Virtual-Azure-DIO/blob/main/imagens/sucesso%20na%20vm.png?raw=true" alt="Tela de sucesso mostrando que a implantação da máquina virtual foi concluída.">

Clique em "Ir para recurso" para ver o painel de controle da sua nova VM.
<img src="https://github.com/ArthurBomfimDev/Como-Criar-Maquina-Virtual-Azure-DIO/blob/main/imagens/VM%20criada.png?raw=true" alt="Página de detalhes da máquina virtual recém-criada, exibindo informações como endereço IP, status e configurações.">

---

# 🎯 Para mim:
Concluir este laboratório foi um passo fundamental. Como um futuro desenvolvedor .NET, entender de Azure e computação em nuvem não é mais um diferencial, é uma necessidade. As aplicações que vamos construir precisam rodar em algum lugar, e a nuvem é o ambiente mais moderno, escalável e eficiente para isso.
