# WELLS CONECT — versão final aprovada

**Estado:** finalizado e validado em aparelho Android real. **Plataforma:** Windows portátil + Wells Audio (APK Android).

WELLS CONECT reúne espelhamento e controle de Android via USB/Wi-Fi, controles de teclado/gamepad e reprodução do áudio do aparelho no computador. A interface possui identidade visual própria, inclusive o ícone do Wells Conect e o aplicativo Android **Wells Audio**.

## Versão oficial vigente

- **Código-fonte exato:** [mucholocco86/fisicos — commit 5cb2452291f85c40245048b2b67598b2a004fb94](https://github.com/mucholocco86/fisicos/commit/5cb2452291f85c40245048b2b67598b2a004fb94).
- **Compilação Windows + APK aprovada:** [GitHub Actions](https://github.com/mucholocco86/fisicos/actions/runs/43313481982).
- **Pacote portátil completo:** [WELLS-CONECT-Windows-Qt6-scrcpy-5.0.1.zip](https://github.com/mucholocco86/projetos-prontos/releases/download/wells-conect-v1.0.0/WELLS-CONECT-Windows-Qt6-scrcpy-5.0.1.zip).
- **Backup do código-fonte:** [WELLS-CONECT-CODIGO-FONTE.zip](https://github.com/mucholocco86/projetos-prontos/releases/download/wells-conect-v1.0.0/WELLS-CONECT-CODIGO-FONTE.zip).
- **Publicação oficial:** [wells-conect-v1.0.0](https://github.com/mucholocco86/projetos-prontos/releases/tag/wells-conect-v1.0.0).

## Wells Audio — validação final

Aprovado pelo autor em 12/11/2026 após testes em dispositivo real:

- Instalação do aplicativo auxiliar Wells Audio e solicitação nativa de autorização para notificações.
- Notificação de transmissão com visual personalizado e quatro controles: **128 kbps**, **96 kbps**, **32 kbps** e **Parar**.
- Transmissão de áudio funcional, com testes anteriores satisfatórios por USB e Wi-Fi.
- O áudio transmitido permanece **PCM original**; os valores em kbps são preferências exibidas na interface, **não** taxas de compressão aplicadas ao fluxo.

O pacote contém executável, DLLs, ADB, scrcpy-server, APK Wells Audio e o script de inicialização. **Não distribuir apenas o arquivo .exe.**

## Preservação e manutenção

Esta pasta representa somente a **versão final vigente**. O histórico de desenvolvimento, versões estáveis anteriores e experimentos permanecem no repositório de origem. O pacote final não inclui os antigos `sndcpy.apk` e `sndcpy.bat`; o código de terceiros e suas licenças são preservados nas fontes.
