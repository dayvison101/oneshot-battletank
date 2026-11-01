# OneShot BattleTank

Canal público de distribuição e atualizações do OneShot BattleTank para Windows x64.

Baixe o pacote ZIP na [release mais recente](https://github.com/dayvison101/oneshot-battletank/releases/latest),
extraia a pasta inteira e abra o executável OneShot. O runtime Python acompanha
o pacote. Microsoft WebView2 e .NET Framework 4.x são componentes necessários.

O [OneShot Hub](https://github.com/dayvison101/oneshot-hub/releases/latest) instala
e atualiza os painéis por estes canais, sem exigir login no GitHub.
Uma atualização disponível aparece no card do painel; feche somente esse painel
antes de instalar. O jogo pode permanecer aberto.

O hub usa ícone grafite; os painéis usam violeta com retículo branco.
Disparos automáticos e ciclo PvP iniciam desligados.

## Integridade e versões

Cada release possui `oneshot-release.json`, o ZIP e `SHA256SUMS.txt`. O hub
confere tamanho, hash SHA-256 e identidade antes de ativar uma instalação nova.
Pacote inválido preserva a versão atual. Os arquivos de preferências do usuário,
registros de partidas, credenciais e dados de sessão não integram a distribuição.

Os testes de distribuição/interface não comprovam acerto ou paridade integral
das funções de combate em partidas reais. O cliente do jogo não é distribuído.

Este repositório é um canal de releases; não é um espelho do diretório de trabalho.
