# Caravela Logger

**Backup de fotos e vídeos para quem fotografa e filma, no Windows.**
Conecte o cartão ou a câmera: o Caravela Logger mostra o que tem nele, separa o material por
trabalho, copia para a pasta certa, confere cada arquivo com o original e deixa tudo pronto para editar.
Ele nunca apaga nada do cartão.

Criado por Pedro Tofo, Caravela Studio.

**[⬇ Baixar a versão mais recente](https://github.com/pedrotofo/caravela-logger/releases/latest)**

![A tela principal do Caravela Logger: o que tem no cartão, separado por trabalho](docs/tela-principal.png)
<sub>Simulação com clientes fictícios e fotos de banco de imagens (Unsplash).</sub>

---

## O que dá para fazer

**Com cartões de memória e câmeras**
- Perceber sozinho quando um cartão ou câmera é conectado, com um aviso discreto no canto da tela.
- Ver o que tem no cartão antes de copiar: fotos, vídeos, tamanho, câmeras usadas e miniaturas.
- Separar o material em trabalhos automaticamente: três horas ou mais sem gravar viram trabalhos diferentes.
  Se o programa errar, um clique junta ou separa de novo.
- Dar nome a cada trabalho (com os nomes usados por último a um clique) e criar a pasta com esse nome.
- Escolher como os arquivos são nomeados: só o nome do trabalho, nome e data, nome e câmera, ou o nome original.
- Organizar a pasta do jeito que fizer sentido: tudo solto, fotos e vídeos separados, ou uma pasta por câmera.
- Ver como a pasta vai ficar antes de copiar.
- Deixar um trabalho no cartão para copiar depois.

**Reconhece sozinho o que foi conectado**
- Câmeras: Sony (Alpha, FX, Venice), Canon (fotográficas e Cinema EOS), Panasonic (Lumix e P2), Fujifilm, Nikon, Leica, OM System.
- Cinema: Blackmagic (BRAW), RED (R3D), ARRI, Canon Cinema RAW.
- Drones e câmeras de ação: DJI, GoPro, Insta360.
- Gravadores de áudio (Zoom, Tascam e outros) e gravadores externos.
- SSDs e HDs externos são ignorados, a não ser que sejam o disco de gravação de uma câmera de cinema (BRAW, RED, ARRI).

**Em toda cópia**
- Conferir cada arquivo com o original depois de copiar. Nada é dado como copiado sem conferência.
- Continuar de onde parou se a cópia for interrompida, sem copiar nada duas vezes.
- Fazer uma segunda cópia em outro disco, se você quiser.
- Abrir as fotos no Lightroom e preparar o projeto do Premiere com os vídeos, quando estiverem instalados.
- Guardar uma ficha de cada backup e um registro (`_backup_log.csv`) com tudo o que foi copiado.

## Como instalar

1. Baixe o arquivo `CaravelaLogger-…-setup.exe` da [versão mais recente](https://github.com/pedrotofo/caravela-logger/releases/latest).
2. Dê dois cliques. Não precisa de senha de administrador.
3. O instalador ainda não tem assinatura digital. Se o Windows mostrar "O Windows protegeu o computador",
   clique em **Mais informações** e depois em **Executar assim mesmo**.

Depois de instalado, o programa fica ao lado do relógio e **se atualiza sozinho** quando sai uma versão nova.

## Privacidade

O programa roda só no seu computador. Não lê agenda nem e-mail e não envia fotos ou dados para nenhum
servidor. A internet só é usada para ver se existe uma versão nova.

---

Este repositório guarda só os instaladores. © 2026 Pedro Tofo / Caravela Studio. Todos os direitos reservados.
