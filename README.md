
# Meu maior projeto WEB
Estou terminando um curso de NodeJS de mais de 500 aulas, e pra por em prática tudo o que aprendi, decidi fazer um ecosistema de blog completamente do zero... indo ALÉM do Crud básico, pensado para gerar receita (**PIX**, Insíginia), e para facilmente modificar qualquer coisa.<br/><br/>
<img width="1536" height="1024" alt="image" src="https://github.com/user-attachments/assets/46101859-c171-4004-95ee-62d2dcb3e8fa" /><br/>

## Recursos
Para ir além do Crud básico, decidi ver até onde conseguiria levar esse projeto... e bem... o resultado foi essas implementações:

## Serviços usados:
- Cloudinary
- Recaptcha (Google)
- MongoDB
- MercadoPago
- SendGrid
- Vercel
- Render

### Usuários
- Sistema completo de autenticação
- Perfil de usuário (foto, banner, nickname, bio e privacidade do e-mail)
- Sistema completo de comentários com proteção anti-bot
- Proteção contra spam e abuso (Rate Limit)
- Sistema de cargos (Administrador, Moderador e Doador via PIX)
- Sistema de curtidas em perfis (estilo Instagram)
- Sistema de banimento de contas com motivo
- Painel de moderação e administração
- Alteração e recuperação de senha
- Verificação de e-mail
- Sistema de notificações em tempo real
- Sistema de badges/conquistas
- Sistema de login usando o Google

### Posts e Enquetes
- Criação, edição e exclusão de posts
- Sistema de enquetes com imagens
- Votação em enquetes (votar, alterar voto e remover voto)
- Upload de capa para posts
- Slugs amigáveis gerados automaticamente
- Busca por título e tags
- Sistema de tags
- Contador de visualizações com proteção contra spam
- Página inicial inteligente (destaques, mais vistos e conteúdo recente)
- Soft Delete (conteúdo pode ser restaurado)
- Paginação

### Receitas
- MercadoPago como principal uso de pagamento (QR Code, ou PIX copia-cola). Com sistema de badges usados para incentivar os usuários

### Proteções no Servidor
- Sistema CAPTCHA para impedir bots na maioria das operações (Captcha)
- Validação de emails para impedir criação de contas fakes (SendGrid)
- Proteção contra XSS usando escapeHTML
- Salvando sessões no Mongodb (para grande escala)
- Soft Delete (nada é realmente deletado, somente oculto para os admins)
- Grandes medidas de validação contra spam,  em todos os aspectos (comentários, curtidas, atomic update, votação/poll, pagamento)
- Outras validações e mecanismos de segurança distribuídos ao longo da aplicação.

### FrontEnd
- TODAS as telas são adaptadas para qualquer tela
- Pega dados do backend e atualiza automaticamente
- Responsivo e estilizado de forma que, se você quiser alterar rapidamente, só precisa mexer em "Global.css"

#### Ainda está faltando algumas coisas...

### Facilitação do código
Quando comecei a desenvolver esse projeto, o que mais me veio na mente foi: **"E se alguém quiser rapidamente modificar algo nele?"**, então concentrei tudo em váriaveis, no .ENV, de forma que, se você quiser fazer o upload agora mesmo, você só precisa preencher os valores<br/><br/>
TODA a estrutura de comentários, sistema de curtidas, badges e etc, foi pensando: **"E se o sistema se escalar rapidamente?"**, então usei métodos para que garantissem uma **boa escalação**, de forma inteligente...<br/><br/>
<img width="300" height="651" alt="Screenshot 2026-07-14 at 19-27-44 Cluster0 Data Cloud MongoDB Cloud" src="https://github.com/user-attachments/assets/c2c66ec9-1363-40b7-8260-f284f9b60cd7" />
<img width="1499" height="236" alt="Screenshot 2026-07-14 at 19-27-35 Cluster0 Data Cloud MongoDB Cloud" src="https://github.com/user-attachments/assets/9c2b7a09-5bdb-4fe0-8c73-6c78c586500f" /><br/>
Você verá que tudo foi organizado de forma inteligente para evitar dor de cabeça futuramente, e para que, se você quiser implementar algo novo, você possa.

### Um vídeo de demonstração básico
Embora o vídeo demonstre o site em ação de forma "simples", lembre-se que há uma estrutura inteligente por trás de tudo para criar um sistema robusto e seguro.<br/><br/>
- [Vídeo de demonstração 1](https://github.com/user-attachments/assets/09d3e4b4-a117-466b-bdd7-a41d0717c3b8)
- [Vídeo de demonstração 2](https://github.com/user-attachments/assets/3d9ce0a0-b2e0-4650-8ecc-ee5a46ac0efa)

### Tem dúvidas?
Eu fiz o site **pensando em VOCÊ**. Eu quero que você entenda o código facilmente, e que, se quiser adaptar pro seu estilo (caso você não queira um blog), você pode mudar facilmente. No entanto, se você tiver dúvidas ou quiser ajuda para implemetarmos ele no ar juntos, estarei disponível para ajuda-lo.<br/>
Discord: **eldimas**

#### É isso....
Demorei meses pra fazer esse site, e aprender como faze-lo corretamente. Qualquer feedback caso você tenha, fique a vontade para comentar.

### Imagens de ALGUMAS telas<br/>
<img width="470" height="468" alt="image" src="https://github.com/user-attachments/assets/6c0f7034-6b5b-430a-b728-dd06ae59caa2" /><br/><br/>
<img width="1920" height="975" alt="image" src="https://github.com/user-attachments/assets/ab7f6c4a-3106-4da9-8db9-a93ce9eedf66" /><br/><br/>
<img width="1920" height="843" alt="image" src="https://github.com/user-attachments/assets/3f4d3a8e-1c19-4919-82d0-48773732eb61" /><br/><br/>
<img width="430" height="866" alt="image" src="https://github.com/user-attachments/assets/47ea0367-3efb-4d71-a352-d456a703128e" /><br/><br/>
<img width="860" height="566" alt="image" src="https://github.com/user-attachments/assets/3bf34b1d-813c-45e7-84c0-acc8d0cd72eb" /><br/><br/>
<img width="860" height="547" alt="image" src="https://github.com/user-attachments/assets/dac2cec0-d573-43ea-8e9f-9f2054a5d039" />
