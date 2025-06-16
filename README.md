# AZURE_criar_VM
LAB para ciração de VM no Portal AZURE

### Criar máquina virtual
    - Já autenticado no Portal Azure, buscar na barra de pesquisa por "Máquinas Virtuais"
    - Selecione o serviço "Máquinas Virtuais"
<img src="/imagens/1.png" alt="selecionar serviço" width=75%>

    Já na página Máquinas virtuais, clique em Criar e selecione Máquina virtual. A página Criar uma máquina virtual é aberta.
<img src="/imagens/2.png" alt="criar máquina" width=75%>

    Em *Detalhes da Instância*, insira o nome MinhaVM para a máquina virtual.
    Em "Opções de disponibilidade, escolha "Nenhuma redundância infraestrutura necessária"
    Em "Imagem", escolha "Windows Server 2022 Datacenter: Azure Edition - x64 Gen 2"
    Os outros campos ficam com a configuração padrão.
<img src="/imagens/3.png" alt="Detalhes da VM" width=75%>

    *Observação*

    Alguns usuários agora verão a opção de criar VMs em várias zonas. Para saber mais sobre essa nova capacidade, confira Criar máquinas virtuais em uma zona de disponibilidade. Captura de tela mostrando que existe a opção de criar máquinas virtuais em várias zonas de disponibilidade.

    Em Conta de administrador, forneça um nome de usuário, como azureuser e uma senha. A senha deve ter no mínimo 12 caracteres e atender a requisitos de complexidade definidos.

    Captura de tela da seção Conta de administrador, onde você fornece o nome de usuário e a senha do administrador.

    Em Regras de porta de entrada, escolha Permitir portas selecionadas e, em seguida, selecione RDP (3389) e HTTP (80) na lista suspensa.

    Captura de tela da seção de regras de porta de entrada, na qual você seleciona as portas nas quais as conexões de entrada são permitidas

    Deixe os padrões restantes e, em seguida, selecione o botão Examinar + criar na parte inferior da página.

    Captura de tela mostrando o botão Examinar + criar na parte inferior da página.

    Após a execução da validação, selecione o botão Criar na parte inferior da página. Captura de tela mostrando que a validação foi aprovada. Clique no botão Criar para criar a VM.

    Após a conclusão da implantação, selecione Ir para o recurso.

    Captura de tela mostrando a próxima etapa de ir para o recurso.
