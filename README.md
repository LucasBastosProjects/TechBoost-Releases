# TechBoost

**Otimizador de Windows 10 e 11 feito por técnico, para gamers e para a bancada.**
Cada ajuste mostra o que muda, guarda backup e pode ser revertido.

## Baixar

**[⬇ Baixar o TechBoost (versão mais recente)](https://github.com/LucasBastosProjects/TechBoost-Releases/releases/latest/download/TechBoost.exe)**

Ou veja todas as versões e as novidades em [Releases](https://github.com/LucasBastosProjects/TechBoost-Releases/releases).

Ao baixar, você só precisa do arquivo `TechBoost.exe`. O arquivo `TechBoost.exe.sha256` é usado pelo próprio programa para conferir as atualizações.

## Requisitos

- Windows 10 ou Windows 11 (64 bits)
- Executar como administrador (o programa pede sozinho)
- Não precisa instalar o .NET: está tudo dentro do arquivo

## Como começar

1. Baixe o `TechBoost.exe` pelo botão acima.
2. Abra o arquivo. Se o Windows mostrar **"O Windows protegeu o computador"**, clique em **Mais informações** e depois em **Executar assim mesmo**. Esse aviso aparece porque o programa ainda não tem assinatura digital paga; ele não indica problema no arquivo.
3. Escolha o modo (Compacto, Avançado ou Técnico) e, se quiser, aceite instalar o programa no computador.

## Atualizações

Depois de instalado, o TechBoost procura versões novas sozinho. Quando há uma, ele baixa em segundo plano, confere o arquivo (SHA-256), mostra as novidades e pergunta se você quer atualizar. Seus ajustes e backups são mantidos. Dá para desligar isso em **Configurações**.

## Conferir o arquivo (opcional)

No PowerShell, na pasta do download:

```powershell
(Get-FileHash .\TechBoost.exe -Algorithm SHA256).Hash
```

O resultado deve ser igual ao texto do arquivo `TechBoost.exe.sha256` da mesma versão.

## Contato

Criado por **gnomeraH**, técnico de informática e streamer: [twitch.tv/gnomerah_](https://twitch.tv/gnomerah_)

---

© gnomeraH. Todos os direitos reservados. É proibida a cópia, a modificação e a redistribuição do programa sem autorização.
