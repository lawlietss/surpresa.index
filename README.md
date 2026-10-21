# OPERAÇÃO RITONA

Primeira versão funcional do site de aniversário, organizada em arquivos separados e pensada primeiro para celular.

## Abrir localmente
1. Extraia a pasta `operacao-ritona`.
2. Abra `index.html` no navegador. Para melhores resultados, hospede a pasta em um serviço de site estático.
3. A resposta da tela de acesso é: **Posso pensar nessa questão depois?**
   A tela é temática, não é segurança real.

## Adicionar fotografias
1. Coloque suas fotos em `assets/photos/`.
2. Abra `data/memories.js`.
3. Em cada fragmento, troque `src: ""` por um caminho como `src: "assets/photos/foto-01.jpg"`.
4. Ajuste `title` e `caption` para que combinem com cada foto.

Nenhuma fotografia foi inventada nem incluída. Os três fragmentos são espaços reservados.

## Adicionar música ambiente
1. Adicione um arquivo de áudio que você tenha direito de usar em `assets/audio/`.
2. Renomeie-o para `ambiente.mp3`.
3. O botão `MÚSICA` no topo controla reprodução e pausa. Alguns navegadores exigem um toque explícito antes de permitir áudio.

## Salvamento
O progresso é guardado automaticamente no `localStorage` do navegador. Ele fica nesse navegador/dispositivo; não sincroniza entre dispositivos. O botão de reinício apaga o progresso salvo.

## Personalização
- Texto e cenas: `data/story.js`
- Itens: `data/items.js`
- Fotos e legendas: `data/memories.js`
- Estilos: `css/`
- Progressão e escolhas: `js/missions.js`
- Acesso, modais e eventos: `js/main.js`

## Observações
- A referência a Sasuke e Sakura é uma piada de roteiro; não há imagens de personagens embutidas.
- Os três espaços reservados da galeria podem ser abertos para testar a progressão mesmo antes de você adicionar as fotos.
- Para hospedar, envie a pasta inteira preservando a estrutura de diretórios.
