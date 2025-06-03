# Projeto base para Raspberry Pi Pico no Gitpod

Este repositório configura um ambiente Gitpod com:

- Compilador ARM (`gcc-arm-none-eabi`)
- SDK oficial do Raspberry Pi Pico
- Firmware exemplo (`main.c`) que imprime via USB

## Como usar

1. Suba este repositório no GitHub
2. Acesse com: `https://gitpod.io/#https://github.com/seu-usuario/seu-repo`
3. O projeto será compilado automaticamente
4. Baixe o `.uf2` da pasta `build/` e copie para o Pico em modo BOOTSEL
