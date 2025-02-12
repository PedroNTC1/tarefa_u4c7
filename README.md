Atividade U4C7 - EmbarcaTech
Descrição
Este projeto, desenvolvido para a atividade U4C7 do EmbarcaTech, demonstra o controle de um servo motor utilizando o Raspberry Pi Pico. São aplicados conceitos de PWM e gerenciamento de hardware para mover o servo de forma programada.

Objetivos
Aplicar conceitos teóricos e práticos de sistemas embarcados.
Controlar com precisão um servo motor por meio de PWM.
Documentar e estruturar um projeto de firmware.
Estrutura do Projeto
wokwi.toml: Configurações para simulação utilizando a plataforma Wokwi.
U4C7.c: Função principal que inicializa o sistema e executa as rotinas de controle do servo.
/inc/include.h: Declarações e funções auxiliares para operação do servo.
// ...outros arquivos e pastas conforme necessário...
Como Compilar e Executar
Configure o ambiente de desenvolvimento com o SDK do Raspberry Pi Pico.
Compile o projeto utilizando seu sistema de build (por exemplo: CMake + Make).
O firmware gerado (U4C7.uf2) será referenciado no arquivo [wokwi.toml] para simulação.
Para simulação, carregue o projeto na plataforma Wokwi.
Vídeo de Demonstração
Assista à demonstração do projeto: Clique aqui

Autor
Pedro Sérgio Martins Lima