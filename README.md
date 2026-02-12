Sistema de Reservas de Hotel (WorkerContracts)
Este projeto é uma aplicação simples em Java desenvolvida para gerenciar reservas de quartos de hotel. Ele foca na lógica de validação de datas e no cálculo de duração de estadias.

🚀 Funcionalidades
*Cadastro de reserva com número do quarto, data de check-in e check-out.
*Cálculo automático do número de noites (estadia).
*Atualização de reservas com validações de segurança:
  *O check-out deve ser posterior ao check-in.
  *Em atualizações, as novas datas devem ser futuras (não é permitido    alterar reservas para datas passadas).

🛠️ Tecnologias Utilizadas
 *Linguagem: Java 17+
 *Manipulação de Datas: java.util.Date e java.text.SimpleDateFormat
 *Cálculo de Tempo: java.util.concurrent.TimeUnit

📁 Estrutura do Projeto
O projeto segue a estrutura básica de pacotes:

Plaintext
src
 ├── application  # Contém a classe principal (Program.java)
 └── model        # Contém a lógica de negócio (Reservation.java)

⚙️ Como executar
1. Certifique-se de ter o JDK instalado em sua máquina.

2. Clone o repositório:

Bash:
git clone https://github.com/edvaldoneto98/WorkerContracts.git

3. Navegue até a pasta do projeto e compile os arquivos:

Bash
javac src/application/Program.java src/model/Reservation.java

4. Execute o programa:

Bash:
java src.application.Program
📝 Exemplo de Uso
Plaintext
Room number: 8021
Check-in date (dd/MM/yyyy): 13/10/2026
Check-out date (dd/MM/yyyy): 15/10/2026
Reservation: Room 8021, check-in: 13/10/2026, check-out: 15/10/2026, 2 nights
Feito com ❤️ por Neto

Como adicionar ao seu projeto:

1. No seu VS Code (ou terminal), crie um arquivo chamado README.md na raiz da pasta WorkerContacts.

2. Cole o conteúdo acima.

3. Para subir para o GitHub, rode:

Bash:
git add README.md
git commit -m "docs: adicionar readme explicativo"
git push
