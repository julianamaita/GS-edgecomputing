# GS- Edge Computing
Projeto - Controle de estoque 

-  Descrição do Problema de Saúde:
O problema abordado diz respeito à gestão de tratamentos medicamentosos contínuos, evidenciando desafios como a falta de aderência à medicação, especialmente quando os pacientes interrompem prematuramente os tratamentos ao sinal de melhora, como apontado pela pesquisa do Instituto Datafolha. Essa falta de continuidade nos tratamentos pode impactar negativamente na qualidade de vida e eficácia do cuidado de saúde.

Visão Geral da Solução Proposta:
- A solução proposta é o desenvolvimento do software inovador MedEcho, integrado à assistente virtual Alexa. O software simplifica a administração de medicamentos, incorporando recursos como identificação visual por meio de fotos, integração com a casa inteligente para ajustes automáticos de ambiente e alertas via SMS para garantir acessibilidade. A aplicação visa não apenas oferecer uma solução tecnológica, mas também transformar positivamente a gestão de tratamentos contínuos, melhorando a aderência, proporcionando uma experiência do usuário aprimorada e promovendo uma abordagem colaborativa entre tecnologia e profissionais de saúde.
- Posto isso desenvolvemos junto ao Telegram e esp32 , um sistema de controle de estoque dos remédios, ou seja quando o estoque está cheio acende o Led Vermelho e o chatbot manda uma mensagem dizendo que o estoque esta cheio, o mesmo acontece quando liga o Led Verde.

Instruções para Configurar e Executar a Aplicação:
1. Baixe e instale o Node-RED em seu ambiente.
2. Importe o fluxo do Node-RED disponibilizado para o controle de medicamentos.
3. Configure as credenciais necessárias para acessar os serviços do Telegram (IDBot e BotFather).
4. Certifique-se de ter um ambiente com o simulador Wokwi configurado e pronto para simular o ESP32 e os componentes necessários.
5. Execute o fluxo no Node-RED e verifique a interação com a assistente virtual, o controle de medicamentos e as notificações via Telegram.

-  Link para a Simulação no Wokwi:
  https://wokwi.com/projects/382153910292286465
