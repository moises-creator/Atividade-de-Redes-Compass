# :large_blue_circle: Processo de Instalação do Linux(Documentação):large_blue_circle:

## :large_orange_diamond: 1. Baixar a Imagem ISO Mais Atual do Sistema

No site oficial da Oracle são encontradas as imagens para download, neste caso foi escolhida a versão 9.0 completa (Full ISO).

## :large_orange_diamond: 2. Preparando Ambiente (Criando a VM)

### :small_blue_diamond:2.1 Local de Instalação e Alocação de Memória

Nesta etapa são feitas as configurações iniciais da Virtual Machine em que será instalado o sistema Linux.
São escolhidos o local de instalação e o tipo de sistema que será instalado, depois o usuário deve escolher a quantidade de memória RAM (Random Acess Memory) que será alocada para utilização desta Virtual Machine.

### :small_blue_diamond:2.2 Configurações de Armazenamento

O usuário deve escolher as opções de armazenamento como:

- Usar um disco virtual ou não.
- Escolher o tipo de disco (neste caso é escolhido o VDI, padrão da virtualbox).
- Se a alocação será dinâmica ou fixa.
- E a quantidade de espaço alocado.

### :small_blue_diamond:2.3 Configurações da Virtual Machine

Aqui são feitas as configurações iniciais, como por exemplo:

- Escolha da ISO de instalação.
- Quantidade e tipo de interfaces de rede.
- Alterar mudanças de alocação feitas no começo.

## :large_orange_diamond: 3. Configurações na Interface Inicial

### :small_blue_diamond:3.1 Configurações do Sistema

Neste menu o usuário faz as configurações iniciais do sistema como tipo de sistema (com ou sem interface), ajustes de disco, LVM, etc…

![image](https://user-images.githubusercontent.com/70618577/180377762-201d7da1-e407-4e17-9fe5-07dc9257c4c9.png)

### :small_blue_diamond:3.2 Layout do Teclado

Escolha do layout brasileiro padrão ABNT2.

![image](https://user-images.githubusercontent.com/70618577/180378091-85a2648f-56b3-44e1-b84f-261e24c8dd99.png)

### :small_blue_diamond:3.3 Suporte de Idiomas

Seleção de idioma do sistema,importante selecionar o inglês porque as atualizações de correção saem primeiro para o sistema padrão (inglês).

![image](https://user-images.githubusercontent.com/70618577/180378579-32d4baa9-abcc-4521-8cea-dfd248165ef6.png)

### :small_blue_diamond:3.4 Data e Hora

- Seleciona a região para definir fuso horário.
- Formatação de horas (24h ou AM/PM).
- Data atual.


### :small_blue_diamond:3.5 Fonte de Instalação

A fonte de instalação neste caso é a ISO do sistema escolhida. Está selecionada a opção de detecção automática.

![image](https://user-images.githubusercontent.com/70618577/180378316-1e3ecb3e-56fe-4ac1-a68d-b7e0d1fb7f6f.png)

### :small_blue_diamond:3.6 Destino de Instalação

Aqui são feitas as configurações de disco e partições, é possível fazer os ajustes dos filesystems com o LVM selecionando a opção “custom”.

![image](https://user-images.githubusercontent.com/70618577/180378429-94fdc470-7d78-4aaa-bd1f-37894b0be857.png)

### :small_blue_diamond:3.7 KDUMP

Kdump é uma ferramenta que captura informações do sistema no caso de um crash para determinar a causa. A ferramenta está habilitada e a memória reservada foi deixada no automático.

![image](https://user-images.githubusercontent.com/70618577/180378675-74e63344-cadf-427a-b392-cd76088e4cb4.png)

### :small_blue_diamond:3.8 Rede 

A rede vem desabilitada por padrão, neste caso foi habilitado manualmente.

Nas opções de configurações é possível alterar o IP para fixo ou automático.

![image](https://user-images.githubusercontent.com/70618577/180382109-48a65e21-4750-4d8d-8388-18099f50db97.png)

### :small_blue_diamond:3.9 Políticas de Segurança

Políticas de segurança opcionais que seguem as recomendações da SCAP (Security Content Automation Protocol).

![image](https://user-images.githubusercontent.com/70618577/180379762-17b96369-0943-4795-9cdd-b3be59b9c3f8.png)

### :small_blue_diamond:3.10 Senha do Usuário ROOT

Define a senha do root user, também é possível deixar sem senha.

![image](https://user-images.githubusercontent.com/70618577/180379890-e402533f-ae2e-4d49-a602-a8c45ce87021.png)

 ### :small_blue_diamond:3.11 Criação do Usuário Padrão
 
Criação opcional do usuário padrão e sua senha. 

![image](https://user-images.githubusercontent.com/70618577/180380082-d84751fc-8715-43fc-96e5-63a238376dc0.png)

### :small_blue_diamond:3.12 Fim da Instalação

Após um breve reboot o sistema irá iniciar e estará pronto para uso e configurações futuras.

![image](https://user-images.githubusercontent.com/70618577/180380150-aa8e6fc2-7041-442f-ba95-8018c9014efd.png)
