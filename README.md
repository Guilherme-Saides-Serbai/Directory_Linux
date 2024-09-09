---

# Diretórios do Sistema de Arquivos Linux

Este documento descreve os principais diretórios do sistema de arquivos Linux e suas funções. 

## Índice

1. **/** (Root)
2. **/bin** (Binary)
3. **/boot**
4. **/dev** (Device)
5. **/etc** (Etcetera)
6. **/home**
7. **/lib** (Libraries)
8. **/media**
9. **/mnt** (Mount)
10. **/opt** (Optional)
11. **/proc** (Process)
12. **/root**
13. **/run**
14. **/sbin** (System Binaries)
15. **/srv** (Service)
16. **/sys**
17. **/tmp** (Temporary)
18. **/usr** (User)
19. **/var** (Variable)

## 1. **/** (Root)

O diretório raiz do sistema. Todos os outros diretórios e arquivos estão organizados a partir deste ponto.

## 2. **/bin** (Binary)

Contém binários essenciais do sistema, como comandos que podem ser executados por todos os usuários (ex.: `ls`, `cp`, `mv`).

## 3. **/boot**

Armazena arquivos necessários para o processo de inicialização do sistema, incluindo o kernel do Linux e o bootloader (ex.: GRUB).

## 4. **/dev** (Device)

Contém arquivos de dispositivos que representam interfaces para o hardware do sistema, como discos rígidos e terminais.

## 5. **/etc** (Etcetera)

Armazena arquivos de configuração do sistema e dos programas instalados, como `/etc/passwd` (informações de usuários) e `/etc/hosts` (configurações de rede).

## 6. **/home**

Diretório de usuários. Cada usuário comum do sistema possui uma pasta individual, por exemplo, `/home/guilherme`, onde são armazenados arquivos pessoais.

## 7. **/lib** (Libraries)

Contém bibliotecas essenciais para binários do sistema localizados em `/bin` e `/sbin`. As bibliotecas funcionam de forma semelhante às DLLs no Windows.

## 8. **/media**

Ponto de montagem para dispositivos removíveis, como CDs, DVDs e pendrives, quando conectados ao sistema.

## 9. **/mnt** (Mount)

Outro ponto de montagem, usado para montar sistemas de arquivos temporários, como discos externos.

## 10. **/opt** (Optional)

Destinado a pacotes de software opcionais que não fazem parte da distribuição padrão do sistema.

## 11. **/proc** (Process)

Sistema de arquivos virtual que fornece informações sobre processos e recursos do sistema, como `/proc/cpuinfo` (informações sobre o processador).

## 12. **/root**

Diretório home do usuário root (administrador do sistema). Este diretório é reservado exclusivamente para o root e não deve ser confundido com o diretório raiz (`/`).

## 13. **/run**

Contém informações sobre o sistema em execução, como identificadores de processos (PID) e sockets de comunicação. Essas informações são geradas após a inicialização.

## 14. **/sbin** (System Binaries)

Contém binários essenciais para a administração do sistema, como `fdisk` e `reboot`, geralmente usados apenas pelo root.

## 15. **/srv** (Service)

Armazena dados para serviços de rede específicos, como servidores HTTP ou FTP.

## 16. **/sys**

Sistema de arquivos virtual que oferece informações sobre dispositivos e drivers do sistema.

## 17. **/tmp** (Temporary)

Diretório usado para armazenar arquivos temporários criados por programas. Esses arquivos são geralmente excluídos após a reinicialização do sistema.

## 18. **/usr** (User)

Contém a maior parte dos utilitários, bibliotecas e documentação do sistema. O diretório `/usr/bin` contém comandos não essenciais e o `/usr/lib` contém bibliotecas. O `/usr/local` é utilizado para programas instalados manualmente pelo usuário.

## 19. **/var** (Variable)

Armazena dados variáveis, como logs do sistema (`/var/log`), arquivos temporários e caches.

---
