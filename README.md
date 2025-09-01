Medication Reminder App
Um aplicativo simples desenvolvido em SwiftUI para lembrar os usuários de tomar seus remédios no horário correto, com suporte a notificações locais.
Captura de Tela

O Medication Reminder App permite que os usuários adicionem remédios com nome, horário e frequência, recebam lembretes via notificações locais e marquem os remédios como tomados. O app armazena os dados localmente usando UserDefaults e é projetado para ser intuitivo e funcional.
Funcionalidades

Adicionar remédios com nome, horário e frequência.
Lembretes via notificações locais.
Marcar remédios como tomados.
Lista de remédios com opção de exclusão.
Interface limpa e responsiva com SwiftUI.

Pré-requisitos

Xcode: Versão 15 ou superior.
macOS: Para desenvolvimento.
Apple Developer Program: Necessário para testes em dispositivo e publicação ($99/ano).
Conhecimento básico de Swift e SwiftUI (opcional, mas recomendado).

Instalação

Clone o repositório:
git clone https://github.com/arefdeveloper91/Reminder


Abra o projeto no Xcode:

Navegue até o diretório do projeto:cd medication-reminder


Abra o arquivo .xcodeproj ou .xcworkspace no Xcode.


Configure o ambiente:

Adicione a permissão de notificações no Info.plist:
Chave: Privacy - Notifications Usage Description.
Valor: "Este app usa notificações para lembrar você de tomar seus remédios."


Certifique-se de que o Xcode está atualizado.
Selecione um simulador iOS (ex.: iPhone 16) ou conecte um dispositivo.


Execute o aplicativo:

Pressione Cmd+R no Xcode para compilar e rodar.



Uso

Abra o aplicativo no simulador ou dispositivo.
Toque em "Adicionar Remédio" para inserir um novo remédio (nome, horário e frequência).
Aguarde a notificação no horário definido ou marque o remédio como tomado na lista.
Deslize para a esquerda em um remédio na lista para excluí-lo.

Estrutura do Código

ReminderApp.swift: Ponto de entrada do aplicativo com configuração de notificações.
ContentView.swift: View principal com lista de remédios, adição e marcação.
AddMedicationView.swift: Tela para adicionar novos remédios.

Contribuindo
Sinta-se à vontade para contribuir! Para melhorias ou correções:

Faça um fork do repositório.
Crie uma branch para sua feature ou correção:git checkout -b feature/nova-funcionalidade


Commit suas alterações:git commit -m "Descrição da alteração"


Envie para o repositório:git push origin feature/nova-funcionalidade


Abra um Pull Request.

Melhorias Futuras

Integração com HealthKit para rastreamento de saúde.
Suporte a múltiplos lembretes por remédio.
Persistência de dados com Core Data ou Firebase.
Interface personalizável (temas, notificações visuais).



<img width="1206" height="2622" alt="Simulator Screenshot - iPhone 16 Pro - 2025-09-01 at 14 37 43" src="https://github.com/user-attachments/assets/87ae59e6-7543-4f47-939c-05d6b3523227" />
<img width="1206" height="2622" alt="Simulator Screenshot - iPhone 16 Pro - 2025-09-01 at 14 37 30" src="https://github.com/user-attachments/assets/98312be7-d383-42a0-a8d4-ab3e43a846cb" />









