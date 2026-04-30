<p align="center">
  <img src="docs/assets/hero.svg" alt="WiFi Speaker Launcher" width="100%">
</p>

<p align="center">
  <a href="https://github.com/srmoraesbrasil/WS-WiFi-Speaker/releases/latest"><img src="https://img.shields.io/badge/Download-Releases-35D0FF?style=for-the-badge&logo=github&logoColor=white" alt="Download"></a>
  <a href="https://www.youtube.com/@srmoraesbrasil"><img src="https://img.shields.io/badge/Canal-SrMoraes-FF0000?style=for-the-badge&logo=youtube&logoColor=white" alt="Canal SrMoraes"></a>
  <img src="https://img.shields.io/badge/Windows-Portable-486CFF?style=for-the-badge&logo=windows&logoColor=white" alt="Windows Portable">
  <img src="https://img.shields.io/badge/Android-Receiver-32D74B?style=for-the-badge&logo=android&logoColor=white" alt="Android Receiver">
</p>

<p align="center">
  <strong>WiFi Speaker Launcher</strong> transforma seu Android em uma caixa de som Wi‑Fi para o PC ou notebook.<br>
  Uma versão <strong>gratuita</strong>, <strong>sem anúncios</strong> e com <strong>tudo liberado</strong>, criada por <strong>SrMoraes</strong>.
</p>

---

<p align="center">
  <img src="docs/assets/section-features.svg" alt="Recursos principais" width="100%">
</p>

<table>
  <tr>
    <td width="92" align="center"><img src="docs/assets/icon-windows.svg" width="72" alt="Windows"></td>
    <td>
      <strong>Launcher Windows Portable</strong><br>
      Execute o launcher no Windows, encontre o Android na rede e envie o áudio do PC sem precisar instalar um programa pesado.
    </td>
  </tr>
  <tr>
    <td width="92" align="center"><img src="docs/assets/icon-android.svg" width="72" alt="Android"></td>
    <td>
      <strong>Android Receiver</strong><br>
      O app Android fica disponível para conexão e mostra status, IP, portas e dispositivo conectado.
    </td>
  </tr>
  <tr>
    <td width="92" align="center"><img src="docs/assets/icon-latency.svg" width="72" alt="Baixa latência"></td>
    <td>
      <strong>Ultra baixa latência</strong><br>
      Perfil de <strong>15 ms</strong> para reduzir atraso em vídeos, jogos e uso diário.
    </td>
  </tr>
  <tr>
    <td width="92" align="center"><img src="docs/assets/icon-background.svg" width="72" alt="Segundo plano"></td>
    <td>
      <strong>Segundo plano e anti-sono</strong><br>
      Serviço em primeiro plano, liberação de bateria, modo tela preta anti-sono e sinal piloto 5 Hz para manter o fluxo ativo.
    </td>
  </tr>
  <tr>
    <td width="92" align="center"><img src="docs/assets/icon-update.svg" width="72" alt="Atualização"></td>
    <td>
      <strong>Atualizações via GitHub</strong><br>
      Validação remota por <code>version.json</code>, aviso de nova versão, modo manutenção e update obrigatório quando necessário.
    </td>
  </tr>
</table>

---

## Visão geral

O projeto possui duas partes:

| Parte | Função |
|---|---|
| **WiFi Speaker Android Receiver** | Recebe o áudio e reproduz no Android |
| **WiFi Speaker Launcher Windows** | Encontra o Android e transmite o áudio do PC |

O objetivo é entregar uma experiência simples: abrir o app no celular, abrir o launcher no Windows, conectar e ouvir o áudio do PC direto no Android.

---

<p align="center">
  <img src="docs/assets/section-install.svg" alt="Instalação e conexão" width="100%">
</p>

## Android

1. Baixe o APK em **Releases**.
2. Instale no Android.
3. Abra o app **WiFi Speaker**.
4. Toque em **Ativar receptor**.
5. Para maior estabilidade, toque em **Liberar segundo plano / bateria**.
6. Em aparelhos mais agressivos, use o **Modo tela preta anti-sono**.

## Windows

1. Baixe o pacote portable em **Releases**.
2. Extraia o arquivo `.zip`.
3. Execute o `WiFiSpeakerLauncher.exe`.
4. Clique em **Procurar dispositivos**.
5. Selecione o Android encontrado.
6. Clique em **Conectar**.
7. Clique em **Iniciar transmissão**.

> O PC e o Android precisam estar na mesma rede Wi‑Fi.

---

## Perfis de sincronização

| Modo | Indicação |
|---|---|
| **Jogo / FPS • 15 ms + piloto 5Hz** | Menor atraso possível |
| **Vídeo / menor atraso • 45 ms** | Melhor equilíbrio para vídeos |
| **Alta estabilidade • 90 ms** | Redes mais fracas ou instáveis |

---

<p align="center">
  <img src="docs/assets/section-gallery.svg" alt="Guia visual" width="100%">
</p>

<table>
  <tr>
    <td align="center" width="33%">
      <img src="docs/images/android-status-desligado.jpg" alt="Android desligado" width="260"><br>
      <strong>1. Receptor desligado</strong><br>
      Toque em <strong>Ativar receptor</strong>.
    </td>
    <td align="center" width="33%">
      <img src="docs/images/android-status-disponivel.jpg" alt="Android disponível" width="260"><br>
      <strong>2. Receptor disponível</strong><br>
      O Windows já pode encontrar o Android.
    </td>
    <td align="center" width="33%">
      <img src="docs/images/android-background-update.jpg" alt="Segundo plano e atualização" width="260"><br>
      <strong>3. Segundo plano e atualização</strong><br>
      Libere bateria, use anti-sono e verifique updates.
    </td>
  </tr>
</table>

---

<p align="center">
  <img src="docs/assets/section-update.svg" alt="Atualizações via GitHub" width="100%">
</p>

O arquivo `version.json` permite controlar remotamente:

- versão atual;
- versão mínima suportada;
- chave de versão;
- modo manutenção;
- atualização obrigatória;
- links de download para APK e Launcher.

Exemplo resumido:

```json
{
  "current_version": "3.3.5",
  "min_supported_version": "3.3.5",
  "force_update": false,
  "maintenance_mode": false,
  "download_url": "https://github.com/srmoraesbrasil/WS-WiFi-Speaker/releases/latest"
}
```

---

<p align="center">
  <img src="docs/assets/section-trouble.svg" alt="Solução de problemas" width="100%">
</p>

## O Android não aparece no launcher

- Confirme que ambos estão na mesma rede Wi‑Fi.
- Verifique se o receptor está **Disponível** no Android.
- Use o IP manual exibido no app Android.

## O áudio para com a tela apagada

- Toque em **Liberar segundo plano / bateria**.
- Remova restrição de bateria do app.
- Use o **Modo tela preta anti-sono**.

## O áudio está com atraso

- Use o modo **Jogo / FPS • 15 ms**.
- Aproxime o celular do roteador.
- Evite redes congestionadas.

## O Windows não iniciou com o sistema

- Abra as configurações do launcher.
- Marque **Iniciar com o Windows**.
- Verifique se o Windows permitiu salvar a configuração.

---

## Estrutura recomendada

```text
WS-WiFi-Speaker/
├─ README.md
├─ version.json
└─ docs/
   ├─ assets/
   │  ├─ hero.svg
   │  ├─ section-features.svg
   │  ├─ section-install.svg
   │  ├─ section-gallery.svg
   │  ├─ section-update.svg
   │  ├─ section-trouble.svg
   │  ├─ icon-windows.svg
   │  ├─ icon-android.svg
   │  ├─ icon-latency.svg
   │  ├─ icon-background.svg
   │  └─ icon-update.svg
   └─ images/
      ├─ android-status-desligado.jpg
      ├─ android-status-disponivel.jpg
      └─ android-background-update.jpg
```

---

## Fundador

<p align="center">
  <strong>SrMoraes</strong><br>
  <a href="https://www.youtube.com/@srmoraesbrasil">youtube.com/@srmoraesbrasil</a>
</p>

<p align="center">
  <a href="https://github.com/srmoraesbrasil/WS-WiFi-Speaker/releases/latest"><strong>Baixar última versão</strong></a>
  &nbsp;•&nbsp;
  <a href="https://www.youtube.com/@srmoraesbrasil"><strong>Canal do SrMoraes</strong></a>
</p>
