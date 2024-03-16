
# Nome do Microsserviço

Uma breve descrição sobre a funcionalide do Microsserviço.

## Instruções para rodar a aplicação

```
digite aqui
```

## Justificativa do Padrão SAGA escolhido

Por se um cenário de uma saga simples, com poucas operações, realizamos a escolha da **saga coreografada** para o nosso projeto.  
A coreografia permite que cada serviço adapte sua parte da transação com base nos eventos que ocorrem em tempo real. Isso permite uma maior flexibilidade para lidar com casos de uso complexos e cenários de exceção. Os serviços permanecem desacoplados e independentes uns dos outros. Eles não precisam se comunicar diretamente para coordenar a transação, o que reduz a complexidade e facilita a manutenção e escalabilidade do sistema. Como cada serviço pode operar de forma independente, é mais fácil escalar partes específicas do sistema conforme necessário, sem afetar outras partes. Em resumo, o padrão SAGA coreografada oferece uma abordagem mais flexível e distribuída para coordenar transações em um ambiente de microserviços e mensageria, mantendo os serviços desacoplados e independentes uns dos outros. Isso resulta em sistemas mais escaláveis, resilientes e flexíveis.A coreografia permite que cada serviço adapte sua parte da transação com base nos eventos que ocorrem em tempo real. Isso permite uma maior flexibilidade para lidar com casos de uso complexos e cenários de exceção. Os serviços permanecem desacoplados e independentes uns dos outros. Eles não precisam se comunicar diretamente para coordenar a transação, o que reduz a complexidade e facilita a manutenção e escalabilidade do sistema. Como cada serviço pode operar de forma independente, é mais fácil escalar partes específicas do sistema conforme necessário, sem afetar outras partes. Em resumo, o padrão SAGA coreografada oferece uma abordagem mais flexível e distribuída para coordenar transações em um ambiente de microserviços e mensageria, mantendo os serviços desacoplados e independentes uns dos outros. Isso resulta em sistemas mais escaláveis, resilientes e flexíveis.

## Links com os relatórios dos processamentos do OWASP ZAP (antes e após a correção)

 - [ZAP Scanning Report Inicial - Pagamento](https://drive.google.com/file/d/1IlyXzk6v3-LyMF0739PYIV8EUwbysm-H/view?usp=drive_link){:target="_blank"}
 - [ZAP Scanning Report Final - Pagamento](https://drive.google.com/file/d/1NxbwyWja7CuOeX6dwDLJ1YdY14LlIZ3X/view?usp=drive_link)

## Link com o relatório RIPD do sistema

 - [RIPD](https://drive.google.com/file/d/1QwHcXojaKHjKTMpnIp0xWjB1zfmLlcNg/view?usp=sharing)

 ## Link para o desenho da arquitetura

  - [Desenho da arquitetura](https://drive.google.com/drive/folders/1yGdvC0Sts3Vi8ygJf4vMCwODX5S0RhRF?usp=sharing)

 ## Link para o video
 
- Projeto rodando, inclusive com o padrão SAGA funcionando;
- Explicação do padrão SAGA escolhido e sua justificativa;
- Arquitetura da estrutura da nuvem e como a comunicação SAGA está montada.

- [VIDEO](https://drive.google.com/drive/folders/1yGdvC0Sts3Vi8ygJf4vMCwODX5S0RhRF?usp=sharing)
