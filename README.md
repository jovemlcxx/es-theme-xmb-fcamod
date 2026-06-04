# Tema XMB para EmulationStation

![Platform](https://img.shields.io/badge/Plataforma-EmulationStation-purple)
![Style](https://img.shields.io/badge/Estilo-XMB-blue)
[![Github](https://img.shields.io/badge/Github-Repositório-black?logo=github)](https://github.com/jovemlcxx/es-theme-xmb-fcamod)

Um tema inspirado no estilo XMB, projetado especificamente para consoles com frontend EmulationStation. Este tema traz a clássica experiência de interface de consoles para o seu sistema com um código limpo, otimizado e um layout refinado.

**Repositório Oficial:** [github.com/jovemlcxx/es-theme-xmb-fcamod](https://github.com/jovemlcxx/es-theme-xmb-fcamod)

Otimizado para **FCAMOD,** um fork do EmulationStation criado por [christianhaitian](https://github.com/christianhaitian/EmulationStation-fcamod)

![Preview](./xmb.png)

## 💻 Sistemas Suportados

Totalmente compatível e otimizado para rodar nas seguintes distribuições:
- [ArkOS](https://github.com/christianhaitian/arkos)
- [dArkOS](https://github.com/christianhaitian/dArkOS)
- [ArchR](https://github.com/archr-linux/Arch-R)
- [Batocera](https://batocera.org/)
- E demais sistemas baseados na engine FCAMOD.

## 🌟 Funcionalidades

- **Interface Clássica XMB:** Recriação aproximada da experiência XMB (Cross Media Bar) encontrada no PSP/PS3.
- **Suporte a Múltiplos Aspect Ratios:** Layouts otimizados para diferentes formatos de tela:
  - **4:3:** Perfeito para R36S, RG351MP e outros portáteis padrão (640x480).
  - **1:1:** Feito sob medida para telas quadradas como o RGB30, R36 Ultra e R36 Pro Max (720x720).
- **Suporte a Modo Escuro:** Apresenta uma paleta de cores escuras elegante e moderna para uma experiência visual confortável.
- **Fundos Dinâmicos:** Suporte para fundos estáticos (imagens .png) e animados (vídeos .mp4).
- **Tipografia de Alta Qualidade:** Utiliza as fontes *FOT-NewRodin Pro* para um visual premium e autêntico.
- **Otimizado para FCAMOD:** Aproveita os layouts de grid avançados e os recursos de delay de vídeo suportados pela engine FCAMOD.

## 📂 Instalação

1. Conecte-se ao seu dispositivo via SCP ou SFTP.
2. Navegue até o seu diretório de temas (geralmente `/roms/themes/` ou `~/.emulationstation/themes/`).
3. Copie a pasta do tema para este diretório. 
   - **Nota:** A pasta deve se chamar `es-theme-xmb-fcamod` ou `es-theme-xmb-fcamod-main` (se baixada diretamente do GitHub).
4. No EmulationStation, vá em **UI Settings** > **Theme Set** e selecione o tema.
5. Vá em **UI Settings** > **Theme Configuration** para customizar:
   - **Aspect Ratio:** Selecione o formato que corresponde ao seu aparelho (4:3 ou 1:1).
   - **System Layout:** Escolha entre **Horizontal (XMB Clássico)** ou **Vertical (Barra Esquerda)**.
   - **Esquema de Cores:** Escolha entre **Escuro** ou **Claro**.
   - **Wallpaper:** Selecione o número correspondente ao seu fundo customizado (de 1 a 20).

## 🖼️ Customização de Papel de Parede (Wallpaper)

O tema suporta até 20 wallpapers customizados (Imagens e Vídeos). **Por favor, note que apenas um wallpaper (`bg_1.png` e `bg_1.mp4`) vem incluído por padrão.**

> **⚠️ Dica de Performance:** Se você sentir lentidão ou quedas de quadros nos menus do seu aparelho, é altamente recomendado apagar o arquivo `bg_1.mp4`. Vídeos de fundo podem ser pesados e causar queda de performance em aparelhos com menos de 1Gb de ram.

Você pode adicionar os seus próprios arquivos facilmente:

### Sobre Resolução e Aspect Ratio
O tema esticará automaticamente as imagens e vídeos para preencherem 100% da tela do seu console. Portanto, para evitar que suas mídias fiquem distorcidas, **certifique-se de que a resolução da sua imagem e vídeo corresponda à proporção da tela do seu dispositivo**.
- Para consoles de tela **4:3** (como o R36S, Miyoo Mini), recomendamos mídias na resolução **1024x768** ou **640x480**.
- Para consoles de tela **1:1** (como o R36 Ultra e R36 Pro Max), recomendamos criar mídias perfeitamente quadradas (ex: **720x720** ou **1080x1080**).

### Passo a passo para adicionar arquivos:

1. **Prepare seus arquivos:** 
   - Imagens estáticas devem estar no formato **.png**.
   - Fundos animados devem estar no formato **.mp4**.
2. **Renomeie os arquivos:**
   - Siga o padrão `bg_{número}.png` ou `bg_{número}.mp4`.
   - Exemplo: `bg_1.png`, `bg_1.mp4`, etc.
3. **Copie para a pasta do tema:**
   - Coloque seus arquivos dentro do diretório `_inc/background/`.
4. **Selecione o wallpaper no menu:**
   - Abra o menu do EmulationStation, vá em **Theme Configuration** > **Wallpaper** e escolha o número correspondente ao seu arquivo.

## 🛠️ Créditos e Referências

Este projeto utiliza assets, lógicas e inspirações de design de diversos projetos incríveis da comunidade:

- **Assets:** Ícones e elementos de interface retirados do repositório [RetroArch Assets](https://github.com/libretro/retroarch-assets).
- **Projeto Base:** [anthonycaccese/xmb-menu-es-de](https://github.com/anthonycaccese/xmb-menu-es-de) - Principal referência estrutural, adaptada para compatibilidade com a antiga engine do FCAMOD.
    - [mohamedhany1024/ps3-xmb-web](https://github.com/mohamedhany1024/ps3-xmb-web) - Referência de lógica e layout para o estilo do XMB do PS3.
    - [RobZombie9043/xmb-es-de](https://github.com/RobZombie9043/xmb-es-de) - Inspirações adicionais de layout.
    - [lcdyk0517/arkos4clone](https://github.com/lcdyk0517/arkos4clone) - Orientação estrutural para compatibilidade com ArkOS.
- **Vídeo de Fundo:** Fundo animado criado por **TizzyT** ([Vídeo Original](https://youtu.be/69RqDjCYiek)).

---

*Desenvolvido para a comunidade Retro Gaming.*