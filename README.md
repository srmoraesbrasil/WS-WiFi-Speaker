# 🎧 WiFi Speaker Launcher

> Transforme seu Android em uma caixa de som Wi‑Fi para o seu PC ou notebook, com **baixa latência**, **receptor em segundo plano**, **atualização via GitHub** e **experiência gratuita, sem anúncios e com tudo liberado**.

<p align="center">
  <strong>Projeto gratuito desenvolvido por SrMoraes</strong><br>
  📺 Canal oficial: <a href="https://www.youtube.com/@srmoraesbrasil">@srmoraesbrasil</a>
</p>

---

## ✨ O que é o WiFi Speaker Launcher?

O **WiFi Speaker Launcher** é um sistema com duas partes:

- **Launcher Windows** → envia o áudio do computador pela rede Wi‑Fi.
- **App Android Receiver** → recebe o áudio e reproduz no celular.

Na prática, ele permite usar o **celular Android como uma “caixinha de som” sem fio do PC**.

---

## 🚀 Principais funções da versão atual

### No Windows (Launcher Portable)
- 🔎 Busca automática de Androids na rede local
- ➕ Adição manual de IP
- 🔗 Conexão e desconexão do receptor
- 🔊 Seleção da saída de áudio do sistema
- ⚡ Modos de latência e estabilidade
- 🎮 **Modo Jogo / FPS com ultra baixa latência (15 ms)**
- 📦 Modo portable
- 🖥️ Interface profissional redesenhada
- 🔄 Atualização via `version.json` no GitHub
- 🧠 Salva preferências em `%APPDATA%`
- 🚀 Opção para iniciar com o Windows
- 🧷 Opção de minimizar para a bandeja (tray)
- 💾 Salvar dispositivos encontrados
- 🧾 Log da sessão em tempo real

### No Android (Receiver)
- 📶 Fica disponível automaticamente para conexão
- ▶️ Controle simples para ativar/desligar o receptor
- 📱 Exibe status do receptor em tempo real
- 🔌 Mostra dispositivo conectado
- 🧠 Serviço em segundo plano
- 🔋 Botão para liberar segundo plano / bateria
- 🌑 **Modo tela preta anti-sono**
- 💤 **Sistema anti-sono com sinal piloto 5 Hz**
- ⚡ Ultra baixa latência com foco em sincronismo
- 🔄 Atualizações via GitHub
- 👑 Botão do fundador com link para o canal

---

## 🧩 Como funciona

1. Você abre o **app Android Receiver**.
2. Ativa o receptor no celular.
3. Abre o **Launcher no Windows**.
4. Procura o Android na rede local.
5. Conecta.
6. Inicia a transmissão.
7. O áudio do PC passa a sair no Android.

---

## 📸 Guia visual de uso

## 1) App Android desligado

Quando o app estiver desligado, o status do receptor aparecerá como **Desligado**.

<p align="center">
  <img src="docs/images/android-status-desligado.jpg" alt="WiFi Speaker Android desligado" width="360">
</p>

### O que fazer nesta tela?
- Toque em **Ativar receptor**.
- O app passará a ficar disponível para o Windows encontrar.

---

## 2) App Android disponível para conexão

Depois de ativar, o receptor passa a ficar **Disponível**.

<p align="center">
  <img src="docs/images/android-status-disponivel.jpg" alt="WiFi Speaker Android disponível" width="360">
</p>

### O que esta tela mostra?
- **Status do receptor**
- **Nome do aparelho**
- **IP local do Android**
- **Portas UDP e Controle**
- Estado atual do dispositivo conectado

### Nesta etapa:
- Abra o launcher no Windows.
- Clique em **Procurar dispositivos**.
- Selecione o Android encontrado.
- Clique em **Conectar**.
- Depois clique em **Iniciar transmissão**.

---

## 3) Segundo plano, bateria e atualização

Esta área foi criada para aumentar a estabilidade do receiver no Android.

<p align="center">
  <img src="docs/images/android-background-update.jpg" alt="WiFi Speaker segundo plano e atualização" width="360">
</p>

### Recursos dessa área:
- **Liberar segundo plano / bateria**
  - Abre as configurações do Android para reduzir bloqueios do sistema.
- **Modo tela preta anti-sono**
  - Ajuda em aparelhos mais agressivos com economia de energia.
- **Atualizações via GitHub**
  - O app consulta a versão remota e informa quando há atualização.

---

## 🖥️ Como usar no Windows

### Passo a passo
1. Abra o **WiFi Speaker Launcher** no PC.
2. Aguarde a checagem de versão.
3. Clique em **Procurar dispositivos**.
4. Selecione o Android localizado.
5. Clique em **Conectar**.
6. Escolha a **saída de áudio** desejada.
7. Escolha o modo de sincronismo:
   - **Jogo / FPS • 15 ms** → menor atraso possível
   - **Vídeo / menor atraso** → equilíbrio entre fluidez e sincronismo
   - **Alta estabilidade** → mais estável em redes piores
8. Clique em **Iniciar transmissão**.

### Dicas
- Para vídeos, use uma rede Wi‑Fi estável.
- Para jogos, prefira o modo **15 ms**.
- Se o Android não for encontrado automaticamente, adicione o **IP manual**.

---

## 📱 Como usar no Android

### Passo a passo
1. Instale o APK.
2. Abra o app **WiFi Speaker**.
3. Toque em **Ativar receptor**.
4. Se quiser mais estabilidade, toque em **Liberar segundo plano / bateria**.
5. Se seu aparelho costuma pausar apps em segundo plano, ative o **Modo tela preta anti-sono**.
6. Deixe o app pronto para receber a conexão.
7. Faça a conexão pelo Windows.

---

## 🎮 Modos de latência

### Jogo / FPS • 15 ms
- Foco em menor atraso possível
- Recomendado para jogos e uso mais responsivo
- Pode exigir rede Wi‑Fi mais estável

### Vídeo / menor atraso
- Bom equilíbrio entre sincronismo e estabilidade
- Indicado para YouTube, filmes e séries

### Alta estabilidade
- Melhor para redes mais fracas ou instáveis
- Aumenta o buffer para reduzir falhas

---

## 💤 Anti-sono e continuidade do áudio

Um dos focos do projeto é evitar que o Android “durma” e pare de reproduzir áudio quando a tela apaga ou quando há um período sem som.

### Soluções implementadas
- **Serviço em segundo plano**
- **Wake lock / Wi‑Fi de baixa latência**
- **Sinal piloto 5 Hz anti-sono** quando não há áudio ativo
- **Modo tela preta anti-sono** para casos mais difíceis
- **Acesso rápido para liberar bateria / segundo plano**

> Em alguns aparelhos Android, o fabricante pode aplicar bloqueios agressivos de economia de energia. Nesses casos, liberar o app nas configurações de bateria é essencial.

---

## 🔄 Atualizações via GitHub

O sistema usa um `version.json` hospedado no GitHub para:

- verificar se existe nova versão
- avisar o usuário
- bloquear versões antigas quando necessário
- direcionar para a página de download/release

### Campos importantes do `version.json`
- `current_version`
- `min_supported_version`
- `force_update`
- `maintenance_mode`
- `android.keyversion`
- `windows.keyversion`
- `download_url`

---

## 📁 Estrutura recomendada do repositório

```bash
WS-WiFi-Speaker/
├─ README.md
├─ version.json
├─ android/
│  └─ AndroidWifiSpeakerV2/
├─ pc-client/
│  ├─ launcher_gui.py
│  ├─ speaker_core.py
│  ├─ build-portable-windows.bat
│  └─ ...
└─ docs/
   └─ images/
      ├─ android-status-desligado.jpg
      ├─ android-status-disponivel.jpg
      └─ android-background-update.jpg
```

---

## 📥 Como baixar e instalar

## Android
1. Vá para a área de **Releases** do repositório.
2. Baixe o APK mais recente.
3. Instale no Android.
4. Se o sistema pedir, permita instalação de fontes desconhecidas.
5. Abra o app e ative o receptor.

## Windows
1. Vá para a área de **Releases** do repositório.
2. Baixe a versão **portable** do launcher.
3. Extraia a pasta.
4. Execute o launcher.
5. Procure o Android e inicie a transmissão.

---

## 🛠️ Configurações do launcher Windows

O launcher pode salvar preferências como:

- iniciar com Windows
- salvar dispositivos
- lembrar último dispositivo
- procurar Android ao abrir
- minimizar para bandeja ao fechar

Essas configurações são salvas em `%APPDATA%`.

---

## ❗ Solução de problemas

### O Android não aparece no Windows
- Verifique se os dois estão na **mesma rede Wi‑Fi**.
- Confira se o receptor está **Ativado**.
- Use o **IP manual** se necessário.

### O áudio para quando o celular fica parado
- Toque em **Liberar segundo plano / bateria**.
- Ative o **Modo tela preta anti-sono**.
- Desative otimizações agressivas de bateria para o app.

### Está com atraso no áudio
- Use o modo **Jogo / FPS • 15 ms**.
- Aproxime os dispositivos do roteador.
- Evite redes congestionadas.

### O launcher não inicia com o Windows
- Verifique se a opção está marcada nas configurações.
- Execute o launcher uma vez com privilégios adequados, se necessário.

---

## 👑 Fundador

**SrMoraes**  
📺 Canal oficial: [https://www.youtube.com/@srmoraesbrasil](https://www.youtube.com/@srmoraesbrasil)

---

## 📜 Licença / uso

Projeto disponibilizado de forma **gratuita**, **sem anúncios** e com **todas as funções liberadas**, pensado para facilitar o uso do Android como receptor de áudio via Wi‑Fi.

Se quiser acompanhar novidades, correções e melhorias, acompanhe o repositório e o canal do **SrMoraes**.

---

<p align="center">
  Feito com dedicação por <strong>SrMoraes</strong> 🚀
</p>
