📘 Tormenta Alpha – Sistema de Fichas / Sheet System
🇧🇷 Guia de Uso Detalhado (Português)

1. Visão Geral
O Tormenta Alpha – Sistema de Fichas é uma extensão web para sessões de RPG. Ela permite:

Criar fichas de personagem completas.

Compartilhar fichas em tempo real entre Mestre e Jogadores.

Rolar dados, testes de perícia, ataques, defesas e magias.

Aplicar regras alternativas (dados, cartas, pontos de esforço, etc.).

Gerenciar status, condições, vantagens e inventário.

Conversar por um chat integrado de rolagens.

Tudo funciona direto no navegador, sincronizado via Supabase (banco de dados em nuvem).

2. Primeiro Acesso
Na tela inicial você verá:

Três campos:

Campo	Descrição
Código da Mesa	6 dígitos que identificam a sala compartilhada.
Seu Nome	Como você aparecerá no chat e na lista de jogadores.
Código do Personagem	6 dígitos da ficha. Só para jogadores.
Três botões:

Botão	Função
👑 Criar Mesa	Cria uma nova mesa. Você vira o Mestre.
👑 Mestre	Entra como Mestre em uma mesa existente (mesmo nome da criação).
🎲 Jogador	Entra como jogador usando o código da ficha.
3. Criando uma Mesa (Mestre)
Digite um código de 6 dígitos em "Código da Mesa".

Digite seu nome em "Seu Nome".

Clique em 👑 Criar Mesa.

Pronto. Você está dentro do Painel do Mestre.

⚠️ Não use códigos óbvios como 123456 ou 000000 — o sistema rejeita automaticamente.

4. Entrando como Mestre
Use quando quiser retornar a uma mesa já criada:

Digite o mesmo Código da Mesa.

Digite o mesmo nome usado na criação.

Clique em 👑 Mestre.

Se o nome não bater, o sistema recusa (proteção contra invasão).

5. Entrando como Jogador
Peça ao Mestre: Código da Mesa + Código do Personagem.

Preencha os três campos.

Clique em 🎲 Jogador.

Ao entrar, a ficha NPC criada pelo Mestre passa a ser sua. Você pode editá-la à vontade.

6. Painel do Mestre
O painel exibe duas seções:

🎲 Jogadores: cada um com botões:

Ícone	Ação
🔄	Atualizar ficha
📋	Copiar código
🔄	Regenerar código
👁️	Ver/editar ficha
❌	Excluir
📦 NPCs: mesmos botões + 📄 Duplicar (cria cópia da ficha).

Botões superiores:

➕ Criar Nova Ficha (NPC): cria ficha vazia.

🔑 Gerar Códigos: gera códigos para fichas antigas sem código.

🔄 Atualizar Todas / Atualizar Selecionadas: força sincronização.

7. Estrutura da Ficha
A ficha é dividida em 8 abas:

Aba	Conteúdo
📋 Principal	Atributos, recursos, atalhos de ataque/defesa.
🎯 Testes	Lista de perícias e Teste de Morte.
✨ Vantagens	Vantagens, desvantagens, perícias, especializações.
🎒 Inventário	Itens, equipamentos, tipos de dano.
🔮 Magias	Magias com controles de dano.
📦 Kits	Kits e habilidades internas.
👥 Mais Fichas	Sub-fichas (aliado/familiar/invocação).
⚠️ Status	Condições ativas.
8. Aba Principal
Avatar e Nome:

Clique no círculo para trocar a imagem (redimensionada para 150×150 automaticamente).

Digite o nome no campo acima.

Escala: campo livre para anotar a escala do personagem.

Atributos (F, H, R, A, PdF):

Cada um tem: Valor, B1, B2 e checkbox para ativar B1/B2.

O losango ao lado do valor mostra o total: Valor + B1 + B2 (quando marcados).

💡 B1/B2 de F, A e PdF entram só nas magias e no total do losango.
B1/B2 de H e R entram também em ofícios e testes.

Recursos:

❤️ PV: Total / Atual / Bônus.

✨ PM: Total / Atual / Bônus.

💰 Pontos: saldo atual e campo "Gastos" (edição só para Mestre).

⭐ XP e botão Converter (10 XP = 1 ponto).

🪙 T$: dinheiro.

Rolagem Genérica: quantidade de dados, modificador e botão 🎲 Rolar.

Atalhos: ⚔️ Ataque Curto, 🏹 Ataque à Distância, 🛡️ Defesa.

9. Aba Testes
Dificuldade global: Fácil, Médio, Difícil (Impossível aparece se a regra estiver ativa).

Cada perícia tem:

Nome + atributo associado (ex: Acrobacia (H)).

Checkbox TREINADO.

Campo Bônus (soma) e Penalidade (subtrai).

Botão 🎲 para rolar.

Teste de Morte: botão que rola 1d6 e retorna:

1 → Muito Fraco.

2-3 → Inconsciente.

4-5 → Quase Morto.

6 → Morto.

10. Aba Vantagens
Vantagem Regional e Vantagem Única (nome, custo, descrição).

Listas de Vantagens, Desvantagens, Perícias e Especializações.

Cada item tem campo Nome, Custo, botão 📖 (descrição) e ícone i (info).

11. Aba Inventário
Três listas: 📦 Itens, ⚔️ Equipamentos, 💥 Tipos de Dano.

Cada item: nome, custo, descrição.

12. Aba Magias
Cada magia tem:

Nome e descrição.

Checkboxes para F, H, R, A e PdF.

Campo Valor (bônus livre).

Campo Dados d6.

Botão 🔮 Lançar Magia.

O cálculo usa o total de cada atributo (com B1/B2).

Exemplo: F=5 (B1=+2, B2=+1), H=4, checkbox F e H marcados, valor=3, dados=2:
(5+2+1) + 4 + 3 + (d6+d6) = 15 + 2d6

13. Aba Kits
Kits com:

Nome e custo.

Descrição.

Habilidades internas (nome + custo + descrição).

14. Aba Mais Fichas (Sub-fichas)
Sub-fichas são fichas completas dentro da ficha principal.

Tipos:

🤝 Aliado.

🐾 Familiar.

✨ Invocação.

Cada sub-ficha tem: atributos próprios (com B1/B2), recursos, listas, magias e status.

Quem pode editar:

Você — sub-fichas que você criou.

Mestre — todas.

15. Aba Status
Lista de mais de 30 condições (Fúria, Cego, Envenenado, Doenças, Petrificado, etc.).

Ao marcar uma condição:

A condição entra no chat.

O badge ⚠️ Status no topo é atualizado.

O popup ⚠️ Condições Ativas mostra todas as condições de todas as fichas (para todos os usuários).

16. Rolagens
Rolagem Genérica: quantidade de dados + modificador.

Testes: marque TREINADO, preencha bônus/penalidade, clique em 🎲.

Ataques: popup com nome, B1/B2/BFA, dados, crítico automático/aprimorado.

Defesas: popup com B1/B2/BFD, inclusão de A/H, dados, crítico.

Magias: botão direto com controle de atributos.

Todas as rolagens vão para o chat em tempo real.

17. Regras Alternativas
O Mestre clica em 📜 Regras da Mesa e escolhe uma das regras de cada categoria:

🎯 Testes:

Contra dificuldade.

Com bonificação treinada.

Pilha de dados.

Com cartas.

Sem fator aleatório (PE).

Nível de sucesso.

⚔️ Ataques:

Teste antes do dano.

Pilha de dados.

Com cartas.

Pontos de Esforço.

Combate sem PV.

Cada regra tem subopções e configurações editáveis. Tudo se aplica em tempo real.

18. Chat de Rolagens
Fica na coluna direita.

Exibe as últimas 30 rolagens.

Atualiza em tempo real via WebSocket.

Mestre pode marcar 🕵️ Segredo — a rolagem só aparece para ele.

19. Baralho (Cartas)
Quando a regra Cartas está ativa:

Clique em 🃏 Comprar mão (4 cartas).

Selecione o radio de uma perícia.

Clique numa carta virada para revelá-la e testar.

Figuras (J/Q/K) = 6 (falha automática).

Coringa = puxa carta do monte: vermelha = sucesso absoluto, preta = falha total.

Só compra nova mão quando as 4 forem usadas.

20. Itens Sustentados
Magias e vantagens têm checkbox à esquerda. Ao marcar:

O item é considerado sustentado.

O badge 🪄 no topo conta os sustentados.

O Mestre pode cancelar de qualquer jogador.

21. Exportar / Importar
📤 Exportar: baixa um JSON com toda a ficha.

📥 Importar: carrega um JSON, substituindo a ficha atual.

Útil para backup ou transferir personagem entre mesas.

22. Dicas e Boas Práticas
Sempre confira o código da mesa antes de criar. Códigos duplicados são bloqueados.

Salve frequentemente: o sistema salva automaticamente após 300 ms, mas o botão 🔄 Atualizar Ficha força sincronização.

Mestre pode marcar rolagens como segredo — útil para testes ocultos.

NPCs duplicados herdam a ficha, mas geram novo código.

Sub-fichas não são compartilhadas automaticamente — apenas o dono as vê, a menos que o Mestre inspecione.

Status são globais: o popup "Condições Ativas" mostra as de todos.

Backup semanal via exportação é recomendado.



🇺🇸 Detailed User Guide (English)

1. Overview
Tormenta Alpha – Sheet System is a web extension for RPG sessions. It allows you to:

Create complete character sheets.

Share sheets in real time between GM and Players.

Roll dice, skill tests, attacks, defenses and spells.

Apply alternative rules (dice pools, cards, effort points, etc.).

Manage status, conditions, advantages and inventory.

Chat via an integrated roll chat.

Everything runs directly in the browser, synced via Supabase (cloud database).

2. First Access
On the login screen you'll see:

Three fields:

Field	Description
Table Code	6 digits identifying the shared room.
Your Name	How you'll appear in the chat and player list.
Character Code	6 digits of the sheet. Players only.
Three buttons:

Button	Function
👑 Create Table	Creates a new table. You become the GM.
👑 GM	Joins an existing table as GM (same name as creation).
🎲 Player	Joins as player using the sheet code.
3. Creating a Table (GM)
Type a 6-digit code into "Table Code".

Type your name into "Your Name".

Click 👑 Create Table.

You're now inside the GM Panel.

⚠️ Avoid obvious codes like 123456 or 000000 — the system rejects them.

4. Joining as GM
Use this to return to an existing table:

Type the same Table Code.

Type the same name used at creation.

Click 👑 GM.

If the name doesn't match, the system refuses (anti-intrusion protection).

5. Joining as Player
Ask the GM for: Table Code + Character Code.

Fill in the three fields.

Click 🎲 Player.

Once inside, the NPC sheet created by the GM becomes yours. You can edit it freely.

6. GM Panel
The panel shows two sections:

🎲 Players: each with buttons:

Icon	Action
🔄	Update sheet
📋	Copy code
🔄	Regenerate code
👁️	View/edit sheet
❌	Delete
📦 NPCs: same buttons + 📄 Duplicate (creates a copy).

Top buttons:

➕ Create New Sheet (NPC): creates an empty sheet.

🔑 Generate Codes: generates codes for old sheets without code.

🔄 Update All / Update Selected: forces sync.

7. Sheet Structure
The sheet is split into 8 tabs:

Tab	Content
📋 Main	Attributes, resources, attack/defense shortcuts.
🎯 Tests	Skill list and Death Test.
✨ Advantages	Advantages, disadvantages, skills, specializations.
🎒 Inventory	Items, equipment, damage types.
🔮 Spells	Spells with damage controls.
📦 Kits	Kits and inner abilities.
👥 More Sheets	Sub-sheets (ally/familiar/summon).
⚠️ Status	Active conditions.
8. Main Tab
Avatar and Name:

Click the circle to change the image (auto-resized to 150×150).

Type the name in the field above.

Scale: free field for the character's scale.

Attributes (F, H, R, A, PdF):

Each has: Value, B1, B2 and a checkbox to enable B1/B2.

The diamond next to the value shows the total: Value + B1 + B2 (when checked).

💡 B1/B2 of F, A and PdF enter only spells and diamond totals.
B1/B2 of H and R also enter crafts and tests.

Resources:

❤️ HP: Total / Current / Bonus.

✨ MP: Total / Current / Bonus.

💰 Points: current balance and "Spent" field (GM-only edit).

⭐ XP and Convert button (10 XP = 1 point).

🪙 $: money.

Generic Roll: dice count, modifier and 🎲 Roll button.

Shortcuts: ⚔️ Melee Attack, 🏹 Ranged Attack, 🛡️ Defense.

9. Tests Tab
Global difficulty: Easy, Medium, Hard (Impossible appears if the rule is active).

Each skill has:

Name + associated attribute (e.g., Acrobatics (H)).

TRAINED checkbox.

Bonus field (adds) and Penalty field (subtracts).

🎲 button to roll.

Death Test: button that rolls 1d6 and returns:

1 → Very Weak.

2-3 → Unconscious.

4-5 → Near Death.

6 → Dead.

10. Advantages Tab
Regional Advantage and Unique Advantage (name, cost, description).

Lists of Advantages, Disadvantages, Skills and Specializations.

Each item has Name, Cost, 📖 (description) and i (info) icons.

11. Inventory Tab
Three lists: 📦 Items, ⚔️ Equipment, 💥 Damage Types.

Each item: name, cost, description.

12. Spells Tab
Each spell has:

Name and description.

Checkboxes for F, H, R, A and PdF.

Value field (free bonus).

d6 Dice field.

🔮 Cast Spell button.

The calculation uses the total of each attribute (with B1/B2).

Example: F=5 (B1=+2, B2=+1), H=4, F and H checked, value=3, dice=2:
(5+2+1) + 4 + 3 + (d6+d6) = 15 + 2d6

13. Kits Tab
Kits with:

Name and cost.

Description.

Inner abilities (name + cost + description).

14. More Sheets Tab (Sub-sheets)
Sub-sheets are full sheets inside the main sheet.

Types:

🤝 Ally.

🐾 Familiar.

✨ Summon.

Each sub-sheet has: its own attributes (with B1/B2), resources, lists, spells and status.

Who can edit:

You — sub-sheets you created.

GM — all of them.

15. Status Tab
List of 30+ conditions (Fury, Blind, Poisoned, Diseases, Petrified, etc.).

When you check a condition:

The condition enters the chat.

The ⚠️ Status badge at the top updates.

The ⚠️ Active Conditions popup shows all conditions from all sheets (for every user).

16. Rolls
Generic Roll: dice count + modifier.

Tests: check TRAINED, fill bonus/penalty, click 🎲.

Attacks: popup with name, B1/B2/BFA, dice, auto/improved critical.

Defenses: popup with B1/B2/BFD, include A/H, dice, critical.

Spells: direct button with attribute controls.

All rolls go to the chat in real time.

17. Alternative Rules
The GM clicks 📜 Table Rules and picks one rule per category:

🎯 Tests:

Against difficulty.

With trained bonus.

Dice pool.

With cards.

Without random factor (EP).

Success level.

⚔️ Attacks:

Test before damage.

Dice pool.

With cards.

Effort Points.

Combat without HP.

Each rule has sub-options and editable configurations. Everything applies in real time.

18. Roll Chat
On the right column.

Shows the last 30 rolls.

Updates in real time via WebSocket.

GM can mark 🕵️ Secret — the roll only appears to them.

19. Deck (Cards)
When the Cards rule is active:

Click 🃏 Buy hand (4 cards).

Select the radio of a skill.

Click a face-down card to reveal it and test.

Face cards (J/Q/K) = 6 (auto fail).

Joker = draw from deck: red = auto success, black = auto fail.

Only buy a new hand when all 4 are used.

20. Sustained Items
Spells and advantages have a checkbox on the left. When checked:

The item is considered sustained.

The 🪄 badge at the top counts them.

The GM can cancel anyone's sustaining.

21. Export / Import
📤 Export: downloads a JSON of the entire sheet.

📥 Import: loads a JSON, replacing the current sheet.

Useful for backups or transferring characters between tables.

22. Tips and Best Practices
Always check the table code before creating. Duplicate codes are blocked.

Save often: the system auto-saves after 300 ms, but 🔄 Update Sheet forces a sync.

GM can mark rolls as secret — useful for hidden tests.

Duplicated NPCs inherit the sheet but get a new code.

Sub-sheets are not shared automatically — only the owner sees them, unless the GM inspects.

Status is global: the "Active Conditions" popup shows everyone's.

Weekly backup via export is recommended.
