---
marp: true
theme: gaia
backgroundColor: white
color: black
paginate: true
footer: Fundamentos de Informática e Aplicativos - Fabrício Barros Cabral <<fabricio.cabral@ead.ifpe.edu.br>>
---
<style>
img[alt~="center"] {
    display: block;
    margin: 0 auto;
}
</style>

<!-- _paginate: false -->
# **Fundamentos de Informática e Aplicativos**

## Capítulo 4 - Pastas Importantes usadas pelo Windows

---

## Pastas Padrão Criadas para o Usuário

- Localizadas em `C:\Users\[nome-do-usuário]`
- Criadas por padrão pelo Windows ao criar uma conta de usuário
- As pastas são:
  - Área de Trabalho (Desktop), Contatos (Contacts), Documentos (Documents), Downloads, Favoritos (Favorites), Imagens (Pictures), Jogos Salvos (Saved Games), Links, Músicas (Music), Objetos 3D (3D Objects), OneDrive, Pesquisas (Searches) e Vídeos (Videos)

---

## Arquivos de Programas e Arquivos de Programas (x86)

- Localizadas em `C:\Program Files` e `C:\Program Files (x86)`
- Local onde geralmente os arquivos dos programas (EXEs e DLLs) são instalados
- Quando se quer remover um programa, não deve-se apagar a pasta que contém os arquivos de programa e sim, fazer a operação de desinstalar o programa (Configurações -> Aplicativos -> Aplicativos e recursos, botão Desinstalar)

---

## Windows e System32

- Localizadas em `C:\Windows` e `C:\Windows\System32`
- A pasta `Windows` contém todos os arquivos necessários para o funcionamento do sistema operacional; a `System32` contém centenas de DLLs e programas como a Calculadora e o Microsoft Paint

---

## Page File

- Localizada em `C:\pagefile.sys` (Para vê-lo deve-se desmarcar a opção "Ocultar arquivos protegidos do sistema operacional" e marcar "Itens ocultos")
- Utilizado como paginação, entre a memóriam RAM e o disco, permitindo que o disco funcione como uma memória RAM
- Só é utilizado em caso de necessidade, pois o disco é bem mais lento que a memória RAM

---

## System Volume Information

- Localizada em `C:\System Volume Information` (Para vê-lo deve-se desmarcar a opção "Ocultar arquivos protegidos do sistema operacional" e marcar "Itens ocultos")
- Armazena Pontos de Restauração do sistema Windows, assim é possível reverter alterações
- Armazena dados para permitir a indexação das unidades (drives), isto permite uma pesquisa por arquivos mais rápida
- Contém o serviço Volume Shadow Copy necessário para backup de arquivos

---

## WinSxS

- Localizada em `C:\Windows\WinSxS`
- WinSxS significa Windows Side by Side e foi criado para resolver problemas de compatibilidade entre DLLs de aplicativos
- Se o conteúdo desta pasta ficar muito grande, não deve-se deletar diretamente. Utilize a operação de Limpeza de Disco do Windows

---

## D3DSCache

- Localizada em `C:\Users\[nome-do-usuário]\AppData\Local`
- Esta pasta contém informações de cache sobre o Direct3D da Microsoft, que é usado por jogos e programas que fazem uso gráfico intensivo
- Normalmente o conteúdo dessa pasta não precisa ser mexido, mas se você estiver sofrendo problemas com jogos (crash), limpar esta pasta pode ser útil

---

## RUXIM

- Localizada em `C:\Program Files\RUXIM`
- Significa Reusable UX Integration Manager (RUXIM)
- Contém programas executáveis necessários para a coleta de informações de diagnóstico do Windows

---

## Referências Bibliográficas

**7 Default Windows Files and Folders You Should Never Touch**. https://www.makeuseof.com/tag/default-windows-files-folders/, acessado em 13/03/2023